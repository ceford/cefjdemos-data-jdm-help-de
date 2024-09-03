<!-- Filename: Help4.x:Languages:_Edit_Content_Language / Display title: Sprachen: Inhaltsprache bearbeiten -->

## Beschreibung

Die Seite *Sprachen: Inhaltsprache bearbeiten* wird verwendet, um die Parameter einer installierten Sprache festzulegen.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).

## Zugriff

- Wähle **System → Verwaltungs-Panel → Inhaltssprachen** aus dem Administrator-Menü. Dann...
  - Wähle den Sprachnamen-Link aus der Spalte **Titel**.

## Screenshot

![Sprachen Inhaltsprache bearbeiten Details-Tab](../../../en/images/languages/languages-edit-content-language-details-tab.png)

## Formularfelder

### Details-Tab

- **Titel** Der Name der Sprache, wie er in den Listen angezeigt wird.
- **Titel in Landessprache** Sprachentitel in der jeweiligen Landessprache.
- **Sprachtag** Gib das Sprachkennzeichen ein, zum Beispiel: en-GB für
  Englisch (en-GB). Dies sollte das genaue Präfix sein, das für die installierte oder zu installierende Sprache verwendet wird.
- **URL-Sprachcode** Sprachcode für diese Sprache. Dieser Sprachcode wird in die URL der Website aufgenommen. Beachte, dass der Sprachcode eindeutig unter allen Sprachen sein muss.
- **Bild** Wähle aus den verfügbaren Bildern für diese Sprache bei Verwendung der Grundoption *Bildflaggen verwenden* im Sprachwechsler.
- **Status** Verfügbare Optionen sind Veröffentlicht, Nicht veröffentlicht und Papierkorb.
- **Zugriff** Die Zugriffsebene für die Anzeige dieses Elements.
- **Beschreibung** Gib eine Beschreibung für die Sprache ein.
- **ID** Dies ist eine eindeutige Identifikationsnummer für dieses Element, die automatisch von Joomla zugewiesen wird. Sie wird verwendet, um das Element intern zu identifizieren, und diese Nummer kann nicht geändert werden. Beim Erstellen eines neuen Elements zeigt dieses Feld "0" an, bis du den neuen Eintrag speicherst, woraufhin ihm eine neue ID zugewiesen wird.

### Optionen-Tab

![Sprachen Inhaltsprache bearbeiten Optionen-Tab](../../../en/images/languages/languages-edit-content-language-options-tab.png)

* Der **Benutzerdefinierte Name der Website** kann in verschiedenen Sprachen unterschiedlich sein!
* Die **Meta-Beschreibung** sollte in verschiedenen Sprachen unterschiedlich sein!

## Tipps

- Benutzer können jede Sprache aus der Liste der installierten Sprachen verwenden, entweder indem sie diese im Benutzerprofil zugewiesen bekommen oder indem sie ein Menüpunkts-Layout - Neu/Bearbeiten - Benutzerformular im Frontend ausfüllen. Dies führt dazu, dass die Joomla!-Systemaufforderungen nur für diesen Benutzer in dieser Sprache generiert werden. Wenn ein Benutzer beispielsweise Spanisch als seine Sprache auswählt, wird das Suchmodul mit Aufforderungen auf Spanisch angezeigt.
- Die Auswahl dieses Benutzers wird nicht durch die für das Frontend festgelegte Standardsprache beeinflusst.
- Das Ändern der Sprache eines Benutzers oder der Standardsprache wirkt sich nicht auf die Artikel und andere Inhalte der Website aus.
- **Wichtig**: Lösche nicht die Standardsprachdateien (z. B. per FTP). Dies führt zu Fehlern sowohl im Frontend als auch im Backend.
- Zusätzliche Sprachen können über den Bildschirm *Erweiterungen - Installieren* hinzugefügt werden.
- Falls gewünscht, kann die Frontend-Seite in einer Sprache und die Backend-Administrationsseiten in einer anderen Sprache angezeigt werden. Außerdem können einzelne Artikel so konfiguriert werden, dass sie in der erweiterten Parameterleiste beim Bearbeiten des Artikels eine andere Sprache verwenden.
