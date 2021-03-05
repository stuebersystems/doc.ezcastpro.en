# Why do you need the app/software?

The use of the free app/software **EZCastPro** offers both the presenter and the other participants of a presentation, various advanced control options and mirroring functions that are otherwise not possible with your device's built-in mirroring function.

## Requirement

You will need to install the EZCastPro app/software. A comprehensive guide on how to download and install the app/software for your device can be found [here](quickstart.md).

When your end device is connected to the EZCast Pro Dongle II via the EZCastPro app/software, the application will appear as follows:

![The EZCast Pro Software for Windows](/assets/img/ProII-Win-App.png)

## Mirror | Extend | Disconnect | Pause

With the buttons at the top of the menu bar you can either `Mirror` or `Expand` your Windows/macOS device screen, during the presentation you can also `Pause` or even `Disconnect` transmission.

![](/assets/img/App-Funktion1.png)

## The roles: Admin, Host and Guest

There are three authorization levels. The **Admin** role manages the devices. The roles of **Host** and **Guest** differ in the functions that they offer. 

### Admin

The Admin manages devices and has access to all advanced settings and features that the Host does not have access to, such as firmware updates.

### Host

In EZCast Pro the moderator is called the "Host" and decides how and when other participants can mirror their screens during a presentation. By default, the first person to log into the EZCast Pro app/software is assigned the Host role and the other participants are Guests. If desired, the Admin can assign a user the Host role permanently. This is called [Fixed Host](fixedhost.md). 

### Guest

A participant who is logged in as a Guest has limited capabilities and cannot access certain features (e.g. Conference Control) of the software. In the EZCast Pro software for Windows and macOS, the role of Host is displayed in the top right corner, as shown below:

![](/assets/img/AppRolle-Host.png)

In the app for iOS/Android you can view the role status by clicking on `Settings` on the top left:

![Settings top left](/assets/img/App-IosAndroidHost.png)

## Privacy

Despite the name, there are not only settings related to the collection of your personal, location and usage data, but also advanced settings that affect several features of the application.

![](/assets/img/AppDatenschutz.png)

### Enter a Username

When you access the app for the first time, we recommend you enter your name in the software. Despite the label "Hostname" it is actually an identifier for Guests as well as the Host. It makes it easier to recognize which participant wants to mirror their screen:

![](/assets/img/AppHostName.jpg)

### Preferred Device

This option allows you to set the current device as your preferred device. When you start the EZCast Pro app/software it will attempt to reconnect to your preferred device first without having to manually select the it again.

![](/assets/img/App-PreferredDevice.png)

### Conference Control (Settings)

A Guest can allow the Host to mirror their screen on demand. If the `Allow remote mirror` setting is enabled, it allows the Host to transfer a guest's screen without requiring the Guest to manually click on "Mirror" in order to send a request to the Host. This option is currently only supported on Windows and macOS. 

![](/assets/img/App-AllowRemoteMirror.png)

### Host Control (Settings)

