<!-- Filename: Help4.x:Templates:_Customise / Display title: Templates: Anpassen -->

## Beschreibung

Auf der Seite *Templates: Anpassen* kann der Quellcode eines Templates bearbeitet werden. Sie können Overrides für PHP-Dateien erstellen sowie user.css- und user.js-Dateien hinzufügen, die die Systemversionen ergänzen. Außerdem können Sie Child-Templates erstellen, um die Masterdateien des Overrides-Templates zu bearbeiten.

## Zugriff

- Wählen Sie **System → Template-Bereich → Seiten-Templates** aus dem Administrationsmenü. Oder...
- Wählen Sie **System → Template-Bereich → Administrator-Templates** aus dem Administrationsmenü. Dann...
  - Wählen Sie einen Templatenamen aus der Spalte **Template**.

## Screenshot

Die Administrator- und Seiten-Templates-Bildschirme verwenden das gleiche Layout. Der Bildschirm für Seiten-Templates wird hier illustriert.

![Templates Anpassen Cassiopeia Editor Tab](../../../de/images/templates/templates-customise-cassiopeia-editor-tab.png)

## Formularfelder

### Editor-Reiter

- Wählen Sie eine Datei zum Bearbeiten aus. Der Bearbeitungsbereich zeigt Text mit Syntaxhervorhebung für die meisten Dateitypen an.

### Reiter "Overrides erstellen"

![Templates Anpassen Cassiopeia Overrides erstellen Tab](../../../de/images/templates/templates-customise-cassiopeia-create-overrides-tab.png)

- Wählen Sie ein Element zum Überschreiben aus. Elemente, die mit einem durchgehenden Dateisymbol markiert sind, öffnen sich, um eine Liste von Elementen anzuzeigen. Elemente, die mit überlagerten offenen und gefüllten Seitensymbolen markiert sind, erstellen sofort ein Override ohne Bestätigungsaufforderung. Das Override wird an der entsprechenden Stelle abgelegt. Es erscheint eine Bestätigungsmeldung, zum Beispiel: 
  *Override erstellt in /templates/cassiopeia/html/mod_whosonline*.

### Reiter "Aktualisierte Dateien"

![Templates Anpassen Cassiopeia Aktualisierte Dateien Tab](../../../de/images/templates/templates-customise-cassiopeia-updated-files-tab.png)

Falls es seit dem Erstellen der Overrides keine Aktualisierungen am Template gegeben hat, enthält dieser Tab eine einfache Nachricht:

<div class="alert alert-success">
Überschriebene Dateien sind auf dem neuesten Stand. Es wurden keine Änderungen im letzten Erweiterungs- oder Joomla-Update vorgenommen.
</div>

Falls es Aktualisierungen gab, zeigt eine Tabelle eine Liste von Overrides an, die überprüft werden müssen.

### Reiter "Template-Beschreibung"

![Templates Anpassen Cassiopeia Template-Beschreibung Tab](../../../de/images/templates/templates-customise-cassiopeia-template-description-tab.png)

- **Vorschaubild und Beschreibung** Informationen zu diesem Template.

## Werkzeugleiste

Beachten Sie, dass sich die Schaltflächen in der Werkzeugleiste ändern, wenn eine Datei zur Bearbeitung ausgewählt wird.

### Keine Datei ausgewählt

Am oberen Rand der Seite sehen Sie die in der obigen Abbildung dargestellte Werkzeugleiste. Die Funktionen sind:

- **Child-Template erstellen** Wählen Sie diese Option, um ein neues Child-Template zu erstellen. Sie werden nach einem neuen Child-Template-Namen gefragt. Es gibt auch die Möglichkeit, das Erstellen eines Child-Templates abzubrechen. Um das neue Child-Template zu entfernen: Wählen Sie die Schaltfläche **Schließen**, dann die Schaltfläche "Styles" in der Toolbar der Template-Liste, markieren Sie das Kästchen des neuen Child-Templates und wählen Sie Löschen in der Werkzeugleiste.
- **Template-Vorschau** Wählen Sie diese Option, um die Standardansicht der Website mit diesem Template in einem neuen Browser-Tab zu öffnen.
- **Ordner verwalten** Wählen Sie diese Option, um einen neuen Ordner innerhalb der Template-Hierarchie zu erstellen. Ein Popup-Fenster erscheint. **Wichtig:** Wählen Sie den Ordner aus, in dem der neue Ordner erscheinen soll, bevor Sie den neuen Ordner erstellen.
- **Neue Datei** Wählen Sie diese Option, um eine neue Datei zu erstellen oder eine Datei von Ihrem Computer in die Joomla!-Template-Hierarchie hochzuladen. Ein Popup-Fenster erscheint. **Wichtig** Wählen Sie den Ordner aus, in dem die neue Datei erscheinen soll, bevor Sie die neue Datei erstellen.
- **Overrides prüfen** Wird aktiviert, wenn im Reiter *Overrides* ein Override ausgewählt wird. Die Optionen sind:
  - Als überprüft markieren
  - Als nicht überprüft markieren
  - Eintrag entfernen
- **Schließen** Schließt den aktuellen Bildschirm und kehrt zum vorherigen Bildschirm zurück, ohne Änderungen zu speichern. Diese Schaltfläche wird nicht angezeigt, wenn Sie ein neues Element erstellen.
- **Hilfe** Öffnet diesen Hilfebildschirm.

### Datei ausgewählt

- **Speichern** Speichert das Element und bleibt auf der aktuellen Seite.
- **Speichern & Schließen** Speichert das Element und schließt die aktuelle Seite.
- **Datei umbenennen** Wählen Sie eine Datei zum Bearbeiten aus. Klicken Sie auf die Schaltfläche "Umbenennen", um einen neuen Namen einzugeben.
- **Datei löschen** Sie werden aufgefordert, die Aktion zu bestätigen oder abzubrechen.
- **Overrides prüfen** Wird aktiviert, wenn im Reiter *Overrides* ein Override ausgewählt wird.
- **Datei schließen** Schließt die geöffnete Datei und kehrt zum Editor-Reiter zurück.
- **Hilfe** Öffnet diesen Hilfebildschirm.

## Tipps

- Bevor Sie die HTML- oder CSS-Dateien des Templates bearbeiten, ist es ratsam, eine Sicherungskopie der zu bearbeitenden Datei zu erstellen. Alternativ können Sie diese Dateien auch außerhalb von Joomla! mit dem HTML- oder CSS-Editor Ihrer Wahl bearbeiten.
