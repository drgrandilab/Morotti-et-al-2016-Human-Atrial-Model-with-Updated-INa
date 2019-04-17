Matlab code for Morotti et al. human atrial model.

_____________________________________________________________________________________________________
Contents:

readme.txt					this file

morotti_et_al_ham_ina_ran_main.m		loads initial conditions and runs the simulation
morotti_et_al_ham_ina_ran_model.m		excitation-contraction coupling model
morotti_et_al_ham_ina_ran_calcCurrents.m	supporting function for simulation output analysis

.mat files			initial conditions (steady-state at 1-Hz pacing)
- yf_ham_ina_ran_1Hz		control model (no acetylcholine, isoproterenol and ranolazine)
- yf_ham_ina_ran_ACh0p1_1Hz	0.1 uM acetylcholine (no isoproterenol and ranolazine)
- yf_ham_ina_ran_ACh1_1Hz	1 uM acetylcholine (no isoproterenol and ranolazine)

_____________________________________________________________________________________________________

Reference:

Morotti S, McCulloch AD, Bers DM, Edwards AG, Grandi E. (2015).
Atrial-selective targeting of arrhythmogenic phase-3 earlyafterdepolarizations in human myocytes.
J Mol Cell Cardiol. doi: 10.1016/j.yjmcc.2015.07.030

Please cite the above paper when using this model.