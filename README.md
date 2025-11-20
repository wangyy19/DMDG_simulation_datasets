# DMDG_simulation_datasets
The dataset provided here accompanies the initial conditions for generating DMDG by galaxy collisions.

These initial conditions files (.g1) correspond to Table 1 in [Wang et al (2509.24270)][https://arxiv.org/abs/2509.24270].
After installing the public software [Gadget4][https://wwwmpa.mpa-garching.mpg.de/gadget4/], running Gadget4 follows
```bash
mpiexec -np nodes Gadget4 param.txt
```
and results listed in Table 1 can be derived from snapshot_020.
