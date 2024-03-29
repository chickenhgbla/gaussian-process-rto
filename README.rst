====================
gaussian-process-rto
====================

Steady state real time optimisation using Gaussian processes to model systems

This repository contains MATLAB files for performing real time optimisation using Gaussian processes. The Gaussian process model is created using MATLAB's fitrgp function, and optimised using MATLAB's fmincon function. 

An example script `example_hysys.m </example_hysys.m>`_ is provided to show optimisation performed on the HYSYS file `testing.hsc </testing.hsc>`_.

-----
To-Do
-----

MATLAB:

- Add plotting function for GPCreator
- Add Williams-Otto file for fast testing
- Add forgetting factor
- Add function to test for system violation

HYSYS:

- Case study function over entire operating envelope
- Level control storage drums