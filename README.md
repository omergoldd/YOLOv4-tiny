# Design and implementation of a computer vision-based autopilot for autonomous cars (Project of 5 parts)
# YOLOv4-tiny(Part 1 out of 5)
# Idea(General):
This is the first part of a project consisting of 5 parts to create an autopilot system, as follows:
1. Object Detection using YOLOv4-tiny.
2. Semantic Segmentation.
3. Modular Approach(Genetic Algorithm) autopilot design.
4. End-to-End Approach(Based on the famous End-to-End Nvidea's paper) autopilot design.
5. Lane tracer (physical car model using our autopilot systems).
# Idea for this part(YOLOv4-tiny):
1. We first pre-trained a YOLOv4-model on all the data taken from Africa St & Ebed Khatim St.
2. We wanted the model to work in real-time but YOLOv4 took about 3 sec for a picture after continuous optimization.
3. We then took the data & the labels produced by the YOLOv4 model and used them to train the YOLOv4-tiny model based on the famous Darknet implementation(trained on COCO dataset) and Techzizo.
4. The YOLOv4-tiny achieved slightly less accuracy but the detection time was 15.689 milliseconds which is acceptable for the overall project.
5. Results of the YOLOv4 & YOLOv4-tiny of the same input picture is provided in this repository te get a better grasp of the accuracy difference.
6. Finally, We want to the thank the create(s) of the Darknet repository and the link to part 2 of the project is provided below:
# Project's Part 2(Semantic Segmentation Link):
https://github.com/Mohammed1999-1-8/semantic-segmentation-for-self-driving-cars
# Project's Part 3(Modular Approach(Genetic Algorithm) autopilot design):
https://github.com/Mohammed1999-1-8/Genetic-Autopilot
# Project's Part 4(End-to-End Approach(Based on the famous End-to-End Nvidea's paper) autopilot design):
https://github.com/Mohammed1999-1-8/end-to-end-Autopilot
# Project's Part 5(Lane tracer (physical car model using our autopilot systems)):
https://github.com/Mohammed1999-1-8/lane-tracer-robotic-car
# The Data:
Link: https://drive.google.com/file/d/149cuQmeziG-pwuTU3M6msJn9g0miorN7/view?usp=sharing
# Darknet Link:
https://github.com/AlexeyAB/darknet
# Example Results:
# The input image:
![car](https://user-images.githubusercontent.com/22389376/167814190-3d81a7a2-7912-433f-8dd5-67c9f3f710dc.jpg)
# YOLOv4 results:
![YOLOv4ExampleResults](https://user-images.githubusercontent.com/22389376/167814769-27c52be0-958f-45b7-9083-26d105e6e60a.jpg)
# YOLOv4-tiny results:
![YOLOv4-tinyFinal](https://user-images.githubusercontent.com/22389376/167814933-e6ffc634-5d3e-448c-9ac8-298b4cdcf700.jpg)
# Picture showing the YOLOv4 output after the detection boxes are added:
![YOLOv4Example](https://user-images.githubusercontent.com/22389376/167815999-d0ae35cc-fe48-463a-a881-ed7516aaf563.jpg)
