# Dobot Magician

  DOBOT Magician is a multifunctional desktop robotic arm for practical training education. Installed with different end-tools, DOBOT Magician can realize interesting functions such as 3D printing, laser engraving, writing and drawing. It supports secondary development by 13 extensible interfaces and over 20 programming languages, which really makes your creativity and imagination increase without any limitation. As the good performance both in hardware design and software application, DOBOT Magician has won the CES 2018 Innovation Award and iF DESIGN AWARD 2018.

## Content

* [Where To Find](#where-to-find)
* [In The Box](#in-the-box)
* [How To Make It Works](#how-to-make-it-works)
  * [Powering Up](#powering-up)
* [Operation](#operation)
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

### Quick Start

Here is the breif introduction of how to operate the Dobot Magician with the software DobotStudio, allowing you to quickly know and use the robotic arm. For details, please go [here](https://www.dobot.cc/downloadcenter.html?sub_cat=73#sub-download) to download the manuals.

1. Connecting Cables to the Dobot Magician

   Step 1  Connect the Dobot Magician to your compututer with the supplied USB cable

   Step 2  Connect the Dobot Magician to the electrical outlet with the supplied power adaper

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
    * Step 4 Use DobotStudio to accopmplish a teaching & playback task.
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
   * Step 1 Start programming with Blochly: click on any command (such as Logic, Loop, or Variable) in the list on the left edge and pull out any block to the programming surface.
   * Step 2 Select a block from the Dobot API and customize it: drag a JumpTo block to the programming area (Dobot API> Motion) and set (x,y,z) to (200,10,10)
   * Step 3 Extract another Dobot API block: pull out a JumpTo block to and set (x,y,z) to (300,10,10). put them together both blocks to create the desired program.
   * Step 4 Run the program in Blockly: click Start to get the Dobot Magition to perform the movements of the blocks discloses. In this case, from (200,10,10) to (300,10,10).
