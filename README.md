# Inferq-DAi
## Table of Contents
- Introduction
- Objective
- Getting Started
  - Prerequisites
  - Installation
- Usage
- Roadmap
- License
- Contact
- Acknowledgements  

## Introduction
Inferq - DAi is an autonomous system or third eye that is capable of guiding the user to find out the specific objects by sensing the environment with very few user inputs. The proposed system is being trained on daily used objects to supervise the user and find it with very little user effort to make life a little easy. 
MobilenetSSD-v2 object detection network trained on COCO dataset is used to detect objects and hand detection network trained to detect human hand in different poses which are trained on EgoHands dataset, both the networks are inference to run parallelly on depth-ai hardware. 
The system is capable of detecting the most commonly used objects in real-time and guiding the user by providing the distance and direction of the detected object from hardware (OAK-D camera) at the initial phase. when the user places the detected object at any other spot( eg.: Table, sofa, or refrigerator), the device will record the spot and guide the user in the future when the particular common object is required, it is assumed that the system is at running phase and the user already had traced the object in the initial phase and took it. The whole system process continues until the next user input.

## Objective

## Getting Started
### Prerequisites 
In order to run the Inferq - DAi system, some dependencies are required to be installed in your platform.<br /><br />
**OpenCV**
```
pip install cv2
```
**depth-Ai** <br />
For more details about depthai, please refer depthai documentation.
```
pip install depthai
```
