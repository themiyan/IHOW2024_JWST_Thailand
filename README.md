# IHOW2024_JWST_Thailand
NIRSpec workshop material for the I-HOW COSPAR JWST JWST Data Analysis and Processing Workshop (South East Asia) organised by NARIT.


If you are using the NARIT servers there are two options:

1. Use the nirspec_jdap environment
> conda activate nirspec_jdap

2. You can use the conda environment created for NIRCam with Dr. Christopher Willmer on Monday.
> conda activate "name of env you created"

Note you may have to follow instructions on installing ipykernel in your local environment for the conda environment to be seen on jupyter notebook. The instructions from Monday were: 

> conda activate nirspec_jdap\
> conda install ipykernel --name nirspec_jdap\
> python -m ipykernel install --user --name=nirspec_jdap\
> pip install ipython jupyter

Then regardless of what option selected above"
> pip uninstall jwst\
> pip install jwst\
> pip install msaexp

Alternatively, you should install this in your own laptops. This is recomended because you will have access to it once you leave the workshop. Install conda and follow:

> conda create --name nirspec_jdap python=3.11\
> conda activate nirspec_jdap\
> conda install ipykernel --name nirspec_jdap\
> python -m ipykernel install --user --name=nirspec_jdap\
> pip install ipython jupyter\
> pip install jwst\
> pip install msaexp

You will have to set the CRDS server and path configurations. In the notebooks, we do this within the code itself. 

