# CarND-Path-Planning-Project
Self-Driving Car Engineer Nanodegree Program

![Simulator Image](./images/midwaydriving.JPG)

## Project Objective :
In this project the goal is to safely navigate around a virtual highway with other traffic that is driving +-10 MPH of the 50 MPH speed limit. The car's localization and sensor fusion data is provided by simulator. The car should try to go as close as possible to the 50 MPH speed limit, which means passing slower traffic when possible.The car should avoid hitting other cars at all cost as well as driving inside of the marked road lanes at all times, unless going from one lane to another. The car should be able to make one complete loop around the 6946m highway. Since the car is trying to go 50 MPH, it should take a little over 5 minutes to complete 1 loop. Also the car should not experience total acceleration over 10 m/s^2 and jerk that is greater than 10 m/s^3.

The followsing steps were followed to achieve project objectives : 
* Running vehicle at a conatant speed (using x,y coordinates) 
* Running car at a center lane (using frenet coordinates)
* Smoothing the paths using previous path projections
* Using sensor fusion data to navigate lane change and applyling state transitions (following,lane change to left, lange change to right, lane change to center)

