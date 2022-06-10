# ImageClassificationonDiabeticRetinopathy
Diabetic Retinopathy (DR) is a diabetes complication that affects eyes. It is a complication that people with Type 1 or 
Type 2 diabetes could suffer from. It impacts the vision by damaging the blood vessels in the light-sensitive tissue in 
the retina. Since the diagnosis of retina images is a relative necessary and pressing topic, our group decided to do image 
classification on diabetic retinopathy images of 5 DR stages with the intention to make a precise and powerful detection system to diagnose this disease

## The layout of this repository
test folder: images used for test
validate folder: images used for validation
train folder: images used for training
VGG16.ipynb: code of VGG16 model
processing_efficientnet.ipynb: code of efficientNet model
mobilenet.ipynb: code of mobilenet model

## Instructions to run the code (VGG/Densenet)
1. Download the whole dataset from https://www.kaggle.com/datasets/amanneo/diabetic-retinopathy-resized-arranged?resource=download
2. Modify the path "/content/Mydrive/MyDrive/ECE228project/archive.zip" to your own path of the downloaded dataset
3. Run the code block by block

## Instructions to run the code(MobileNet/EfficientNet)
1. Download the whole dataset from https://www.kaggle.com/datasets/amanneo/diabetic-retinopathy-resized-arranged?resource=download
2. Unzip the dataset
3. Modify the path "/Users/katherinequan/Desktop/ECE228/FINALPROJECT/archive" to your own path of the unzipped dataset
4. Run the code block by block

## Packages used
1. numpy
2. pandas 
3. sklearn
4. matplotlib
5. cv2
6. itertools
7. os
8. shutil
9. glob
10. random
11. matplotlib
12. tensorflow
13. torch