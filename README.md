# YOLOv4_DarkNet

 - This is a project that I am working on, at NCRAI in collaboration with Kerala Agricultural University. I will be working on the machine learning part of the project. I have created an object detection model using Yolo V4 algorithm using Darknet framework .

 - You can download the **YOLO V4 paper** [here](https://arxiv.org/pdf/2004.10934)
 
 ## Index of this Repository

 - The **yolov4_custom_object_detection.ipynb** is the code to train yolov4 using darknet
 
 - The folder **yolov4_test** contains the following data **:**
 
**1.** obg.zip (annotated training image data)

**2.** test.zip (annotated testing image data)

**3.** generate_train.py (python code to generate train.txt file)

**4.** generate_test.py (python code to generate test.txt file)

**5.** obj.names (names of the classe(s) )

**6.** obj.data (contains informations like class, location of train.txt&test.txt)

**7.** yolov4-obj.cfg (contains various arguments like convolutional layers, filters, max_batch,various augmentation parameters...)
 
 
## Problem

Detect and classify two classes of Pineapples

 **1.** MATURED PINEAPPLE
 
 **2.** UNMATURED PINEAPPLE

## Dataset

The Dataset for this project is collected and annotated physically by ourself.

## Hardware

We have used Google Colab to train the model 


`| NVIDIA-SMI 455.45.01    Driver Version: 418.67       CUDA Version: 10.1     |`
`| GPU  Name        Persistence-M| Bus-Id        Disp.A | Volatile Uncorr. ECC |`
`| Fan  Temp  Perf  Pwr:Usage/Cap|         Memory-Usage | GPU-Util  Compute M. |
                                                                        MIG M. |`

`|   0  Tesla T4            Off  | 00000000:00:04.0 Off |                    0 |`
`| N/A   57C    P8    10W /  70W |      0MiB / 15079MiB |      0%      Default |
                                                                          ERR! |`

## Our Research
 
  - Inorder to improve our  detection and classification perfomance of the model we have performed some experiments on color augmentation parameters of YOLO V4 .
 We have adjusted the color augmentation parameters **HUE**, **SATURATION** and **EXPOSURE** and trained the YOLO V4 and analyzed the results .
 
  - `Checkout this to know  more about the color augmentation parameters that we have experimented` : [Color Augmentation ](https://www.ccoderun.ca/darkmark/DataAugmentationColour.html)
 
 ![](map.jpg)
 
 ![](chart.jpg)
