Final Project Writeup

I want my robot to be a cute and lazy telephone robot. I made the movement of the robot arm slow when the robot picks up the telephone to make the robot look not very passionate about his job. The arm is built with thick acrylic. The robot body is built with fabric to get rid of the robotic image of a robot. I am very happy about how the design of the arm turn out to be. For the stuffed fabric body, I planned to put a mechanics inside the robot body to make the mouth move up and down, but the way that I sewed the mouth made it hard to be moved. I would redesign the mouth structure of the robot to make the open and close of the mouth independent from the fabric of the body.

I learnt about how the servos works and how to design a structure using the movement of servos. I learnt it by talking to the professor. And I learnt about working with sewing machine and fabric. I got help for Judy in the costume shop.

For the control part of the project, I used bluetooth to control the rotation of two servos. When the robot picks up the telephone, servo A goes from 0 to 90 then servo B goes from 0 to 90. When the robot puts down the telephone, servo B goes from 90 to 0 then servo A goes form 90 to 0. I also used bluetooth to control an LED. Whenever a button is pressed from the bluetooth size, the LED is on, and if the button is pressed again, the LED is off.

For the mechanical part of the project, I put one servo at the buttom. Another servo is placed on top of this servo. When the top servo rotates, the telephone is picked up. When the bottom servo rotates, the top servo along with the telephone rotates.

Three most difficult parts are making the mouth open and close (which I didn't make it work in the end), making the arm pick up the telephone nicely and time management. I rushed to put everything together in the end of the project that things are not polished enough, especially the development of the robot movement with the whole storyline. I would spend more time with my teammate on the story at the beginning of the project, because I think that is the most impoartant part of the theater performance. We came up some interesting ideas but we didn't spend much effort in developing a strong story to put the ideas together.

---------------------------------------------------------------------------------------

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
