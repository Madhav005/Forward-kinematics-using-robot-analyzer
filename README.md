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
#### Open Robo Analyzer application
![Screenshot (37)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/44f17684-560f-4221-9fb6-b5a2d432a40d)
#### Change DOF to 6
![Screenshot (38)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/5cf0b9cf-93d1-46e8-9b03-c27376bc02cc)
#### Set Parameters
![Screenshot (39)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/254f3c74-3c7c-4eeb-b6ea-4ea207945337)
#### Click Fkin to simulate
![Screenshot (40)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/a046b426-733c-4387-ac3c-361d208b2581)
#### Plot the graphs
![Screenshot (41)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/7ce101b5-eae0-4af2-9551-667e97b0a250)


### SIMULATION 
 ![Screenshot (40)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/0d62d774-8bb2-47c6-89d1-ac2888ad2b5a)

 
 
 ### PLOT 
 #### LINKS
 Link 1
 ![Screenshot (41)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/ae77ecc1-a988-44fb-b553-74f71198afad)
Link 2
![Screenshot (42)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/4b5b54c4-5e13-44ff-a7cc-24837df83b6b)
Link 3
![Screenshot (43)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/b85900d4-bcc1-4589-ad86-23de277fdbc0)
Link 4
![Screenshot (44)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/3868ce4b-0743-4984-b84a-98428be29289)
Link 5
![Screenshot (45)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/1845296d-2a01-46e5-b364-35ca0d9a8370)
Link 6
![Screenshot (46)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/05218217-768c-4d2d-82f1-304d5c0cd1b1)

#### JOINTS
Joint 1
![Screenshot (47)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/ad93ecdf-3f64-459a-ad4e-5725c2582900)
Joint 2
![Screenshot (48)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/f8b4cce4-4c99-40b1-8c28-d1f3a6495e95)
Joint 3
![Screenshot (49)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/23b9c235-f231-4581-88d2-63365cf317f8)
Joint 4
![Screenshot (50)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/6065dd06-55b2-42bc-b761-85a517d7ea45)
Joint 5
![Screenshot (51)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/23e69e30-0faa-409e-b1fe-3e2d1bf5b02c)
Joint 6
![Screenshot (52)](https://github.com/Madhav005/Forward-kinematics-using-robot-analyzer/assets/110885274/d067911a-675c-448f-b3b2-16e813879689)


### RESULTS :  
