<!-- Filename: Help4.x:Site_Modules:_Wrapper / Display title: Module: Wrapper -->

## Beschreibung

Der Modultyp *Wrapper* ermöglicht es, eine externe Website in einem Modul anzuzeigen. Die Funktionalität ist dieselbe wie die des *iFrame Wrapper*, den Sie als Menüpunkt hinzufügen können. Wenn die Seite, auf die der Wrapper verweist, größer als der Rahmen ist, werden vertikale und horizontale Scrollbalken angezeigt.

### Allgemeine Elemente

Einige Elemente dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Symbolleisten](jdocmanual?article=help/common-elements/toolbars).
* [Die Module: Modul-Tab](jdocmanual?article=help/modules/modules-module-tab).
* [Die Module: Menüzuweisungs-Tab](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [Die Module: Erweitert-Tab](jdocmanual?article=help/modules/modules-advanced-tab).
* [Der Berechtigungen-Tab](jdocmanual?article=help/common-elements/edit-permissions).

## Zugriff

- Wählen Sie **System → Verwaltungspanel → Website-Module** aus dem Administrationsmenü. Dann...
  - Um ein neues Modul zu erstellen: Wählen Sie die Schaltfläche **Neu** in der Symbolleiste. Dann...
    - Wählen Sie den erforderlichen Modultyp aus.
  - Um ein bestehendes Modul zu bearbeiten:
    - Suchen Sie das Modul in der Liste der installierten Module und wählen Sie den Titel-Link in der Spalte **Titel**.

## Screenshot

![wrapper modul tab](../../../de/images/modules-site/modules-wrapper-module-tab.png)

## Formularfelder

- **Titel** Der Titel des Moduls. Dies ist auch der Titel, der für das Modul angezeigt wird, abhängig vom Formularfeld *Titel anzeigen*.

### Modul-Tab

#### Linkes Panel

- **URL** URL der Website oder Datei, die Sie im iFrame anzeigen möchten.
- **Auto Hinzufügen** Standardmäßig wird http:// hinzugefügt, es sei denn, es wird http:// oder https:// in der von Ihnen angegebenen URL erkannt. Dies ermöglicht es, diese Funktion zu deaktivieren.
- **Scrollbalken** Horizontale und vertikale Scrollbalken anzeigen oder ausblenden.
- **Breite** Breite des iFrame-Fensters. Sie können eine absolute Zahl in Pixeln oder eine relative Zahl in Prozent angeben.
- **Höhe** Höhe des iFrame-Fensters.
- **Automatische Höhe** Die Höhe wird automatisch an die Größe der externen Seite angepasst. Dies funktioniert nur für Seiten in Ihrer eigenen Domain.
- **Rahmen** Einen Rahmen um den iFrame anzeigen.
- **Zielname** Name des iFrame, wenn es als Ziel verwendet wird.
