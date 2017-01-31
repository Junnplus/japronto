# Japronto!

Japronto (from Portuguese "já pronto" meaning "already done") is a __screaming-fast__
Python 3.5+ web __micro-framework__ integrated with __pipelining HTTP server__
based on [uvloop](https://github.com/MagicStack/uvloop) and [picohttpparser](https://github.com/h2o/picohttpparser).

Tutorial
--------

1. [Getting started](tutorial/1_hello.md)
2. [Asynchronous handlers](tutorial/2_async.md)
3. [Router](tutorial/3_router.md)
4. [Request object](tutorial/4_request.md)
5. [Response object](tutorial/5_response.md)
6. [Handling exceptions](tutorial/6_exceptions.md)
7. [Extending request](tutorial/7_extend.md)

Features
--------

- HTTP 1.x implementation with support for chunked uploads
- Full support for HTTP pipelining
- Keep-alive connections with configurable reaper
- Support for synchronous and asynchronous views
- Master-multi worker based on forking
- Support for code reloading on changes
- Simple routing

License
-------

This software is distributed under [MIT License](https://en.wikipedia.org/wiki/MIT_License). This is a very permissive license that let's you use this software for any
commercial and non-commercial work. Full text of the license is
incuded in [LICENSE.txt](LICENSE.txt) file.

The source distribution of this software includes a copy of picohttpparser which is distributed under MIT license as well.
