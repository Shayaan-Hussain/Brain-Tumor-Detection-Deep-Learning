# Brain Tumor Detection using modified VGG-19 and InceptionResnetV2

***IEEE Publication :*** This project was presented in International Conference on Industrial Electronics: Developments and Applications

## ***About the Project:***
Two pre-trained models, namely VGG-19 and Inception-ResNet V2 were modified to classify a Brain MRI Image as Tumor or Non Tumor.<br/><br/>

## ***About the Dataset Used:***
The following dataset was collected from Kaggle: <a href="https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection">Click Here</a><br/>
The dataset consists of 98 images of negative class and 155 images of positive class. These images were augmented using Keras Image Data Generator. The augmented data consists of 848 images of negative class and 883 images of positive class. These were further divided into training, testing and validation as 80%, 10% and 10% respectively.

## ***Results Acheived:***
#### ***<b>Modified VGG-19 Model:<b/>***
Accuracy achieved on Training Data : 99.71%<br/>
Accuracy achieved on Validation Data : 97.67%<br/>
Accuracy achieved on Testing Data : 94.86%<br/><br/>

#### ***<b>Modified Inception ResNet V2 Model:<b/>***
Accuracy achieved on Training Data : 99.28%<br/>
Accuracy achieved on Validation Data : 94.86%<br/>
Accuracy achieved on Testing Data : 97.09%<br/>

## ***To run this code:***
The code was executed on jupyter notebook with ***<b>python 3.9.13<b/>***<br/>
To install all the dependancies, run the following shell command :<br/>
```
pip install -r requirements.txt
```
To run the code of data augmentation, execute the cells in ```data_augmentation.ipynb``` file.<br/>
To run the code to train the models, execute the cells in ```model_training.ipynb``` file. <br/>

### ***Note:***
Inception ResNet V2 Model could not be uploaded due to high filesize.
