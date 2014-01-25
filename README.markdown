## python-libevent - Python bindings for libevent

See the "samples" directory and the tests for now.

## Compile on windows using msvc

* start visual studio 2008 command prompt
* cd libevent-2.0.21-stable
* nmake -f Makefile.nmake
* cd python-libevent
* set LIBEVENT_ROOT=/path/to/libevent-2.0.21-stable 
* python setup.py build

