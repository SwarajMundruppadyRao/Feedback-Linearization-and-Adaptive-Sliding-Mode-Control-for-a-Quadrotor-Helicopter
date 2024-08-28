# Feedback-Linearization-vs-Adaptive-Sliding-Mode-Control-for-a-Quadrotor-Helicopter

## Introduction 

The project aim was to study and compare two different approaches, Feedback Linearization and Adaptive Sliding Mode,  for controlling a highly coupled nonlinear system(quadrotor)


Based on Journal Paper : Daewon Lee, H. Jin Kim, and Shankar Sastry, “Feedback Linearization vs. Adaptive Sliding Mode Control for a Quadrotor Helicopter”, International Journal of Control, Automation, and Systems (2009) 7(3):419-428. 



## Dependencies

MATLAB Simulink with all Toolboxes and support packages 

## Contents

The file Contains the following items:

1. Feedback_Linearization.slx: This file is for controlling the Quadcopter model using Feedback Linearization Controller.

2. ASMC_without_Sensor_Noise.slx : This file is for controlling the Quadcopter model using Adaptive Sliding Mode Controller without the inclusion of sensor noise.

3. ASMC_with_Sensor_Noise.slx : This file is for controlling the Quadcopter model using Adaptive Sliding Mode Controller with the inclusion of sensor noise.

4. plot_3d.m : This file contains MATLAB code to print the 3-D trajectory of the Quadcopter.


## Steps to Run Feedback Linearization

Steps to be followed to run Feedback_Linearization.slx file:

1. Under Modelling Ribbon, Select Model Settings. In the settings, Select Solver type as Fixed-Step, Solver as ode1be, Fixed-Setp size as 0.1 and Number of Newton's Iterations as 

2. Run the Model after setting stop time as 30 seconds.

3. Open the individual Scopes to visualise the outputs

4. Run the plot_3d.m file to visualise the trajectory in 3D 


## Steps to Run Adaptive Sliding Mode Control - Considering Sensor Noise of Quadrotor

Steps to be followed to run ASMC_with_Sensor_Noise.slx file:

1. Under Modelling Ribbon, Select Model Settings. In the settings, Select Solver type as Fixed-Step, Solver as auto and Fixed-Setp size as 0.1.

2. Run the Model after setting stop time as 30 seconds.

3. Open the individual Scopes to visualise the outputs

4. Run the plot_3d.m file to visualise the trajectory in 3D 


## Steps to Run Adaptive Sliding Mode Control - Without Considering Sensor Noise of Quadrotor


Steps to be followed to run ASMC_without_Sensor_Noise.slx file:

1. Under Modelling Ribbon, Select Model Settings. In the settings, Select Solver type as Fixed-Step, Solver as auto and Fixed-Setp size as 0.1.

2. Run the Model after setting stop time as 30 seconds.

3. Open the individual Scopes to visualise the outputs

4. Run the plot_3d.m file to visualise the trajectory in 3D 

