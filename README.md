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
##6 DOF:
![image](https://github.com/Augustine0306/Forward-kinematics-using-robot-analyzer/assets/119404460/7d68b356-c2c4-4426-b13a-c5cf9ceeeeda)
##4 DOF:
![image](https://github.com/Augustine0306/Forward-kinematics-using-robot-analyzer/assets/119404460/eecd5271-e14c-4767-bcf6-16d51e109d15)

 ### PLOT 
## 6 DOF:
 ![image](https://github.com/Augustine0306/Forward-kinematics-using-robot-analyzer/assets/119404460/1308df18-a81f-4f38-a78c-ba795fa436dd)
##4 DOF:
![image](https://github.com/Augustine0306/Forward-kinematics-using-robot-analyzer/assets/119404460/8882eaa9-45ce-4c6f-b5d4-3e3273c1872c)
![image](https://github.com/Augustine0306/Forward-kinematics-using-robot-analyzer/assets/119404460/ca098b43-b426-4beb-adef-85a93a4f2918)

### RESULTS :  
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
