# Real time object detector with computer vision


<!-- ABOUT THE PROJECT -->
## About The Project

![Demo](https://github.com/Gent-Zambaku/object-detector/blob/main/images/object_detector.gif)


### What is object detection?
Object detection is a computer vision technique that works to identify and locate objects within an image or video. Specifically, object detection draws bounding boxes around these detected objects, which allow us to locate where said objects are in (or how they move through) a given scene.

Object detection is commonly confused with image recognition.

Image recognition assigns a label to an image. A picture of a dog receives the label “dog”. A picture of two dogs, still receives the label “dog”. Object detection, on the other hand, draws a box around each dog and labels the box “dog”. The model predicts where each object is and what label should be applied. In that way, object detection provides more information about an image than recognition.

This demo project shows how we can use deep learning (the inception model architecture) for real time object detection using python, tensorflow 2 and opencv. 

- [x] Python3 as programming language
- [x] Tensorflow 2 as ML framework
- [x] OpenCV as CV framework
- [x] A simple camera

### Installation

_You can follow the installation steps below to run the app._

1. Clone the repo
   ```sh
   git clone https://github.com/Gent-Zambaku/object-detector.git
   ```
2. Get inside the repository
   ```sh
   cd object-detector
   ```
3. Create a virtual environment
   Using anaconda
   ```sh
   conda create -n detector python==3.9.1
   ```
   Using python
   ```sh
   pip install virtualenv
   python3 -m venv env
   source env/bin/activate
   ```
4. Install dependencies
   ```sh
   pip install -r requirements.txt
   ```
   or
   ```sh
   pip3 install -r requirements.txt
   ```
5. Run the object detector
   ```sh
   python detector.py
   ```
   or
      ```sh
   python3 detector.py
   ```
<p align="right">(<a href="#readme-top">back to top</a>)</p>
