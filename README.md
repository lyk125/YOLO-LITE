# YOLO-LITE
All the trained models used while developing YOLO-LITE

# Demo
[Check out our models trained on COCO and VOC here.](https://reu2018dl.github.io/)

Below is the COCO YOLO-LITE model performing real-time object detecion at about 10 FPS from a Dell XPS 13 laptop:

![Real-time detection](https://github.com/rachuang22/tfjs-yolo-tiny-demo/raw/master/src/img/car.gif)

# Get Started

### Training
We used AlexeyAB's Darknet for Windows to train our model.
Install Darknet [here](https://github.com/AlexeyAB/darknet).

To find the mAP for each training model, run the command under the scripts folder:

	`python mapScript.py`

When prompted, add the location of the cfg and the location of the weights folder.

### Testing
In order to get the FPS, we used a Python adaption of Darknet called Darkflow [here](https://github.com/thtrieu/darkflow/tree/master/darkflow).


### Web Implementation
To convert the model to JavaScript, we followed the following tutorial: 