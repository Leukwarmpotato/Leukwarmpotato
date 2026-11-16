## Poorvash Muthumaheswaran

MSc Machine Learning and Process Systems Engineering at Imperial College London. BEng Chemical Engineering (First Class) from the University of Edinburgh.

I work on machine learning for physical and process systems: surrogate models for expensive simulations, mechanistic process models, and optimisation and control.

### Projects

| Project | Description | Tools |
|---|---|---|
| [Porous media surrogates](https://github.com/Leukwarmpotato/porous-media-surrogates) | Lattice Boltzmann solver in JAX, validated against analytical solutions, used to label 1,000 porous geometries. A CNN that corrects a Kozeny-Carman baseline predicts permeability with 4.3% error, a third of the baseline’s, with calibrated uncertainty. | Python, JAX, PyTorch |
| [Photobioreactor Bayesian optimisation](https://github.com/Leukwarmpotato/pbr-bayesopt) | Gaussian process Bayesian optimisation of light intensity and dilution rate for biomass per kWh, run on a Python port of the reactor model below. Within 30 simulations it lands a median 0.18% from the true optimum against 3.46% for random search, and finds a design with 60% higher energy yield than the original. | Python, scikit-learn, SciPy |
| [Photobioreactor model](https://github.com/Leukwarmpotato/tubular-photobioreactor-model) | Dynamic model of a tubular photobioreactor for growing *Dunaliella salina*. 606 coupled stiff ODEs covering growth kinetics, light attenuation and carbonate chemistry, solved with DifferentialEquations.jl. | Julia |
| [FUGK distillation design](https://github.com/Leukwarmpotato/FUGK-Distillation-Column-Design) | Shortcut design of a multicomponent distillation column, from minimum stages and reflux ratio through to duties, exchanger areas and column diameter. | Python |

### Currently

Coursework at Imperial on multi-fidelity Bayesian optimisation, reinforcement learning and multi-objective optimisation.

### Skills

**Languages:** Python, Julia, MATLAB, SQL<br>
**Libraries:** PyTorch, JAX, scikit-learn, NumPy, SciPy, pandas, DifferentialEquations.jl<br>
**Engineering software:** UniSim, ANSYS Fluent, COMSOL, SolidWorks, Aspen HYSYS

### Contact

[LinkedIn](https://www.linkedin.com/in/poorvashmuthumaheswaran)
