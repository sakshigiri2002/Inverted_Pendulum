# Inverted-Pendulum
Aim is to stabilzse pendulum using PID and LQR controller

## PID Control 

PID control was used to stabilize the inverted pendulum in upright position. The drawback behind PID was that it was giving force that was much above physical limit due to which cart contineously moves in direction of force for longer period of time seen in below results :-

![](https://i.imgur.com/AD1bufn.png)

![](https://i.imgur.com/8mvxrjP.png)

![](https://i.imgur.com/SAmLpDJ.png)

## LQR Control 
After seeing drawback in PID controller we moved to LQR controller to stabilize the pendulum in upright position. We tunned the Q (penalty on states) and R (penalty on actuators) matrix to obtain the desired results within some physical limits. Below plots shows variation of theta, force and postion(x) with time. In animation we can see pendulum stabilize in upright postion at desired (x=5). p

![image](https://user-images.githubusercontent.com/86155751/172771977-73ba34db-e274-4d0f-bf75-29d50ab4f545.png)

![LQR_Inverted_Pendulum](https://user-images.githubusercontent.com/86155751/172772171-16a02b85-6390-4b52-b85d-4816d8d92166.gif)

