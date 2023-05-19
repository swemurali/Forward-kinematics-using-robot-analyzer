# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:
1.open the roboanalyzer software.
2.select the robot and its degrees of freedom.
3.change the values with the link lenght wherever necessary.
4.simulate the model for forward kinematics.
5.plot the graph between the link and the joints.
6.update the DH parameters of the link configuration and end effector configuration.
### SIMULATION 
 ### 4 DOF
 ![4 DOF WORKSPACE](https://github.com/swemurali/Forward-kinematics-using-robot-analyzer/assets/94165336/24636cd2-f3c8-4e9d-8165-95bab24df953)

 ![4 DOF EE CODING](https://github.com/swemurali/Forward-kinematics-using-robot-analyzer/assets/94165336/ce02816d-1bb8-44d5-b683-753b4db1cc18)

![image](https://github.com/swemurali/Forward-kinematics-using-robot-analyzer/assets/94165336/570f33d1-e6b6-44a2-bd87-87efd3d4aac5)

![image](https://github.com/swemurali/Forward-kinematics-using-robot-analyzer/assets/94165336/a2e14455-9160-461d-beb0-f12a46705e70)

 ### PLOT 
 ### 4 DOF
 ![image](https://github.com/swemurali/Forward-kinematics-using-robot-analyzer/assets/94165336/79f5c872-ea2c-488a-ada1-1963a5c993aa)

 ### 6 DOF
 ![image](https://github.com/swemurali/Forward-kinematics-using-robot-analyzer/assets/94165336/4d346a74-18ae-432e-b8a4-96934ba8995b)
 
### RESULTS :  
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles is analysed.
