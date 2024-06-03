# License-Plate-Recognition
License Plate Recognition:
Detecting and recognizing vehicle license plates represents a widely recognized challenge that has garnered significant attention.This challenge revolves around the utilization of two distinct datasets:
1. A collection of vehicle images, totaling 900 images, sourced from the internet and meticulously annotated. These annotations encompass the precise coordinates of bounding boxes encapsulating the license plates within each image.
2. An assemblage of license plate images, also amounting to 900 images, where the annotations take the form of the alphanumeric text inscribed on each license plate.
The primary aim of this task is twofold: first, to identify and locate the license plates affixed to the vehicles in the images, and second, to perform character recognition on these license plates, deciphering the alphanumeric text they contain.

The dataset is organized into three distinct sets:
1. Training Set 1: This set comprises 900 images, with each image featuring a single car along with its corresponding license plate. The provided annotations include the coordinates of the bounding box (ymin, xmin, ymax, xmax) that outlines the license plate in each image.
2. Training Set 2: Consisting of another 900 images, this set focuses solely on license plates. Each image in this set contains a license plate, and the provided annotations contain the characters present on each license plate.
3. Test Set: This set consists of 201 images and is structured similarly to the first training set. In this set, your task is twofold: you need to detect the license plates within the images and recognize the characters on those plates. 
In summary, the data provided is segregated into three sets, each serving a specific purpose in training and evaluating models for license plate detection and character recognition.
However, during the evaluation phase, your performance will be assessed based solely on the accuracy of character recognition.

