# Yolov5 object detection model deployment using flask

## Web app
Simple app consisting of a form where you can upload an image, and see the inference result of the model in the browser. Run:

`$ python3 webapp.py --port 5000`

then visit http://localhost:5000/ in your browser:

<p align="center">
<img src="https://github.com/noorkhokhar99/yolov5-flask-object-detection/blob/main/Screen%20Shot%201444-04-10%20at%2012.52.33%20PM.png" width="450">
</p>

<p align="center">
<img src="https://github.com/robmarkcole/yolov5-flask/blob/master/docs/app_result.jpg" width="450">
</p>

## Rest API
Simple rest API exposing the model for consumption by another service. Run:

`$ python3 restapi.py --port 5000`



## Run & Develop locally
Run locally for dev, requirements mostly originate from [yolov5](https://github.com/ultralytics/yolov5/blob/master/requirements.txt):
* `python3 -m venv venv`
* `source venv/bin/activate`
* `(venv) $ pip install -r requirements.txt`
* `(venv) $ python3 restapi.py --port 5000`



