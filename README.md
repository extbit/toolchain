# Toolchain for ExtBit

The toolchain includes `clang` (well tweaked for ExtBit blockchain apps),
`llvm` based compilers for new language(s) and utilities for developing apps
and working with the ExtBit network.

Purpose
-------

* Minimize the OS differences
* Common compilation environment
* Cross compilation (experimental)
* Network branded compilation (verified)

Specification
=============

Latest version:

* v0.0.1-alpha (pre-release)

Languages:

* C17 (clang)
* C++2a (clang++)
* experimental new language(s) (in progress)

Operating systems:

* MacOSX (darwin)
* Linux/*nix (TODO)
* Windows (TODO)

Architectures:

* X86_64
* ARM/ARM64 (TODO)
* MIPS/MIPS64 (TODO)
* WebAssembly (experimental)

Versioning (experimental)
==========

The version number `v0.0.1` has three parts of digits, **major version**,
**minor version** and **patch version**.

The patch numver changes indicate **pre-release** version. That `v0.0.1` is
the first **pre-release**, no production version release yet.

TODOS
=====

* Other operating systems:
  * Linux distros, OpenBSD, Windows, Android, etc.
* New language designed for blockchain apps.

Known Issues
============

Please [submit known issues](https://github.com/extbit/toolchain/issues/new).
