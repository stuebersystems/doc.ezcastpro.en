# Advanced Settings

The Advanced Settings allow you to update the firmware and adjust many settings of the EZCast Pro Dongle II conveniently and remotely. To access Advanced Settings, make sure you have installed the [software](quickstart.md#windows-and-macos) or [app](quickstart.md#android-and-ios) and connect to your EZCast Pro II device.

Launch the `EZCastPro` software or app on your device.

On Windows/macOS select `Advanced settings`:

![](/assets/img/ProII-Win-App-Advanced-Settings.png)

On iOS/Android select the Settings button at the top left then tap `Advance`.

![](/assets/img/iOS_adv-settings.png)

## Admin Login

Enter the admin password and click `OK` to log in. The default password is `000000`. If this password is not accepted please reset the device via the [reset switch](reset.md#hardreset).

![](/assets/img/EZCastII_Login.png)

When you first log in, you will be prompted to update the admin password. Then you will be asked to log in once more using your new password.

![](/assets/img/new_password.png)

## Main Menu Options

After logging in the following main menu options will appear:

+ [Connected Devices](#connecteddevices)
+ [Conference Control](#conferencecontrol)
+ [Device Management](#devicemanagement)
+ [Network Management](#networkmanagement)
+ [Admin Settings](#adminsettings)
+ [Reboot](#reboot)
+ [About Device](#aboutdevice)

### Connected Devices {#connecteddevices}

Shows the connected users and their assigned roles as either `Host` or `Guest`. For more information about Host and Guest, see [here](#the-roles-admin-host-and-guest).

![](/assets/img/link-status.png)

### Conference Control {#conferencecontrol}

You can use the Conference Control to perform the following tasks:

* Disconnect all devices
* Assign the role of Host(moderator) to a Guest
* Reposition devices on the screen

![](/assets/img/conferencecontrol.png)

A comprehensive guide on this topic can be found [here](#conferencecontrol).

### Device Management {#devicemanagement}

This section helps you change settings such as the [Language](#Language) of the settings menu system, the [Resolution](#Resolution) or specify the allowed [Maximum Connections](#MaxConnections).

#### Language {#Language}

Here you can select your prefered language for the menu system of advanced settings.

![](/assets/img/Select_language.png)

#### Device/SSID Name

Here you can change the SSID name which in turn changes the device name. For security reasons, the SSID can be hidden or disabled.

![](/assets/img/ezcastpro.II.devicename.png)

The EZCast Pro Box II has three network interfaces. When disabling the SSID (wlan1) the boxe will only be accessible via Router or Miracast (P2P).

| wlan | Description |
| :------------- |:-----:|
| wlan0 | Router / Access Point |
| wlan1 | softAP (Direct Connection) SSID/HotSpot |
| wlan2 | P2P, MiraCast |


#### Resolution {#resolution}

Here you can select the output resolution of the EZCast Pro II device. You can either select a specific resolution or simply select `Auto` and the Pro Dongle II will automatically set the optimal resolution for your screen.

| Standard | Resolution|
| :------------- |:-----:|
| HD | 1280 × 720 |
| Full-HD | 1920 × 1080 |
| 4K UHD | 3840 × 2160 |
| DCI 4K | 4096 × 2160 |

You can set the following resolutions:

![](/assets/img/ezcastpro.II.resolution.png)

#### Display Mode {#displaymode}

Here you can define whether EZCast Pro II should output the original aspect ratio of your enddevice or stretch it to fit the whole of your screen or projector display.

![](/assets/img/ezcastpro.II.displaymode.png)

##### Fit to Screen

The default setting `Fit to Screen` outputs the original aspect ratio of your enddevice to the display or projector:

![Das iPad wird im Original angezeigt](/assets/img/fit_to_enddevice_screen.png)

##### Stretch to Full Screen

With `Stretch to Full Screen` aspect ratio of your device is adjusted to fit the full screen of the display or projector:

![Das iPad wird im Vollbild angezeigt](/assets/img/stretch_to_full_screen.png)

#### AirPlay Mode {#AirPlayMode}

With AirPlay you can mirror your iOS/macOS screen without needing to install the app/software. This function is enabled by default. A comprehensive guide on how to use AirPlay can be found [here](airplay.md).

For video streaming there are three settings available:

* `Auto` - Automatic mode
* `Screen Mirroring Only` - Mirrors the screen and video contents
* `Screen Mirroring + Video Streaming` - Mirrors the screen. Online videos (e.g. YouTube) are streamed

![](/assets/img/ezcastpro.II.EZAir_Mode.png)

#### AirView {#AirView}

Users can view a picture output of the presentation with a refresh rate based on the specified preference. **The minimum refresh rate is 5 seconds.** A comprehensive guide to using AirView can be found [here](ezcastproapp.md#airview).

![](/assets/img/AirView.png)

#### EZNote {#EZNote}

Allows note-taking using the EZCast Pro app. 

![](/assets/img/EZNote.png)

#### Castcode {#Castcode}

Use a four digit Castcode to prevent unauthorized casting and ensure all participants present are in the same room:

* `OFF` - Castcode is disabled
* `Random` - Castcode is randomly generated when EZCast Pro starts up
* `Fixed` - Specify a fixed Castcode

The Castcode is displayed here:

![The Castcode](/assets/img/D10_Castcode.png)

#### Maximum Connections {#maxconnections}

This setting limits the number of direct connections the EZCast Pro II device will support via its own Wi-Fi hotspot. An additional 32 connections are supported via router. Please be aware that increasing the number of
connections may lower the network bandwidth for individual devices.

![](/assets/img/ezcastpro.II.max.connections.png)

#### Android Audio Streaming {#android-audio-streaming}

Enable Android users to cast video and audio to the external display. This setting is activated by default.

![](/assets/img/Android-Audio-Streaming.png)

#### ChromeCast {#Chromecast}

Direct casting via Chromecast for Android and Chrome browser. Please note that the EZCast Pro II device must be connected to the internet in order to cast via Chromecast. A comprehensive guide to using Chromecast can be found [here](chromecast.md).

![](/assets/img/Chromecast-support.png)

#### Miracast {#Miracast}

Direct casting via Miracast for Windows and Android devices with optional pin code security. A comprehensive guide to using Miracast can be found [here](miracast.md).

![](/assets/img/Miracast.png)

#### Legacy Mode (2.4 GHz WLAN) {#legacymode}

Activate Legacy Mode to support older devices and routers via the 2.4 GHz band instead of the default 5 GHz. By default, this setting is deactivated.

![](/assets/img/legacy.wifi.mode.png)

#### Timed Restart {#timedrestart}

To optimize the performance of the EZCast Pro device, especially for devices that are in continuous operation, turn the `Timed Restart` option **ON**. The EZCast Pro device will automatically restart when the following conditions apply:

* The EZCast Pro device has not been in operation for 8 hours. 
* No users have connected for at least 8 hours.
* The EZCast Pro settings web interface has not been accessed for 8 hours.

![Activate Timed Restart](/assets/img/timed.restart.png)

### Network Management {#networkmanagement}

In this section you can connect EZCast Pro to the internet. You can also customize TCP/IP and Wi-Fi channel settings.

#### Connect to 5GHz Wi-Fi {#internet}

Connect the EZCast Pro device to your Wi-Fi router in order to gain internet access.

**Please note:** EZCast Pro II can by default only be connect to a 5GHz Wi-Fi router. Use [Legacy mode](#legacymode) if you wish to switch to the 2.4 GHz Wi-Fi frequency.

![](/assets/img/EZCastPro.II.Wifi.png)

#### Remember Wi-Fi {#remember-wifi}

If you want EZCast Pro to automatically reconnect to your Wi-Fi router then this option must be enabled.  

![](/assets/img/ezcastpro.II.remember.password.png)

#### Wi-Fi IP Settings {#wifi-ip-settings}

Assign a static IP address to the EZCast Pro device or set automatic IP addressing (DHCP).

![](/assets/img/static-IP.png)

#### Wi-Fi Password (change/hide) {#wifipassword}

Set a custom password for EZCast Pro's Wi-Fi and choose whether to hide the password for security reasons.

![](/assets/img/ezcastpro.II.password.png)

#### Wi-Fi Channel {#wifi-channel}

To manually optimize your EZCast Pro's Wi-Fi set a static channel. The default setting is `Auto`. Please note: It is not possible to change Wi-Fi channel settings while still connected to external internet.

![](/assets/img/ezcastpro.II.wifi.channel.png)

### Admin Settings {#adminsettings}

In this section you can customize settings which require the highest permission such as updating firmware, reset to factory default and many other advanced settings.

#### Admin Password {#adminpassword}

Change the Admin enhanced security.

![](/assets/img/new_password.png)

#### Wi-Fi Enterprise {#wifienterprise}

For higher level access authorization upload digital certificates.

![](/assets/img/ezcastpro.II.digital_certificate.png)

#### Host Authority {#hostauthority}

Select what functions the host is allowed to access in the Advanced Settings menu without requiring an `Admin` to log in.

![Host  Authortiy](/assets/img/Host_permissions.png)

For example, if you don't want the host to be allowed access to the `Settings` button within the software or app, you can set the `Device Management` option to `Off`.

![Host Settings can be hidden by deactivating Device Management in Host Authority](/assets/img/ezcastpro.II.software.no-hostsettings.png)

![When the Device Management function is switched off, the Host Settings button is hidden](/assets/img/ezcastpro.II.software.hostsettings.hidden.png)

With the above configuration (Device Management Control and Network Management Control disabled), only the 'Conference Control' and 'Reboot' functions are displayed to the Host in the main manu. Please note: The `Connected devices` and `About Device` functions are always available.

![Device Management and Network Management hidden](/assets/img/ezcastpro.II.Host_authority_example.png)

#### Host Control

The first user to connect to EZCast Pro via the software or app is assigned the moderator (Host) role and the others are guests. By default, each request to send must be approved by the Host by responding with either `FullScreen`, `Share`, or `Deny`: 

![](/assets/img/host.control_answer.png)

**Auto Allow Requests**

If `Auto Allow Requests` is set to `OFF` any request to cast is automatically approved.

**Share Screen**

By default, this function is enabled meaning the screen is divided to display up to four devices at the same time, also known as split screen mode. When `Share Screen` is off, the next approved enddevice takes over in full screen mode.

![](/assets/img/host.control.png)

A status of Host Control settings is display at the bottom of the Landing Page:

![](/assets/img/host.control_status.png)

#### Internet Access Control {#internetaccesscontrol}

Define whether or connected enddevices are allowed to access the internet when connect to the EZCast Pro II receiver. By default, all devices are allowed:

![](/assets/img/internet_access.png)

#### SNMP {#SNMP}

The netowrk administrator can integrate EZCast Pro II device into the existing SNMP monitoring tool. Please be advised that EZCast Pro II supports SNMP v3 protocol.

![](/assets/img/SNMP_support.png)

#### My Screen {#myscreen}

If desired, you can change the landing page image. This is a permanent change. After importing a new image, the previous image cannot be restored even after performing a [reset](reset.md) of the box. **Please note, the image format must be PNG with 1920x1080 resolution and smaller than 2MB.** 

A download of the landing page we provide can be found [here](https://download.stueber.de/doc/en/ezcastpro/EZCastPro2_landingpage.png).

![](/assets/img/My_Screen.png)

#### OTA Update URL {#ota-server}

Specify an alternative server to perform over-the-air firmware updates from. Please be advised that the function is specifically designed for distributors, resellers, and users having trouble upgrading firmware via internet. For end users, you can upgrade EZCast Pro Box via the [Upgrade](#upgrade-firmware) function.

![](/assets/img/OTA_server.jpg)

#### Connection (interfaces) {#Connection_to_Receiver}

There are two ways to connect to the receiver. When setting up the box for the first time, the **Direct Connection** is available by default.

*   **Direct Connection**

    Connect your enddevice (Windows/Android/Apple/etc.) to the EZCast Pro receiver's hotspot using the SSID displayed on the screen. Content from the internet will be delivered to your end device via the receiver's [internet access](internet.md) function in the second step, if enabled by the administrator. This basically provides the best bandwidth between your device and the EZCast Pro receiver if the distance from the network access point is very long. This option requires the user to switch from the previous network to another network i.e. the receiver's SSID.


    ![The SSID and password of EZCast Pro's hotspot are displayed at the top](/assets/img/ezcastpro.II.Direkte_Verbindung_zugangsdaten.png)

    ![In the EZCast Pro software an available EZCast Pro device via direct Wi-Fi connection is indicated by a dongle icon on the right side](/assets/img/ezcastpro.II.App.direct_connection.png)

*   **Via Router**

    The EZCast Pro receiver has been connected to your router in advance by the administrator via the [Internet Access](internet.md) function of the receiver. Content from the internet is delivered to your device from your network infrastructure in the first step. In the second step, you connect your enddevice (Windows/Android/Apple/etc.) to the EZCast Pro receiver. With this option, the user does not need to switch to any other network.

    ![In the EZCast Pro software an available EZCast Pro device Via Router is indicated by a dongle icon on the right side](/assets/img/ezcastpro.II.App.connect.via.Router.png)

By default, both connection interfaces are enabled via the `Both` option. However, you have the choice to disable one of the interfaces:

![](/assets/img/Connection_EZCastProII.png)

With the first two options `Both` and `Direct Link Only` the SSID and password are displayed on the landing page, as shown below:

![](/assets/img/ProIIDongle_landingpage.png)

With `Via Router Only` the hotspot is deactivated and you can only connect to the EZCast Pro II device via your router. The SSID and password are greyed out and the infrustructure IP address is displayed at the bottom of the landing page, as shown below:

![](/assets/img/ezcastpro.II.via.Router.only.png)

!!! warning "Warning"

    Please note that by not enabling `Both`  setting means that connections via the other interface are no longer possible. If for example you enable `Direct Link Only` as well as [Hide SSID](#devicessid-name) or [Hide Password](#wifipassword) then you must not forget your access credentials, otherwise it will be necessary to perform a [reset](reset.md#reset-per-reset-switch) of the EZCast Pro device via its reset switch!
	

#### Fixed Host

Set a specific user who should always be selected as the host of the presentation within the software or app. A comprehensive guide to using Fixed Host can be found [here](fixedhost.md).

![](/assets/img/ProIIDongle_Fixedhost.Select.png)

#### Upgrade Firmware

Update the firmware of your EZCast Pro device  to take advantage of the latest enhancements and features. A comprehensive guide to upgrading the firmware can be found [here](#upgrade-firmware.md).

![](/assets/img/Upgradefirmware.png)

#### Central Management System

Activate this option to manage the EZCast Pro device via the Central Management System (CMS). More information on this topic can be found [here](cms.md).

![](/assets/img/cms.png)

#### Reset to Factory Defaults {#reset}

Use this option to reset the EZCast Pro device to factory settings. More information on this topic can be found [here](reset.md).

![](/assets/img/Reset.png)

### Reboot {#restart}

Use this option to restart your EZCast Pro device.

![](/assets/img/restart.png)

### About Device {#aboutdevice}

Use this option to get an overview of your EZCast Pro device e.g. firmware version, IP address as well as Wi-Fi related information.

![](/assets/img/D10.about_device.png)