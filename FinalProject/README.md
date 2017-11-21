-There are five main part of the robot. I will discuss each part separately first. 

1. The arm to pick up the phone (must-do) and a gripper for holding the phone (optional)

The arm had two degrees of freedom: pick up the phone and rotate the phone to the ear. I plan to use two servos for the arm. As the picture shows, servo A rotates the whole base and servo B brings the arm up and down. If the gripper doesn't work in the end, I can tie the hand with the telephone.

![Alt text](./arm.JPG?raw=true "Arm")

2. Wheels so that the robot can move around (Optional)

The story is not totally decided yet that we are not sure if the robot's going to move around on stage. If so, I will use the same method as we did before.

3. Bluetooth for remote controlling (must-do)

The robot will be manually controlled. Based on the audience reaction, I can control the robot to act out corresponding stories. If we use gripper, I need to control the robot to go to the exact position to pick up the phone. This is an area with the greatest risk. The plan B is to tie the hand with the phone. 

4. A big mouth that moves (must-do)

The mouth's mechanics is similar to the drum robot's. A spiral struture drives the upper mouth to move up and down. I will need a DC motor for it.

![Alt text](./mouth.JPG?raw=true "Mouth")

5. Body of the robot (must-do)

The whole robot will be covered by fabric that makes the robot looks not robotic. 


-Parts List: Arduino uno, bluetooth, two servos, one dc motor, four 5V batteries and one 9V battery.

-Outline of the program

The movement of getting the phone and putting it back are two series of programmed movement. 

Telephone rings -> Bluetooth tells the robot to pick up the phone -> Two servos moves to pick up the phone -> The robot stops talking -> Bluetooth tells the robot to put down the phone -> Two servos moves to put down the phone