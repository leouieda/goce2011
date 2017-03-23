# Optimal forward calculation method of the Marussi tensor due to a geologic structure at GOCE height

by **Leonardo Uieda, Everton P. Bomfim, Carla Braitenberg, and Eder Molina**

Abstract, code, poster and proceedings presented at the 4th International GOCE
User Workshop in Munich, Germany.

Poster is available on figshare:
[doi:10.6084/m9.figshare.92624](http://dx.doi.org/10.6084/m9.figshare.92624)

A PDF of the proceedings is available from: [leouieda.com](http://www.leouieda.com)

Results were generated using open-source software
[Tesseroids](http://tesseroids.leouieda.com/).

Citation:

> Uieda, L., E. P. Bomfim, C. Braitenberg, and E. Molina (2011), Optimal forward
> calculation method of the Marussi tensor due to a geologic structure at GOCE
> height, Proc. of 4th International GOCE User Workshop, pp. 1-5

## Abstract

The new observations of GOCE present a challenge to develop new calculation
methods that take into account the sphericity of the Earth. We address this
problem by using a discretization with a series of tesseroids. There is no
closed formula giving the gravitational fields of the tesseroid and numerical
integration methods must be used, such as the Gauss Legendre Cubature (GLC). A
problem that arises is that the computation times with the tesseroids are high.
Therefore, it is important to optimize the computations while maintaining the
desired accuracy. This optimization was done using an adaptive computation
scheme that consists of using a fixed GLC order and recursively subdividing the
tesseroids. We have obtained an optimum ratio between the size of the tesseroid
and its distance from the computation point. Furthermore, we show that this
size-to-distance ratio is different for the gravitational attraction than for
the gravity gradient tensor.
