# Aplication 5: Black-Box Methods
Contributed by: Diogenes Figueroa

The power of reduced basis methods lies in their ability to capture the directions of maximal variation of some high-dimensional representation of our objects of interest. By concentrating on the most relevant of those directions we can obtain a low-dimensional representation (the reduced coordinates) of the problem which, although not perfect, can capture a lot of the dynamics of the system to a sufficiently good degree. 

In all the examples that have been discussed so far we first found the reduced coordinates -usually through a principal component analysis- and then took the analytical expression governing the dynamics of our system and built the Galerkin projections using these reduced coordinates. But what if we don't know the governing equations for our system? What if we know them but we can't efficiently transform them into their reduced counter parts (when the EIM fails)? Can we build an approximation of these equations from the data itself? It would make sense that it is so, since the solutions all have in common the governing equation. This is what we explore in this chapter.
