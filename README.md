# Mask-No-Mask-Face-Detection
## 1st step 
Map to google drive by mounting the drive
### 2nd step 
Install Yolov5 and clone the github repository. Check if GPU is available on collab. 
#### 3rd step
Training the model using the dataset thats stored on our drive(The copy of dataset has to be placed in the yolov5 folder with the yaml file). Run 'Train.py' Mention the image size, number of batches, number of epochs we will be running on the dataset, specify the data, specify the model we will be using, randomly initialize the weights and specify the folder where the weights will be stored and specify the optimization algorithm we will be running.
### 4th step
After the model is trained we can run inferences on videos(mp4) images(jpg) and youtube links. We need to run 'detect.py' and specify the folder where the weights are stored, specify the source of input which can be video(youtube link or mp4) or image. define the iou-thres and conf-thres(values are given by default). 
After running inferences the outputs are stored on drive
