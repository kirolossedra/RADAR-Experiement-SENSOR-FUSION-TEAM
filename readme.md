# Sensor Fusion Team
## Radar Experiment in prescan to simulate publishing and subscribing to ROS Topics and sharing radar readings via this Topics
## *Don't Forget to start the ros in matlab by typing rosinit in MATLAB Command Line*

- - -
## Radar Signals 


| Signal Name | Description |
| --- | --- |
| Active BeamID[-] | ID of the beam in the current simulation time step. Value is 0 when there is not detection |
| Range[m] | Range at which the target object has been detected |
| DopplerVelocity[ms-1] | Velocity of target point relative to the sensor along the beam |
| DopplerVelocityXYZ[ms-1] | Velocity of target point relative to the sensor along the beam decomposed into X,Y,Z of the sensor's coordinate system |
| Theta[deg] | Azimuth angle in the sensor coordinate system at which the target is detected |
| Phi[deg] | Elevation angle in the sensor coordinate system at which the target is detected |
| TargetID[-] | The Type ID of the detected object |
| EnergyLoss[dB] | Ratio recieved power/ transmitted power |
| Alpha[deg] | Azimuthal incidence angle of the RADAR on the target object |
| Beta[deg] | Elevation incidence angle of the RADAR on the target object |
