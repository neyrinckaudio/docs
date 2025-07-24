title: Master V-Control Pro for Professional Audio Production
description: Learn how to connect control surfaces like D-Command and FaderPort to Pro Tools, Cubase, Logic Pro X, and more. Discover advanced MIDI mapping techniques, troubleshooting tips, and optimize your audio production workflow. Perfect for sound engineers, music producers, and audio professionals seeking to enhance their studio experience with powerful control surface integration.

# Welcome To V-Control Pro
V-Control Pro is a Mac and Windows application that connects control surfaces to digital audio and video workstations. It connects surfaces such as D-Command, C24, Control 24, FaderPort to DAWs such as Pro Tools, Cubase, Logic Pro X and many others. It uses iLok licensing that can be activated on your computer or on an iLok USB key. It provides MIDI Mode for surfaces so that surface buttons, faders, and encoders can be mapped to any application that provides MIDI mapping.

[See the full compatibility list](https://neyrinck.com/vcpro-compatibility/){ .md-button }

## Premiere Pro 

* In the Premiere Pro top menu bar select: Premiere Pro/Preferences/Control Surface...
* Select Add for new Device Class
* Select Device Class: Mackie
* Select Settings... to open Device Class settings window
* Select Mackie in the settings window and select Edit
* Configure Mackie Control as the following
Device Type: Mackie Control
MIDI Input Device: V-Control
MIDI Output Device: V-Control

Here is how to setup additional controllers for up to 32 tracks of control simultaneously.

* * In the Configure Mackie Controller window, click on Add and set up as:
Device Type: Mackie Control XT
MIDI Input Device: V-Control XT2
MIDI Output Device: V-Control XT2
Repeat this step replacing V-Control XT2 with V-Control XT3 and V-Control XT4 for 32 tracks total.

NOTE: Some commands need to be manually mapped in Premiere Pro CC for full use. Go into the Button Assignments window in the Control Surface setup and assign the following:

Button: Flip - Command: Go To Previous Edit Point
Button: SMPTE/Beats - Command: Go To Next Edit Point
Button: Cycle - Command: cmd.audiomixer.loop
NOTE: For the Channel/Bank select buttons to work, there must be more audio tracks created in the current session than the number of tracks that are controlled by V-Control Pro. For example, if setup for 16 tracks of control, there must be at least 17 created audio tracks in Premiere for the Channel/bank select buttons to function.

<a id="setting-up-reason"></a>

## Reason Setup

* In the Reason top menu bar go to: Reason / Preferences...
* Select "Control Surfaces" in the preferences window.
* Click on "Add" and select the following:
Manufacturer: Mackie
Model: Control
Input: V-Control
Output: V-Control
*  Click "OK" to close window.

Here is how to add an additional controller device for when using a separate controller.

* Click on "Add" and select the following:
Manufacturer: Mackie
Model: Extender
Input: V-Control XT 2
Output: V-Control XT 2
* Click "OK" to close window.

Here is how to setup for V-Console 16 to have all 16 channels linked together:

* Click on "Add" and select the following:
Manufacturer: Mackie
Model: Combo, Extender Right
Control Input: V-Control
Extender Input: V-Control XT 2
Control Output: V-Control
Extender Output: V-Control XT 2

<a id="setting-up-reaper"></a>

## Reaper

#### 8 Channel

* In the Reaper top menu bar go to: Reaper / Preferences...
* Navigate to the Control/OSC/Web section of the Preferences window.
* Click on Add to bring up the Control surface setup window.
* Select the following in the Control Surface Settings Window:
Control Surface Mode: Mackie Control Universal
MIDI Input: V-Control
MIDI Output: V-Control

<img src="./images/reaper1.png" style="width:50%"></img>

#### 16 Channel

* Click on Add again to bring up a new window:
* Select the following in the Control Surface Settings Window to add the 2nd bank:
* Control Surface Mode: Mackie Control Extender
MIDI Input: V-Control XT2
MIDI Output: V-Control XT2
Surface Offset (Tracks): 8

<img src="./images/reaper2.png" style="width:50%"></img>

#### 24 Channel

* Click on Add again to bring up a 3rd new window:
* Select the following in the Control Surface Settings Window to add the 3rd bank:
* Control Surface Mode: Mackie Control Extender
MIDI Input: V-Control XT3
MIDI Output: V-Control XT3
Surface Offset (Tracks): 16

<img src="./images/reaper3.png" style="width:50%"></img>


<a id="setting-up-tracktion"></a>

## Tracktion

* Click on the "Settings" tab and select "MIDI Devices" on the side bar.
* Enable V-Control for the Input and Output.
* Select "Control Surfaces" on the side bar.
* Select "Mackie Control Universal and configure as follows:
Input Device: V-Control
Output Device: V-Control

<a id="setting-up-sonar"></a>

## Sonar

* In the Sonar top menu bar go to: Edit / Preferences / Control Surfaces...
* Configure for Connected Controllers/Surfaces as follows:
Controller/Surface: Mackie Control
In Port: V-Control
Out Port: V-Control

<img src="./images/sonar.png" style="width:75%"></img>

<a id="setting-up-flstudio"></a>
## FL Studio

* Go To Options and select MIDI Settings (F10)
* Select V-Control Pro in the Input section and Enable. Choose Mackie Control Universal as Control Type.
* Select V-Control Pro in the Output section and Enable.
* Set the MIDI Input/Output Ports to 102 for V-Control Pro
* V-Console and FL Studio should now have bidirectional communication with each other.

NOTE: FL Studio only supports one device for setup. It is not possible to setup for more than 8 tracks of control through V-Control Pro.

<a id="setting-up-fmod"></a>

## FMOD Studio

* In the FMOD Studio top menu bar select: FMOD Studio / Preferences...
* In the Preferences window, select the Control Surface tab.
* Select the following for an 8 channel surface:
Device Type: Mackie Control
Input Port: V-Control
Output Port: V-Control
FMOD Mackie 1

<img src="./images/fmod1.png" style="width:75%"></img>

* Select the following for an 16 channel surface:
Device Type: Mackie Control with Extender
Input Port: V-Control
Output Port: V-Control
Input Port 2: V-Control XT2
Output Port 2: V-Control XT2
FMOD Mackie 1

<img src="./images/fmod2.png" style="width:75%"></img>

<a id="setting-up-wwise"></a>

## Wwise

* In the Wwise top menu bar select: Project / Control Surface Devices
Click on "Add.." in the Control Surface Devices Window
* In the Wwise top menu bar select: Project / Control Surface Devices
Type out a name for device being used with V-control Pro.
name

<img src="./images/wwise1.png" style="width:75%"></img>

* In the Wwise top menu bar select: Project / Control Surface Devices
* In the Wwise top menu bar select: Project / Control Surface Devices
Set the settings of the device as shown:
Device Type: Mackie Control
Receive From: V-Control
Send To: V-Control

<img src="./images/wwise2.png" style="width:75%"></img>

<a id="setting-up-resolve"></a>

## DaVinci Resolve

* In the Resolve top menu bar select: DaVinci Resolve / Preferences...
* In the Preferences window, select "Control Panels"
* In the Audio Console section, enable "Use MIDI audio console".
* Setup with with the following settings:
MIDI Protocol: HUI compatible
MIDI Input: V-Control
MIDI Output: V-Control

<img src="./images/resolve.png" style="width:75%"></img>
