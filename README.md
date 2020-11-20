# SimulinkEKFAttitude
Real time EKF Attitude Estimation for Simulink

Using the attached Simulink Model, You can use real time Acceleromter, Gyroscope, Magnetometer from any source you have to estimate the euler angles of your device. Extended Kalman Filter (EKF) is being used which is commonly used in UAVs and many flight controllers e.g. Pixhawk.

Inputs:
* Accelerometer data should be m/s 
* Gyroscope data should be  rad/s
* Magnetometer data should be ut 
* dt (time step) can be either a fixed step time  or variable (in secounds)

Outputs:
* Euler Angles Roll,Pitch,Heading (Yaw) in Radians



*** Remember to add the path to AHRS-master folders and subfolders in your matlab setting.


Soon I will publish a demonstration Video as well.


[![View SimulinkEKFAttitude on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/83113-simulinkekfattitude)

<br />

I used the project "Attitude and Heading Reference System using MATLAB as simple as possible" in github for the algorithm link: https://github.com/raimapo/AHRS
