# Shagai Throwing

## Introduction
Fine Tuning was done for the Model to exactly replicate the Robot’s Throw. 
The Score obtained after each throw, mass of Shagai and Angle of projection was noted.
After physically testing the collected data, the model correctly identified the outcome in at least 95% of the cases.

<img src="Videos\Shagai_Throwing_Sim_Iso.gif" width="45%" style="float:left padding:2%"/>
<img src="Videos\Shagai_Pistons_Real_World_Case.gif" width="45%" style="float:right;"/>

## Data Collection
The purpose of the Shagai Throwing Model was to predict the outcome for any giving variation in the conditions.
The goal was to ensure that the Shagai lands with the Golden Side on top and thus obtain 50 pts, the maximum score.

The data was collected from a loop based program which would change the angle of projection from 8.0 to 14.2. After every loop the mass of the Shagai is changed (the Shagai mass can vary from 600g to 800g as mentioned in Robocon 2019 Rulebook).

Data Collected reflected the Shagai Landing Orientation for Various Angles for Shagai of different masses. 
Analyzing it helped us find the ideal conditions to throw the Shagai which would result in 50 points.

In order to Visualize this data a graph was created with the outcome of the Shagai throw (20, 40, 50 points) on the Y-axis against the Angle in the X-axis. Multiple lines were drawn, each representing a Shagai of a different mass. The range of angles most suitable for the projection was then selected.

<img src="Model%20Results\Graph_AngleJustification.jpg" width="100%" />



## How to Use:
+ Simply Download/Clone the repo
+ Navigate to File SHagai_Values.m from MATLAB
+ Change Following Values as required:
  +  Mass of Shagai
  +  Force Provided by Piston
  +  Angle of Projection
  +  Landing Surface Dimensions
  +  Thowing Surface Dimensions
  +  Contact forces between Shagai and Landing Surface
  +  Contact forces between Shagai and Throwing Surface
  +  Static and Kinetic Friction Between Shagai and Landing Surface
  +  Static and Kinetic Friction Between Shagai and Throwing Surface
+ RUn the file