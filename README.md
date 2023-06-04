# Inverse-kinematic-modeling-using-robo-analyzer-

 
## AIM: 
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given  input end effector position .


### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
### Inverse Kinematics
 

Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

 Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

### solving inverse kinematic model 
![image](https://user-images.githubusercontent.com/36288975/170622829-3fe97ef7-8ef1-44af-afae-b0954871aa0c.png)


![image](https://user-images.githubusercontent.com/36288975/170622902-f48fd9c7-f2ec-4fd5-904b-ea51be8298c3.png)

![image](https://user-images.githubusercontent.com/36288975/170622934-a3fd7f77-7eb2-4408-b66d-d6e3adbd1f99.png)

![image](https://user-images.githubusercontent.com/36288975/170622982-9c4d8b23-1563-4e17-9616-87bcc4f4501d.png)
![image](https://user-images.githubusercontent.com/36288975/170623020-f27efc12-bb58-4f62-840d-af544ac6689e.png)

### PROCEDURE:

1.Open the roboanalyzer software.

2.Select the robot and its degrees of freedom.

3.Change the values of X and Y wherever necessary.

4.Stimulate the model for inverse kinematics.

5.Plot the graph between the joints.

6.Update the DH parameters of the link configuration and end effector configuration.







### SIMULATION 

RPR ROBOT:

![KIN 5](https://github.com/pradeepasri26/Inverse-kinematic-modeling-using-robo-analyzer-/assets/131433142/cdef3846-c2cf-449b-944e-0dda00719e9a)

![KIN 6](https://github.com/pradeepasri26/Inverse-kinematic-modeling-using-robo-analyzer-/assets/131433142/f5e59bc3-8301-4284-baed-632143596932)

3R ROBOT:

![KIN 7](https://github.com/pradeepasri26/Inverse-kinematic-modeling-using-robo-analyzer-/assets/131433142/b22909a7-5029-428a-b364-fe887fa7fb38)

![KIN 8](https://github.com/pradeepasri26/Inverse-kinematic-modeling-using-robo-analyzer-/assets/131433142/9e20f8dd-66be-4576-b6db-40af95ba321e)


 
 
 
 
 
 
 
 ### PLOT 
 
 RPR ROBOT:
 
 ![KIN 9](https://github.com/pradeepasri26/Inverse-kinematic-modeling-using-robo-analyzer-/assets/131433142/08d0c4eb-0f82-437b-883f-9b2e92b158d2)
 
 ![KIN 10](https://github.com/pradeepasri26/Inverse-kinematic-modeling-using-robo-analyzer-/assets/131433142/c05ee68d-f64d-4e03-8976-50360079f7df)
 
 3R ROBOT:
 
 ![KIN 11](https://github.com/pradeepasri26/Inverse-kinematic-modeling-using-robo-analyzer-/assets/131433142/335cab88-21e9-4045-aece-4e1afefc4b02)
 
 ![KIN 12](https://github.com/pradeepasri26/Inverse-kinematic-modeling-using-robo-analyzer-/assets/131433142/4b69a3ac-5a15-4234-b46d-61adbfe08ccd)




 
 
 
  
 

 
 
 
 
 
 
 
 
 
 
 
 

 
 














### RESULTS :  
Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given input end effector position is plotted.
