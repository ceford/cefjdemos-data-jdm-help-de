<!-- Filename: Help4.x:Templates:_Customise_Source / Display title: Templates: Quellcode anpassen -->

<div class="alert alert-warning">
Diese Seite erscheint im Index der Hilfeseiten, wird jedoch nicht über eine Hilfeschaltfläche verwendet.
Dies ist ein Fehler, der voraussichtlich behoben wird.
</div>

## Beschreibung

Auf der Seite *Templates: Quellcode anpassen* können die Quellcode-Dateien eines Templates bearbeitet werden. Sie bietet eine einfache Textschnittstelle zur Bearbeitung der Template-Dateien. Die HTML- und PHP-Programmiersyntax wird hervorgehoben, um das Lesen der Quellcodedateien zu erleichtern. In der Titelleiste erscheint das Wort *Source* als Name des Templates, zum Beispiel *(Cassiopeia)*.

## Zugriff

- Wählen Sie **System → Template-Bereich → Seiten-Templates** aus dem Administrationsmenü. Oder...
- Wählen Sie **System → Template-Bereich → Administrator-Templates** aus dem Administrationsmenü. Dann...
  - Wählen Sie einen Templatenamen aus der Spalte **Templates**. Danach...
    - Wählen Sie eine Datei zum Bearbeiten im Reiter **Editor**.

## Screenshot

![Templates Quellcode anpassen Cassiopeia Editor Tab](../../../de/images/templates/templates-customise-cassiopeia-edit-component-editor-tab.png)

## Formularfelder

### Editor-Reiter

- Wählen Sie eine Datei zum Bearbeiten. Der Bearbeitungsbereich zeigt Text mit Syntaxhervorhebung für die meisten Dateitypen an.

### Reiter "Overrides erstellen"

- Wählen Sie ein Element zum Überschreiben. Wenn ein Ordner ausgewählt wird, wird er erweitert, um eine Liste von Dateien anzuzeigen. Wenn eine Datei ausgewählt wird, wird sie ohne Bestätigungsaufforderung sofort in den HTML-Ordner kopiert. Das Override wird an der entsprechenden Stelle abgelegt. Eine Bestätigungsmeldung erscheint, zum Beispiel: *Override erstellt in /templates/cassiopeia/html/mod_whosonline*.

### Reiter "Aktualisierte Dateien"

Falls es seit dem Erstellen der Overrides keine Aktualisierungen am Template gegeben hat, enthält dieser Tab eine einfache Nachricht:

- **Hinweis** Überschriebene Dateien sind auf dem neuesten Stand. Es wurden keine Änderungen im letzten Erweiterungs- oder Joomla-Update vorgenommen.

Falls es Aktualisierungen gab, zeigt eine Tabelle eine Liste von Overrides an, die überprüft werden müssen.

### Reiter "Template-Beschreibung"

- **Vorschaubild und Beschreibung** Informationen zu diesem Template.

## Werkzeugleiste

Die Symbole in der Werkzeugleiste ändern sich je nach Aktion. Mögliche Symbole:

- **Speichern** Speichert das Element und bleibt auf der aktuellen Seite.
- **Speichern & Schließen** Speichert das Element und schließt die aktuelle Seite.
- **Template kopieren** Kopiert das aktuelle Template. Ein Dialogfeld fordert zur Eingabe eines neuen Namens auf.
- **Template-Vorschau** Öffnet die Website in einem neuen Browser-Tab.
- **Ordner verwalten** Ermöglicht das Erstellen und Löschen von Template-Ordnern über ein Dialogfeld.
- **Neue Datei** Ermöglicht den Upload einer Datei von Ihrem Computer in die Template-Dateihierarchie über ein Dialogfeld.
- **Datei umbenennen** Wählen Sie eine Datei zum Bearbeiten aus. Klicken Sie auf die Schaltfläche "Umbenennen", um einen neuen Namen einzugeben.
- **Datei löschen** Sie werden aufgefordert, die Aktion zu bestätigen oder abzubrechen.
- **Datei schließen** Schließt die geöffnete Datei und kehrt zum Editor-Reiter zurück.
- **Hilfe** Öffnet diesen Hilfebildschirm.

## Tipps

- Wichtig: Löschen Sie keine Standard-Template-Dateien über FTP, da dies sowohl im Frontend als auch im Backend zu einem Fehler führt.
- Bevor Sie die HTML- oder CSS-Dateien des Templates bearbeiten, sollten Sie eine Sicherung der zu bearbeitenden Datei erstellen. Alternativ können Sie diese Dateien auch außerhalb von Joomla! mit dem HTML- oder CSS-Editor Ihrer Wahl bearbeiten.
