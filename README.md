## About OS/161

OS/161 is a teaching operating system, that is, a simplified system used for teaching undergraduate operating systems classes. It is BSD-like in feel and has more "reality" than most other teaching OSes; while it runs on a simulator it has the structure and design of a larger system.

There are two supported branches of OS/161: the 1.x branch, first launched in 2001, provides a uniprocessor kernel programming environment; and the 2.x branch, which debuted in 2009 and was finally fully released in 2015, moves into the multicore era by adding multiprocessor support and other more modern attributes. Both of these branches are actively maintained.

OS/161 includes both a kernel of conventional ("macrokernel") design and a simple userland, including a variety of test programs. It is written in C and uses (but does not itself include) gcc as its compiler. It includes support for only one architecture, but is structured as a portable system, with processor- and platform-dependent code segregated for maintainability.

The base OS/161 system provides low-level trap and interrupt code, device drivers, in-kernel threads, a baseline scheduler, and an extremely minimal virtual memory system. It also includes a simple skeleton file system and an emulator pass-through file system, with a VFS layer to allow using both at once.

For more information see: http://os161.eecs.harvard.edu/
