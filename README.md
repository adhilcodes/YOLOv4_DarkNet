# YOLOv4_DarkNet
This repository contains python code to perform custom object detection using YOLOv4 algorithm using Darknet framework

 - The **yolov4_custom_object_detection.ipynb** is the code to train yolov4 using darknet

 - The folder **yolov4_test** contains the following data:
1. obg.zip (annotated training image data)
2. test.zip (annotated testing image data)
3. generate_train.py (python code to generate train.txt file)
4. generate_test.py (python code to generate test.txt file)
5. obj.names (names of the classe(s) )
6. obj.data (contains informations like class, location of train.txt&test.txt)
7. yolov4-obj.cfg (contains various arguments like convolutional layers, filters, max_batch,etc...)
