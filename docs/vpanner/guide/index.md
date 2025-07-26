# Welcome to V-Panner
V-Panner is a Surround Panner Utility used with V-Control Pro. With V-Panner and Pro Tools, users can control surround panning for tracks or use Atmos Mode and control the Dolby Atmos Panning Plug-in. Users can also control the stereo panning in Logic and Cubase.

## Installation And Setup
For information on Installation and Setup for the V-Control Pro App go to the V-Control Pro Users Guide.

## Setting Up V-Panner On iPad.

Launch V-Control Pro on the Host Computer.
Launch iTunes/App Store on the iPad.
Search for V-Panner in the Search bar.
Tap GET and Install V-Panner.
Launch V-Panner on the iPad.
Tap the Gear Icon on the top left corner and select the connection type.
For Wired, please ensure that USB cable is connected between the iPad and computer.

## General Troubleshooting
Verify the device running V-Panner is on the same network as the host computer running V-Control Pro.
Verify that you have the host computer selected running V-Control Pro in the Connection section of the V-Panner settings.
Verify the host computer running V-Control Pro has a Computer name setup such as "John's Mac" in System Preferences / Sharing
Verify that V-Control Pro sees the device running V-Panner in the list of available devices.
Verify that the USB is securely plugged in to the host computer and iPad if using a wired connection.
Back to top
Setting Up With Pro Tools
Here are the instructions to setup V-Panner with Pro Tools.

Launch V-Control Pro.
Launch V-Panner on your device and connect to V-Control Pro.
Launch Pro Tools.
In Pro Tools go to "Setup/MIDI/Input Devices.."
Enable V-Pan 1
Enable V-Pan 2
In Pro Tools go to "Setup/Peripherals". Select "MIDI Controllers"
Setup as shown below in the first available row in Peripherals.


Type: "SurroundPanner" Receive From: "V-Pan 1" Send To: "V-Pan 1"
Type: "SurroundPanner" Receive From: "V-Pan 2" Send To: "V-Pan 2"
Back to top
Using V-Panner In Pro Tools
Here are the functions of V-Panner for Pro Tools. There are two sides for V-Panner with each panner having its own navigation control.


Pro Tools: Touch here to switch V-Panner to Pro Tools Mode.
Atmos: Touch here to switch V-Panner to Atmos Mode.
Navigation Bar
Left Arrow: Touch here to move the track selector one track to the left.
Right Arrow: Touch here to move the track selector one track to the right.
Up Arrow: Touch here to move the track selector up to cycle through available Aux Sends and Output on the track.
Down Arrow: Touch here to move the track selector down to cycle through available Aux Sends and Output on the track.
L/R: Touch here to switch the panner to the right pan controller in a stereo track. Touch again to switch back to the left.
When on a stereo track, open the panner window in Pro Tools and disable "Link" mode for independent control of the left and right panner.
Window: Touch here to toggle the panner window in Pro Tools.
To use the V-Panners, Navigate to the track that you would like to control with V-Panner. As V-Pan 1 and V-Pan 2 act as two independent controllers, you must navigate to the designated track with both panners separately.

Back to top
Setting Up V-Panner with the Dolby Atmos Panning Plug-in
V-Panner can be used to control the Dolby Atmos Panning plug-in in Pro Tools. Here is how to set it up.

Launch V-Control Pro
Launch Pro Tools
When using the Atmos panner, make sure the Surround Panner is disabled in the Pro Tools Peripherals section. It will conflict with the Atmos panner if enabled during control.
Launch V-Panner on the iPad
Touch the Atmos button in V-Panner to switch to Atmos Mode.
Insert Dolby Atmos Panner on a Mono or Stereo track in Pro Tools.
Open Dolby Atmos Panner plug-in window.
Select the Gear icon in the plug-in window to open the Settings.

In the Joystick Device box do the following:
Input: V-Pan 1
Output: V-Pan 2

You can setup a separate mono dolby panner plug-in as well:
Input: V-Pan 2
Output: V-Pan 2
NOTE: As it stands, only one panner plug-in can be active at a time. To activate the panner for control, click in the the plug-in panning window in Pro Tools to select and activate it. The background color of the window will be blue to indicate it is active. It will be dark grey if inactive.

Back to top
Using V-Panner with Dolby Atmos Panning Plug-In
Here is a list of functions for the buttons going from top to bottom.


Pro Tools: Touch here to switch V-Panner to Pro Tools Mode.
Atmos: Touch here to switch V-Panner to Atmos Mode.
Z Toggle: Touch here to toggle Elevation Mode On/Off.
Default Elevation Mode: Touch here to switch to Default elevation Mode.
Wedge Elevation Mode: Touch here to switch to Wedge Elevation Mode.
Sphere Elevation Mode: Touch here to switch to Sphere Elevation Mode.
Ceiling Elevation Mode: Touch here to switch to Ceiling Elevation Mode.
Z Fader: Touch and drag the Z Fader to adjust Z Axis. Can be used with Default Elevation Mode only.
Size Fader: Touch and drag the size fader to adjust the object size.