Here you will find the `Do not disturb` and `Auto allow request` settings of the Host Control function. A comprehensive guide to using Host Control can be found [here](#host-control).

![](/assets/img/App-DataProtection-HostControl.png)

### Analytics

You have the option to enable or disable collection of your personal, location and usage data.

![](/assets/img/App-Analytik.png)

## Host Control

By default the first user to connect via the software or app is assigned the moderator (Host) role and all proceeding participants are Guests. Each screen mirroring request must be approved by the Host by responding with either `FullScreen`, `Share`, or `Deny`: 

![](/assets/img/AppHostKontrolle.png)

There are two additional controls available to the Host:

**Do not disturb**

When `Do not disturb` is activated the Host will not accept any requests from Guests to mirror their screen. If the Host wishes to let Guest participants mirror their screen at certain points of the presentation they can either release the `Do not disturb` function or [Conference Control](#conference-control) to manually mirror the selected participant's screen.

**Auto allow request**

When the Host activates `Auto allow request` the Guests do not require approval from the Host to mirror their screen.

![](/assets/img/App-DataProtection-HostControl.png)

The above mentioned settings can be found in the [Privacy](#privacy) section.

Further settings for host control, which you can set permanently in the firmware configuration, can be found in the Host Control section [Advanced Settings](adv.settings.md#host-control).

## Split Screen

The **Split Screen** feature is a simple Moderator control for the Host with the following options: 

* Show the Host's device mirror in Full Screen (disconnect all other Guests)

* Move the Host's device mirror to a new position on the display.

* End screen mirroring of all participants and return to the Landing Page.

![](/assets/img/Split.Screen.png)

The **Split Screen** function is located on the left panel of the app/software. 

![](/assets/img/Bildschirmaufteilen1.png)

The EZCast Pro device can mirror the screens of up to four partipants to the display at once.

!!! tip "Tip"

    The **Split Screen** feature cannot reposition or stop mirroring individual Guest screens. For a more advanced moderator view we recommend you use [Conference Control](#conference-control) found under Advanced Settings.

## Conference Control

Conference Controlis a way for the Host to have full control of the entire flow of the presentation. The host can choose exactly how and when other participants mirror their screens during a presentation. Buttons to 'repositioning', 'Show Full Screen', or even 'Disconnect' can be found on the right side column.

![](/assets/img/conferencecontrol.png)

The Host cam even reassign the Host role to another participant.

![](/assets/img/conferencecontrol2.png)

![](/assets/img/conferencecontrol3.png)

How can I open `Conference Control`?

The Conference Control function is located in **Advanced Settings** section. 

![](/assets/img/adv.settingsapp.png)

![](/assets/img/conferencecontrol6.png)

!!! tip "Tip"

    In order to be able to access Conference Control the `Admin` must grant the Host permission in the Host Authority section of Advanced Settings. Click [here](adv.settings.md#Host-Authority) for further information.
								
## Update

![](/assets/img/update.png)

The `Update` button allows you to update the EZCastPro app/software to the latest version.

## Video Quality and Audio

Mit diesen Schaltflächen sind Sie in der Lage, die Qualität einer Videoübertragung zu kontrollieren und das Ton ein- oder auszuschalten.

![](/assets/img/App-Funktion2.png)

## Musik (stream)

The EZCastPro app/software also allows you to wirelessly stream music. Create playlists to stream a variety of music via Wi-Fi.

![Music stream](/assets/img/playlistapp.png)

![Music stream](/assets/img/App-Musiccasting.png)

## Video (stream)

If it's important to ensure smooth playback of a video, use the video function. Unlike the standard mirroring function, this will stream the video, which means that the video is only shown on the large display instead of being played on your end device at the same time.
As soon as you select the video file on your end device or from your network, a small "buffer" will be generated. Depending on the end device and network performance, this can take a few seconds before playback begins.

![Control video playback using the app's control bar](/assets/img/videoapp.png)

Besides, you can sync subtitle files with videos, just make sure that the file name and the video name are the same. It will be displayed automatically during playback.

!!! tip "Tip"

    All major video formats are supported. For subtitles please use formats srt, smi, ssa and cdg with UTF-8 encoding.

## AirView

With AirView, you have the option to view an image output of the presentation on your end device. By default AirView is enabled on EZCast Pro II devices. However, should you need to reactivate it the feature `AirView` can be found in [Advanced Settings](adv.settings.md#AirView) of the firmware.

![One enddevice to a Public Display and multiple enddevices](/assets/img/airviewapp.png)

You will find the AirView button at the top right of the EZCast Pro software for Windows and macOS and in the list of functions in the app for Android and iOS:

![](/assets/img/airViewapp2.png)

Use the buttons in the upper right corner to start the image output. By default, an image of the presentation is taken every 5 seconds, which you can optionally download.

![](/assets/img/airviewapp3.jpg)

Here you can see the image output from one participant in full screen:

![](/assets/img/airviewapp4.png)

Here you can see the image output of two participants in split screen:

![](/assets/img/airviewapp5.png)

!!! warning "Warning"

    AirView does not support video or audio streams. It is a picture output of the presentation updated at a regular given time interval i.e. every 5 secs.

## Camera

With the camera function for mobile devices, you have the option of streaming your camera live to the projector or large screen. For example, would you like to show your students a close-up of the experimental apparatus during a science lesson without them having to leave their desks?

![Camera function in EZCast Pro app](/assets/img/App-Camera.png)

When you start the camera function, your camera will immediately start streaming. You can also save and sketch on a photo of the stream:

![Live stream and still photo sketch](/assets/img/App-Camera_functions.png)

The teacher is streaming a live her camera to the projector on the left. On the right is a slideshow of the teaching material. Both displayed simultaneously in split screen:

![Live stream and slideshow split screen](/assets/img/App-Camera_splitscreen.png)

## Advanced Settings 

Advanced Settings allows you to update the firmware and adjust many settings of EZCast Pro Dongle II conveniently remotely. More information about this topic can be found [here](adv.settings.md).

![](/assets/img/advsettingsapp.png)
