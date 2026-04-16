# YOLO11n Segmentation Training

## Setup
pip install -r requirements.txt

## Train 1
yolo task=segment mode=train model=yolo11n-seg.pt data=data.yaml epochs=120
## Train 2
yolo task=segment mode=train model=yolo11n-seg.pt data=data.yaml epochs=100
## Train 3
yolo task=segment mode=train model=yolo11n-seg.pt data=data.yaml epochs=100 augmentaion=true