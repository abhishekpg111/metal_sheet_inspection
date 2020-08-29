# metal_sheet_inspection

This is project is to classifly 6 different types of deffects in hot rolled steel metal sheets. It is trained using CNN in Keras with tensorflow as backend. 

    class_names = ['crazing',
    'inclusion',
    'patches',
    'pitted_surface',
    'rolledin_scale',
    'scratches']

## 1. Development Environment
- Google colaboratory
- tensorflow 2.0

__Step 1: Download the data set__

Download  the dataset (train folder) and upload to the google drive.

The dataset is prepared using imagedatagenerator

__Step 2: Run the jupyter notebook__

upload and run all the cells of the jupyter notebook in google colab. It uses data augmentation technique to prevent over fitting. 

## Model performance 

Train loss      : 0.15   Train accuracy      : 0.95

Validation loss : 0.04   Validation accuracy : 0.99
