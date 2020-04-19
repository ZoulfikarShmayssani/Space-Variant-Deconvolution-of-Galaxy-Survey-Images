# Space-Variant-Deconvolution-of-Galaxy-Survey-Images

## Introduction
Removing the aberrations introduced by the point spread function (PSF) is a fundamental aspect of astronomical image processing. The presence of noise in observed images makes deconvolution a nontrivial task that necessitates the use of regularisation. This task is particularly difficult when the PSF varies spatially as is the case for the Euclid telescope.

## Work done

This work introduces the use of the low-rank matrix approximation as a regularisation prior for galaxy image deconvolution and compares its performance with a standard sparse regularisation technique. This new approach leads to a natural way to handle a space variant PSF. Deconvolution is performed using a Python code that implements a primal-dual splitting algorithm. 

## Data Set

The data set considered is a sample of 10 000 space-based galaxy images convolved with a known spatially varying Euclid-like PSF and including various levels of Gaussian additive noise.

Data set available at: http://www.cosmostat.org/software/sf_deconvolve

## Performace and results

Performance is assessed by examining the deconvolved galaxy image pixels and shapes. The results demonstrate that for small samples of galaxies sparsity performs better in terms of pixel and shape recovery, while for larger samples of galaxies it is possible to obtain more accurate estimates of the galaxy shapes using the low-rank approximation.



## References

1. Farrens, S., FM Ngolè Mboula, and J-L. Starck. "Space variant deconvolution of galaxy survey images." (2017).
2. Condat, Laurent. "A primal–dual splitting method for convex optimization involving Lipschitzian, proximable and linear composite terms." Journal of Optimization Theory and Applications 158.2 (2013): 460-479.
