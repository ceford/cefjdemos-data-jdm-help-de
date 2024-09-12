<!-- Filename: Help4.x:Tags:_New_or_Edit / Display title: Schlagwörter: Neu oder Bearbeiten -->

## Beschreibung

Die Seite *Tags: Neu oder Bearbeiten* wird verwendet, um Tags hinzuzufügen oder zu bearbeiten, die zur Anzeige von Website-Inhalten nach Tag-Namen verwendet werden können.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).

## Zugriff

- Wählen Sie **Komponenten → Tags** im Administrator-Menü. Dann
  - Wählen Sie die Schaltfläche '**Neu**' in der Werkzeugleiste, um ein neues Tag zu erstellen.
  - Wählen Sie den Titel eines Tags aus der **Titel**-Spalte der Liste, um ein vorhandenes Tag zu bearbeiten.

## Screenshot

![tags edit tag details tab](../../../de/images/tags/tags-edit-tag-details-tab.png)

## Formularfelder

- **Titel** Der Name dieses Elements. Dieses Feld ist erforderlich.
- **Alias** Der interne Name des Elements. Normalerweise können Sie dieses Feld leer lassen und Joomla füllt es automatisch aus, indem der Titel in Kleinbuchstaben und mit Bindestrichen anstelle von Leerzeichen verwendet wird.

### Tag-Details-Tab

#### Linkes Panel

- **Beschreibung** Geben Sie den Zweck dieses Tags an.

#### Rechtes Panel

- **Übergeordnetes Element** Das übergeordnete Element (Kategorie, Menüpunkt usw.), das dem bearbeiteten Element übergeordnet ist.
- **Status** Der Veröffentlichungsstatus des Elements.
- **Zugriff** Die Zugriffsebene für dieses Element.
- **Sprache** Sprache des Elements.
- **Notiz** Dies dient in der Regel zur internen Verwendung durch den Administrator (z. B. zum Dokumentieren von Informationen über dieses Element) und wird nicht auf der Website angezeigt.
- **Versionshinweis** Ein optionales Feld, um diese Version des Elements im Versionsverlauf des Elements zu identifizieren.

### Optionen-Tab

![tags edit tag options tab](../../../de/images/tags/tags-edit-options-tab.png)

#### Optionen-Panel

- **Layout** Verwenden Sie ein Layout aus der mitgelieferten Komponentensicht oder aus Template-Overrides.
- **CSS-Klasse für Tag-Link** Fügen Sie spezifische CSS-Klassen für den Tag-Link hinzu. Wenn leer, wird standardmäßig *label label-info* vom Tag-Layout hinzugefügt.

#### Bilder-Panel

- **Teaserbild** Das Bild, das als Teil der Liste angezeigt wird.
- **Float** Float-Attribut für das Bild.
- **Alt** Alt-Text für das Bild.
- **Bildunterschrift** Die Bildunterschrift für das Bild.
- **Vollbild** Ein Bild, das in der Einzel-Tag-Ansicht angezeigt wird.

### Veröffentlichungs-Tab

![tags edit tag publishing tab](../../../de/images/tags/tags-edit-publishing-tab.png)

#### Veröffentlichungs-Panel

- **Erstellungsdatum** Datum, an dem das Element (Artikel, Kategorie usw.) erstellt wurde.
- **Erstellt von** Name des Joomla-Benutzers, der dieses Element erstellt hat. Standardmäßig wird der derzeit angemeldete Benutzer angezeigt. Wenn Sie dies ändern möchten, klicken Sie auf die Schaltfläche Benutzer auswählen, um einen anderen Benutzer auszuwählen.
- **Alias des Erstellers** Dieses optionale Feld ermöglicht es Ihnen, für diesen Artikel einen Alias für den Autor einzugeben. Dadurch können Sie einen anderen Autorennamen für diesen Artikel anzeigen.
- **Änderungsdatum** Datum der letzten Änderung.
- **Geändert von** Benutzername der Person, die die letzte Änderung vorgenommen hat.
- **Revision** ...
- **Aufrufe** Die Anzahl der Ansichten dieses Elements.
- **ID** Dies ist eine eindeutige Identifikationsnummer für dieses Element, die automatisch von Joomla vergeben wird. Sie wird intern verwendet und kann nicht geändert werden. Bei der Erstellung eines neuen Elements zeigt dieses Feld "0" an, bis der neue Eintrag gespeichert wird und eine neue ID zugewiesen wird.

