# What is Captive Portal?

A captive portal presents the user with a login page that automatically opens after the initial connection to Wi-Fi networks found in certain public places like hotels, airports or even schools. You must then accept the terms of use before being granted access. In some cases, the captive portal may require a username and password. Using a captive portal gives a school or hotel increased control over its bandwidth while providing customizable limits on how long users can stay connected to your network.

![Captive Portal in use at a school](/assets/img/captiveportal.login.png)

## Can EZCast Pro Log Into a Captive Portal?

Since a captive portal requires manual entry of credentials, EZCast Pro cannot log into a captive portal. However, it is possible to integrate EZCast Pro into your infrastructure by creating a `MAC authentication` as an exception on your router or firewall to eliminate this step.

The MAC address of your EZCast Pro II device can be found in the `About Device` section of the [Advanced Settings](adv.settings.md):

![MAC address in About Device](/assets/img/D10.About.MAC.jpg)

A MAC address is a better choice than using an IP address because the MAC address does not change. Please contact your IT department to allow the MAC address of the EZCast Pro device.

## Deactivate Direct Connections

After enabling EZCast Pro on your infrustructure without Captive Portal there is a possible security vulnerability that you can easily overcome in order to prevent users being able to access your network without logging in through the Captive Portal first. Disable the hotspot interface of your EZCast Pro device by setting EZCast Pro's available interfaces to `Via Router Only`. See our [Advanced Settings](adv.settings.md#Connection_to_Receiver) guide for more information on Connection configuration:

![Connection - Via Router Only](/assets/img/ezcastpro.II.via.Router.only.settings.png)

With `Via Router Only` the hotspot (SSID) of your EZCast Pro device is deactivated and it will only be possible to connect to it via your router. The SSID and password are greyed out and the infrustructure IP address is displayed at the bottom of the landing page, as shown below:

![](/assets/img/ezcastpro.II.via.Router.only.png)

!!! info "Info"

    Despite the above `Via Router Only` setting Miracast devices will still be mirrored to EZCast Pro using the P2P standard while remaining simultaneously connected to the same Wi-Fi network as before for access to internet content. The user will therefore still have to log into the Captive Portal if this is a requirement of your network.