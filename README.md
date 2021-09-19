# armaggaedon


## Eventual Objective
Cleaning 3D prints is a pain and we hate it so we decided to make an arm that will get attached to 3D prints to do this. 
Simple?


## Objective Stage 1
A. 6 DOF arm controlled by servo motors which can move each motor independently and each motor command should be achieved with reasonable error.
B. Unity simulation of a 6 DOF arm that can reach an XYZ using ML agents on its own with the input of XYZ and giving the theta of each motor as output. 


## TODOS
### A
[] Assemble the arm
[] Control arm using a rasp controller


### B
[] Recreate servo based 6 DOF model close to reality on unity
[] Setup control system on it to be able to move with physics and motor angles 
[] Setup training system for ML agents with reward model
[] Get motor angle outputs real time from model on a learnt system
[] Feed above to A and see our lives fall apart