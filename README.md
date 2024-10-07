# parameter_estimation

Repository to learn signal parameter estimation with PyMC. The final goal is to estimate the mass quotient parameter for a nonspinning binary black hole signal. The estimation should be done with a custom likelihood function which can be found at [Canizares, Priscilla, et al. "Accelerated gravitational wave parameter estimation with reduced order modeling."](https://link.aps.org/accepted/10.1103/PhysRevLett.114.071104), (Eq. 1).

To build the likelihood function we use [Scikit-reducedmodel](https://github.com/francocerino/scikit-reducedmodel), a package that performs subdomain partition to achieve higher precision.

## Step 1: Random signal parameter estimation with predefined likelihood
The goal here is get to know pyMC package and perform parameter estimation on a simple signal 

## Step 2: Gravitational wave parameter estimation with predefined likelihood
we use pyMC with a gravitational signal to estimate mass quotient q

## Step 3: Gravitational wave parameter estimation with custom likelihood

## Step 4: Gravitational wave parameter estimation with ROQs likelihood



## References

[1] Canizares, Priscilla, et al. "Accelerated gravitational wave parameter estimation with reduced order modeling." Physical review letters 114.7 (2015): 071104.
[2] Canizares, Priscilla, et al. "Gravitational wave parameter estimation with compressed likelihood evaluations." Physical Review D—Particles, Fields, Gravitation, and Cosmology 87.12 (2013): 124005.
[3] Tiglio, Manuel, and Aarón Villanueva. "Reduced order and surrogate models for gravitational waves." Living Reviews in Relativity 25.1 (2022): 2.
[4] Cerino, Franco, J. Andrés Diaz-Pace, and Manuel Tiglio. "An automated parameter domain decomposition approach for gravitational wave surrogates using hp-greedy refinement." Classical and Quantum Gravity 40.20 (2023): 205003.
