# Autonomous Land Vehicle Prototype for Mapping of Industrial Environments
The use of mobile robots is increasingly present in the development of society, from
simple tasks like domestic services to more complex ones like rescue missions. Currently,
the main challenge of a mobile robot occurs when the robot is inserted in an
unknown environment, causing its route to be recalculated several times, with the detection
of information from the environment, until reaching its final goal. Therefore,
this work proposes the development of a prototype of an autonomous terrestrial vehicle
capable of moving around industrial environments and mapping it. The CAD model
of the vehicle was first designed in the Solidworks software and to have a low production
cost, its parts were produced using additive manufacturing through 3D printing.
The electrical part of the vehicle has a Raspberry Pi for processing data from several
sensors capable of detecting obstacles and mapping the area, in addition to actuators
that allow its locomotion in the environment. To facilitate the connections between
the various devices present, a printed circuit board (PCB) was developed that works
as a shield, connecting the microcontroller used to the devices. For programming the
algorithms, the Robot Operating System (ROS) was chosen to facilitate the connection
between the various devices and for containing packages for implementing the
mapping algorithms, such as Hector SLAM. The robot was assembled and tested in
3 environments with industrial characteristics and presented an average of 93.67% of
accuracy in relation to the floor plan of the place, taking approximately 12.06min/m2
to perform the mapping in each one of the environments.
