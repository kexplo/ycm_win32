## Welcome to YCM-Win32

[YouCompleteMe][youcompleteme] is a fast, as-you-type, fuzzy-search
code completion engine for [Vim][vim].

This project provide YouCompleteMe binaries with Clang support for
Windows using Visual Studio 2012 Update 2.

Visit [YouCompleteMe User Guide][ycm_user_guide] for more details
about semantic completions.

## Instructions

1. Setup [Vundle][vundle].
2. Configure bundles:

    ```vim
    Bundle 'Valloric/YouCompleteMe'
    Bundle 'scrooloose/syntastic'
    ```

3. Copy ``libclang.dll`` and ``ycm_core.pyd`` to
``C:\<path_to>\YouCompleteme\python``.

## Contact

If you have questions, bug reports, suggestions, etc. please use the
[issue tracker][tracker].

## Notices

[YouCompleteMe][youcompleteme] is released under the
[GPL v3 license][gpl].

[LLVM][llvm] and [Clang][clang] is available under the [University of
Illinois/NCSA Open Source License][ncsa].


<!-- Link -->
[youcompleteme]: https://github.com/Valloric/YouCompleteMe
[vim]: http://www.vim.org/
[ycm_user_guide]: https://github.com/Valloric/YouCompleteMe#user-guide
[vundle]: https://github.com/gmarik/vundle
[tracker]: https://github.com/bcbcarl/ycm_win32/issues
[gpl]: http://www.gnu.org/copyleft/gpl.html
[llvm]: http://llvm.org/
[clang]: http://clang.llvm.org/
[ncsa]: http://opensource.org/licenses/UoI-NCSA.php
