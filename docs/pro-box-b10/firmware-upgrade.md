# Upgrade Firmware

## Why Update the Firmware? 

To benefit from the latest features of EZCast Pro Box II, you can quickly and conveniently install the latest firmware update via the Internet. When upgrading the firmware the previous settings are retained. To do this, the EZCast Pro device must have access to the internet which is indicated by a Wi-Fi or LAN icon at the top right of the landing page and an `Infrustructure IP` address on the bottom left, as shown below:

![](/assets/img/ProII_fw.upgrade.available.png)

If your EZCast Pro device is not connected to the internet [click here](internet.md) and follow the user guide.

## Upgrade Firmware via EZCast Pro Software

### Open Advanced Settings

To update the firmware you will need to open `Advanced Settings`. In this example, we show you how to access Advanced Settings via the EZCast Pro software:

* Install the EZCast Pro [Software](quickstart.md#InstallSoftware) and connect to your EZCast Pro Box II.

* Launch the `EZCastPro` software on your device.

* Select `Advanced Settings` at the bottom left.

    ![](/assets/img/ProII-Win-App-Advanced-Settings.png)

### Log In as Admin

* Enter the Admin password and click `OK` to log in. The default password is `000000`. If this password is not accepted please reset the device via the [reset switch](reset.md#hardreset).

	![](/assets/img/EZCastII_Login.png)

### Begin Firmware Upgrade

* Select `Admin Settings` from the main menu:

![](/assets/img/ezcastpro.II.select.adminsettings.png)

*   If a new firmware version is available, it is indicated with `New version available!` next to the menu item `Upgrade`. To continue, select this button:

    ![](/assets/img/ProII_Firmware-Menuoption.png)

*   The new firmware version is displayed in the `Server Version` field. To continue, click on `Upgrade`.

    ![](/assets/img/ProIIStick_Start.Upgrade.png)

The new firmware is downloaded and installed automatically. 

!!! warning "Warning"
    
	Do not interrupt the power supply during the update.

![](/assets/img/ProII_Firmware_installing.png)

The EZCast Pro device restarts automatically and returns to the landing page. The updated firmware version is displayed on the bottom right:

![](/assets/img/ProIIDongle_firmware.png)

## Update Firmware via internet with CMS

The CMS ([Central Management System](cms.md)) allows you to install the latest firmware either via the Internet or a local download of the firmware on multiple EZCast Pro II or QuattroPod devices.

* When a new firmware is available for the receiver or the transmitter a ![](/assets/img/CMS-firmware.available.png) icon will appear next to the device:

![](/assets/img/CMS-firmware.OTA.select.devices.png)

* Select the desired devices, then click on the `Remote` button -> and select the option `Device firmware upgrade`.

![Die Firmware wird installiert](/assets/img/CMS-firmware.install.latest.firmware.png)

* Under the `OTA` tab, simply click on the `Apply` button to perform the update:

![Die Firmware wird installiert](/assets/img/CMS-firmware.upgrade.OTA.png)

The new firmware is downloaded and installed automatically. 

* While the receiver is being updated the following message will appear:

![Firmware-Version aktualisieren](/assets/img/ProIIStick_Firmware_installing.png)

!!! warning "Warning"
    
	Do not interrupt the power supply during the update.

## Update Firmware without internet with CMS

The CMS ([Central Management System](cms.md)) also allows you to install the latest firmware on devices that are not connected to the internet. Please use the links below to download the firmware for your devices in advance:

Device Type               | Download      |
------------------------- | ------------------------- | 
Pro Dongle II | [Download](../pro-dongle-d10/firmware-reinstall.md#D10_install_other_fw)
Pro Box II | [Download](firmware-reinstall.md#B10_install_other_fw)

* Select the desired devices, then click on the `Remote` button -> and select the option `Device firmware upgrade`.

![](/assets/img/CMS-firmware.install.latest.firmware.png)

* Under the `FILE` tab, browse to the firmware file you downloaded earlier:

![](/assets/img/CMS-firmware.upgrade2.png)

* When ready, click on the `Apply` button to perform the update:

![](/assets/img/CMS-firmware.upgrade.FILE.apply.png)

* While the receiver is being updated the following message will appear:

![](/assets/img/ProIIStick_Firmware_installing.png)

!!! warning "Warning"
    
	Do not interrupt the power supply during the update.
	
## Recommended Settings After Firmware Update {#recommendedsettings}

After updating the firmware please review all available Advanced Settings. See recommended settings [here](reset.md#recommendedsettings).

!!! tip "Tip"
    
	If you are viewing Advanced Settings in a web browser instead of the EZCast Pro app please clear your browser cache after upgrading firmware in order to see all newly available options.
	