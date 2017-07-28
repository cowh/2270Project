Summary
-------
My final project implementation will be a graph & linked list implementation. The main functionality of the program will be to create, store & traverse graphs to gather information about the graph & determine whether or not the graph is Eulerian. An Eulerian graph can be traversed completely (meaning we visit each vertex once) while only touching each graph once. There are two different concepts that I will touch on in this project. The first being determining & Eulerian trail which finds a path accross a graph that visits each vertex while only touching each edge exactly one time. The second concept is similar, but modified in that it is an Eularian trail that starts & ends on the same node; this is called an Eularian circuit. The linked list functionaly will come into play in my adjacency list. Each index in my adjacency list will be a linked list in which the head contains each city & the trailing nodes & the connected nodes for which the head node has a direct path.

How-To
------
Download the five files included & store them in a like directory.

The driver file of my code contains the description of how to use my program & it is detailed so I'm leaving it out of my ReadMe file.

Dependencies
------------
To guarantee that the program will run you should compile with C++11 or later. Otherwise, I use vectors to store nodes for graphs & information about adjacent nodes. My project contains two separate classes that depend on each other to run properly.

System Requirements
-------------------
MacOS 10.6.8 (or later)
Windows XP (or later)

Coby Whitmore
