
# Embedded Systems - Video Annotation


In this project, we applied various methods to generate annotated videos of a  dataset. The methods that we used were - Roboflow, YOLOv8 live object annotation and YOLOv8 annotation via uploading videoes and dividing videoes into frames(FPS). Let’s dive into the specifications of each method.


## Team Members

- Anurag Singh - B21ES004
- Anupam Singh Bhadouriya - B21CS086

## Instruction to run the video annotation part

This tool provides a graphical user interface for annotating videoes using the YOLO (You Only Look Once) object detection algorithm. It allows users to upload an video, detect objects in the video by dividing it into videos, and annotate them with bounding boxes.

## Installation

1. create a virtual environment of python
   ```
   python -m venv venv
   source venv/bin/activate  # for Linux/macOS
   venv\Scripts\activate  # for Windows
   
2. install requirement.txt
   ```
    pip install -r requirements.txt
   
3. Install the required weights and config files from the below links and add these files to the root:

   - [yolov3.weights](https://pjreddie.com/media/files/yolov3.weights)

   - [yolov3.cfg](https://raw.githubusercontent.com/pjreddie/darknet/master/cfg/yolov3.cfg)

   - [coco.names](https://raw.githubusercontent.com/pjreddie/darknet/master/data/coco.names)

   - [MobileNetSSD_deploy.caffemodel](https://github.com/yash42828/YOLO-object-detection-with-OpenCV/blob/master/real-time-object-detection/MobileNetSSD_deploy.caffemodel)

   - [MobileNetSSD_deploy.prototxt.txt](https://github.com/yash42828/YOLO-object-detection-with-OpenCV/blob/master/real-time-object-detection/MobileNetSSD_deploy.prototxt.txt)
     
4. then run the main file
   ```
   pyhton .\demo.py

## Roboflow

Roboflow is an intelligent tool that smartly annotates the images based on various classes that it has been trained on. We annotated 500 videoes by dividing them into images  using roboflow. Following are the steps :   

### Step 1 : Upload the video

![image](https://github.com/anurag3414/video-object-annotation/assets/116138151/ff71b31a-170e-4811-8b66-a67b1b1d6fd2)


### Step 2 : Choose classes that you want to detect

![image](https://github.com/anurag3414/video-object-annotation/assets/116138151/9e2c433f-4427-4a59-8696-913af46dbdc9)


### Step 2 : Choose appropriate confidence intervals

![image](https://github.com/anurag3414/video-object-annotation/assets/116138151/06d93639-d0cc-4b11-a73d-32a553093d78)








## YOLOv8 Model Live Annotation


YOLOv8 is a cutting-edge object detection algorithm employing a powerful backbone network, feature pyramid, and advanced training techniques to accurately detect objects across various scales. Its efficient architecture and post-processing methods make it a widely utilized solution for real-time applications such as autonomous driving and surveillance.


### Model Dashboard

![image](https://github.com/anurag3414/video-object-annotation/assets/116138151/0291a3c6-88a2-490b-8bd7-07febdc708f9)


## YOLOv8 Model on an uploaded image

In this model, we will directly upload the video to get the video with annotated boxes and their coordinates


### Dashboard

![image](https://github.com/anurag3414/video-object-annotation/assets/116138151/2cc886a7-1064-488a-bd14-ac35e419531f)


### Raw video


https://github.com/anurag3414/video-object-annotation/assets/116138151/dcce8e91-c57f-4c68-bd70-967c75d9aa22




### Annotated video


https://github.com/anurag3414/video-object-annotation/assets/116138151/05292082-6046-4a62-82bc-f1ea8e7d022f

