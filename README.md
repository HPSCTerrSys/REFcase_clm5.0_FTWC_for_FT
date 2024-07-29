# REFcase_clm5.0_FTWC_for_FT
Reference case for clm5.0_FTWC of FruitTree

This test case is a point case of an apple orchard in the Adige River valley, South Tyrol, Italy (46°21′ N, 11°16′ E; 240 m a.s.l.).

Forcing data for the case were created on an hourly basis from 2009-2020 using meteorological data, recorded partly at an EC tower in the orchard and at the Laimburg meteorological station located 4 km from the site (46°23′ N, 11°17′ E; 224 m a.s.l.). 

Orchard structure and available sand, clay, and organic matter fractions from the site were used to characterize the surface file (`surfdata_1x1_Adige_hist_78pfts_CMIP6_simyr2000_c210125_APPLE.nc`).

The newly implemented apple crop functional type (PFT 35 and 36: rainfed and irrigated apple) was parameterized using site measurements, literature values, and model calibration. The parameter file containing new and updated parameters is `clm5_params.c171117__FruitTree_with_cv.nc`.

Detailed information on the technical development and modelling results were published in <a href="https://gmd.copernicus.org/articles/15/5167/2022/" target="_blank">Dombrowski et al. (2022)</a>. Additionally, the FruitTree development was used in a recent publication in a Greek apple growing region (<a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2023WR036139" target="_blank">Dombrowski et al., 2024</a>).