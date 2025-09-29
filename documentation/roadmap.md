---
title: Roadmap 2021-
permalink: /roadmap/
---

## Introduction

The FEniCS core libraries have undergone a major redevelopment to bring
new functionality, improved performance and better underpinning software
engineering. The FEniCS Project is now approximately 20 years old, and
over that time our understanding has developed and the available tools
have changed significantly. The latest developments of FEniCS follow
these principles:

- Compact, modular core designed to be extensible and to support custom
  additions
- Reduced public interface that could be kept more stable
- Proper namespacing
- Use of established standards and conventions wherever possible
  (design, packaging, testing, etc)
- Properly separated C++ and Python interfaces
- Simplified software engineering
- Distributed memory parallel design throughout
- Improved documentation
- Faster just-in-time compilation
- Support for modern Python JIT tools, e.g. [numba](http://numba.pydata.org/)
- Simple implementation of fast user 'kernels' from Python
- Just one way to perform an operation wherever possible

## New core functionality

### Short-term
- Support for ADIOS2 I/O
- Implemention of PointSource
- Support wider range of FE types (e.g. serendipity)
- FunctionSpaces on facets
