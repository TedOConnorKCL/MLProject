# MLProject

I have included in this repository the notebooks used to train each generation of the NN model used in this project, as well as the reconstruction analysis notebook. The training files will not run as I have not included the datasets due to their large size, however, you can look at them and see how each model was structured. 

The following files were used to train each generation:

1. Generation 1 - "Original_HK-training.ipynb"
2. Generation 2 - "HK-Separate.ipynb"
3. Generation 3 - "HK-training.ipynb"

The file "recon_check.ipynb" was used for all reconstruction analysis. You will require pytorch, matplotlib, numpy etc so it may be worth creating a virtual environment. 

Inside recon_check, there are all of the metrics and plots used in the report, as well as a number of others that were not included, as the report already contains over 40 figures. They were helpful tools for developing the model however, so they have been left in the recon_check file so that you can see them yourself. 


The paths of files within the recon_check.ipynb notebook will need to be changed to where you have saved the files locally, please alter the paths by navigating to the file on your machine and selecting 'copy path'.
