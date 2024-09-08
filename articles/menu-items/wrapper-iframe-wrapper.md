<!-- Filename: Help4.x:Menu_Item:_Iframe_Wrapper / Display title: Iframe Wrapper -->

## Beschreibung

Der Menüpunkt-Typ *Iframe Wrapper* wird verwendet, um eine Seite mit eingebettetem Inhalt über ein IFrame zu erstellen, bei dem die Größe, Breite und Höhe des IFrames gesteuert werden können.

### Allgemeine Elemente

Einige Aspekte dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Symbolleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Details-Tab](jdocmanual?article=help/menu-items-common/menu-item-details).
* [Der Link-Typ-Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [Der Seitendarstellung-Tab](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [Der Metadaten-Tab](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [Der Verknüpfungen-Tab](jdocmanual?article=help/common-elements/edit-associations).
* [Der Modul-Zuweisungs-Tab](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Zugriffsmethode

Um einen neuen Menüpunkt *Iframe Wrapper* zu erstellen:

- Wählen Sie **Menüs → \[Name des Menüs\]** aus dem Administrator-Menü (zum Beispiel **Menüs → Hauptmenü**). Dann...
  - Wählen Sie die Schaltfläche **Neu** in der Symbolleiste. Dann...
  - Wählen Sie die Schaltfläche zum Auswählen des Menüpunkt-Typs.
  - Im Dialogfeld wählen Sie den Punkt *Benutzer* aus, um eine Liste zu öffnen, und wählen dann den Menüpunkt **Iframe Wrapper**.

Um einen bestehenden Menüpunkt *Iframe Wrapper* zu bearbeiten:

- Wählen Sie dessen Titel in der Liste *Menü: Elemente*.

## Screenshot

![Iframe-Wrapper-Details-Tab](../../../de/images/menu-items/wrapper-iframe-wrapper-details-tab.png)

## Formularfelder

### Scrollleisten-Parameter-Tab

![Iframe-Wrapper-Scrollleisten-Parameter-Tab](../../../de/images/menu-items/wrapper-scroll-bar-parameters-tab.png)

- **Breite** Breite des IFrame-Fensters. Geben Sie eine Pixelzahl oder einen Prozentsatz ein. Zum Beispiel bedeutet *550* 550 Pixel; *75%* bedeutet 75% der Breite des `<main>`-Containers. Eine absolute Pixelzahl kann breiter als der Container sein und Layoutprobleme verursachen. Im Zweifelsfall probieren Sie 100%.
- **Höhe** Höhe des IFrame-Fensters. Geben Sie eine Pixelzahl ein. Zum Beispiel bedeutet *550* 550 Pixel.

### Erweitert-Tab

![Iframe-Wrapper-Erweitert-Tab](../../../de/images/menu-items/wrapper-advanced-tab.png)

- **Automatische Höhe** Die Höhe wird automatisch auf die Höhe der externen Seite eingestellt. *Hinweis* - dies funktioniert nur, wenn die externe Seite auf der **gleichen Domain** liegt. Zum Beispiel muss bei `http://www.beispiel.de` die externe HTML-Datei im Root-Verzeichnis von `beispiel.de` liegen. Subdomains funktionieren nicht, da sie als separate Domains betrachtet werden.
- **Automatisch hinzufügen**. Webadresse automatisch mit http:// voranstellen. Diese Funktion erkennt automatisch, wenn eine URL bereits mit http:// oder https:// beginnt, und stellt sie nicht erneut vor.
- **Lazy Loading** ...
