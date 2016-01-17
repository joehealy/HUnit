# HUnit

HUnit is a unit testing framework for Haskell, inspired by the
[JUnit](http://junit.org/) tool for Java.  HUnit is free software; see
its "License" file for details.

HUnit 1.1.1 consists of a number of files.  Besides Haskell source files
in Test/HUnit (whose names end in ".hs" or ".lhs"), these files include:

```
  * README.md       -- this file
  * doc/Guide.html  -- user's guide, in HTML format
  * LICENSE         -- license for use of HUnit
```

See the user's guide for more information.

## Changes

### 1.3.1.0

- add minimal support for GHC 8.0

### 1.3.0.0

- removed support for old compilers

- add source locations for failing assertions (GHC >= 7.10.2 only)
