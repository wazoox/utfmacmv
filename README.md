# utfmacmv

Simple script to rename files whose name is utf8-mac encoded (UTF8 NFD) to plain utf8 (UTF8 NFC) without using any mac-only program (like the MacOS version of iconv).



## Install

Clone the repo and run the command. It doesn't need any non standard modules so it should run out of the box on any Linux machine (tested on Slackware 14.2, CentOS 7.3, Debian 9 and Ubuntu 16.04).

Two files with utf8-mac encoded filenames are provided for tests.

## Run

  utfmacmv [filename] [filename ...]
  
Will reencode the filename and let the data untouched (hopefully). Treats all passed filenames. Doesn't recurse directories.

## Options

None. 

## To do

A "recursive" option would be nice.

## License

WTFPL.
