title: Master V-Control Pro for Professional Audio Production
description: Learn how to connect control surfaces like D-Command and FaderPort to Pro Tools, Cubase, Logic Pro X, and more. Discover advanced MIDI mapping techniques, troubleshooting tips, and optimize your audio production workflow. Perfect for sound engineers, music producers, and audio professionals seeking to enhance their studio experience with powerful control surface integration.

# Welcome To V-Control Pro
V-Control Pro is a Mac and Windows application that connects control surfaces to digital audio and video workstations. It connects surfaces such as D-Command, C24, Control 24, FaderPort to DAWs such as Pro Tools, Cubase, Logic Pro X and many others. It uses iLok licensing that can be activated on your computer or on an iLok USB key. It provides MIDI Mode for surfaces so that surface buttons, faders, and encoders can be mapped to any application that provides MIDI mapping.

[See the full compatibility list](https://neyrinck.com/vcpro-compatibility/){ .md-button }

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
