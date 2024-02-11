# trivial-system-loader

`trivial-system-loader` provides a portable system downloader/loader
abstraction for Common Lisp.  Instead of hard-coding `(ql:quickload
:mysystem)`, use `(tsl:load-system :mysystem)`. `tsl:load-system` will
first try to use [ocicl](https://github.com/ocicl/ocicl) if available,
then [quicklisp](https://quicklisp.org), then plain
`asdf:load-system`.

`trivial-system-loader` was written by Anthony Green and is
distributed under the terms of the MIT license.  See the
`trivial-system-loader` source files for details.
