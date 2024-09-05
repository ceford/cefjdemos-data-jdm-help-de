<!-- Filename: Help4.x:Media:_Options / Display title: Medien: Optionen -->
## Beschreibung

Die Seite *Medien: Optionen* wird verwendet, um die globalen Parameter für die Medien festzulegen.

### Allgemeine Elemente

Einige Aspekte dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Reiter Berechtigungen](jdocmanual?article=help/common-elements/edit-permissions).

## Zugriff

- Wählen Sie **Inhalt → Medien** aus dem Administratormenü.
- Wählen Sie die Schaltfläche **Optionen** in der Werkzeugleiste.

## Screenshot

![Medien Optionen](../../../de/images/media/media-options.png)

## Formularfelder

### Medien

- **Maximale Größe (in MB)** Verwenden Sie null für kein Limit. Hinweis: Der Server hat ein maximales Limit.
- **Pfad zum Dateiordner** Geben Sie den Pfad zum Dateiordner relativ zum Stammverzeichnis Ihres Webspace ein. Beginnen Sie den Pfad nicht mit einem Schrägstrich. Das Ändern zu einem anderen Pfad als dem Standard *images* kann Ihre Links unterbrechen.
- **Pfad zum Bilderordner** Geben Sie den Pfad zum Bilderordner relativ zum Stammverzeichnis Ihres Webspace ein. Beginnen Sie den Pfad nicht mit einem Schrägstrich.
- **Uploads einschränken** Beschränken Sie Uploads für Benutzer unterhalb der Manager-Ebene auf Bilder, wenn `Fileinfo` oder `MIME Magic` nicht installiert ist.
  - **Erlaubte Erweiterungen** Beschränken Sie Uploads für Benutzer unterhalb der Manager-Ebene auf Dateien in der Liste.
  - **MIME-Typen überprüfen** Verwenden Sie `Fileinfo` oder `MIME Magic`, um zu versuchen, Dateien zu verifizieren. Deaktivieren Sie dies, wenn Sie Fehler bei ungültigen MIME-Typen erhalten.
- **Zulässige Bilddateierweiterungen (Dateitypen)** Bilddateierweiterungen (Dateitypen), die Sie hochladen dürfen (kommagetrennt). Diese werden verwendet, um gültige Bild-Header zu überprüfen und Bilder auszuwählen.
- **Zulässige Audiodateierweiterungen (Dateitypen)** Audiodateierweiterungen (Dateitypen), die Sie hochladen dürfen (kommagetrennt). Diese werden verwendet, um gültige Audio-Header zu überprüfen und Audiodateien auszuwählen.
- **Zulässige Videodateierweiterungen (Dateitypen)** Videodateierweiterungen (Dateitypen), die Sie hochladen dürfen (kommagetrennt). Diese werden verwendet, um gültige Video-Header zu überprüfen und Videos auszuwählen.
- **Zulässige Dokumentdateierweiterungen (Dateitypen)** Dokumentdateierweiterungen (Dateitypen), die Sie hochladen dürfen (kommagetrennt). Diese werden verwendet, um gültige Dokument-Header zu überprüfen und Dokumente auszuwählen.
- **Ignorierte Erweiterungen** Ignorierte Dateierweiterungen für die Überprüfung von MIME-Typen und eingeschränkten Uploads.
- **Zulässige MIME-Typen** Eine kommagetrennte Liste zulässiger MIME-Typen für Uploads.

## Tipps

- Wenn Sie ein Anfänger sind, können Sie hier die Standardwerte beibehalten, bis Sie mehr über die Verwendung globaler Optionen lernen.
- Wenn Sie ein fortgeschrittener Benutzer sind, können Sie Zeit sparen, indem Sie hier gute Standardwerte festlegen.
