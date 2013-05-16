## Welcome
This project provide YCM binaries with Clang support for Windows using Visual Studio 2012 Update 2.

## Instructions
1. Setup [Vundle](https://github.com/gmarik/vundle).
2. Configure bundles:

    ```vim
    Bundle 'Valloric/YouCompleteMe'
    Bundle 'scrooloose/syntastic'
    ```
3. Copy ``libclang.dll`` and ``ycm_core.pyd`` to ``C:\<path_to>\YouCompleteme\python``.