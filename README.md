ocaml-soundtouch
==========

This package contains an OCaml interface for sound stretching library, 
otherwise known as libsoundtouch.

Please read the COPYING file before using this software.

Prerequisites:
-------------

- ocaml
- libsoundtouch
- findlib
- dune >= 2.0

Compilation
-----------

```sh
dune build
```

This should build both the native and the byte-code version of the
extension library.

Installation
------------

Via `opam`:

```sh
opam install gstreamer
```

Via `dune` (for developers):
```sh
dune install
```

This should install the library file (using ocamlfind) in the
appropriate place.

License
-------

Please see the COPYING file.

Author
------

This author of this software may be contacted by electronic mail at the
following address: savonet-users@lists.sourceforge.net.
