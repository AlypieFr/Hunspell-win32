# Hunspell-win32

Hunspell for windows (32bits and 64 bits)

### How to compile it?

##### 1. Install necessaries packages

Install MinGW:

    mingw32-base
    mingw32-gcc-g++
    msys-base

Install required libraries from [this site](http://gnuwin32.sourceforge.net/packages.html):

    freetype
    libjpeg
    libpng
    libtiff
    zlib


##### 2. Compile and install hunspell

To build hunspell, run MSYS by executing C:\MinGW\msys\1.0\msys.bat. In the terminal window that opens, run the following commands:

On 64bits:

    ./configure --prefix=/c/hunspellX64
    cd src/hunspell
    make install

On 32bits:

    ./configure --prefix=/c/hunspellI686
    cd src/hunspell
    make install


This will build hunspell and install it in C:\texworks\libs.


That's all ! :-)
