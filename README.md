# YOLO Object Detection for CustomDataset
Weeds to increase crop yields Weeds are an unwanted intruder in the agricultural business. We have to detect the Crop and weeds using YOLOV8 Model.

#Dataset Folder 
I add the image for dataset folder must be have.Inside the train folder we have a images and labels folder for same for the Test and Val folder have a images and labels folder.

<img width="217" alt="Screenshot_20230219_023401" src="https://user-images.githubusercontent.com/112500121/219939652-7c3d3d15-cdfa-4326-87be-0cd1ccfbc24a.png">

#Custom.yaml formation
  The main thing for the YOLO Custom object detection is custom.yaml formation.It attached the format is given below and also I add the My custom.yaml file in this repository 
 
path: (optinal) 
train: # train folder path 
val:   # val images 
test:  # test images (optional)
nc: 2 #number of classes 
names: ['crop','weed'] # mention the object name 

The main thing in yaml file variable after colan(:) a space must be provided before the values.If you are correctly mention the path ,nc and names but forget the space it will show the error.


#Output 
   The all the output will be saved same path under the runs/detect/train.
   prediction result also saved in the same path in runs/detect/predict
   The Predict folder object detected images.
 
#Sample image
![agri_0_1026](https://user-images.githubusercontent.com/112500121/219940716-8d2392c6-9e01-4c32-b2f6-4e8ad5073292.jpeg)

Predicted Image
![agri_0_1026](https://user-images.githubusercontent.com/112500121/219940737-dc4ad608-658d-402e-8a54-c4d6865394e6.jpeg)


#Thank you !🤗✨



