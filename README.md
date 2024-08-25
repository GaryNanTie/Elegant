# Elegant
- math pearls

In mathematics there is an aesthetic, a notion of beauty, often referred to as elegance.  For example, proofs that are pedestrian, turning the obvious crank, are eschewed in favor of those with surprising flashes of insight that bring a sense of wonder.  Typically an elegant proof is short and enables deep understanding.  The Shelah proof of the Hales-Jewett theorem comes to mind.

Recall Lewin’s maxim: 
There is nothing as practical as a good theory!



The file 'Koopman Transfer Learning via Pertubation' introduces a closed form solution for predicting future states of nonlinear dynamical systems. In constrast to spectral theory and neural network approaches to learning Koopman embeddings, a reproducing kernel Hilbert space Representer Theorem is used to construct both a Koopman operator and a Koopman embedding. The embedding has an invertible perturbation enabling future state prediction. Applications of data-driven Koopman analyses include fluid dynamics, plasma physics, protein folding, epidemiology, neuroscience, video processing, and robotics. The following algorithm given in these notes awaits implementation.



Dynamical system state prediction algorithm:

Given the following data:
a) a trajectory of observed dynamic system states x,
b) observable maps g from states to real numbers, and
c) measurements g(x), for each map and trajectory state

1) Determine a vector-valued Koopman operator K
2) Determine a Koopman embedding φ
3) Determine invertible perturbation φ^ (let ψ^ = φ^-inverse)
4) Predict future states x^ = ψ^(Kφ(x))


The 'FreD' file introduces deep learning in the 2-dimensional frequency domain via tensors akin to word embedding, to forecast nonlinear multivariate time series.

The 'HPNN' file introduces homotopy perturbation neural networks to parsimoniously solve general non-linear regression problems. Inspired by He’s homotopy perturbation method, we introduce a new deep learning technique to solve regression problems.  Essentially, a homotopy is constructed that deforms a linear problem to our desired non-linear regression 
problem.

The 'Sparse KAN' file sparsifies Kolmogorov-Arnold Network function matrix layers by introducing two sparse DCD matrix forms, enabling sub-quadratic computation.
