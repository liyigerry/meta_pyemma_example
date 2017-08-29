# meta_pyemma_example
metadynamics trajectory analysis by pyemma

This is an example for (issues)[https://github.com/markovmodel/PyEMMA/issues/1014#issuecomment-325313185].

2017.08.29, asking for help from @fabian-paul

metadynamics simulation

I select two distance between the center of mass of atom groups as collective variables (CVs), and then run using well-temper method with Gromacs, seeing plumed.dat.

After simulation, I got these following files:
1. CVS, which contain CVs as time evolution.
2. HILLS_CVS, which contain the bias added during the simulation
3. fes.dat, which generated by run plumed driver method.

For my understanding, I try to employ the tram in pyemma to analysis this metadynamics trajectory.

The ipython notebook is at emma.ipynb or [gist](https://gist.github.com/liyigerry/3b6b80a671003d268dd9f5cbbf23587b)
