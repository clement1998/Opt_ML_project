# Opt_ML_project

Project in Optimization for Machine Learning made by Loïc Signer and Clément Barbier on: How to achieve large batch size training of a DNN with SGD by adjusting hyperparameters?


## Structure

This project is composed of:
	*How_to_achieve_large_batch_size_training_of_a_DNN_with_SGD_by_adjusting_hyperparameters.pdf: The report of our project
	*Bibliography: All the articles cited in the report
	*Results: Folder where the results of the models where saved
	*OptML_project_main.ipynb: A Python Notebook to reproduce all our results

## Instructions

### Needed Libraries
	*Numpy
	*Pandas
	*Pytorch
	*Torchvison

### How to use the Python Notebook?

The notebook created and launched under Google Collab.

You can run all the notebook at once, it will choose the GPU if available otherwise the CPU will be used.
The results are saved on the drive under the folder OptML_project/, to be used and plot later.
At the beginning of the notebook, a variable path_to_files is used define where to save and load the results of the models. (This Notebook was run on Google Collab + Google Drive so change the path to "Results" to run it locally)


Running this notebook will give you our baseline result, our other result can be obtained when changing the parameters of the train_model function and using the sqrt/linearScaleRule as shown in the comment part of the function main.



