===========================================================================
Simulator for PrOjected donwlinK bEaMfOrmiNg (POKEMON) in massive MIMO
---------------------------------------------------------------------------
(c) 2016 Christoph Studer, Sven Jacobsson, and Oscar Castañeda
e-mail: studer@cornell.edu, sven.jacobsson@ericsson.com & oc66@cornell.edu
===========================================================================

# Important information:

If you are using the simulator (or parts of it) for a publication, then you MUST cite our paper:

@inproceedings{CastanedaGoldsteinStuder:OneBitBeamforming:2017,
  author={O. Casta\~neda and T. Goldstein and C. Studer},
  journal={Proceedings of the IEEE International Conference on Acoustics, Speech and Signal Processing},
  title={{POKEMON}: A Non-Linear Beamforming Algorithm for 1-bit Massive {MIMO}},
  month={Mar.},
  year={2017}
}

and clearly mention this in your paper. More information about our research can be found at: http://vip.ece.cornell.edu

# How to start a simulation:

Simply run  

>> POKEMON_MIMO_sim

which starts a simulation in a 128 BS antennas, 16 users massive MIMO system with QPSK modulation using ZF (with both infinite precision and 1-bit quantization) and 1-bit POKEMON as beamformers.

The simulator runs with predefined parameters. You can provide your own system and simulation parameters by passing your own "par"-structure (see the simulator for an example). 

We highly recommend you to execute the code step-by-step (using MATLAB's debug mode) in order to get a detailed understanding of the simulator. 

# Version 0.1 (January 5, 2017) - oc66@cornell.edu - initial version for public access
# Version 0.2 (August 14, 2017) - studer@cornell.edu - minor fixes and delayed release on GitHub