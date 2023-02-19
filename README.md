## Free energy calculation

This scripts concatenate gmx_density output in [.xvg] and create a density_profiles.csv datasheet.

Afterward, the free energy plots for all molecules are calculated according to the given formula:

**dG=-RTln(q(z))**

Both jupyter lab scripts generate two output files:

* density_profiles.csv
* free_energies.csv

The output may be visualized with matplotlib.