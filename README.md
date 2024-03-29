**[Bellinger, E. P.](https://earlbellinger.com), Kanbur, S. M., Bhardwaj, A., Marconi, M.** (2019). *[When a Period Is Not a Full Stop: Light Curve Structure Reveals Fundamental Parameters of Cepheid and RR Lyrae Stars](https://arxiv.org/abs/1911.11767)*. MNRAS accepted.

The notebooks (`Cepheids.ipynb` and `RR_Lyrae.ipynb`) provide the source code for all of the analysis and all of the figures presented in the paper. The `matplotlibrc` file is for making the plots pretty. 

Github sometimes has problems displaying jupyter notebooks. If the notebooks do not display properly, try these nbviewer links instead:
[Cepheids.ipynb](https://nbviewer.jupyter.org/github/earlbellinger/Cepheid-neural-network/blob/master/Cepheids.ipynb), 
[RR_Lyrae.ipynb](https://nbviewer.jupyter.org/github/earlbellinger/Cepheid-neural-network/blob/master/RR_Lyrae.ipynb). 

The trained neural networks can be found in the files of the associated names (`Cepheids.ann` and `RR_Lyrae.ann`). They can be loaded using the `joblib` library. See the above `ipynb` notebook files for usage and best practices (e.g., not using them on data outside of the range of the training set). 

Catalogs of these networks applied to real data of Cepheid stars in the Large Magellanic Cloud and RR Lyrae stars in the Large and Small Magellanic Clouds and the galactic bulge can be found in the `catalogs` directory. 
