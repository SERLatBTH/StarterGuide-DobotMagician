# Dobot Magician

  DOBOT Magician is a multifunctional desktop robotic arm for practical training education. Installed with different end-tools, DOBOT Magician can realize interesting functions such as 3D printing, laser engraving, writing and drawing. It supports secondary development by 13 extensible interfaces and over 20 programming languages, which really makes your creativity and imagination increase without any limitation. As the good performance both in hardware design and software application, DOBOT Magician has won the CES 2018 Innovation Award and iF DESIGN AWARD 2018.

## Content

* [Where To Find](#where-to-find)
* [In The Box](#in-the-box)
* [How To Make It Works](#how-to-make-it-works)
  * [Assembly](#assembly)
    * [SuctionCup](#suctioncup)
    * [Gripper](#gripper)
    * [Pen](#pen)
    * [3D Printing](#3d-printing)
    * [Laser Engraving](#laser-engraving)
    * [WIFI Kit](#wifi-kit)
    * [Bluetooth Kit](#bluetooth-kit)
  * [Connecting With PC And Software Setup](#connecting-with-pc-and-software-setup)
* [Operation](#operation)
  * [Quick start 1 - Teaching and Playback](#quick-start-1---teaching-and-playback)
  * [Quick start 2 - Writing and Drawing](#quick-start-2---writing-and-drawing)
  * [Quick start 3 - Blockly](#quick-start-3---blockly)
* [Functions](#functions)
* [SDK](#sdk)
  * [SDK Demos Content](#sdk-demos-content)
  * [Source code](#source-code)
  * [API Interface Description](#api-interface-description)
  * [Examples On Github](#examples-on-github)
* [Putting The Device Back](#putting-the-device-back)
* [More Documentations](more-documentations)


## Where To Find

Storage room - shelve C

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
   5.1 Shipping list
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
    10.3 Tool Package (Hexagon Screwdriver M1.5 M2 M2.5, Quick Fix Screw, Calibration Tool, Jackscrew * 2)
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

### Assembly
The robot already assembled and just few steps is needed to get it to work
1. Choose the tool you want to Connect
2. Put it at the end of the robot arm by losing the screw below
3. Follow the steps below for the tool you chose
Below is the picture which showing the official name of the different parts in Dobot Magician arm.
![alt text](/images/armDescription.jpg)
#### SuctionCup
For connecting SuctionCup, you need the suction cup kit and an air pump.
1. Connect the air pump's power cable SW1 to the SW1 connector on the Dobot Magician base' rear panel and the siganl cable GP1 to the GP1 connector.
2. Insert a suction cup kit into the end's port, and fasten it with clamp fixing screw.
3. Connect the air pump's air tube to the air tube connector of the suction cup kit
4. Connect the servo's GP3 cable to the GP3 connector on the Forearm
#### Gripper
For connecting Gripper, you need the Gripper kit and an air pump which helps open and close the gripper.
1. Dismantle the suction cup by unfastening its terminal strand with a 1.5mm hexagon wrench.
2. Install a gripper kit to the servo with a 2.5mm hexagon wrench
3. Connect the gripper kit and an air pump to the Dobot Magician in the same way as the suction cup kit is installed
#### Pen
A writing and drawing kit consists of a pen and a pen holder.
1. Install a pen in the pen holder
2. Fasten the writing and drawing kit to the Dobot Magician's end with clam fixing screw
3. Posistion a sheet of paper on the work surface within the workspace of the Dobot Magician
#### 3D Printing
3D printing kit contains extruder, hot end, motor cable, filament, and filament holder.
1. Press down the lever on the extruder, and push down the filament to the bottom of the hole via the pulley
2. Connect the end of the PTFE tube to the hot end and push it down to the bottom of the hot end, and connect the other end to the extruder
3. Insert the filament intto the PTFE tube and push it down to the bottom of the hot end
4. Fix the hot end on the Dobot Magician with lamp fixing screw
5. Insert the heating cable to the interface4 on the Forearm, the fan cable to the interface5 and the thermistor cable to the interface6
6. Connect the extruder to the Stepper1 interface on the back of the base with motor cable
7. Place the filament and the extruder to the filament holder

#### Laser Engraving
A laser kit includes a laser. Both grayscale-engraving and laser-engraving use the laser kit as the end-effector.
1. Fasten the laser kit to the Dobot Magician's end with clamp fixing screw.
2. Connect the laser's power cable to the SW4 connector on the Forearm and the TTL control cable to the GP5 connector

#### WIFI Kit
You can connect Dobot Magician to a PC via WIFI kit without USB cable, making Dobot Magician and PC in the same WLAN.

Prerequisites:

* Dobot Magician has been connected to a PC via USB cable
* Dobot Magician has been connected to the power adapter
* The WIFI name and password have been obtained and must be the same as that of PC

Procedure:

1. Connect the WIFI kit to the UART interface on the base
2. Press down the power button to turn on the Dobot Magician
3. Select the corresponding serial port from the serial drop-down list, and click Connect
4. Click Setting>Wi-Fi. The Set Dobot Wi-Fi page is displayed.
5. Set the related parameters on the Set Dobot Wi-Fi page
6. Click OK.
7. Click Disconnect on the lft pane of the DobotStudio page.
8. After 2 second later, select IP address from the drop-down list on the upper left pane of the DobotStudio page and click Connect.

#### Bluetooth Kit
Dobot Magician can be connected to smart phone with Bluetooth.
Please download the matched DobotStudio APP from the website [https://cn.dobot.cc/downloadcenter.html?sub_cat=69#sub-download](https://cn.dobot.cc/downloadcenter.html?sub_cat=69#sub-download).

Prerequisites:

* Dobot Magician has been connected to the power adapter
* The DobotStudio APP has been downloaded

Procedure:

1. Connect the Bluetooth kit to the UART interface on the base
2. Press down the power button to turn on the Dobot Magician.

After turning on, there are three short beep sounds and the blue LED indicator on the Bluetooth module is on and the green one is blinking. Turn on the Bluetooth and launch DobotStudio APP on your phone. And click Connect to connect with Dobot Magician.

### Connecting With PC And Software Setup

Here is the brief introduction of how to operate the Dobot Magician with the software DobotStudio, allowing you to quickly know and use the robotic arm. For details, please go [here](https://www.dobot.cc/downloadcenter.html?sub_cat=73#sub-download) to download the manuals.

1. Connecting Cables to the Dobot Magician

   Step 1  Connect the Dobot Magician to your computer with the supplied USB cable

   Step 2  Connect the Dobot Magician to the electrical outlet with the supplied power adapter

2. Installing the DobotStudio

   1. System Requirements

      * Windows 7, Windows 7, Windows 8, and Windows 10 (This manual is explained based on this version)
      * macOS 10.10, macOS 10.11, and macOS 10.12

   2. Obtaining the DobotStudio Package

      Before using Dobot Magician, download the Windows DobotStudio package from https://www.dobot.cc/downloadcenter.html. The macOS version is also downloadable in this URL

   3. Installing the DobotStudio

      Prerequisites

         The DobotStudio package has been obtained.

      Procedure

        Step 1 Unpack the DobotStudio package to a destination directory.

        For example, this directory is Installation Directory\DobotStudio. You can install the DobotStudio to another location based on site requirements.

        Step 2 In the installation directory double-click DobotStudioSetup.exe. The Select Setup Language dialog box is displayed.

        Step 3 Choose a setup language such as English

        Step 4 Click OK to follow the on-screen instructions to continue with the installation. During the installation, the Driver Installation dialog box is displayed.

        Step 5 Click Next to install the first driver, and then click INSTALL to install the second driver.

        When the drivers are installed successfully, the Completing the Device Driver Installation Wizard dialog box is displayed . Click Finish.

        Step 6 Click Next to continue to install the DootStudio by following the prompts on the Setup-DobotStudio dialog box.

        When the installation is complete, the Completing the DoobotStudio Setup Wizard dialog box is displayed, click Finish.

       Verifying the Installation
         * Verifying the DobotStudio
            If the DobotStudio is launched and runs properly by double-clicking the desktop shortcut to this program, it means that it is installed successfully.
         * Verifying the Dobot Magician Driver
            If an available COM port is displayed on the upper left corner of the DobotStudio page after the robotic arm is powered on, the Dobot Magician driver is installed successfully.

3. Powering On/Off the Dobot Magician

   * Power on: align the Dobot Magician into its neutral position with its Forearm and Rear Arm constructing a 45-degree angle, and press down the power button in the base. Once the robotic arm is powered on, the LED indicator turns yellow, and all the stepper motors lock. And then wait about seven seconds, a short beep sound will be heard, and the LED indicator turns from yellow to green. Now the Dobot Magician is ready to use.

    * Power off: When the LED indicator is green, press down the power button to turn off the robotic arm. In this case, the Forearm moves slowly to the Rear Arm while the angle between them becomes small. Finally, the two arms reach a specific position.

4. Getting Started

   This topic describes how to use the Dobot Magician to complete the teaching & playback function by saving three points in the MOVJ mode, allowing you to get the basic knowledge of the usage of the robotic arm.

    Prerequisites

      * The DobotStudio has been installed. For details, see 2. Installing the DobotStudio.
      * The Dobot Magician is powered on. For details, see 3. Powering On/Off the Dobot Magician.

   Procedure

    * Step 1 Double-click the desktop shortcut to the DobotStudio.
    * Step 2 Click Connect on the DobotStudio page.
    * Step 3 Click Link Now.
    * Step 4 Use DobotStudio to accomplish a teaching & playback task.
    * Step 5 Enter times in Loop text box.
    * Step 6 Click Start to perform the motions.
    * Step 7 Click Exit to exit the Teaching & Playback page.

## Operation

### Quick start 1 - Teaching and Playback
  * Step 1 Preparation: mount the suction cup on the robot arm
  * Step 2 Choose tool suction cup in DobotStudio: click Teaching & Playback i DobotStudio and choose SuctionCup in tools dropdown menu
  * Step 3 Set and save date for point A: use DobotStudio to run the Dobot Magician to point A where the item is available so that the suction cup nudeges article. Click on the Suction Cup and then + Point.
  * Step 4 Set and save data for Point B: use DobotStudio to run Dobot Magician to point B where the object is to placed, click out the check mark at SuctionCup, and click + Point.
  * Step 5 Run the recorded program: Press Start to run the program, Dobot Magician will move item from point A to point B as they have been saved in the list.
  You can also set the Dobot Magician by holding the button on the arm. Each time the button is released, a point is added to the list.

### Quick Start 2 - Writing and Drawing
   * Step 1 Preparation: Mount the pen on the robot arm and place one paper in the robot's working area.
   * Step 2 Select tool get pencil: click on Write & Draw and select the Pen tool
   * Step 3 Select a figure: select a pre-programmed figure from input Shapes.
   * Step 4 Adjust the tip height: click Z + or Z- to adjust the arm iZ-point so that the tip touches the paper. Press AutoZ.
   * Step 5 Run writing and drawing function: click Start to get the Dobot Magician to draw and write.

### Quick Start 3 - Blockly
   * Step 1 Start programming with Blockly: click on any command (such as Logic, Loop, or Variable) in the list on the left edge and pull out any block to the programming surface.
   * Step 2 Select a block from the Dobot API and customize it: drag a JumpTo block to the programming area (Dobot API> Motion) and set (x,y,z) to (200,10,10)
   * Step 3 Extract another Dobot API block: pull out a JumpTo block to and set (x,y,z) to (300,10,10). put them together both blocks to create the desired program.
   * Step 4 Run the program in Blockly: click Start to get the Dobot Magition to perform the movements of the blocks discloses. In this case, from (200,10,10) to (300,10,10).
   
## Functions
* 3D Printing
  - As a robotic arm, Dobot Magician is precise enough for 3D printing models with nice finishing, it is comparable with many other 3D printers on the market. Thanks to its two extra stepper motor ports, Dobot Magician can also do double color 3D printing. Dobot Magician is compatible with mainstream open-source 3D printing
* Laser Engraving (available in Educational version only)
  - Dobot Magician can engrave not just lines, it can also sketch images with shades. Its powerful laser head is capable of engraving on harder materials like leather and wood. Only available in the Educational version.
* Grabbing and Sucking
  - With grabber and sucker accessories, Dobot Magician can move small objects. By customizing its movements, you can use it to help you out in some situations.
* Teach & Playback
  - You can build up a list of movements for Dobot Magician to execute. You can also make Dobot Magician memorize movements by simply dragging it, and make it repeat by one click. You can also customize its movements by more accurately setting parameters on its PC
software, where the playback list can be manually edited.
* Visualized Programming
  - Dobot Blockly is a visualized programming environment developed for Dobot Magician, based on Google’s open-source platform Google Blockly. On Dobot Blockly you can program by simply putting puzzles together, it is intuitive and highly readable. It also integrated exclusive API for Dobot Magician, you can use them right away.
* Multi-Dobot Cooperation
  - Through WIFI connection or connecting both machines to an external board, you can control multiple Dobot Magicians all at once. This not only saves you controlling devices, but also improved efficiency in operating and calibrating.

## SDK

Here document describes the secondary development environment building and demo codes in  multiple languages, frameworks, and systems, aiming to help secondary developer to understand common API of Dobot Magician and build development environment quickly.

To start developing apps for Dobot Magician, go to the [download center](https://www.dobot.cc/downloadcenter.html). Here you can find all the required documentation, SDKs and tools needed to develop applications for Dobot Magician.

1. Download [Dobot Demo](https://www.dobot.cc/downloadcenter/dobot-magician.html?sub_cat=72#sub-download) by going to download center->dobot magician -> development protocol -> dobot demo.
2. Extract the package content somewhere on your computer using compression tool.
3. The package contains demos for all the supported platforms and programming languages.
4. Open the demo for the desired programming language or platform using your preferred IDE.
5. Inside you will find the API for the Dobot Magician as well an example code.
6. Connect the Dobot Magician to your computer and run the demo. Note: in case you are using mobile application and would like to run the mobile demo, you will need to connect the Bluetooth module to be able to communicate with the robot. Go to the [Bluetooth module](#bluetooth-module) section to learn how to connect it.
For common system, we have supported DLLs for secondary developer. You can call DLL directly to control Dobot Magician without development related to communication protocol.

### SDK Demos Content

1. MFC based on Visual studio C++2008 and above;
2. Demo based on QT5.6;
3. C# Demo based on Visual studio 2013 and above;
4. Demo based on Python 3.5;
5. STM32 Demo for embedded controller;
6. Arduino Demo based on communication protocol (arduino mega board);
7. VB Demo based on Visual Basic.net;
8. Java Demo based on 32/64 bit JDK;
9. Multi-control DemoForQt5.6;
10. Dobot SDK Demo V1.0.0 for iOS;
11. Bluetooth Demo for Android.

### Source Code

* Dobot DLL
  
  The source codes and precompiled files can be found in DobotDLL directory. Please use Qt 5.6 software to check source codes. In addition, the corresponding DLLs for Windows 32-bit, Windows 64-bit, Linux and Mac can also be found in this directory.

* Compiling
  * Please download the Qt version for your system and install it. The download path is [here](https://download.qt.io/archive/qt/5.6/5.6.0/).
  * NOTICE: If the Qt library is used when compiling DLLs, please use the Qt software with MSVC compiler and compile Dobot DLLs with MSVC.

* Usage
  * For Windows OS, please add the DLLs directory to environment variable Path.
  * For Linux OS, please add the following statement at the end of ~/.bash_profile file and restart computer.

  Program 1.1 Add statement in Linux OS

  ```export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:DOBOT_LIB_PATH```

 * For Mac OS, please add the following statement at the end of ~/.bash_profile file and restart computer.

  Program 1.2 Add statement in Max OS

  ```export DYLD_LIBRARY_PATH=$DYLD_LIBRARY_PATH: DOBOT_LIB_PATH```


### API Interface Description

There are two features of communication commands when communicating with Dobot controller:

1. All commands can be returned to the controller; regarding to setup commands, the controller can cut command parameter domain and then return; while for getting commands, the controller can fill the parameters got in parameter domain and then return.
2. Dobot controller supports two kind of commands: Immidinate instruction and queen instruction:
* Immidinate instruction: Dobot controller will process the command once received regardless of whether there is the rest commands processing or not in the current controller;
* Queue command: Dobot controller receives the queue instruction, the command is pressed into the controller internal instruction queue. Dobot controller will execute instructions in the order in which the instruction was pushed into the queue.

For more detailed information about Dobot commands, please refer to Dobot protocol
[here](http://www.dobot.it/wp-content/uploads/2018/03/dobot-api-en.pdf)


### Examples On Github
* Python library could be found on github [repository](https://github.com/luismesas/pydobot)
* More libraries and examples could be found on [github as well](https://github.com/topics/dobot)

## Putting The Device Back
After finish using the device, it is important to turn off, disassemble and put it back in the box as it was found, then put the box back in its place.

## More information
For details how to operate Dobot Magician with DobotStudio APP, please see [here](https://www.youtube.com/watch?v=kyeXwuf17IY)
