## HOPGD

HOPGD, abbreviation for Higher-Order Proper Generalized Decomposition, is a multi-dimensional arrays decomposition method. Similarly to PARAFAC, it can be used to compress multi-dimensional arrays to multiple simple vectors. But differently, it determines automatically the necessary number of vectors for a given approximation accuracy. 

Beside data compression, HOPGD can be used for reduced order surrogate modeling,  model calibration and optimization, uncertainty quantification, as well as real-time simulation of complex systems.

This website summarizes our recent work on HOPGD and shares some implementation examples. If you use the codes, please consider citing our work.

### Standard implementation

Standard implementation of HOPGD is based on full order arrays with known values for all the components. An example of full order arrays is a N-by-N matrix fulfilled by N^2 given values. Using HOPGD can significantly reduce the storage momery for such matrix.  

Applications related to this implementation can be found below

1. Lu, Y., Blal, N., & Gravouil, A. (2018). Multi-parametric space-time computational vademecum for parametric studies: Application to real time welding simulations. Finite Elements in Analysis and Design. [url](https://www.sciencedirect.com/science/article/pii/S0168874X16305832)

2. Blal, N., & Gravouil, A. (2019). Non-intrusive data learning based computational homogenization of materials with uncertainties. Computational Mechanics. [url](https://link.springer.com/article/10.1007/s00466-019-01682-7)

**A matlab code is available** [**`here`**](https://github.com/yelu-git/hopgd/blob/master/New%20folder.zip)


### Implementation in case of gappy data

HOPGD can be performed with sparse/gappy arrays. This kind of arrays can have many unknown values for the components and usually arises from problems where only incomplete data is available, e.g. experimental mesurement by sensors or the generation of complet data is not affordable. 

Applications related to this implementation can be found below

1. Lu, Y., Blal, N., & Gravouil, A. (2018). Adaptive sparse grid based HOPGD: Toward a nonintrusive strategy for constructing space‐time welding computational vademecum. International Journal for Numerical Methods in Engineering. [url](https://onlinelibrary.wiley.com/doi/abs/10.1002/nme.5793)

2. Lu, Y., Blal, N., & Gravouil, A. (2019). Datadriven HOPGD based computational vademecum for welding parameter identification. Computational Mechanics. [url](https://link.springer.com/article/10.1007/s00466-018-1656-8)

**A matlab code of sparse HOPGD is available** [**`here`**](https://link.springer.com/article/10.1007/s00466-019-01682-7), **the code for parameter identification is** [**`here`**](https://link.springer.com/article/10.1007/s00466-019-01682-7)


### Contact

Contact me: ye.lu@northwestern.edu, if you have any questions.

We would like to acknowledge Dr. Shuai Chen for his help in the database generation for our work.

