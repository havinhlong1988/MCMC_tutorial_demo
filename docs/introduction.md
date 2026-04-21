
This tutorial provides a step-by-step guide to performing **Markov Chain
Monte Carlo (MCMC) inversion** for geophysical applications, with a
focus on helping students understand both the **conceptual framework**
and the **practical implementation** of the method.

The original code used in this tutorial was developed by Elizabeth M.
Berg (e.g., Berg et al., 2018, 2020), with later improvements and
extensions contributed by Liu et al. (2021). This work is associated
with the research efforts of Fan-Chi Lin’s group at the University of
Utah. The earlier implementations mainly focused on using **B-spline
parameterization** to smooth the model. In contrast, this tutorial
adopts a **gradient-based approach**, which is more suitable for the
current application and provides a clearer interpretation of model
variations with depth.

MCMC inversion is a powerful technique that allows us to estimate model
parameters, such as subsurface velocity structures, by **sampling a
range of possible solutions** rather than finding a single best-fit
model. This probabilistic approach helps quantify uncertainties and
provides deeper insight into the reliability of inversion results.

However, for many beginners, the main difficulty is not the theory
itself, but understanding:

- how to **prepare and organize input data files**

- how to **prepare control files**

- and how to **execute the program.**

This tutorial is still evolving, and your feedback plays an important
role in improving it for future users. If you come across anything that
is confusing, incomplete, or could be explained more clearly, we would
really appreciate hearing from you. Your suggestions and comments help
us refine both the content and the structure of the tutorial. Please
feel free to reach out through the **“Give us feedback”** section in the
Appendix.

**References**

Berg, E. M., Lin, F.-C., Allam, A., Qiu, H., Shen, W., & Ben-Zion, Y.
(2018). Tomography of Southern California via Bayesian joint inversion
of Rayleigh wave ellipticity and phase velocity from ambient noise
cross-correlations. Journal of Geophysical Research: Solid Earth, 123,
9933–9949. <https://doi.org/10.1029/2018JB016269>

Berg, E. M., Lin, F.-C., Allam, A., Schulte-Pelkum, V., Ward, K. M., &
Shen, W. (2020). Shear velocity model of Alaska via joint inversion of
Rayleigh wave ellipticity, phase velocities, and receiver functions
across the Alaska transportable Array. Journal of Geophysical Research:
Solid Earth, 125, e2019JB018582.
<https://0120100299/10.1029/2019JB018582>

Liu, C.-N., Lin, F.-C., Huang, H.-H., Wang, Y., Berg, E. M., & Lin,
C.-H. (2021). High-resolution 3-D shear wave velocity model of Northern
Taiwan via Bayesian joint inversion of Rayleigh wave ellipticity and
phase velocity with Formosa array. Journal of Geophysical Research:
Solid Earth, 126, e2020JB021610. <https://doi.org/10.1029/2020JB021610>
