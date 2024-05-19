# Overview
This project is a 3-category classification task based on the ResNet architecture, utilizing the Bivoid dataset. The model is designed to infer three distinct categories based on facial descriptions provided by FLACC.

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Python (version 3.x)
- Jupyter Notebook
- Required libraries

## Installation
To install the necessary libraries, run the following command:

pip install -r requirements.txt


## Usage
To train and infer the model, follow these steps:

1. Open the `FLACC_3cls.ipynb` Jupyter Notebook.
2. Execute the cells in order to train the model.
3. After training, the model can be used to infer the categories based on the input facial descriptions.

**Note:** The trained weights have been saved in `checkpoint.pt`. You can skip the training step and proceed directly to the inference step if you wish to use the pre-trained model.

### Training the Model
The training process is encapsulated within the `FLACC_3cls.ipynb` notebook. It includes data preprocessing, model definition, training, and validation.

### Inference
Once the model is trained, you can use it to predict the category of new facial descriptions. This can also be done within the same notebook or by exporting the trained model for use in other applications.

### Dataset
The Bivoid dataset is used for this project. Please ensure you have the appropriate rights and access to use this dataset.