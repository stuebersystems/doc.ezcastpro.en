# Was ist Captive Portal?

Ein Captive Portal präsentiert dem Benutzer eine Anmeldeseite, die sich nach der Erstverbindung mit dem WLAN automatisch öffnet. Er muss die Nutzungsbedingungen akzeptieren, bevor er auf das WLAN-Netzwerk der Schule bzw. des Unternehmens zugreifen darf. In manchen Fällen kann das Captive Portal einen Benutzernamen und ein Kennwort erfordern. Die Verwendung eines Captive Portals gibt einer Schule bzw. einem Hotel erhöhte Kontrolle über ihre Bandbreite und bietet gleichzeitig individuell anpassbare Grenzen dafür, wie lange Benutzer mit Ihrem Netzwerk verbunden bleiben können.

![Captive Portal im Einsatz in einer Schule](/assets/img/captiveportal.login.png)

## Kann der EZCast Pro sich in einem Captive Portal anmelden?

Da ein Captive Portal ein manuelles Eingeben der Zugangsdaten benötigt, kann EZCast Pro sich nicht in einem Captive Portal anmelden. Jedoch, es ist möglich EZCast Pro in Ihre Infrastruktur zu integrieren, in dem Sie eine `MAC-Authentifizierung` als eine Ausnahme auf Ihrem Router bzw. auf Ihrer Firewall erstellen, damit dieser Schritt entfällt.

Die MAC-Adresse des EZCast Pro Dongle II ist im Rubrik `Über` in den [Erweiterten Einstellungen](adv.settings.md) zu finden:

![MAC-Adresse im Rubrik Über](/assets/img/D10.About.MAC.jpg)

Eine MAC-Adresse ist die bessere Wahl als die Verwendung einer IP-Adresse, da sich die MAC-Adresse nicht ändert. Bitte wenden Sie sich an Ihre IT-Abteilung, um die MAC-Adresse des EZCast Pro Dongle II zuzulassen.

## Die Direkte Verbindung deaktivieren

Damit der EZCast Pro Dongle II den Nutzern keinen Zugang zu Ihrem Netzwerk ermöglicht, ohne sich erst über das Captive Portal anmelden zu müssen, stellen Sie die Verbindungsmöglichkeit des EZCast Pro Dongle II auf `Nur via Router` um.

![Verbindung - Nur via Router](/assets/img/Connection_EZCastProII.jpg)

Weitere Informationen bzgl. `Direkte Verbindung` und `Über Router` [finden Sie hier](adv.settings.md#Connection_to_Receiver).

Mit `Nur über Router` **(Nur via Router)** wird der Access-Point des EZCast Pro Dongle II  ausgeschaltet und Sie können nur über Ihren Router mit den Dongle verbinden. Die SSID und das Passwort werden ausgegraut und die vom Router vergebenen IP-Adresse bzw. die statische IP-Adresse des Dongles wird auf der Landing Page angezeigt (unten links), wie unten abgebildet:

![](/assets/img/ezcastpro.II.Nur.Ueber.Router.jpg)

!!! info ""

    Bei Miracast handelt es sich trotz der o.g. Einstellung immer um eine direkte Miracast-Verbindung (P2P), die als zusätzliche WLAN-Verbindung nur zur Übertragung des Bildschirms ausgebaut wird. Für die Internetinhalte verwendet das Endgerät die bisherige bzw. die zuletzt verbundene WLAN-Verbindung und dafür müsste der Nutzer sich über die Anmeldeseite angemeldet haben. Das Protokoll Miracast kann sogar auch deaktiviert werden, wenn gewünscht.