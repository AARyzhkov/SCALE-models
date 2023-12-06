# MOX3600

This folder includes the full core models of MOX3600 with the EOEC fuel composition. The model is generally based upon the public domain and the OECD Nuclear Energy Agency benchmark:

> NEA, 2015. Benchmark for Neutronic Analysis of Sodium-cooled Fast Reactor Cores with Various Fuel Types and Core Sizes (No. NEA/NSC/R(2015)9). OECD Publishing, Paris.

The reference solution was obtained via CSAS6 with the ENDF/B-VII.1-based SCALE 6.2 library and the disabled probability tables, providing a smaller bias, due to the issue in the SCALE 6.2 libraries (should have been fixed in the SCALE 6.3 libraries). The result is in good agreement with the following work:

> Bostelmann, F., 2020. Systematic Sensitivity and Uncertainty Analysis of Sodium-Cooled Fast Reactor Systems (Doctoral dissertation). Ecole polytechnique fédérale de Lausanne, Switzerland.

## Citing

If you use the models in your work, please consider citing our paper for which we developed the model:

> Ryzhkov, A.A., Tikhomirov, G.V., Ternovykh, M.Yu., 2024. Angular distribution uncertainty influence in a large sodium-cooled fast reactor with mixed-oxide fuel. Annals of Nuclear Energy 197, 110248. https://doi.org/10.1016/j.anucene.2023.110248


