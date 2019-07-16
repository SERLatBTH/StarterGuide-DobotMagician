# Dobot Magician

  DOBOT Magician is a multifunctional desktop robotic arm for practical training education. Installed with different end-tools, DOBOT Magician can realize interesting functions such as 3D printing, laser engraving, writing and drawing. It supports secondary development by 13 extensible interfaces and over 20 programming languages, which really makes your creativity and imagination increase without any limitation. As the good performance both in hardware design and software application, DOBOT Magician has won the CES 2018 Innovation Award and iF DESIGN AWARD 2018.

## Content

* [Where To Find](#where-to-find)
* [In The Box](#in-the-box)
* [How To Make It Works](#how-to-make-it-works)
  * [Charging The Batteries](#charging-the-batteries)
  * [Powering Up](#powering-up)
* [Device's Functionalities and Features](#device's-functionalities-and-features)
* [SDK](#sdk)
  * [Become A Developer](#becaome-a-developer)
* [Putting The Device Back](#putting-the-device-back)
* [More Documentations](more-documentations)


## Where To Find

Storage room - shelve ?

## In The Box

Here you can see the included components and their locations. The Dobot Magician box has two layers and many boxes. Please check the content list when you get and place them well by following the presented pictures before you return since the components are fragile.
1. Robot Arm
2. Power Cable Box
   2.1 Power Adapter
   2.2 USB Cable
   2.3 Charger
3. Masking Tape (3D Printing)
4. Feed Pipe (3D Printing)
5. Accessories Box
   5.1 Shippling list
   5.2 User Manual
   5.3 Glass Plate (3D Printing)
   5.4 Sensor Calibration Board
   5.5 Kraft Linner Paper (Laser Engraving)
6. Wireless module box
   6.1 Bluetooth Module (wireless-1)
   6.2 WIFI Module (wireless-2)
7. Laser controller box
   7.1 Joystick controller kit
   7.2 Laser Module
   7.3 USB Connector Host
8. Laser Protective Glasses
9. Laser Engraving Kit
10. Main kit box
    10.1 Writing Drawing Kit (Pen Holder, Pen)
    10.2 Pneumatic Kit (Pneumatic Gripper, Suction Cup & Joint 4, Air Pump Controller)
    10.3 Tool Package (Hexagon Screwdriver M1.5 M2 M2.5, Quick Fix Screw, Calibration Tool, Jackscrew *2)
11. Extruder
12. Hot End
13. 3D Printing Filament Holder
14. Filament 200g
![alt text](/images/outward.jpg)
![alt text](/images/layer1.jpg)
![alt text](/images/layer2-1.jpg)
![alt text](/images/layer2-2.jpg)
![alt text](/images/accessoriesBox.jpg)
![alt text](/images/contentDetails.jpg)

## How to make it works
Step1: Download Software and Install Arduino Driver

1.Download software from our website: dobot.cc/download 

2.Install Arduino drivers. You can download Arduino from www.arduino.cc or directly from our website. 
DobotTools: Basic version,including functions of Teach & playback,writing,drawing,laser engraving and mouse control. 
Download DobotApplication:Professional version, two more functions comparing to basic function,leap motion and EEG.
Download check whether Arduino is installed properly in Device Manager.

Step2: Connect Cable
1.Connect the stepper motors according to labels (Stepper_L, Stepper_R, Stepper_rot ) on the black cable.Note: Stepper_L and Stepper_R subject to right ahead Dobot body. 
2.Connect the angle sensors: loosen the neighboring screws before inserting the sensor modular. 
3.Connect the servo Note: servo cable connection order: orange to white; red to red; brown to black. 
4.connect air tube and suction cup 
5.connect power cable and USB cable Correct inatllation diagram of the sensor 

Step3: Start Dobot
1.Put Dobot in the following recommended position 
2.Power up 
3.Reset 
info about the recommended position: When Dobot is powered up at a limited position, it will be locked up and not capable of moving. The angle sensors have more accurate readings when it is positioned in less than 45°regarding the horizontal plane, which gives a good start for Dobot. Info about Reset: Dobot requires a reset to get the current angle sensor reading after powering up. 

Step4: Run the software (DobotApplication/ DobotTools) and Play!
Operation instruction of software interface
1. Jog Mode: you can set Axis Mode or Linear Mode.
2. Jog Button:hold the button to move robot. 
3. Velocity Ratio：change the jog velocity. 
4. End Effector Operation: Turn ON/OFF the pump or OPEN/CLOSE the Gripper. 
5. Current State: A table showing current joint angle value,coordinate of end,and default MotionStyle and PauseTime. 
6. Playback List: table of saved points, which can be edited. 
7. Save: add a point to the playback list. 
8. Start/Stop: start/stop playback. 
9. Import/Export: import(export) the playback list from(to) an .xml file. 
10. Loop Number: set how many to repeat the playback list;Current Loop: index of the loop has been sent to controller. 
11. Velocity Ratio & Acceleration Ratio:Set the velocity/acceleration ratio for playback. 

Step5: Let's Play
Click Range①,change JogMode to liner mode. Place one small object(such as mobile phone) near Dobot,,click Range② to operate Dobot and move above the small object,then click ⑥, open the pump, and the small object will be sucked up. Click ⑦ to save one point. Now turn back Range ②, click Z+ firstly, then raise the height of mobile phone, next move Dobot on another place, place the object on desk, click ⑥, close pump at last. Click ⑦ to save another point. Click Z+, place the object to original location. Click ⑧ start, task for moving the object from current location to another location is completed successfully.
