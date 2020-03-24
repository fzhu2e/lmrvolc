[![DOI](https://zenodo.org/badge/229547352.svg)](https://zenodo.org/badge/latestdoi/229547352)

# LMRvolc: the data & code repository for "Resolving the differences in the simulated and reconstructed temperature response to volcanism"

This repository includes the data and code that can be used to reproduce the figures for the paper entitled _Resolving the differences in the simulated and reconstructed temperature response to volcanism_ published in _Geophysical Research Letters_.

The code is tested with Python v3.7, and the package [LMRt](https://github.com/fzhu2e/LMRt) (Zhu et. al., 2019) is required to perform essential analysis (e.g. Superposed Epoch Analysis) and the corresponding visualization.


## Repository Structure

+ notebooks
    - Fig-1.ipynb : the notebook that performs analysis and generates Fig. 1 of the main text
    - Fig-2.ipynb : the notebook that performs analysis and generates Fig. 2 of the main text
    - Fig-3.ipynb : the notebook that performs analysis and generates Fig. 3 of the main text
+ data
    - volc_forcing : volcanic forcing data
        - eVolv2k_v3_ds_1.nc : the eVolv2k version 3 Volcanic Stratospheric Sulfur Injection (VSSI) compilation (Toohey & Sigl, 2017).
        - IVI2TotalInjection_501-2000Version2.txt : Version 2 of IVI2 hemispheric and global volcanic stratospheric sulfate injection (Gao et al., 2008)
    - lmr_recons : the LMR reconstructions generated in this study
    - lmr_proxy_db : the LMR proxy database, which includes the PAGES 2k version 2 network (PAGES 2k Consortium, 2017)
    - gcm_sims : GCM simulations
    - psm_calibration : PSM calibration data
    - precalculated_corr : since the field data is too large to upload, only precalculated correlation between LMR reconstruction and the Berkeley Earth instrumental temperature analysis (Rohde et al., 2013) is uploaded for plotting; field data will be shared upon request
+ figs
    - Fig-1.pdf : Fig. 1 of the main text
    - Fig-2.pdf : Fig. 2 of the main text
    - Fig-3.pdf : Fig. 3 of the main text

## References

+ Gao C, Robock A, Ammann C (2008) Volcanic forcing of climate over the past 1500 years: An improved ice core-based index for climate models. Journal of Geophysical Research: Atmospheres 113:.  https://doi.org/10.1029/2008JD010239
+ PAGES 2k Consortium (2017) A global multiproxy database for temperature reconstructions of the Common Era. Scientific Data 4:170088.  https://doi.org/10.1038/sdata.2017.88
+ Toohey M, Sigl M (2017) Volcanic stratospheric sulfur injections and aerosol optical depth from 500 BCE to 1900 CE. Earth System Science Data 9:809–831.  https://doi.org/10.5194/essd-9-809-2017
+ Robert Rohde, Richard A. Muller, et al. (2013) Berkeley Earth Temperature Averaging Process. Geoinfor Geostat: An Overview 1:2.  doi:10.4172/gigs.1000103
+ Zhu, Emile-Geay, Hakim, Tardif, & Perkins. (2019, December 22). LMR Turbo (LMRt): a lightweight implementation of the LMR framework (Version 0.6.3). Zenodo.  http://doi.org/10.5281/zenodo.3590258

## How to cite this repository

+ Feng Zhu, Julien Emile-Geay, Gregory J. Hakim, Jonathan King, & Kevin J. Anchukaitis. (2020, March 24). LMRvolc: the data & code repository for "Resolving the differences in the simulated and reconstructed temperature response to volcanism". Zenodo.  http://doi.org/10.5281/zenodo.3725050
