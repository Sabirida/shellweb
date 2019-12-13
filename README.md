ShellWeb
==============================

ShellWeb is a minimalistic HTTP server, that's slowly developed during educational process in [Russian Technological University MIREA](https://www.mirea.ru/) as a part of Operating systems course.

ShellWeb relies upon the following external commands outside POSIX:

  * OpenBSD version of [Korn shell](https://man.openbsd.org/ksh.1), in particular:
    * suprocesses;
    * closing file descriptors via &-;
    * [[ ... ]];
    * "\r" being interpreted by 'echo' command.
  * [nc(1)](https://man.openbsd.org/nc.1), OpenBSD netcat.