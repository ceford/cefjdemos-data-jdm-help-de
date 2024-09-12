<!-- Filename: Help4.x:Permissions_for_Group / Display title: Berechtigungen für Gruppen -->

## Beschreibung

Die Seite *Berechtigungen für Gruppe* zeigt einen Berechtigungsbericht, der die 
genauen Berechtigungen für eine bestimmte Benutzergruppe über alle Website-Assets hinweg anzeigt. Diese Seite ist nützlich, um Zugriffsprobleme von Benutzern zu debuggen.

### Allgemeine Elemente

Einige Elemente dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Listenfilter](jdocmanual?article=help/common-elements/list-filters).
* [Listen-Spaltenüberschriften](jdocmanual?article=help/common-elements/list-column-headers).
* [Listen-Paginierung](jdocmanual?article=help/common-elements/list-pagination).

## So greifen Sie darauf zu

- Wählen Sie **Benutzer → Gruppen** aus dem Administrator-Menü. Dann...
  - Wählen Sie das **Berechtigungen**-Symbol für eine bestimmte Gruppe aus der Liste der Benutzergruppen.

## Screenshot

![Benutzer Berechtigungen für Gruppe](../../../de/images/users/users-permissions-for-group.png)

Oberhalb der Berechtigungstabelle werden ausgewählte Elemente angezeigt, die die Zugriffsberechtigungen mithilfe von Symbolen für *Erlaubt*, *Nicht Erlaubt* und *Verboten* darstellen. Die Symbollegende befindet sich unter der Tabelle.

- **Website-Login** Können sich Benutzer der Gruppe im Frontend der Website anmelden.
- **Administrator-Login** Können sich Benutzer der Gruppe im Backend der Website anmelden.
- **Web-Services-Login** Können Benutzer der Gruppe über einen Super-User-API-Token auf die Joomla-Web-Services-API zugreifen.
- **Offline-Zugriff** Können Benutzer der Gruppe auf das Frontend der Website zugreifen, wenn es offline ist.
- **Super User** Können Benutzer der Gruppe unabhängig von anderen Berechtigungseinstellungen jede Aktion auf der gesamten Website ausführen.

### Spaltenüberschriften

In der Tabelle mit den Website-Assets werden die Berechtigungen für die ausgewählte Gruppe angezeigt.

- **Asset-Titel** Der Asset-Name in Klartext.
- **Asset-Name** Der interne Asset-Name.
- **Konfigurationsoptionen bearbeiten** Können Benutzer der Gruppe die Optionen dieses Assets (außer Berechtigungen) bearbeiten.
- **Zugriff auf die Administrationsoberfläche** Können Benutzer der Gruppe auf die Administrationsoberfläche des Assets zugreifen.
- **Erstellen** Können Benutzer der Gruppe Inhalte im Asset erstellen.
- **Löschen** Können Benutzer der Gruppe Inhalte im Asset löschen.
- **Bearbeiten** Können Benutzer der Gruppe Inhalte im Asset bearbeiten.
- **Status bearbeiten** Können Benutzer der Gruppe den Status des Assets bearbeiten.
- **Eigene Inhalte bearbeiten** Können Benutzer der Gruppe Inhalte bearbeiten, die sie im Asset besitzen.
- **Benutzerdefinierte Feldwerte bearbeiten** Können Benutzer der Gruppe benutzerdefinierte Feldwerte im Asset bearbeiten.
- **LFT** Die linken und rechten Werte in der Verschachtelungshierarchie. Dies wird für die Asset-Verschachtelung und -Reihenfolge verwendet.
- **ID** Dies ist eine eindeutige Identifikationsnummer, die Joomla diesem Element automatisch zuweist. Sie dient zur internen Identifizierung des Elements und kann nicht geändert werden.
