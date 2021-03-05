# Einstellungen zurücksetzen

Es gibt mehrere Gründe für einen Zurücksetzen (Reset) des EZCast Pro Dongle II auf seine Werkseinstellungen:

* Sie haben das Admin-Kennwort für die [Erweiterte Einstellungen](adv.settings.md) vergessen.

* Sie haben Änderungen in Ihrer Netzwerkinfrastruktur, den IP-Einstellungen oder den SSID-Zugangsdaten des Dongles vorgenommen und Ihr Dongle ist nicht mehr erreichbar.

* Sie haben Probleme eine ungewollte Änderung auf dem Dongle rückgängig zu machen.

Bei einem Zurücksetzen werden alle Einstellungen zurückgesetzt, außer die [WLAN-SSID](adv.settings.md#Geraetename), das [Hintergrundbild](adv.settings.md#Mein-Bildschirm) der  Landing Page und die Firmware-Version.

## Zurücksetzen per App bzw. Software

Mit Hilfe der `Erweiterte Einstellungen` können Sie sich anmelden und die Standardeinstellungen zurücksetzen. Um die `Erweiterte Einstellungen` zu erreichen, stellen Sie sicher, dass Sie die [App](quickstart.md#InstallApp) installiert haben und dass Sie mit Ihrem EZCast Pro Dongle II [verbunden](quickstart.md#app-mit-ezcast-pro-ii-dongle-verbinden) sind.

* Rufen Sie die App bzw. die Software `EZCastPro` auf Ihrem Gerät auf und wählen Sie den Pro Dongle II aus der Geräteliste aus.

* Auf Windows/macOS wählen Sie `Erweiterte Einstellungen`.

![](/assets/img/Win-App-Advanced-Settings.png)

* Auf iOS/Android wählen Sie die Schaltfläche `Settings` oben links.

![](/assets/img/iOS_settings.png)

* Auf iOS/Android wählen Sie anschließend `Advanced Settings` bzw. `Erweiterte Einstellungen`.

![](/assets/img/iOS_adv-settings.png)

### Anmeldung

* Geben Sie das Admin-Kennwort ein und klicken Sie auf `OK`, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#zurücksetzen-per-reset-schalter) zurück.

![](/assets/img/EZCastII_Login.png)

* Aus dem Menü oben links wählen Sie `Admin-Einstellungen`.

![](/assets/img/ezcastpro.II.select.admineinstellungen.png)

* Wählen den Punkt `Auf Standardeinstellungen zurücksetzen` aus.

![](/assets/img/ezcastpro.II.Standardeinstellungen.zuruecksetzen.png)

* Zum Bestätigen wählen Sie `Ja`.

![](/assets/img/Reset.png)

## Zurücksetzen per Reset-Schalter 

Wenn Ihnen die Zugangsdaten für die [Erweiterte Einstellungen](adv.settings.md) nicht bekannt sind, haben Sie die Möglichkeit mit dem Reset-Schalter die Standardeinstellungen zurückzusetzen:

* Wenn die Stromversorgung angeschlossen ist, halten Sie den Reset-Schalter ca. 10 Sekunden lang gedrückt. Der Reset-Schalter befindet sich an der Seite des Dongles neben dem USB-Anschluss.

![Reset-Schalter ca. 10 Sekunden lang gedrückt halten](/assets/img/ProII-Press-Reset-Button.jpg)

* Wenn die folgende Meldung erscheint, lassen Sie den Reset-Schalter los.

![](/assets/img/Reset_config_complete.jpg)

## Einstellungen nach dem Zurücksetzen {#recommendedsettings}

Nach dem Zurücksetzen werden Sie bei der ersten Anmeldung auf der Funktion [Erweiterte Einstellungen](adv.settings.md) aufgefordert, das Admin-Kennwort zu ändern. Standardmäßig lautet es `000000`. Wir empfehlen, dass Sie anschließend die folgenden Einstellungen überprüfen:

Firmware-Version: 1.8617.21

**Gerätemanagement**

* [Sprache](adv.settings.md#Sprache): `DEUTSCH`
* [Android Audioübertragung](adv.settings.md#Android-Audio-Streaming): `EIN`
* [AirView](adv.settings.md#AirView): `EIN`
* [Timed Restart](adv.settings.md#timedrestart): `EIN`

**Netzwerkmanagement**

* [WLAN-Modus](adv.settings.md#Wifi-Channel): `Land = EUROPE`, `Kanal = Auto`, `Bandbreite = 20MHz`

**Admineinstellungen**

* [Mein Bildschirm](adv.settings.md#Mein-Bildschirm): unsere [Landing Page](https://download.stueber.de/doc/de/ezcastpro/EZCastProV2_Landing PageDE.png) in der deutschen Sprache
* [Host-Berechtigungen](adv.settings.md#Host-permissions):
    * `Konferenzsteuerung = Ein`
    * `Netzwerkmanagement = Aus`
    * `Gerätemanagement = Aus`
    * `Neustart = Ein`



