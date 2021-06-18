# Opt_ML_project

Project in Optimization for Machine Learning made by Loïc Signer and Clément Barbier on: How to achieve large batch size training of a DNN with SGD by adjusting hyperparameters?


## Structure

This project is composed of:
*report.pdf: The report of our project
*Bibliography: All the articles cited in the report
*Results: Folder where the results of the models where saved
*Code.ipynb: A Python Notebook to reproduce all our results

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

Running this notebook will give you our baseline result, our other result can be obtained when changing the parameters of the train_model function and using the sqrt/linearScaleRule as shown in the comment part of the function main.



