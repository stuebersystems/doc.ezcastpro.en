# Castcode Security

The Castcode provides additional security against unauthorized screen mirroring by requiring each Guest to enter a four-digit code to be allowed to cast content. This allows you to ensure that only participants in the same room can mirror to the large screen. The following settings are available:

* `OFF` - No Castcode is required.
* `Random` - Random (updates automatically on power up or reboot).
* `Fixed` - Specify a fixed castcode.

The castcode is displayed at the top center of the start page:

![The castcode](/assets/img/B10_Castcode.png)

When the enddevice correctly enters the castcode, screen mirroring is authorized to start:

![The castcode](/assets/img/Enddevice_MiracastPin.png)

## What streaming protocols does castcode support?

Castcode is supported using the following applications and protocols:

* EZCast Pro software for Windows and macOS.
* EZCast Pro app for Android and iOS
* AirPlay on iOS and macOS

## What streaming protocols does castcode not support?

Due to a limitation in the protocol technology, castcode cannot be supported under the following streaming protocols. You can however still protect against unauthorized screen casting:

* Google Cast
* Miracast

### Google Cast

Currently there is no castcode functionality within the Chromecast protocol. However, you do have the ability to use the Host Control feature of the EZCast Pro app/software to protect against unauthorized screen mirroring. When a Chromecast device attempts to cast, the cast request must be approved by the moderator (Host):

![Host Control](/assets/img/AppHostControl.png).

A comprehensive user guide on Host Control can be found [here](ezcastproapp.md#host-control).

### Miracast

The Miracast protocol does not support a four-digit cast code, it uses an eight-digit pin code. You can enable this feature in [Advanced Settings](adv.settings.md#Miracast):

![Host Control](/assets/img/Miracast.png)

When a Miracast device sends EZCast Pro a cast request, the eight-digit pin code appears in yellow at the top of the landing page. This pin must be entered on the enddevice before screen mirroring is allowed to begin.

![Host Control](/assets/img/ProIIDongle_MiracastPin.png)

## How to Enable Castcode

Enable the Castcode feature in Advanced Settings in the `EZCastPro` software for [Windows and macOS](quickstart.md#InstallSoftware) or in the app for [Android and iOS](quickstart.md#InstallApp).

### Open advanced settings

* Open the software `EZCastPro` on your device and select the Pro Dongle II from the device list.

* On Windows/macOS select `Advanced Settings`.

![](/assets/img/Win-App-Advanced-Settings.png)

* On iOS/Android, select the `Settings` button on the top left, then tap `Advanced`:

![](/assets/img/iOS_adv-settings.png)

### Log in as Admin

* Enter the admin password and click `OK` to log in. By default, the password is `000000`. If this password is not accepted reset the device via the [reset-switch](reset.md#reset-per-reset-switch).

![](/assets/img/EZCastII_Login.png)

* During first login, you will need to change the admin password. Then you will have to log in once more with the new password.

![](/assets/img/new_password.png)

### Enble Castcode

* Select 'Device Management' from the menu:

![](/assets/img/ezcastpro.II.select.devicemanagement.png)

* Select the menu item `Castcode Control`:

![](/assets/img/ezcastpro.II.devicemanagement.castcode.png)

* Select the desired setting:

![](/assets/img/ezcastpro.II.select.castcode.png)

* You must now restart the Pro Box II in order to activate Castcode. In the menu select 'Restart'.

![](/assets/img/prostickII_menu.restart.png)

* Then select the button 'Restart' again.

![](/assets/img/restart.jpg)



Translated with www.DeepL.com/Translator (free version)