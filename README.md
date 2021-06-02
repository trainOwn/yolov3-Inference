# yolov3 - Default model -  Inference script
This Implimentation of yolov3 to showcase the default yolov3 model inference on images, video & webcam

## First clone this repo
```
git clone https://github.com/trainOwn/yolov3-Inference.git
```
goto model directory and download model
```
cd yolov3-Inference/model
sh get_model.sh
```

## Requirment 
```
pip install -r requirements.txt
```

# How to use
1) Run Inference on image
```
python3 inference.py -i ./data/horse.jpeg 
```

2) Run Inference on Video
```
python3 inference.py -v ./data/street.mp4 
```
Output video will be saved in current dir.

3) Run on web-cam
```
python3 inference.py
```

If 'weights' and 'config' are placed somewhere else in local machine provide path to it.
look for help 
```
python3 inference.py -h
```
