Matlab code for Morotti et al. human atrial model with updated INa formulation.

This model integrates a Na current Markov model (Grandi et al. Biophys J. 2007;93:3835-47, and 
Wagner et al. Circ Arrhythm Electrophysiol. 2009;2:285-94) into the framework of the Grandi et al.
human atrial model (Circ Res. 2011;109:1055-66, available for download on this website).
The Na current model is here extended to reproduce the dose-dependent effect of the Na channel 
blocker ranolazine (as in Moreno et al. Circ Res. 2013;113:e50-61).

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

References:

Morotti S, McCulloch AD, Bers DM, Edwards AG, Grandi E.
Atrial-selective targeting of arrhythmogenic phase-3 earlyafterdepolarizations in human myocytes.
J Mol Cell Cardiol. 2016 Jul; 96:63-71. doi: https://doi.org/10.1016/j.yjmcc.2015.07.030

Grandi E, Pandit SV, Voigt N, Workman AJ, Dobrev D, Jalife J, Bers DM.
Human Atrial Action Potential and Ca2+ Model: Sinus Rhythm and Chronic Atrial Fibrillation.
Circ Res. 2011 Oct 14;109(9):1055-66. doi: https://doi.org/10.1161/CIRCRESAHA.111.253955

Please cite the above papers when using this model.
