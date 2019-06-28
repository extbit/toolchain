# Toolchain for ExtBit

The toolchain includes `clang` (well tweaked for ExtBit blockchain apps),
`llvm` based compilers for new language(s) and utilities for developing apps
and working with the ExtBit network.

Purpose
-------

* Minimize the OS differences
* Common compilation environment
* Cross compilation (experimental)
* Universal execution on different platforms (TODO)
* Network branded compilation (verified production)
* Ease software construction process with [smart](https://github.com/extbit/smart)

Latest
------

* [v0.0.1-alpha](https://github.com/extbit/toolchain/releases/tag/v0.0.1-alpha)

Specification
=============

Languages:
----------

* C17 (clang)
* C++2a (clang++)
* experimental new language(s) (in progress)

Operating systems:
------------------

* MacOSX (darwin)
* Linux/*nix (TODO)
* Windows (TODO)

Architectures:
--------------

* X86_64
* ARM/ARM64 (TODO)
* MIPS/MIPS64 (TODO)
* WebAssembly (experimental)
* ExtBit specific arch (TODO)

Released Versions
=================

The version number `v0.0.1` has three parts, **major version**,
**minor version** and **patch version**. The patch number change normally
indicates bugfix or patching release. The minor number change normally
indicates usefull improvement without changing major features. The major
number change indicates an important feature upgrade.

That `v0.0.1-alpha` is the first alpha release.

* [v0.0.1-alpha](https://github.com/extbit/toolchain/releases/tag/v0.0.1-alpha)

TODOS
=====

* Other operating systems:
  * Linux distros, OpenBSD, Windows, Android, etc.
* New language designed for blockchain apps.

Known Issues
============

Please [submit your issues](https://github.com/extbit/toolchain/issues/new).
