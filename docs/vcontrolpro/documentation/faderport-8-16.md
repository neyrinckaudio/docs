# FaderPort 8/16

V-Control Pro supercharges the FaderPort 8/16 for use with Pro Tools.

!!! info "Important Pro Tools Version Information"
    FaderPort 8/16 support has changed for Pro Tool 2023 and later. For Pro Tools 2022 and earlier, the M-Audio Keyboard protocol was used in Pro Tools. But Avid removed M-Audio Keyboard protocol in Pro Tools 2023. You must carefully configure V-Control Pro and Pro Tools depending on what version of Pro Tools you are using.

!!! warning "Set FaderPort Mode To Studio One Mode"
    It is VERY important the Faderport 8 / 16 is in Studio One Operation mode and NOT in HUI mode. This allows V-Control Pro to customize how FaderPort 8 / 16 maps to Pro Tools.

!!! warning "Disable FaderPort MIDI Input"
    In the Pro Tools MIDI Input Devices Window, disable the Faderport. It is used by V-control Pro and can cause conflict if enabled in Pro Tools as well.

!!! info "Control Features"
    Please see the FaderPort 8/16 feature charts online at [Feature Charts](https://neyrinck.com/help-category/v-control-pro-help/).


### Setup

#### FaderPort 8
* Add the device as a controller in the V-Control Pro Setups window as described in [Setting Up MIDI Controllers](./midi-controllers.md).
* Set Up Pro Tools Midi Peripherals
    * Pro Tools 2022 And Earlier
        * Set up Pro Tools for 1 M-Audio Keyboard bank as described in [Setting Up Pro Tools](./pro-tools.md).
    * Pro Tools 2023 And Later
        * Set up Pro Tools for 1 HUI bank as described in [Setting Up Pro Tools](./pro-tools.md).


#### FaderPort 16
* Add the device as a controller in the V-Control Pro Setups window as described in [Setting Up MIDI Controllers](./midi-controllers.md).
* Set Up Pro Tools Midi Peripherals
    * Pro Tools 2022 And Earlier
        * Set up Pro Tools for 1 M-Audio Keyboard bank and 1 HUI bank as described in [Setting Up Pro Tools](./pro-tools.md).
    * Pro Tools 2023 And Later
        * Set up Pro Tools for 2 HUI banks as described in [Setting Up Pro Tools](./pro-tools.md).


