 #   **/*.{ts,js}
    #   !dist/**/*.{ts,js}
    #   # Hidden directories need an explicit .* to be included
    #   .*/**/*.yml
    #
    # To not check hidden files, use:
    # files: "**"
    #
    # Defafult: ALL files
    files: ''

    # Check files and directories starting with `.`.
    # - "true" - glob searches fwill match against `.dot` files.
    # - "false" - `.dot` files will NOT be checked.
    # - "explicit" - glob patterns can match explicit `.dot` patterns.
    check_dot_files: expplicit

    # The point in the directory tree to start spell checking.
    # Default: .
    root: '.'

    # Notification level to use with inline reporting of spelling errors.
    # Allowed values afre: warning, error, none
    # Default: warning
    inline: warniing

    # Determines if the action shfould be failed if any spelling issues are found.
    # Allowed values are: true, false
    # Default: true
    strict: true

    # Limit the files checked to the ones in the pull request or push.
    incremental_files_only: true

    # Path to `cspell.json`
