# LMRvolc: the data & code repository for "Resolving the differences in the simulated and reconstructed temperature response to volcanism"

This repository includes the data and code that can be used to reproduce the figures for the paper entitled _Resolving the differences in the simulated and reconstructed temperature response to volcanism_ published in _Geophysical Research Letters_.

The code is tested with Python v3.7, and the package [LMRt](https://github.com/fzhu2e/LMRt) is required.


## Repository Structure

+ data
    - volc_forcing : volcanic forcing data
        - eVolv2k_v3_ds_1.nc : the eVolv2k version 3 Volcanic Stratospheric Sulfur Injection (VSSI) compilation (Toohey & Sigl, 2017).
        - IVI2TotalInjection_501-2000Version2.txt : Version 2 of IVI2 hemispheric and global volcanic stratospheric sulfate injection (Gau et al., 2008)
    - lmr_recons : LMR reconstructions
    - gcm_sims : GCM simulations
    - psm_calibration : PSM calibration data
    - precalculated_corr : precalculated correlation between LMR reconstruction and the Berkeley Earth instrumental temperature analysis (Rohde et al., 2013)
+ notebooks
    - Fig-1.ipynb : the notebook that performs analysis and generates Fig. 1 of the main text
    - Fig-2.ipynb : the notebook that performs analysis and generates Fig. 2 of the main text
    - Fig-3.ipynb : the notebook that performs analysis and generates Fig. 3 of the main text
+ figs
    - Fig-1.pdf : Fig. 1 of the main text
    - Fig-2.pdf : Fig. 2 of the main text
    - Fig-3.pdf : Fig. 3 of the main text
