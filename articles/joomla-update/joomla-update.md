<!-- Filename: Help4.x:Joomla_Update / Display title: Joomla-Aktualisierung -->

## Beschreibung

Diese Seite ermöglicht es, Joomla! mit einem Update-Paket aus dem Joomla!-Code-Repository zu aktualisieren. Es ist am besten und sichersten, Joomla! über diese Methode selbst aktualisieren zu lassen.

## Zugriff

Im **Start-Dashboard → Benachrichtigungs-Panel** wird das Joomla-Symbol eine von zwei Nachrichten anzeigen:
- **Joomla ist auf dem neuesten Stand**
- **X.Y.Z verfügbar - Jetzt aktualisieren!**

Wähle das Symbol aus.

Auch im **System → Update-Panel → Joomla** wird entweder ein Häkchen angezeigt, was bedeutet, dass Joomla auf dem neuesten Stand ist, oder eine Versionsnummer, die anzeigt, dass eine neue Version verfügbar ist.

## Screenshot

Wenn deine Website auf dem neuesten Stand ist, siehst du diesen Bildschirm:

![Hochladen & Aktualisieren](../../../en/images/joomla-update/upload-update-up-to-date.png)

Wenn ein Update verfügbar ist, siehst du diesen Bildschirm:

![Hochladen & Aktualisieren](../../../en/images/joomla-update/upload-update-available.png)

Wenn du eine Haupt- oder Nebenversion aktualisierst, siehst du einen Pre-Update-Check-Bildschirm:

![Pre-Update-Check](../../../en/images/joomla-update/upload-update-pre-update-check.png)

Wähle jeden der drei Menüpunkte aus, um zu prüfen, ob etwas Aufmerksamkeit benötigt.

## Update starten

Wenn du nicht die neueste Version von Joomla hast, kannst du das neueste Update von dieser Seite aus installieren. Stelle sicher, dass du ein Backup gemacht hast, und aktiviere das Kontrollkästchen **Ich bin mir bewusst...** um zu bestätigen, dass du dies getan hast. Wähle dann die Schaltfläche **Update starten**, und Joomla wird die neueste Version installieren.

Während des Updates zeigt der Bildschirm einen Fortschrittsbalken an.

### Hochladen und Aktualisieren

Du kannst diese Schaltfläche verwenden, um Joomla zu aktualisieren, wenn dein Server hinter einer Firewall steht oder anderweitig nicht in der Lage ist, die Update-Server zu kontaktieren. Lade zuerst das Joomla-Upgrade-Paket im ZIP-Format von der offiziellen Joomla-Download-Seite herunter.

Deine PHP-Einstellungen für *upload_max_filesize* und *post_max_size* müssen auf 64 MB und das PHP-Speicherlimit auf 256 MB gesetzt sein. Andernfalls kann das Update fehlschlagen. Ein weiterer guter Grund, ein Backup zu machen!

![Hochladen und installieren](../../../en/images/joomla-update/upload-update-upload-install.png)

## Update-Optionen

Die Schaltfläche *Optionen* in der Werkzeugleiste ermöglicht es dir, den Update-Typ auszuwählen:

- **Standard** Dies wird für Seiten verwendet, die bei der installierten Version bleiben sollen.
- **Joomla Next** Dies wird für Seiten verwendet, die normalerweise auf die nächste Hauptversion wechseln, sobald eine stabile Version veröffentlicht wird.
- **Benutzerdefinierte URL** Für Entwickler, um eine Update-Quelle auszuwählen.
