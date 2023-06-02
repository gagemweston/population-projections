# PWI Population Projections

This is a version of [Population Wellbeing Initiative](https://sites.utexas.edu/pwi/) (PWI) projections and code from the 2023 working papers "Simulating the Long-Run Population Impacts of Child Mortality Reductions" by Sangita Vyas and Gage Weston and "Long-term population projections: Scenarios of low or rebounding fertility" by Sangita Vyas, Gage Weston, Dean Spears, and Michael Geruso. This code will be kept up-to-date with any new features our team designs.

### What is this program?

This program uses python to run the cohort component method to project population from 2025 until any given date. We use fertility and mortality conditions from the 2022 version of the United Nations World Population Prospects from 2025 until 2100, after which the program generates its own projections based on user input. You can define different 'treatments' which can alter the population size, fertility rates, or mortality rates and compare the effect of these treatments with the baseline projection where this treatment doesn't happen. 

This program was last updated May 2023. It was primarily written by Gage Weston, a researcher at Population Wellbeing Initiative at University of Texas at Austin as of May 2023, with help from Sangita Vyas at CUNY Hunter College. You may contact Gage at gageweston@utexas.edu for issues or questions about the code or contact Kevin Kuruc at kevinkuruc@utexas.edu to learn about PWI.

See [this YouTube tutorial](https://youtu.be/_lf5rqdI7hs) on how to use the program.

### This repository contains:

1. **input.csv**: demographic projections from UN WPP zero-migration variant (2022 version) for years 2025-2100, re-formatted for our program. To re-create this file, complete the steps at the top of "background code" in population_projections.ipynb.
2. **pop_projections.ipynb**: A jupyter notebook containing the python code to run the projections alongside instructions for how to use this program and meta-data describing the input/output files

### About PWI

PWI is an interdisciplinary research organization at University of Texas at Austin studying the long-term causes, consequences, and moral and political implications of low fertility and depopulation across the world.
