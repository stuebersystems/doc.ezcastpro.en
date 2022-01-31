# Why reset your EZCast Pro device?

There are a few reasons you may wish to reset your EZCast Pro Dongle II to default settings:

* You have forgotten the Admin password for the [Advanced Settings](adv.settings.md).

* The dongle is no longer accessible since making changes to your network infrastructure, IP settings or to the SSID credentials of the dongle.

* The dongle is experiencing other performance difficulties.

All settings will be reset except the [Device/SSID Name](adv.settings.md#devicessid-name), the [customized landing page](adv.settings.md#myscreen) image and the firmware version.

## Soft Reset via App/Software {#softreset}

To reset the EZCast Pro Dongle II open the `EZCastPro` app or software on your enddevice. See our compehensive guide to installing the software for [Windows and macOS](quickstart.md#InstallSoftware) or the app for [Android and iOS](quickstart.md#InstallApp) should you need to install it.

Open `Advanced Settings` on your device. For Windows/macOS users it is located at the bottom of the left panel:

![](/assets/img/ProII-Win-App-Advanced-Settings.png)

On iOS/Android select the `Settings` button at the top left then tap `Advance`.

![](/assets/img/iOS_adv-settings.png)


### Log In as Admin

* Enter the Admin password and click `OK` to log in. The default password is `000000`. If this password is not accepted please reset the device via the [reset switch](reset.md#hardreset).

![](/assets/img/EZCastII_Login.png)

* Select `Admin Settings` from the main menu:

![](/assets/img/ezcastpro.II.select.adminsettings.png)

### Reset to Factory Default

* Select the `Reset to Factory Default` option.

![](/assets/img/ezcastpro.II.resetfactorydefaults.png)

* To confirm click `Yes`.

![](/assets/img/Reset.png)

## Hard Reset via Reset-Switch {#hardreset}

If you do not know the Admin password, you must perform a hard-reset using the reset switch found on the dongle:

* With the power supply connected, press and hold the reset switch for about 10 seconds using a pin or paper clip. The reset switch is located on the side of the dongle next to the USB port.

![Press and hold the reset switch for approx. 10 seconds](/assets/img/ProII-Press-Reset-Button.jpg)

* When the following message appears release the reset switch.

![](/assets/img/Reset_config_complete.png)

*  After the reset when you first log must select a Wi-Fi country and restart:

   ![](/assets/img/wifi.land.selection.png)
   
## Recommended Settings after Device Reset {#recommendedsettings}

The first time you log in after resetting the device you will be asked to change the Admin password. The default password is `000000`. For optimal device performance we then recommend the following device settings:

Firmware Version: [1.13781.17](whatsnew.md#ezcast-pro-dongle-ii-firmware-11378117)

**Device Management**

* [Language](adv.settings.md#Language): `English`
* [Android audio streaming](adv.settings.md#android-audio-streaming): `ON`
* [AirView](adv.settings.md#AirView): `ON`
* [Castcode](adv.settings.md#Castcode): `Random`
* [Timed Restart](adv.settings.md#timedrestart): `ON`

**Network Management**

* [Wi-Fi Mode](adv.settings.md#wifi-channel): `Country = Europe`, `Channel = Auto`, `Bandwidth = 20MHz`

**Admin Settings**

* [Host's Authority](adv.settings.md#hostauthority):
    * `Conference Control = ON`
    * `Network Management Control = OFF`
    * `Device Management Control = OFF`
    * `Reboot Control = ON`
* [My Screen](adv.settings.md#myscreen): Our recommended [Landing Page](https://download.stueber.de/doc/en/ezcastpro/EZCastPro2_landingpage.png) in English language
* [Central Management System](adv.settings.md#central-management-system) = `ON`



