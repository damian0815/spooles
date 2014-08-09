spooles
=======

Mirror of Spooles (http://www.netlib.org/linalg/spooles/) that compiles on OSX (probably Linux too).

Includes parts of patch at http://lists.freebsd.org/pipermail/freebsd-ports-bugs/2004-September/042528.html ("ports/72216: math/spooles: missing symbols in the library") plus other stuff.

Note MPI is disabled as it's probably not threadsafe (ref the freebsd ports bugreport).

Building
--------

`$ make global` will generate spooles.a.

`$ make` will build a bunch of test applications. I've only checked a handful of them.

