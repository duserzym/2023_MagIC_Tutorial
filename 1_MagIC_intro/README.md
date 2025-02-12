# Part 1: Anatomy of a MagIC contribution

1. Log-in to MagIC/Earthref (https://www2.earthref.org/MagIC)
2. Go to upload tool (https://www2.earthref.org/MagIC/upload)
3. Download and examine contribution 

   <img src="images/download_contribution.png" width="500"/>
4. Go to Data model to learn table/column names (https://www2.earthref.org/MagIC/data-models/3.0)
5. Go back to main upload page and let's drag and drop the file to upload

   <img src="images/upload_data.png" width="500"/>
6. Upon uploading, we can examine the tables which are parsed and matched up with the table name and data model fields

   <img src="images/import_data.png" width="500"/>
7. Click the upload button in the lower right, which will bring you to an upload page where you can click through to upload data into your private workspace
   
   <img src="images/private_workspace.png" width="500"/>
8. Here we can add the DOI for the study which is `10.1029/93JB00024` (then click save), add the lab for the study `Paleomagnetic Laboratory (USGS Menlo Park, USA)`, and then click to validate the contribution
   
   <img src="images/manage_contribution.png" width="500"/>
9. Once the study is validated, a contribution can be published (let's not do that here as this study is already in MagIC) or for a private contribution a private link can be shared. Sharing such a link enables data to be made available for peer review. Note that the DOI for the contribution (Future Data DOI) is already available at this stage which enables the data to be properly referenced within a manuscript when it is submitted. 

   <img src="images/private_share.png" width="400"/>

# Part 2: Inspecting a contribution using PmagPy

In this part of the tutorial, we are going to download and inspect a MagIC contribution using PmagPy. We will use a Jupyter notebook that is hosted on the EarthRef.org JupyterHub server:

 https://jupyterhub.earthref.org/ 

This JupyterHub enables you to run PmagPy code without having to install anything locally. You can get to it via the MagIC website:

<img src="images/jupyter_link.png" width="500"/>

Once you are on JupyterHub, open the `MagIC Workshop 2023 Tutorial - Setup.ipynb` notebook:

<img src="images/setup_notebook.png" width="500"/>

By executing cells in this setup notebook, you will install the MagIC workshop materials into your JupyterHub. We will now be working in a notebook called `Inspecting_a_MagIC_contribution.ipynb` within the `1_MagIC_intro` folder of the `2023_MagIC_Tutorial` folder.

<img src="images/notebook_navigation.png" width="500"/>

We will use this notebook to inspect a MagIC contribution using `PmagPy` functions.

<img src="images/inspecting_notebook.png" width="500"/>