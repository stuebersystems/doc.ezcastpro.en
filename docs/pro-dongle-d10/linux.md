# Linux

Although Linux is not officially supported by EZCast Pro there are two ways to mirror your screen using the Google Chrome Browser:

1. To simply mirror your screen use the [Cast](#linuxchromecast) function in the Google Chrome Browser:

![Cast Source](/assets/img/Linux.Chrome_select_stream2.png)

2.  The [EZCast Pro Chrome Extension](#LinuxInstallApp) offers both the Moderator and the other participants of the presentation, various advanced control options and mirroring functions that are otherwise not possible using the `Cast..` function in Chrome Browser:

![casting source](/assets/img/EZCastPro.Chrome.App.png)

This user guide will explain the above two methods using Google Chrome on Ubuntu 20.04. Chrome Browser can however be installed on many other distributions such as [Debian](https://www.debian.org/distrib/), [Kali](https://www.kali.org/) and [Linux Mint](https://linuxmint.com/).

## Enable Google Cast on EZCast Pro

By default Chrome Cast is enabled on EZCast Pro II devices. However, should you need to reactivate this feature the option `Chromecast` can be found in [Advanced Settings](adv.settings.md#Chromecast):

![](/assets/img/Chromecast-support.png)

## Install Google Chrome Browser

* Press the keyboard shortcut `CTRL` + `Alt` + `T` in order to open a terminal window.

* Update package information:

```
apt-get update
```

* Then execute the following two commands:

```
$ wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
$ sudo apt install ./google-chrome-stable_current_amd64.deb
```

## 1. Cast from Chrome Browser {#linuxchromecast}

* Find and launch Google Chrome:

![](/assets/img/Linux.Launch.Chrome.png)

* Select `Cast...` via the three-dot menu in the top left:

![Streamen..](/assets/img/Linux.Chrome_stream.png)

Select cast source you wish to use:

+ `Cast tab` - Casts only the current tab. This is the default option. 
+ `Cast desktop` - Casts the entire desktop
+ `Cast file` - Casts a selected video file. Offers best video playback performance.

![Casting source](/assets/img/Linux.Chrome_select_stream2.png)

To start casting simply click on the desired Google Cast receiver from the list.

![Start casting](/assets/img/Linux.Chrome_start_stream.png)

To stop casting click on the Google Cast receiver once again.

![Stop casting](/assets/img/end_stream.png)

Right click on the Cast icon to pin it to the menubar:

![Always show Cast icon](/assets/img/Linux.Chrome.Always_show_icon.png)

## 2. Advanced: EZCast Pro Chrome Extension

### Install Extension {#LinuxInstallApp}

Add the [EZCastPro Chrome Extension](https://chrome.google.com/webstore/detail/ezcastpro/kngnopamkonohfcjpdjjecalmbifepfl/related):

![EZCast Pro in the App Store](/assets/img/EZCastPro.Chrome.WebStore.Google.png)

### Connect App to EZCast Pro

If your EZCast Pro device is [set up](quickstart.md#Connect_ProStickII) correctly the following landing page will appear on the screen:

![Die Startseite](/assets/img/ProIIDongle_landingpage.png)

Proceed as follows:

1.  Connect your Linux device to the Wi-Fi SSID displayed at the top left of the screen as illustrated above. By default, the password is displayed.

2.  Find and start the `EZCastPro` app:

    ![](/assets/img/Linux.Launch.EZCastPro.png)

3.  Click on the `SEARCH DEVICES` button:

    ![Search EZCast Pro devices](/assets/img/chromeextension.searchdevices.png)

4.  Select your EZCast Pro device:

	![Select your EZCast Pro device](/assets/img/chrome-windows_device-list.png)

5.  To begin mirroring your screen select `Mirror On`:

    ![Start mirroring](/assets/img/chromeextension.mirror.png)

