# Forest Path Planning

## Introduction
The idea was to be able to approximate the actual path to be traversed with our input equation.
This helped us find minute violations and errors that Robot could make such as touching the poles, running into the fence.

## How it was Made
The Skeleton of the MR1 Drive and the entire Arena model was reconstructed in Simulink. A program was developed that would successfully emulate any given system in the form of x and y (displacement).

The model is simple to understand with subsystems and groups making them intuitive and easily modifyable. The Simulation is quick enough to execute on the click of a button and is built completely on Simulink.

<img src="Videos\SinePath_Sim_All.gif" width="45%" style="float:left padding:2%"/>
<img src="Videos\SinePath_Real_World_Case.gif" width="45%" style="float:right;"/>  

## How to Use:
+ Simply Download/Clone the repo
+ Navigate to File Swerve_SinePath.slx from MATLAB
+ Open File and Run it