Deutsch | [English](https://github.com/BachErik/WinDoofOS)

## WinDoofOS Beta-Releases!

Hallo, WinDoofOS basierend auf [MineOS](https://github.com/IgorTimofeev/MineOS).
Ich habe an der ursprünglichen [API](https://github.com/IgorTimofeev/MineOS/wiki) nichts geändert, aber es gibt mehr Funktionen.
Hier ist eine Liste einiger Features:

- Multitasking
- Doppelt gepufferte grafische Benutzeroberfläche
- Sprachpakete und Softwarelokalisierung
- Mehrere Benutzerprofile mit Passwortauthentifizierung
- Eigene EEPROM-Firmware mit Funktionen zum Auswählen/Formatieren/Umbenennen des Boot-Volumes und Internet-Wiederherstellungsmodus
- Dateifreigabe über das lokale Netzwerk über Modems
- Client-Verbindungen zu echten FTP-Servern
- Eine interne IDE mit Syntaxhervorhebung und Debugger
- Integrierter Anwendungs- und Bibliotheks-App-Markt mit der Möglichkeit, Ihre eigenen Skripte und Programme für jeden WinDoofOS und [MineOS](https://github.com/IgorTimofeev/MineOS) Benutzer zu veröffentlichen
- Fehlermeldesystem mit der Möglichkeit, Informationen an Entwickler zu senden
- Animationen, Hintergrundbilder, Bildschirmschoner, Farbschemata und riesige Anpassungsmöglichkeiten
- Open-Source-System [API](https://github.com/IgorTimofeev/MineOS/wiki) und detaillierte bebilderte Dokumentationen

## Wie installiert man WinDoofOS?

Am einfachsten ist es, das Standardskript **pastebin** zu verwenden. Legen Sie eine OpenOS-Diskette in den Computer ein, legen Sie eine Internetkarte ein, schalten Sie den Computer ein und geben Sie Folgendes ein, um WinDoofOS zu installieren:

    pastebin run zSYdMMkx

Sie können es mit der mittleren Maustaste oder der Einfügetaste (standardmäßig) in die Konsole einfügen. Wenn Ihnen die Pastebin-Methode aus irgendeinem Grund nicht zur Verfügung steht (z. B. auf der Blacklist auf dem Spieleserver oder vom Internetanbieter blockiert), verwenden Sie den alternativen Befehl, um das Installationsprogramm direkt von der Github-Seite herunterzuladen:

    wget -f https://raw.githubusercontent.com/BachErik/WinDoofOS/master/Installer/BIOS.lua /tmp/bios.lua && flash -q /tmp/bios.lua && reboot

Nach einem Moment wird ein nettes Systeminstallationsprogramm angezeigt. Sie werden aufgefordert, Ihre bevorzugte Sprache und das Startvolume auszuwählen (kann bei Bedarf formatiert werden), ein Benutzerprofil erstellen und einige Einstellungen anpassen

## Wie erstelle ich Anwendungen und arbeite mit der API?

Das ist die API von [MineOS](https://github.com/IgorTimofeev/MineOS).

[API / Wiki](https://github.com/IgorTimofeev/MineOS/wiki)