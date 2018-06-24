[//]: # (Image References)
[image_0]: ./misc/rover_image.jpg
# Rover search and sample return


![alt text][image_0] 

The rover search and sample return project was based after the [NASA sample return challenge](https://www.nasa.gov/directorates/spacetech/centennial_challenges/sample_return_robot/index.html). It gives a first hand experience with the three essential elements of robotics, which are perception, decision making and actuation. The project uses the Unity game engine application (simulator details below) that simulates rover environment. 

## The Simulator
The platform specific simualtors can be downloaded below
* [Linux](https://s3-us-west-1.amazonaws.com/udacity-robotics/Rover+Unity+Sims/Linux_Roversim.zip)
* [Mac](https://s3-us-west-1.amazonaws.com/udacity-robotics/Rover+Unity+Sims/Mac_Roversim.zip)
* [Windows](https://s3-us-west-1.amazonaws.com/udacity-robotics/Rover+Unity+Sims/Windows_Roversim.zip)  

Simulator operates in  "Training Mode" and "Autonomous mode". Training mode was used to collect rover data for data analysis and Jupyter notebook code.
Autonomous mode was used for testing. 

## Dependencies
The code requires Python 3 and other dependencies installed with Anaconda distribution. [RoboND-Python-Starterkit](https://github.com/ryan-keenan/RoboND-Python-Starterkit) repository has a detailed steps to get things working. 

## Running the code
* Start the simulator in "Autonomous mode".
* Activate the conda environment. `source activate RoboND` 
* Run `python ./code/driver_rover.py` script to test the rover navigation.

## Notebook Analysis
The jupyter notebook includes all major functions, which are broken down into separate sections as follows:




