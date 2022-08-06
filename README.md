# Object-Detection-YoloV5

Dataset:
Dataset should have images along with their annotation file. The annotation should be done in .txt so that it will be easy for us to train the model.

Directories:
Create 3 directories. One is for training data, one is for validation data and one for both training and testing data.

Training data directory:
Take around 80% of the image with their annotation file for the training.

Validation data directory:
Take 20% data with their annotation file for the validation purpose.

Process:
1. Install the Yolo v5 from the github of ultralytics
2. In the directory of YoloV5, install all the requirements. 
3. We will need to choose the YAML file so for that we will go to Coco128 model of YAML and edit that file as per our requirements.
4. We will upload the weights downloaded from ultralytics. There are many weights available, but Yolov5.pt is the fastest one so we will choose that.
5. Now we are ready to train the model. Training will take around 1 hour 30 minutes but it may differ as per the size of the dataset and your system.
    we will train the model on 10 epochs but for accuracy you can increase the epochs. 
7. After the completion of training, we will validate the model. After validation, you will get all the accuracy measures as pictures.
8. We will perform a test of our model by a random image and test the model performance on it. 
