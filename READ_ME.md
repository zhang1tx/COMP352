University of Windsor COMP-3520 Winter-2019 Final Project
========
Group Member: | Student ID
Qingyi Ji       104606939
Haixu Shen      104401549
Zekun Zhang	104947128
Xiaoyue Liang	104766970
========

project romantic yard
--------
This project contains the source code of a graphic design about a scene of yard. 
It is mainly built based on the Shane's SDL2.0 template, and we implemented our own design using source picture file and modified by us as assets.

The project was written using Visual Studio and can be run perfectly using Visual Studio 2017 with solution.

Introduction
--------
The scene was implemented using SDL2.0 package and eigen for matrix calculation.


We constructed a Open World where the player was in a first personal perspective.
A player can move upward, downward, forward, backward, left and right. 
A player is also allowed to change camera horizontally by moving mouse.

In the world, we built up a 1800*1800 square yard. There is a front gate of the yard and 2 rooms inside the yard. 
Each door or gate has a unique button to control open.

The objects and human figure in the yard are all in 2.5D. The trees, table are all still pictures rendered directly to the screen.
However chairs and human figures all has its different sprite to be rendered relative to the player's position.

the player are also able to change the back ground from day to night.


Controls
-------------------
Move		|button
-------------------
forward		|w
backward	|s
leftward	|a
rightward	|d
upward		|t
downward	|g
zoom-in		|h
zoom-out	|y
camera		|mouse click


door control (press down to open, release for close)
-------------------
door(front)	|k
door(westroom)	|n
door(eastroom)	|m

background changing
-------------------	
day <-> night	|b


Existing problems
--------
Due to painter's problem, the rendering work might be tough for some computers with bad graphic processing ability.
The performace of this project could be bad on some computers. (Acturally happened on our own computers.)
Changing background needs to reload all textures and re-rendering. So it might have several seconds lag depending on performance.



