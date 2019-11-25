**[Bellinger, E. P.](https://earlbellinger.com), Kanbur, S. M., Bhardwaj, A., Marconi, M.** (2019). *When a Period Is Not a Full Stop: Light Curve Structure Reveals Fundamental Parameters of Cepheid and RR Lyrae Stars*. MNRAS accepted.

The notebooks (`Cepheids.ipynb` and `RR_Lyrae.ipynb`) provide the source code for all of the analysis and all of the figures presented in the paper. The `matplotlibrc` file is for making the plots pretty. 

The trained neural networks can be found in the files of the associated names (`Cepheids.ann` and `RR_Lyrae.ann`). They can be loaded using the `joblib` library. See the above `ipynb` notebook files for usage and best practices (e.g., not using them on data outside of the range of the training set). 

Catalogs of these networks applied to real data of Cepheid stars in the Large Magellanic Cloud and RR Lyrae stars in the Large and Small Magellanic Clouds and the galactic bulge can be found in the `catalogs` directory. 
