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
The ESP32 checks the value to a preset value if it is lesser then it activates the hhaptic sennsor and creates vibrations if not it will continue to compare values
The vibration motor creates vibrations and alerts the user of any obbstaces in front of them



Assembly of our product 
We started out product by trying to attach out sensors onto a pair of glasses, however we soon realised that we could not attach the sensors and other electronic equipment onto the glasses because the weight of the components woiuld be too much for the small glasses to hold leading to the user being uncomfortable and also it would also cause a risk of the sensors falling down from the glasses. 

We switched to thinkinng of attaching all our sensors to a headset that would also allow us to make it comfortable for the user while also makinng it easy to use and wear. We went forward to making platform for the components with a small slit *cad1* for the ear to fit through and a back strap to contain all the wires between the sensors and the boards on the platform. We nade tgus first prototype out of cardboard and foamboard. *photo 1&2*

We then went onto another prototype where we moved the placement of the componenets and made the platform out of acrylic instead of foam to increase sturdiness and durability. *photo3* For the power supply we soldered 4 AA batteries to each other *photo4* We attached all the components to the platform *photo5,6,7,8*

We then laser cut the leg module box on acrylic from the cad file provided by BAT-NAV *cad2* and we joined it together to see the fitting. We then assembled the led module internal parts by connecting a 9V battery to a arduino nano on a breadboard. We also connected a vibration motor, switch and sensor to the esp *photo9,10*

We then connected all the parts and the final result is *photo11*. The testing of the product was done by my teammate Dhruv *photo13,14*
We also tried to attach the leg module using tape but however it was very unstable *photo15,16*

Later we found an issue in the leg mdoule so we altered it to have a velcro strap for the fastening and also added a gap for the switch to fit through *cad3*







https://makersasylum.com/project/project-bat-nav/
https://github.com/AryamanTandon/Project-Bat-NAV
