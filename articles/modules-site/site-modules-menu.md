<!-- Filename: Help4.x:Site_Modules:_Menu / Display title: Module: Navigation - Menü -->

## Beschreibung

Der Modultyp *Menü* ermöglicht es, ein Menü an der gewünschten Position und auf den gewünschten Webseiten zu platzieren. Eine Website kann mehr als ein Menü auf einer einzigen Seite sowie unterschiedliche Menüs auf verschiedenen Webseiten haben.

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

![Menü-Modul-Tab](../../../de/images/modules-site/modules-menu-module-tab.png)

## Formularfelder

- **Titel** Der Titel des Moduls. Dieser wird abhängig vom Formularfeld *Titel anzeigen* auch als Modultitel angezeigt.

### Modul-Tab

#### Linkes Panel

- **Menü auswählen** Wählen Sie ein Menü aus der Liste der verfügbaren Menüs.
- **Basis-Element** Wählen Sie ein Menüelement, das immer als Basis für die Menüanzeige verwendet wird. Sie müssen das Start-Level auf die gleiche Ebene oder höher als das Basis-Element setzen. Dies bewirkt, dass das Modul auf allen zugewiesenen Seiten angezeigt wird. Wenn *Aktuell* ausgewählt ist, wird das aktuell aktive Element als Basis verwendet, was dazu führt, dass das Modul nur angezeigt wird, wenn das übergeordnete Menüelement aktiv ist.
- **Start-Level** Ebene, bei der das Menü gerendert werden soll. Wenn das Start- und End-Level auf die gleiche Nummer gesetzt und *Untermenüelemente anzeigen* auf *Anzeigen* gesetzt wird, wird nur diese einzelne Ebene angezeigt.
- **End-Level** Ebene, bei der das Menü-Rendering gestoppt wird. Wenn Sie *Alle* auswählen, werden alle Ebenen angezeigt, je nach Einstellung von *Untermenüelemente anzeigen*.
- **Untermenüelemente** Untermenüelemente anzeigen oder ausblenden.
