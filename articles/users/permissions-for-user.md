<!-- Filename: Help4.x:Permissions_for_User / Display title: Berechtigungen für Benutzer -->

## Beschreibung

Die Seite *Berechtigungen für Benutzer* zeigt einen Berechtigungsbericht, der die genauen Berechtigungen für einen bestimmten Benutzer über alle Website-Assets hinweg anzeigt. Sie ist nützlich, um Zugriffsprobleme von Benutzern zu debuggen.

### Allgemeine Elemente

Einige Elemente dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Listenfilter](jdocmanual?article=help/common-elements/list-filters).
* [Listen-Spaltenüberschriften](jdocmanual?article=help/common-elements/list-column-headers).
* [Listen-Paginierung](jdocmanual?article=help/common-elements/list-pagination).

## So greifen Sie darauf zu

- Wählen Sie **Benutzer → Verwalten** aus dem Administrator-Menü. Dann...
  - Wählen Sie die Schaltfläche **Berechtigungen** für einen bestimmten Benutzer.

## Screenshot

![Benutzer Berechtigungen für Benutzer](../../../de/images/users/users-permissions-for-user.png)

Oberhalb der Berechtigungstabelle werden ausgewählte Elemente angezeigt, die die Zugriffsberechtigungen mithilfe von Symbolen für *Erlaubt*, *Nicht Erlaubt* und *Verboten* darstellen. Die Symbollegende befindet sich unter der Tabelle.

- **Website-Login** Kann sich der Benutzer im Frontend der Website anmelden.
- **Administrator-Login** Kann sich der Benutzer im Backend der Website anmelden.
- **Web-Services-Login** Kann der Benutzer über einen Super-User-API-Token auf die Joomla-Web-Services-API zugreifen.
- **Offline-Zugriff** Kann der Benutzer auf das Frontend der Website zugreifen, wenn es offline ist.

### Spaltenüberschriften

In der Tabelle mit den Website-Assets werden die Berechtigungen für den ausgewählten Benutzer angezeigt.

- **Asset-Titel** Der Asset-Name in Klartext.
- **Asset-Name** Der interne Asset-Name.
- **Super User** Kann der Benutzer Super-User-Aktionen für das Asset unabhängig von anderen Berechtigungseinstellungen ausführen.
- **Konfigurationsoptionen bearbeiten** Kann der Benutzer die Optionen des Assets (außer Berechtigungen) bearbeiten.
- **Zugriff auf die Administrationsoberfläche** Kann der Benutzer auf die Administrationsoberfläche des Assets zugreifen.
- **Erstellen** Kann der Benutzer Inhalte im Asset erstellen.
- **Löschen** Kann der Benutzer Inhalte im Asset löschen.
- **Bearbeiten** Kann der Benutzer Inhalte im Asset bearbeiten.
- **Status bearbeiten** Kann der Benutzer den Status des Assets bearbeiten.
- **Eigene Inhalte bearbeiten** Kann der Benutzer eigene Inhalte im Asset bearbeiten.
- **Benutzerdefinierte Feldwerte bearbeiten** Kann der Benutzer benutzerdefinierte Feldwerte im Asset bearbeiten.
- **LFT** Die linken und rechten Werte in der Verschachtelungshierarchie. Dies wird für die Asset-Verschachtelung und -Reihenfolge verwendet.
- **ID** Dies ist eine eindeutige Identifikationsnummer, die Joomla diesem Element automatisch zuweist. Sie dient zur internen Identifizierung des Elements und kann nicht geändert werden. 
