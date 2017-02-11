# A brief history of unix

## The old age
1937 - 1950, The computer was built to serve specific research or engineering purpose, like US Army. 

1950 - 1960, more and more computers were built for research & commerical purpose, to surve the purpose, computers were mainly doing batch process jobs, like [IBM's 701 Electronic Data Processing](http://www.computerhistory.org/timeline/1953/#169ebbe2ad45559efbc6eb357208a518) and IBM has procuded various machines and they were called [mainframe](https://en.wikipedia.org/wiki/Mainframe_computer).

1960, [DEC](https://en.wikipedia.org/wiki/Digital_Equipment_Corporation) invented [PDP-1](http://www.computerhistory.org/pdp-1/the-machine/) as first mini-computer. MIT purchased PDP-1 and invented operating system to do time-sharing like [ITS](https://en.wikipedia.org/wiki/Incompatible_Timesharing_System), and ITS was written in assemly language, so the system can not be ported to different hardware. Inventions run on ITS like Emacs, LISP are still alive today.

## The early age
1964, [multics](http://web.mit.edu/multics-history/) was started to build an operating system for [GE 645](https://en.wikipedia.org/wiki/GE-600_series), jointly by MIT, GE and Bell Labs, multics intended to be a felxible operating system and provide an interactive programming environment, but it failed, enginner [Ken Thompson](https://en.wikipedia.org/wiki/Ken_Thompson) who worked in Bell Labs  worked on multics, created a game called [Space Travel](https://www.bell-labs.com/usr/dmr/www/spacetravel.html) on multics. 

In 1969, multics was dead, and Ken and engineeris love the model of multics, but could not find an alternative, while they were rewriting the space travel on [PDP-7](https://en.wikipedia.org/wiki/PDP-7), they built [an early version of Unix including File system, process control and IO redirection](https://www.bell-labs.com/usr/dmr/www/hist.html) and also [B Programming Language, which can support cross-platform compile](https://en.wikipedia.org/wiki/B_(programming_language)).

In 1971, with the expectation to build an office software to do text editing, Bell Labs bought a new PDP-11 and Ken started to port the early version of unix, but the system were written mostly in B programming language are word-oriented, so it is not easy to port to byte-addressed PDP-11, so [C Programming Language](https://www.bell-labs.com/usr/dmr/www/chist.html) was invented, and UNIX was re-written in C. 

Since C can support cross-platform compile, so the first operating system which can run on different hardware was invented and soon become popular.

## The develop age
In 1973, Unix was firstly introduced publicly in [Symposium on Operating Systems Principles
](https://en.wikipedia.org/wiki/Symposium_on_Operating_Systems_Principles), and research started interest with Unix & C, more universities compile Unix source code and port it to different hardware

In 1975, Ken Thompson become a visit professor of Brackley, students worked with him invented a text editor and some softwares, which later asked by other universities, then they start make the Brackley Software Distribution (BSD) as close source

In 1981, AT&T started to make UNIX commerical and System III was firstly introduced publicly as close souce, and later released System V in 1985

In 1982, the student Bill Joy who worked with Ken Thompson back in Brakley funded Sun Microsystem, and start to make workstation business and invented NFS, and make its own Sun OS base on BSD and but when System V was released, they built Solaris based on System V

In 1984, HP start to build the computer business and built HP-UX based on System III

In 1985, Steve Jobs was "out" of Apple, he pulled out engineers and started NeXT and in 1990 NeXTSTEP release 1.0, which more focused on graphics user interface, which was purchased by Apple in 1996, then it merge into Mac OS and become the Mac OS X


