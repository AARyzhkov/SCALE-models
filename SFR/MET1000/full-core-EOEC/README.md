# MET1000 

This folder includes the full core models of MET1000 (also known as ABR1000) with the EOEC fuel composition. The SCALE model is taken from the following works:

> Bostelmann, F., 2020. Systematic Sensitivity and Uncertainty Analysis of Sodium-Cooled Fast Reactor Systems (Doctoral dissertation). Ecole polytechnique fédérale de Lausanne, Switzerland.

> Bostelmann, F., Ilas, G., Celik, C., Holcomb, A.M., Wielselquist, W.A., 2021. Nuclear Data Assessment for Advanced Reactors (No. ORNL/TM-2021/2002). Oak Ridge National Laboratory, Oak Ridge, TN, US.

The following changes were introduced in our model:
* The redundunt layer of control rods in the control rod assemblies was removed
* The volumes were recalculated with an increased number of rays
* The symmetry was exploited (wedge)
* The statistical parameters were changed

The reference solution was obtained via CSAS6 with the ENDF/B-VII.1-based SCALE 6.2 library and the disabled probability tables, providing a smaller bias, due to the issue in the SCALE 6.2 libraries (should have been fixed in the SCALE 6.3 libraries). 


