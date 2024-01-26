# vehicle-counting-using-python-yolo

Vehicle counting in a conjusted traffic road where background subtraction gives lower performance.

![SCREENSHOT](/Screenshot.png)
ps: The car with-1.5Km/h is actually going in reverse :D

This project use YOLOv3 for Vehicle detection and SORT(Simple Online and Realtime Tracker) for vehicle tracking

# To run the project:

1. Download the code or simply run: ``` git clone https://github.com/Hiteshthecoder/Vehicle-Counting--YOLO ``` in the terminal

2. Make sure you change the line of detection according to your video and fine tune the threshold and confidence for YOLO model

2. Run ```main.py -input /path/to/video/file.avi -output /path/for/output/file.avi -yolo /path/to/YOLO/directory/``` 

# References:


[YOLO](https://www.pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv/)

[SORT Algorithm](https://github.com/abewley/sort)