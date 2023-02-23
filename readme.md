# Sensor Fusion Team
## Radar Experiment in prescan to simulate publishing and subscribing to ROS Topics and sharing radar readings via this Topics
## Each Radar Signal is shared in a topic of it's name 
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

- - -
## Publishing Signals 

![2023-02-23 (3)](https://user-images.githubusercontent.com/59807200/221026037-b592984a-3c50-44be-ba11-7ddda917590c.png)
![2023-02-23 (4)](https://user-images.githubusercontent.com/59807200/221026182-264efd8a-23f5-478c-ac3f-a16eee0fbf32.png)
![2023-02-23 (5)](https://user-images.githubusercontent.com/59807200/221026292-2e1569a5-842a-4068-8190-f62aa7c4b000.png)

- - -
## Subscriping Signals 

![2023-02-23 (2)](https://user-images.githubusercontent.com/59807200/221027045-fff29955-7b40-4caa-b36e-01fa319e8c5c.png)
![2023-02-23 (1)](https://user-images.githubusercontent.com/59807200/221027246-6389406e-0c90-4fe9-967b-e9f037337a0d.png)

