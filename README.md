# Self_Driving_Car
This Project deals with the simulation results of an autonomous
car learning to drive in a simplified environment containing only lane
markings and static obstacles. Learning is performed using the Deep Q
Network. This code is a self-driving car simulation written in python with
kivy framework

![image](https://user-images.githubusercontent.com/70893078/229139198-88414f2d-4a31-4376-9e35-7ad1d0346353.png)

In stage 1,
 the small car initially moves in a sporadic manner, similar to that of an insect, as it begins to explore the map and learn how to travel from the starting position to the destination.

In stage 2, 
the small car has been trained to follow a specific route from the top left to the bottom right of the map.

In stage 3,
 when a new path is created randomly, the small car will stop exploring and focus on training itself to follow the new path. Once it has successfully learned the path, it will continue to follow it. If the new path is removed, the small car will revert back to exploration mode while still following its previously learned route.
