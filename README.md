Problem Statement: My friends and I had nothinng inn mind when we though of ideas for this project, but then we came up out problem that we wanted to solve. We wanted to help the blind in their problem of walkinng with a stick. 

Solution: Out first idea was to make a smart stick which would be able to detect objects at a certain distance ahead and tell the user about the obstacle using vibration motors and different pre-programmed sets of combination. We planned to use a short burst for go, long burst for stop, 2 short burts for turn right, 2 long bursts for go left.

Prototype 1: We started our project by using a bought walking stick for the blind and trying to figure out where to attach the sensors and motors along with all the other electronnic equipment like out ESP32 boards, wires, breadboard, power supply. We spend approximetly a day on the stick but evennntually guided from our mentors we found that our project would have more flaws than we would have been able to fix. We also found out that addinng a detection system onto a detection system(The originnal stick) was not an effective idea. 

Our Though process: We started brainstorming and also reached out to the National Association For The Blind and gained their insight, although they were not that helpfull in telling us what issues the blind community face they did however open a path which we hadn't though of. They helped us realise that we could create another detection system for walking that gets rid of the stick altogether enabling the user to walk normally without a stick. 

Prototype 2: We endded up taking forward an incomplete idea by another set of creaters named ,they made a project called BAT-NAV which was a small module attached to the the back of their foot. Their project can be viewed in detail below in the given links. We decided fix all the flaws from their project while adding our own innovvation into it. We fixed the foot modules by shifting it up to the ankle/shin and also adding a head module which fits arround the ears of the user to also detect any obstaces at head level.

Objectives:
Detect objects using a ultrasonic sensor
Cross-check output of sensor with a preprogrammed value such as 150cm
Activates the actuator connected to a haptic motor which creates vibrations
Inform user of obstaces using different combinations of vibration 

Materials:

Cardboard strip to connected the 2 ear pieces to each other

2 Acrylic pieces with a eliptical hole in the middle of dimensions 25x45 (Head Module)

Jumper Wires

ESP32 

Breadboard

Ultrasonic Sensors

Simple on-off switch

Haptic vibration motor

9V Battery

Arduino Nano

AA Batery

Aclylic Box (Foot module)



How the product works: 
The ultrasonic sensor measures the distance between itself and the object and transmitts it to the ESP32
The ESP32 checks the value to a preset value if it is lesser then it activates the hhaptic sennsor and creates vibrations if no it will continue to compare values



https://makersasylum.com/project/project-bat-nav/
https://github.com/AryamanTandon/Project-Bat-NAV
