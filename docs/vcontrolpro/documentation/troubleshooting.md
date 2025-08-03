# Troubleshooting

<a id="step-1"></a>
## Step 1 - Verify The License

V-Control Pro needs to be licensed for most systems, using either a trial license or a purchased license. [Learn more about Licensing](../v-control-pro-licensing/)

!!! note "RAVEN Info"
    RAVEN users do not need to use a V-Control Pro license.

#### Check If V-Control Pro Is Licensed

* Launch V-Control Pro
* Select the <b>About V-Control Pro</b> menu item to open the About window.
* The About window will indicate "Licensed" or "Not Licensed."
* If it is licensed, proceed to [Step 2](#step-2).

#### V-Control Pro Is Not Licensed, What Next?

* Get A License

    * You can get a trial license at the [Neyrinck Trial License Page](https://neyrinck.com/v-control-pro-trial/).
    * You can purchase a license at the [Neyrinck Store](https://neyrinck.com/store/).
    
* Activating A License
    * After getting a license deposited to your iLok user account, you must [activate the license](../v-control-pro-licensing/#license-activate).
    * After activating, verify that V-Control Pro is licensed.
        * Quit V-Control Pro.
        * Go back to [Step 1 - Verify The License](#step-1)
        * If the license is activated, go to [Step 2](#step-2)

<a id="step-2"></a>

## Step 2 - Make Sure Your Surface Is Added And Connected

V-Control Pro will only work if your control surface is added and is detected to be  in the Setups window.

* Launch V-Control Pro.
* Select the V-Control Pro <b>Setups...</b> menu item to open the Setups window.
* Look at the <b>Controllers</b> section at the lower left.
    * If your surface is already added, [verify it is connected](#verify-connected)
    * If your surface is not added, [add your control surface](#add-surface)

<a id="add-surface"></a>

#### Add Your Control Surface
* Launch V-Control Pro.
* Select the V-Control Pro <b>Setups...</b> menu item to open the Setups window.
* Click the <b>Add new...</b> button in the Controllers section at the lower left of the Setups window.
* Select the type of surface you are adding. For more information see 

<a id="verify-connected"></a>

#### Verify Your Control Surface Is Connected

* Launch V-Control Pro.
* Select the V-Control Pro <b>Setups...</b> menu item to open the Setups window.
* Look at the Controllers section of the Setups window
    * If the control surface name is "grayed out," then it is not connected.
        *  Try looking at 
    * If the control surface name is "bold," then it is connected 

#### Troubleshooting Controllers That Are Not Connected

If the Setups window shows your surface name as "grayed out," then it is indicating the surface is not detected.

* Try [Troubleshooting Ethernet Issues](#ethernet-issues)
* Review the [Ethernet Controllers Section](../ethernet-controllers/)

<a id="ethernet-issues"></a>

#### Troubleshooting Ethernet

<a id="ethernet-led"></a>

##### Ethernet LED Indicator
Ethernet control surfaces have an LED indicator on the rear panel next to the ethernet cable jack. This LED indicates if an ethernet connection is active.

* Check the rear panel of your control surface to make sure an ethernet cable is connected.
* Check the rear panel of your control surface to make sure the LED indicator at the ethernet connector indicates activity. If the LED does not indicate activity, then there are several possible probelms:
    * The ethernet cable is faulty. Try using a different cable.
    * The ethernet cable is not connected at both ends.
    * The control surface hardware has an issue.

##### The Add Ethernet Device... Window Does Not Show The Surface

When you select the <b>Add Ethernet Device...</b> option in the <b>Add new...</b> controller window, V-Control Pro monitors a network to detect if a surface is available. If no surface is seen, you will need to check a few things:

* Is the [Ethernet LED Indicator](#ethernet-led) on the surface active?
* Is the ethernet port enabled in the computer?
    * For Mac OS, open System Settings / Network. If the ethernet port is colored red, then it is not enabled. Using a low cost network switch between the computer and surface usually solves this.
    * For Windows, make sure the "Npcap" utility is installed. Learn more about [Mac OS and Windows Networking](../ethernet-controllers/#networking)
    * For Windows, make sure the "Win10Pcap" utility is NOT installed.

## Step 3 - Windows OS Issues

Windows OS users have been able to solve problems using one or more of these steps.

#### Updating To V-Control Pro 3 From V-Control Pro

Some DAWs, especially Pro Tools on Windows, keep track of MIDI ports by number rather than by name. V-Control Pro 3 changed the ports and Pro Tools can get confused if you are updating V-Control Pro.

* Quit Pro Tools
* Trash Pro Tools Prefs
* Launch Pro Tools
* Reset Pro Tools Midi Input Enables.
* Reset Pro Tools Midi Peripherals.

#### Updating To Windows 11 From Windows 10

Some users have seen an issuee wher V-Control Pro is unable to launch when updating a WIndows 10 system to Windows 11.

* Install Windows 11 from scratch