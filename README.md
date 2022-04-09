# headingdetector

Raw IMU data: 3 axis accelerations and angle velocities 
processed in the Kalman filter:
3d cartesian coordinadt x,y,z and attitude pitch, yaw, roll angles

Here we are using the yaw angle to detetc when and how long certain actions happened:
a 180 deg rotation of the entire device at the beginning of measurements (done for IMU calibration)

