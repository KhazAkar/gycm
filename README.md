gycm
====

A Geany plugin to support the ycmd code completion server.

Currently kind of operational and very unstable.

Installation
============
Prerequisites:
- jsoncpp headers
- Neon headers
- Geany headers
- OpenSSL headers

After installing those, then execute

`cmake .`

After that, if everything went smoothly,

`make`

After it completes, it's (for now) necessary to put compiled gycm.so file using those commands:

`sudo cp gycm.so /usr/lib64/geany` - (For openSUSE)

`sudo ldconfig`

After those steps, GYCM should be available in Geany's Plugin Manager

See Also
--------

- [ycmd-core website](https://github.com/ycm-core/ycmd) - core server for YouCompleteMe - YCMD
- [YouCompleteMe](https://github.com/Valloric/YouCompleteMe) - The original plugin for vim
- [Original GYCM plugin creator](https://github.com/jakeanq/gycm)
