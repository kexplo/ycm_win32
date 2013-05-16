## Welcome to YCM-Win32

[YouCompleteMe][youcompleteme] is a fast, as-you-type, fuzzy-search
code completion engine for [Vim][vim].

This project provide YouCompleteMe binaries with Clang support for
Windows using Visual Studio 2012 Update 2.

Visit [YouCompleteMe User Guide][ycm_user_guide] for more details
about semantic completions.

## Instructions

1. Setup [Vundle](https://github.com/gmarik/vundle).
2. Configure bundles:

    ```vim
    Bundle 'Valloric/YouCompleteMe'
    Bundle 'scrooloose/syntastic'
    ```
3. Copy ``libclang.dll`` and ``ycm_core.pyd`` to
``C:\<path_to>\YouCompleteme\python``.

## Contact

If you have questions, bug reports, suggestions, etc. please use the
[issue tracker][tracker]. The latest version is available at
https://github.com/bcbcarl/ycm_win32.


<!-- Link -->
[vim]: http://www.vim.org/
[youcompleteme]: https://github.com/Valloric/YouCompleteMe
[ycm_user_guide]: https://github.com/Valloric/YouCompleteMe#user-guide
[tracker]: https://github.com/bcbcarl/ycm_win32/issues
