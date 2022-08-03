# One-Dimensional Model for TRMLs
This repository contains annotated notebooks that can be used to compute one-dimensional solutions of Turbulent Radiative Mixng Layers.

Notebooks 1 & 2 allow users to specific their choices of $\mathcal{M}_{\rm rel}$, $\chi$, $\tau$, h, $f_{\nu}$, and $Pr$ and compute a corresponding solution using either the cosine vx or the cosine x-momentum profile setup, respectively. 

Notebooks 3 & 4 allow users to specific their choices of $\mathcal{M}_{\rm rel}$, $\chi$, $\tau$ and computes the corresponding $f_{\nu}$ and $Pr$ that satisfies energy conservation ($\mathcal{H}_visc = 0.5 \dot m \mathcal{M}_{\rm rel}^2$). (again, using either the cosine vx or the cosine x-momentum profile setup, respectively)

The folder named column_density_calculation contains notebook 5 that can be used to calculate a 1D solution using the cosine vx profile and a realistic cooling curve, and plot the corresponding ion fractions and ion column densities for any list of ions of interest. In order to run the notebook successfully, the user have to download two files: edot_P1e3.data.npz, which can be found in the column_density_calculation folder as well, and hm2012_hr.h5, which can be downloaded at this website: http://trident-project.org/data/ion_table/
