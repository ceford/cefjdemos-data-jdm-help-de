<!-- Filename: Help4.x:Site_Modules:_Custom / Display title: Module: Eigenes Modul -->

## Beschreibung

Der Modultyp *Benutzerdefiniert* ermöglicht es Ihnen, eine eigenständige HTML-Einheit zu erstellen, die an jeder gültigen Stelle auf einer Seite platziert werden kann.

Es gibt viele Fälle, in denen Sie freiformatiertes HTML in eine Webseite einfügen möchten. Zum Beispiel könnten Sie eine HTML-Bildkarte erstellen oder HTML-Code von PayPal, Amazon oder einer anderen Website einfügen.

### Allgemeine Elemente

Einige Elemente dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Module-Tab](jdocmanual?article=help/modules/modules-module-tab).
* [Der Menüzuweisung-Tab](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [Der Erweiterte-Tab](jdocmanual?article=help/modules/modules-advanced-tab).
* [Der Berechtigungen-Tab](jdocmanual?article=help/common-elements/edit-permissions).

## Zugriff

- Wählen Sie **System → Verwaltungsbereich → Seitenmodule** aus dem Administratormenü. Dann...
  - Um ein neues Modul zu erstellen: Wählen Sie die Schaltfläche **Neu** in der Werkzeugleiste. Dann...
    - Wählen Sie den gewünschten Modultyp aus.
  - Um ein vorhandenes Modul zu bearbeiten:
    - Suchen Sie das Modul in der Liste der installierten Module und wählen Sie den Titel-Link in der Spalte **Titel**.

## Screenshot

![benutzerdefiniertes Modul-Tab](../../../de/images/modules-site/modules-custom-module-tab.png)

## Formularfelder

- **Titel** Der Titel des Moduls. Dies ist auch der Titel, der für das Modul abhängig vom Formularfeld *Titel anzeigen* angezeigt wird.

### Modul-Tab

#### Linkes Panel

- **Editor** Die Joomla-Textfilter und der TinyMCE-Editor erlauben jeweils nicht die Eingabe bestimmter HTML-Tags.
  - Die Textfilter können im Tab *Textfilter* der globalen Konfiguration konfiguriert werden. Zum Beispiel dürfen standardmäßig die Benutzergruppen Gäste, Öffentlich und Registrierte keine HTML-Tags in Formularfeldern eingeben.
  - Die TinyMCE-Filter können im entsprechenden Plugin konfiguriert werden. Standardmäßig verbietet es die Eingabe von Script-, Applet- und Iframe-Tags.
  
### Optionen-Tab

- **Inhalt vorbereiten** Optional können Sie den Inhalt mit Joomla Content Plugins vorbereiten.
- **Wählen Sie ein Hintergrundbild** Wenn Sie hier ein Bild auswählen, wird es automatisch als Inline-Stil für das umschließende div-Element eingefügt.
