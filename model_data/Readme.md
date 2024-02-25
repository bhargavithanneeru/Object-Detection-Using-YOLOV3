## Download YOLOv3 weights 

Download YOLOv3 weights from the YOLO website, or use curl command:

- curl https://pjreddie.com/media/files/yolov3.weights
- Copy downloaded weights file to model_data folder and convert the Darknet YOLO model to a Keras model:
- python convert.py model_data/yolov3.cfg model_data/yolov3.weights model_data/yolo_weights

  