#### Metadaten-Panel

- **Meta-Beschreibung** Ein optionaler Absatz, der als Seitenbeschreibung im HTML-Output verwendet wird. Dies wird in der Regel in den Ergebnissen von Suchmaschinen angezeigt. Wenn eingegeben, wird ein HTML-Meta-Element mit einem name-Attribut von `<description>` und einem content-Attribut mit dem eingegebenen Text erstellt.
- **Schlüsselwörter** Optionaler Eintrag für Schlüsselwörter. Müssen durch Kommas getrennt eingegeben werden (zum Beispiel: katzen, hunde, haustiere) und können in Groß- oder Kleinbuchstaben geschrieben werden. Schlüsselwörter können auf verschiedene Weisen verwendet werden:
  1.  Um Suchmaschinen und anderen Systemen zu helfen, den Inhalt des Artikels zu klassifizieren.
  2.  In Kombination mit Banner-Tags, um spezifische Banner basierend auf dem Artikelinhalt anzuzeigen. Zum Beispiel können Sie ein Banner mit Werbung für Hundeprodukte und ein anderes Banner für Katzenprodukte haben. Sie können festlegen, dass das Hundebanner angezeigt wird, wenn ein Benutzer einen hundebezogenen Artikel liest, und das Katzenbanner für einen katzenbezogenen Artikel. Dazu würden Sie:
      - Die Schlüsselwörter "hund" und "katze" zu den entsprechenden Artikeln hinzufügen.
      - Die Tags "hund" und "katze" zu den entsprechenden Bannern im Banner: Bearbeiten hinzufügen.
      - Den Parameter 'Nach Tags suchen' im Banner-Modul auf "Ja" setzen.
  3.  Für Artikel nur in Kombination mit dem Modul Artikel - Verwandte, um Artikel anzuzeigen, die mindestens ein gemeinsames Schlüsselwort haben. Wenn zum Beispiel der aktuell angezeigte Artikel die Schlüsselwörter "katzen, hunde, affen" enthält, werden alle anderen Artikel, die mindestens eines dieser Schlüsselwörter haben, im Modul "Artikel - Verwandte" angezeigt.
- **Autor** Optionaler Eintrag für den Namen des Autors innerhalb der Metadaten. Wenn eingegeben, wird ein HTML-Meta-Element mit dem Namen 'author' und dem Inhalt des hier eingegebenen Werts erstellt.
- **Robots** Die Anweisungen für Web-"Robots", die auf diese Seite zugreifen:
  - *index, follow* Diese Seite indizieren und die Links auf dieser Seite folgen.
  - *noindex, follow* Diese Seite nicht indizieren, aber den Links auf der Seite folgen. Zum Beispiel könnten Sie dies für eine Sitemap-Seite tun, auf der Sie die Links indizieren lassen möchten, aber nicht wollen, dass die Seite in Suchmaschinen erscheint.
  - *index, nofollow* Diese Seite indizieren, aber keinen Links auf der Seite folgen. Dies könnte zum Beispiel für einen Veranstaltungskalender nützlich sein, bei dem die Seite in Suchmaschinen erscheinen soll, aber nicht jede Veranstaltung indiziert werden soll.
  - *noindex, nofollow* Diese Seite weder indizieren noch den Links auf der Seite folgen.
  - *Globale Einstellungen verwenden* In den globalen Metadaten-Einstellungen festgelegt.