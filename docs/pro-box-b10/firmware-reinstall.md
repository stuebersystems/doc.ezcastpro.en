# Reinstall Firmware

You can restore EZCast Pro Dongle II by reinstalling the firmware. There are multiple reasons for doing this:

* EZCast Pro Dongle II does not power on and the power supply has already been checked. This could be due to an interrupted [firmware upgrade](firmware-upgrade.md).

* EZCast Pro Dongle II is running unstable. Performing a [device reset](reset.md) did not help.

There are two options: Install the latest firmware or select a specific firmware.

!!! warning "Warning"
    
	When you reinstall the firmware **all** existing settings will be lost.

## Requirements

* A Windows computer to load the firmware software onto the EZCast Pro Dongle II.

* EZCast Pro Box II must be connected to the Windows computer via [USB Type A Male to Male cable](https://www.amazon.co.uk/Rankie-Type-Male-Cable-Black/dp/B01KRO8D20/ref=sr_1_5?dchild=1&keywords=USB+3.0+Cable+A%2FA&qid=1615341940&sr=8-5).

![USB Cable-Cable AA ](/assets/img/USB-Kabel-AA.jpg)

## Install EZCast Pro Repair Tool

* Download [EZCast Pro Dongle II (B10) Repair Tool](https://download.stueber.de/doc/de/ezcastpro/repair_tools/EZCastPro.B10.Repair.Tool.zip).

* Extract the **EZCastPro.B10.Repair.Tool.zip** file.

![Extract EZCastPro.B10.Repair.Tool.zip](/assets/img/B10.Repair_Tool_Extract.png) 

* Install the driver by running the batch file `EZCastPro.B10.Repair.Tool\usb_driver\install.bat` as Administrator.

![Run install.bat as Administrator](/assets/img/B10.install.bat.png)

* When the following security message appears select **„Install“**:

![Select Install](/assets/img/EZCastPro_Upgrade_Tool_Driver.Install.png)

## Connect USB Type C cable

* Connect the included USB Type C cable to the USB port of the dongle. The dongle remains powered off at this stage.

* To put the EZCast Pro Dongle II in reinstall mode press and **hold** the reset button on the side of the dongle. Then connect the USB Type C cable to your Windows PC. After five seconds release the reset button.

![EZCast Pro Dongle II in reinstall mode](/assets/img/ProII-Press-Reset-Button.jpg)

If the driver is installed and the EZCast Pro Dongle II is properly connected, a **„Realtek generic USB Device“** driver will appear in Device Manager. If not, please check the driver installation, cable configuration and reinstall mode, as described in the previous step.

![EZCastPro driver in Device Manager](/assets/img/EZCastPro_Driver.png)

## Install Latest Firmware

* Launch the **EZCastUpdate.exe** file in the `EZCastPro.B10.Repair.Tool` directory.

![Launch EZCastUpdate.exe](/assets/img/B10.Repair_Tool_Update.exe.png)

The following window will appear. If the EZCast Pro Dongle II is in reinstall mode „EZCast device connected“ will display in the tool.

* Select `Download` in order to download the latest firmware.

![Select the Download button](/assets/img/EZCastUpdate.DeviceConnected.jpg)

The latest firmware will download from the internet.

!!! warning "Warning"

    You must not disconnect the power while the firmware is installing.

![EZCastPro Firmware is downloading](/assets/img/EZCastUpdate.Firmware.Downloading.jpg)

* To start the installation select `Upgrade`.

![Select Upgrade to start the installation](/assets/img/EZCastUpdate.Upgrade.jpg)

The firmware is installed.

![The firmware is installed](/assets/img/EZCastUpdate.Firmware.Updating.jpg)

If the installation has been succesfully installed the following message will appear:

![The installation was successful](/assets/img/EZCastUpdate_Upgrade.Success.jpg)

The EZCast Pro Dongle II is ready to use again.

## Install Specific Firmware {#B10_install_other_fw}

To install a previous or a beta firmware download one of the following files:

Firmware                       | Download
------------------------- | ------------
1.13781.18 | [Download](https://download.stueber.de/doc/de/ezcastpro/firmwares/B10/B10_1.13781.18.gz)
1.13781.17 | [Download](https://download.stueber.de/doc/de/ezcastpro/firmwares/B10/B10_1.13781.17.gz)
1.13781.15 | [Download](https://download.stueber.de/doc/de/ezcastpro/firmwares/B10/B10_1.13781.15.gz)
1.12170.19 | [Download](https://download.stueber.de/doc/de/ezcastpro/firmwares/B10/B10_1.12170.19.gz)
1.12170.16 | [Download](https://download.stueber.de/doc/de/ezcastpro/firmwares/B10/B10_1.12170.16.gz)
1.9871.37 | [Download](https://download.stueber.de/doc/de/ezcastpro/firmwares/B10/B10_1.9871.37.gz)


* Launch the **Update_for_localfile.exe** file in the `EZCastPro.B10.Repair.Tool` directory.

![Launch Update_for_localfile.exe](/assets/img/B10.localfile.exe.png)

The following window will appear. If the EZCast Pro Dongle II is correctly in reinstall mode **"Device connected"** will be displayed in the tool.

* Select the desired firmware using the `Firmware` button.

![Select Firmware](/assets/img/EZCastUpdate.SelectFirmware.png)

* To start the firmware installation select `Upgrade`.

![Select Upgrade to start the installation](/assets/img/EZCastUpdate.Upgrade.jpg)

The firmware installs.

![Firmware is installing](/assets/img/EZCastUpdate.Firmware.localfile.Updating.jpg)

After the installation has been succesfully installed the following message will appear:

![The installation was successful](/assets/img/EZCastUpdate_localfile.Upgrade.Success.jpg)

The EZCast Pro Dongle II is ready to use again.

## Recommended Settings after Device Reset {#recommendedsettings}

During a firmware reinstall all default factory settings are restored. After completion please review our [recommended settings](reset.md#recommendedsettings).

