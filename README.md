# ROB-GY-6413-project



This repository contains my efforts towards a project for the Robots for Disability course of Dr. Vikram Kapila as offered in Fall 2022.


## 17th November 2022

I wish to design a simple reacher type robot that can be operated by the user with limited mobility in lower legs - just to grab something out of hands reach, too high or too far into the room.  A robust reacher/adjustable gripper design on a mobile platform is the heart of the project. But to make it actually useful, the contraption has to have the ability to come to user firest from wherever it has been docking. This is challenging, if it is in the other room, an half-hour research last week couldn't yield a good beaconing or homing mechanism for a robot from another room. 

Anyway, will focus on simulation assignment first.  Wanted to design the robot body and  get it simulated for some basic task. Spent a couple of hours today morning trying to figure out whether there is any lighweight software where one can design a robot, simulate it and also download a 3D-printable file for the design.  Ruled out ROS and Gazebo because I don't want to work from Linux on my machine when all of my notes and everything are on Windows :/ Also, lightweight please.  Then Webots looked promising - specially with what looked like some builtin indoor scenes. But couldn't find a straighforward way to do good design on Webots.  Found many resources on Solidworks, but its not free. Checked out Processing at one point, just because, and was amazed to see how more rich the Coding Train channel has become and was reinspired by the superhero Daniel Shiffman and his general awesomeness. Got sidetracked a bit as a went through some of his websites. Did not know that he was NYU affiliated!  Also, found some works  of his community's works related to the Ability Project of NYU! 

Anyway, as I resumed search for good platform, TinkerCAD kept becoming a better and better option for me, also it lacked the simulation aspect.  Soumic, when I called him for his suggestions, informed that he had used Blender and Webots. But Blender does have a learning curve that I don't want to spend time on at this point. Soumic suggested Fusion 360, but I'm only going for open-source services.  He agreed that there aren't that great options for a single catch-all platform. I asked whether Webots can handle .STL files, and when he said yes, I told him I will try the TinkerCAD + Webots combo. 

-----
So here I am, trying Webots. 

Installed Webots, despite my OS complaining. 

Now Webots complaining that my device's graphics setup is not up to par. 

Nevertheless, played with some example worlds.  

Opened a new world in E:/  

PROBLEM:  Had crossed out all windows.  Now could not bring them in from View etc. 
SOLUTION: Tools --> Restore Layout.   Restores the four main windows. 

Following this video: https://www.youtube.com/watch?v=luyg3plGujg ('Introduction to webots: how to install and run your first simulation in 10 min | Webots Tutorial 1' by Kajal Gada).  Played around with the ball hitting the robot in different ways.  The Physics set up is so good, when I had a large ball it didn't roll around too much.  But I saw the tutorial video's ball rolling around quite a lot after falling from a high initial position, so I made my ball smaller like the one in the tutorial. Fun to make it hit the epuck robot or make the epuck robot hit the ball. The e-puck robot even kind of  tilts a bit, as the ball falls down from it! 

