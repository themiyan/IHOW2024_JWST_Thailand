# IHOW2024_JWST_Thailand
NIRSpec workshop material for the I-HOW COSPAR JWST JWST Data Analysis and Processing Workshop (South East Asia) organised by NARIT.


If you are using the NARIT servers:
> conda activate nirspec_jdap
OR you can use the conda environment created for NIRCam with Dr. Christopher Willmer on Monday. 

Note you may have to follow instructions on install ipykernel in your local environment for the conda environment to be seen on jupyter notebook. 

Alternatively, you should install this in your own laptops. Install conda and follow:

> conda create --name jwst_nirspec python=3.11
> conda activate jwst_nirspec
> conda install ipykernel --name jwst_nirspec
> python -m ipykernel install --user --name=jwst_nirspec
> pip install ipython jupyter 
> pip install jwst 
> pip install msaexp

