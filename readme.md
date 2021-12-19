# PROCEDURE

## TRAINING

To implement the Transfer Learning Model, we first Trained our own model and saved the model which can be then used to evaluate the Transfer Learning model. The related dataset and code can be found under **./env1** directory.

<br />

Dataset Directory: **./env1/MFPT_DS_ENV1.mat**

CNN Code Runner Directory: **./env1/cnn_save.ipynb**

<br />

To Train the CNN model, we just need to run the CNN Code Runner File. This also saves the model in the **./env2/env1sv** directory to be used for later.
<br />
<br />

## TRANSFER LEARNING

We have already saved the model weights for Transfer Learning in the Training Phase. The dataset, CNN code runner, and saved model can be found under the following directory.

<br />

Dataset Directory: **./env2/MFPT_DS_ENV2.mat**

CNN Code Runner Directory: **./env1/cnn_load.ipynb**

Saved Model from training phase: **./env2/env1sv**

<br />

To execute the Transfer Learning model, we just need to run the **cnn_load.ipynb** file which will automatically load the dataset and the model weights and architectures and execute the model.

<br />

# Note

The following contains dataset from MFPT repository. The CWRU and MIMII follows the same procedure but the dataset is different.

CWRU: https://engineering.case.edu/bearingdatacenter

MIMII: https://zenodo.org/record/3384388#.XxXloZ4zaUk
