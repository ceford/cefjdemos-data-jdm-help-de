<!-- Filename: Help4.x:Admin_Modules:_Custom / Display title: Module: Benutzerdefiniert -->

## Beschreibung

Der Modultyp *Benutzerdefiniert* ermöglicht es Ihnen, eine eigenständige HTML-Einheit zu erstellen und diese an einer beliebigen gültigen Position auf einer Seite zu platzieren.

Es gibt viele Fälle, in denen freiformatiertes HTML in der Administratoroberfläche angezeigt werden kann. Beispielsweise könnte eine temporäre Systemnachricht oben auf allen Administratorseiten angezeigt werden (Position: `customtop`). Zusätzliche Formatierungen können über den *Erweitert*-Tab erforderlich sein.

### Allgemeine Elemente

Einige Elemente dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Module-Tab](jdocmanual?article=help/modules/modules-module-tab).
* [Der Erweiterte-Tab](jdocmanual?article=help/modules/modules-advanced-tab).
* [Der Berechtigungen-Tab](jdocmanual?article=help/common-elements/edit-permissions).

## Zugriff

- Wählen Sie **System → Verwaltungsbereich → Administrator-Module** aus dem Administratormenü. Dann...
  - Um ein neues Modul zu erstellen: Wählen Sie die Schaltfläche **Neu** in der Werkzeugleiste. Dann...
    - Wählen Sie den gewünschten Modultyp.
  - Um ein vorhandenes Modul zu bearbeiten:
    - Suchen Sie das Modul in der Liste der installierten Module und wählen Sie den Titel-Link in der Spalte **Titel**.

## Screenshot

![Module Artikel Neueste Tab](../../../de/images/modules-admin/modules-custom-module-tab.png)

## Formularfelder

- **Titel** Der Titel des Moduls. Dies ist auch der Titel, der für das Modul abhängig vom Formularfeld *Titel anzeigen* angezeigt wird.

### Modul-Tab

#### Linke Spalte

- **Editor** Die Joomla-Textfilter und der TinyMCE-Editor erlauben jeweils nicht die Eingabe bestimmter HTML-Tags.
  - Die Textfilter können im Tab *Textfilter* der globalen Konfiguration konfiguriert werden. Zum Beispiel dürfen standardmäßig die Benutzergruppen Gäste, Öffentlich und Registrierte keine HTML-Tags in Formularfeldern eingeben.
  - Die TinyMCE-Filter können im entsprechenden Plugin konfiguriert werden. Standardmäßig verbietet es die Eingabe von Script-, Applet- und Iframe-Tags.