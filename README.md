[![DOI](https://zenodo.org/badge/229547352.svg)](https://zenodo.org/badge/latestdoi/229547352)

# LMRvolc: data & code repository for "Resolving the differences in the simulated and reconstructed temperature response to volcanism"

This repository includes the data and code that can be used to reproduce the figures for the paper:
+ Zhu, F., Emile‐Geay, J., Hakim, G. J., King, J., & Anchukaitis, K. J. (2020). Resolving the Differences in the Simulated and Reconstructed Temperature Response to Volcanism. Geophysical Research Letters, 47(8), e2019GL086908. https://doi.org/10.1029/2019GL086908

The code is tested with Python v3.7, and the package [LMRt](https://github.com/fzhu2e/LMRt) (Zhu et. al., 2019) is required to perform essential analysis (e.g. Superposed Epoch Analysis) and the corresponding visualization.

Note: due to shortage of GitHub LFS storage of the account, the directory for data is moved to Google Drive and can be downloaded with this [link](https://drive.google.com/drive/folders/1cN0zy9dSc1FnctnDAfTl0hJcATCUNl4F?usp=sharing).

## Repository Structure

+ notebooks
    - Fig-1.ipynb : the notebook that performs analysis and generates Fig. 1 of the main text
    - Fig-2.ipynb : the notebook that performs analysis and generates Fig. 2 of the main text
    - Fig-3.ipynb : the notebook that performs analysis and generates Fig. 3 of the main text
    - Fig-4.ipynb : the notebook that performs analysis and generates Fig. 4 of the main text
+ data (moved to Google Drive: [download link](https://drive.google.com/drive/folders/1cN0zy9dSc1FnctnDAfTl0hJcATCUNl4F?usp=sharing))
    - volc_forcing : volcanic forcing data
        - eVolv2k_v3_ds_1.nc : the eVolv2k version 3 Volcanic Stratospheric Sulfur Injection (VSSI) compilation (Toohey & Sigl, 2017).
        - IVI2TotalInjection_501-2000Version2.txt : Version 2 of IVI2 hemispheric and global volcanic stratospheric sulfate injection (Gao et al., 2008)
    - lmr_recons : the LMR reconstructions generated in this study
    - lmr_proxy_db : the LMR proxy database, which includes the PAGES 2k version 2 network (PAGES 2k Consortium, 2017)
    - gcm_sims : GCM simulations generated by iCESM (Stevenson et al., 2019; Brady et al., 2019), CESM1 (Otto-Bliesner et al., 2015), BCC CSM1.1 (Wu et al., 2014), GISS-E2-R (Schmidt et al., 2006), HadCM3 (Gordon et al., 2000), IPSL-CM5A-LR (Dufresne et al., 2013), MIROC-ESM (Watanabe et al., 2011), MPI-ESM-P (Giorgetta et al., 2013), CSIRO (Rotstayn et al., 2012), and CCSM4 (Landrum et al., 2012)
    - psm_calibration : PSM calibration data
    - precalculated_corr : since the field data is too large to upload, only precalculated correlation between LMR reconstruction and the Berkeley Earth instrumental temperature analysis (Rohde et al., 2013) is uploaded for plotting; field data will be shared upon request
+ figs
    - Fig-1.pdf : Fig. 1 of the main text
    - Fig-2.pdf : Fig. 2 of the main text
    - Fig-3.pdf : Fig. 3 of the main text
    - Fig-4.pdf : Fig. 4 of the main text

## References
+ Brady E, Stevenson S, Bailey D, et al (2019) The Connected Isotopic Water Cycle in the Community Earth System Model Version 1. Journal of Advances in Modeling Earth Systems 11:2547–2566. https://doi.org/10.1029/2019MS001663
+ Dufresne J-L, Foujols M-A, Denvil S, et al (2013) Climate change projections using the IPSL-CM5 Earth System Model: from CMIP3 to CMIP5. Clim Dyn 40:2123–2165. https://doi.org/10.1007/s00382-012-1636-1
+ Gao C, Robock A, Ammann C (2008) Volcanic forcing of climate over the past 1500 years: An improved ice core-based index for climate models. Journal of Geophysical Research: Atmospheres 113:. https://doi.org/10.1029/2008JD010239
+ Giorgetta MA, Jungclaus J, Reick CH, et al (2013) Climate and carbon cycle changes from 1850 to 2100 in MPI-ESM simulations for the Coupled Model Intercomparison Project phase 5. Journal of Advances in Modeling Earth Systems 5:572–597. https://doi.org/10.1002/jame.20038
+ Gordon C, Cooper C, Senior CA, et al (2000) The simulation of SST, sea ice extents and ocean heat transports in a version of the Hadley Centre coupled model without flux adjustments. Climate Dynamics 16:147–168.  https://doi.org/10.1007/s003820050010
+ Landrum L, Otto-Bliesner BL, Wahl ER, et al (2012) Last Millennium Climate and Its Variability in CCSM4. J Climate 26:1085–1111.  https://doi.org/10.1175/JCLI-D-11-00326.1
+ Otto-Bliesner BL, Brady EC, Fasullo J, et al (2015) Climate Variability and Change since 850 CE: An Ensemble Approach with the Community Earth System Model. Bull Amer Meteor Soc 97:735–754.  https://doi.org/10.1175/BAMS-D-14-00233.1
+ PAGES 2k Consortium (2017) A global multiproxy database for temperature reconstructions of the Common Era. Scientific Data 4:170088.  https://doi.org/10.1038/sdata.2017.88
+ Robert Rohde, Richard A. Muller, et al. (2013) Berkeley Earth Temperature Averaging Process. Geoinfor Geostat: An Overview 1:2. doi:10.4172/gigs.1000103
+ Rotstayn LD, Jeffrey SJ, Collier MA, et al (2012) Aerosol- and greenhouse gas-induced changes in summer rainfall and  circulation in the Australasian region: a study using single-forcing climate  simulations. Atmos Chem Phys 12:6377–6404. https://doi.org/10.5194/acp-12-6377-2012
+ Schmidt GA, Ruedy R, Hansen JE, et al (2006) Present-Day Atmospheric Simulations Using GISS ModelE: Comparison to In Situ, Satellite, and Reanalysis Data. J Climate 19:153–192. https://doi.org/10.1175/JCLI3612.1
+ Stevenson S, Otto‐Bliesner BL, Brady EC, et al (2019) Volcanic Eruption Signatures in the Isotope-Enabled Last Millennium Ensemble. Paleoceanography and Paleoclimatology 34:1534–1552. https://doi.org/10.1029/2019PA003625
+ Toohey M, Sigl M (2017) Volcanic stratospheric sulfur injections and aerosol optical depth from 500 BCE to 1900 CE. Earth System Science Data 9:809–831.  https://doi.org/10.5194/essd-9-809-2017
+ Watanabe S, Hajima T, Sudo K, et al (2011) MIROC-ESM 2010: Model description and basic results of CMIP5-20c3m experiments. Geoscientific Model Development 4:845–872. https://doi.org/10.5194/gmd-4-845-2011
+ Wu T, Song L, Li W, et al (2014) An overview of BCC climate system model development and application for climate change studies. Acta Meteorol Sin 28:34–56. https://doi.org/10.1007/s13351-014-3041-7
+ Zhu, Emile-Geay, Hakim, Tardif, and Perkins. (2019, December 22). LMR Turbo (LMRt): a lightweight implementation of the LMR framework (Version 0.6.3). Zenodo. http://doi.org/10.5281/zenodo.3590258

## How to cite this repository
+ Feng Zhu, Julien Emile-Geay, Gregory J. Hakim, Jonathan King, & Kevin J.  Anchukaitis. (2020, March 24). LMRvolc: the data & code repository for "Resolving the differences in the simulated and reconstructed temperature response to volcanism". Zenodo.  http://doi.org/10.5281/zenodo.3725030.


