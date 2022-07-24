
# Real-time Vehical Detection and Tracking Using Machine Learning



## Avinash Yadav [2022]

Making use of the powerful machine learning technique that is deep learning we can solve lot of real-life problems. Now a days lot of accidents happen due to human error. So, I have Developed an AI-based machine learning model using Python, NumPy, SciPy, Matplotlib, MoviePy, OpenCV, and TensorFlow. Which can detect vehicles on the road. This system will be very useful in the road, vehicle, and most importantly diver's safety. Our model takes input visual data which will receive from the camera in the vehicle and displays output on the screen which will be really useful in Autonomous Vehicles.
This repository contains a computer vision and traditional machine learning solution to vehicle detection and tracking from dash cam footage in a self driving car.

## Proposed System
- At present, the number of vehicle owners is increasing, and the cars with autonomous driving functions have attracted more and more attention.
- Detecting and tracking a vehicle’s lane position on the road assists in lane-level navigation. For instance, it would be important to know whether a vehicle is in the correct lane for safely making a turn, or whether the vehicle’s speed is compliant with a lane-specific speed limit.
- So, planning a prototype of lane detector using simple machine learning and python based, which can be used in smartphone as well.

## Implementation


![App Screenshot](https://i.ibb.co/s5KkQ3n/Picture1.png)
- Basically, what we are doing is taking raw input from the camera which is fitted in front of the vehicle to get visuals.
- After getting video input to the system, we are dividing video into frames, checking for the vehicle in the frame and doing same for every frame.
- After successfully detecting the vehicle, we are drawing on it and providing the output.  
- Optimization techniques included changes to window sizing and overlap as described above and lowering the heatmap threshold to improve accuracy of the detection (higher threshold values tended to underestimate the size of the vehicle).

![App Screenshot](https://i.ibb.co/7tDSq93/Screenshot-44.png)

A convolutional neural network could learn to detect cars like this pretty easily in an image. It does that by breaking an image down into small convolutions which generate edges. These edges ensemble into shapes and so on. Since we are going to use traditional machine learning algorithms, we need to transform this image into a more meaningful feature space. To do this we will use 3 different feature extraction methods, but first let's convert every image to the YCrCb color space.

![App Screenshot](https://github.com/galenballew/SDC-Lane-and-Vehicle-Detection-Tracking/blob/master/Part%20III%20-%20Vehicle%20Detection%20and%20Tracking/saved_figures/car_notcar.png?raw=true)

 HOG is a really amazing algorithm, it takes an image and breaks it down into a grid. Then, in each cell of the grid, every pixel has its gradient direction and magnitude computed. Those gradients are then but into a histogram with a number of bins for possible directions, however gradients with larger magnitudes contribute more than smaller magnitudes. The cell is then assigned the overall gradient direction and magnitude. This algorithm produces a feature vector that can be thought of like a signature for different objects.

![App Screenshot](https://github.com/galenballew/SDC-Lane-and-Vehicle-Detection-Tracking/blob/master/Part%20III%20-%20Vehicle%20Detection%20and%20Tracking/saved_figures/hog_comparison.png?raw=true)

What's amazing is that each cell of the HOG looks similar to the edges produced by the low levels of a convolutional neural network.

## Preview

![App Screenshot](https://github.com/akhilesh-k/Lane-and-Vehicles-Detection/blob/master/out.gif")

## 🛠 Skills And Tools Required
#### S/W Requirements
- Jupyter Notebook
- Python
- NumPy
- SciPy
- matplotlib
- OpenCV
- MoviePy
- TensorFlow

#### H/W Requirements
- Any linux PC can be suffice the purpose.

