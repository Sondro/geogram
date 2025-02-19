# geogram

![](https://github.com/BrunoLevy/geogram/wiki/geogram_banner.gif)

Geogram is a programming library with geometric algorithms.
It contains the main results in Geometry Processing from the former
ALICE Inria project, that is, more than 30 research articles published
in ACM SIGGRAPH, ACM Transactions on Graphics, Symposium on Geometry 
Processing and Eurographics. It was supported by two grants from the
European Research Council (ERC): GOODSHAPE and VORPALINE.

Geogram includes a simple yet efficient Mesh data structure (for surfacic
and volumetric meshes), exact computer arithmetics (a-la Shewchuck,
implemented in GEO::expansion ), a predicate code generator (PCK: the
Predicate Construction Kit), standard geometric predicates
(orient/insphere), Delaunay triangulation, Voronoi diagram, spatial
search data structures, spatial sorting) and less standard ones (more
general geometric predicates, intersection between a Voronoi diagram
and a triangular or tetrahedral mesh embedded in n dimensions), and 
semi-discrete optimal transport.


Compiling
---------
  - [Instructions for Linux](https://github.com/BrunoLevy/geogram/wiki/compiling_Linux)
  - [Instructions for Windows](https://github.com/BrunoLevy/geogram/wiki/compiling_Windows)
  - [Instructions for OS/X](https://github.com/BrunoLevy/geogram/wiki/compiling_MacOS)

Releases
--------
   - [Latest release](https://brunolevy.github.io/geogram/Releases/)

Mini tutorials and example programs
-----------------------------------
  - [Geogram wiki](https://github.com/BrunoLevy/geogram/wiki)

Programmer's reference manual
------------------------------
  - [Doxygen documentation](https://brunolevy.github.io/geogram/)

Design principles
-----------------
- Make it as *simple as possible* _(but not simpler)_
- Make it as *easy to use as possible*
- Make it as *easy to compile as possible*
- Maximize *speed*
- Minimize *memory consumption*
- *Minimize* number of *lines of code*
- *Minimize* number of *C++ classes*

_Simplicity is the ultimate sophistication [Leonardo da Vinci]_

References
----------
 - [Projects and publications with geogram](https://github.com/BrunoLevy/geogram/wiki/Publications)
 - [Third-party libraries](https://github.com/BrunoLevy/geogram/wiki/ThirdParty)
 - [Keynote Eurographics presentation on geogram](https://fr.slideshare.net/BrunoLevy4/the-joy-of-computer-graphics-programming).
