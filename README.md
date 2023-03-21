[![Actions Status](https://github.com/tbrowder/Windows-Test/actions/workflows/windows.yml/badge.svg)](https://github.com/tbrowder/Windows-Test/actions)

NAME
====

**Windows::Test** - Provides a '/.github/workflows/windows.yml' file for Win64 Raku module testing

SYNOPSIS
========

```raku
use Windows::Test;
```

DESCRIPTION
===========

**Windows::Test** is intended to provide a comprehensive set of Windows OS system components for Gitbub Workflows testing of any Raku module on Github-provided Windows computer.

Users are encouraged to file an issue anytime this module's `/.github/workflows/windows.yml` file doesn't work for your module. Please include a link to the problem repository on [https://github.com](https://github.com).

TODO
----

Use Choclatey to add some programs to the Github Workflow Windows Virtual Machine including:

  * `libfreetype6-dev`

    This C/C++ library is required for many of the `PDF*` modules in the Raku module collections.

AUTHOR
======

Tom Browder <tbrowder@acm.org>

COPYRIGHT AND LICENSE
=====================

© 2023 Tom Browder

This library is free software; you may redistribute it or modify it under the Artistic License 2.0.

