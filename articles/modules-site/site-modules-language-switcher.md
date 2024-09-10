<!-- Filename: Help4.x:Site_Modules:_Language_Switcher / Display title: Site Module: Sprachauswahl -->

## Beschreibung

Der Modultyp *Sprachumschalter* ermöglicht es, zwischen den verfügbaren Inhalts-Sprachen zu wechseln. Durch die Auswahl einer Sprache gelangt man zur entsprechenden Seite in dieser Sprache.

### Allgemeine Elemente

Einige Elemente dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Symbolleisten](jdocmanual?article=help/common-elements/toolbars).
* [Das Module: Module-Tab](jdocmanual?article=help/modules/modules-module-tab).
* [Das Module: Menüzuweisung-Tab](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [Das Module: Erweitert-Tab](jdocmanual?article=help/modules/modules-advanced-tab).
* [Das Berechtigungen-Tab](jdocmanual?article=help/common-elements/edit-permissions).

## Wie man darauf zugreift

- Wählen Sie **System → Steuerzentrale → Website-Module** aus dem Administrationsmenü. Dann...
  - Um ein neues Modul zu erstellen: Klicken Sie auf die Schaltfläche **Neu** in der Symbolleiste. Dann...
    - Wählen Sie den gewünschten Modultyp aus.
  - Um ein vorhandenes Modul zu bearbeiten:
    - Suchen Sie das Modul in der Liste der installierten Module und wählen Sie den Titel-Link in der Spalte **Titel** aus.

## Screenshot

![Sprachumschalter Modul-Tab](../../../de/images/modules-site/modules-language-switcher-module-tab.png)

## Formularfelder

- **Titel** Der Titel des Moduls. Dieser wird abhängig vom Formularfeld *Titel anzeigen* auch als Modultitel angezeigt.

### Modul-Tab

#### Linkes Panel

- **Vor-Text** Dies ist der Text oder HTML-Code, der über dem Sprachumschalter angezeigt wird.
- **Nach-Text** Dies ist der Text oder HTML-Code, der unter dem Sprachumschalter angezeigt wird.
- **Dropdown verwenden** Die folgenden drei Elemente ändern sich für *Ja* und *Nein*:
  - **Nein**
    - **Bildflaggen verwenden** Wenn auf *Ja* gesetzt, wird die Sprachauswahl als Bildflaggen angezeigt. Andernfalls werden die nativen Namen der Inhaltssprachen verwendet. Wenn auf *Nein* gesetzt, erscheint ein zusätzliches Feld: **Vollständige Sprachennamen**, das einen zweibuchstabigen Sprachcode in Großbuchstaben für jede Sprache anzeigt.
    - **Aktive Sprache** Zeigt die aktive Sprache an oder nicht. Wenn angezeigt, wird die Klasse `lang-active` dem Element hinzugefügt.
    - **Horizontale Anzeige** Standardmäßig auf *Ja* gesetzt, d. h. eine horizontale Listenanzeige wird erstellt. Auf *Nein* setzen für eine vertikale Liste.
  - **Ja** Das Element *Aktive Sprache* wird als ausgewählt angezeigt.
    - **Flaggen für Dropdown verwenden** Wenn auf *Ja* gesetzt, wird die Sprachflagge vor dem Sprachnamen in der Dropdown-Liste angezeigt.
    - **Vollständige Sprachennamen** Wenn auf *Nein* gesetzt, wird ein zweibuchstabiger Sprachcode in Großbuchstaben für jede Sprache angezeigt.
    - **Aktive Sprache** Hat keine Auswirkung in der Dropdown-Liste.
