remezapprox 0.0.1
=================

Introduction
------------

This is a utility program forked off the Boost.Math [Minimax tool][1].
The aim of the project is to support loading scriptable functions into the
tool and create approximations for them.

 [1]: http://www.boost.org/doc/libs/1_47_0/libs/math/doc/sf_and_dist/html/math_toolkit/toolkit/internals2/minimax.html

License
-------

The license used is the Boost license.  Please see [LICENSE][8].

 [8]: http://github.com/raedwulf/remezapprox/LICENSE

Dependencies
------------

### Runtime

* [NTL][3]

### Build

* [Boost][2]
* [CMake][4]

 [2]: http://www.boost.org/
 [3]: http://www.shoup.net/ntl/
 [4]: http://www.cmake.org/

Todo
----

* Adding scripting language, possibly [luajit][5] either using native [ffi][6] or by using [luabind][7].
* Add more functions.
* Add non-interactive mode.

 [5]: http://luajit.org/
 [6]: http://luajit.org/ext_ffi.html
 [7]: http://www.rasterbar.com/products/luabind.html


Copyright (C) 2011 Tai Chi Minh Ralph Eastwood
