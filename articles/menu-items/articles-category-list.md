<!-- Filename: Help4.x:Menu_Item:_Category_List / Display title: Menüeintrag: Kategorieliste -->

## Beschreibung

Der Menüpunkt "Kategorie Liste" wird verwendet, um Artikel, die zu einer bestimmten Kategorie gehören, in einer Listenansicht anzuzeigen.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Details-Tab](jdocmanual?article=help/menu-items-common/menu-item-details).
* [Der Integration-Tab](jdocmanual?article=help/menu-items-common/menu-item-integration).
* [Der Link-Typ-Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [Der Seitendarstellung-Tab](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [Der Metadaten-Tab](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [Der Verknüpfungen-Tab](jdocmanual?article=help/common-elements/edit-associations).
* [Der Modulzuweisungs-Tab](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Zugriff

Wählen Sie **Menüs → \[Name des Menüs\]** aus dem Administrator-Menü.

So fügen Sie einen Menüpunkt hinzu:

1. Wählen Sie die Schaltfläche **Neu** in der Symbolleiste.
2. Wählen Sie die Schaltfläche **Auswählen** beim *Menüpunkt-Typ*.
3. Wählen Sie den Eintrag **Beiträge** im Popup-Dialog.
4. Wählen Sie den Punkt **Kategorie Liste**.

So bearbeiten Sie einen Menüpunkt:

- Wählen Sie einen **Titel** aus der Liste.

## Bildschirmfoto

![Menüpunkt Kategorie Liste](../../../de/images/menu-items/articles-category-list-details-tab.png)

## Formularfelder

- **Titel** Der Titel, der für diesen Menüpunkt angezeigt wird.
- **Alias** Der interne Name des Menüpunkts. Normalerweise können Sie dieses Feld leer lassen, und Joomla wird einen Standardwert aus dem Titel in Kleinbuchstaben und mit Bindestrichen anstelle von Leerzeichen einfügen.

### Details-Tab

#### Linke Spalte

- **Menüpunkt-Typ** Der Menüpunkt-Typ, der ausgewählt wurde, als dieser Menüpunkt erstellt wurde. Dies kann einer der Core-Menüpunkt-Typen oder ein Menüpunkt-Typ sein, der von einer installierten Erweiterung bereitgestellt wird.
- **Kategorie auswählen** Die Artikel, die sich in dieser Kategorie befinden, werden angezeigt.
- **Tags** Optional kann die Anzeige auf Artikel mit den ausgewählten Tags beschränkt werden.
- **Link** Der systemgenerierte Link für diesen Menüpunkt. Dieses Feld kann nicht geändert werden und dient nur zur Information.
- **Ziel-Fenster** Wählen Sie aus der Dropdown-Liste.
- **Template-Stil** Wählen Sie aus der Dropdown-Liste.

#### Rechte Spalte

- **Menü** Zeigt, in welchem Menü der Link angezeigt wird.

### Kategorie-Tab

Diese Parameter steuern, wie die Kategorieninformationen auf der durch diesen Menüpunkt-Typ erzeugten Seite angezeigt werden.

![Menüpunkt Kategorie Liste - Kategorie-Tab](../../../de/images/menu-items/articles-category-list-category-tab.png)

- **Kategorie-Titel** Den Titel der Kategorie anzeigen oder ausblenden.
- **Kategoriebeschreibung** Die Beschreibung der Kategorie anzeigen oder ausblenden.
- **Kategorie-Bild** Das Bild der Kategorie anzeigen oder ausblenden.
- **Unterkategorie-Ebenen** Steuert, wie viele Ebenen von Unterkategorien angezeigt werden.
- **Leere Kategorien** Leere Kategorien, die keine Artikel oder Unterkategorien enthalten, anzeigen oder ausblenden.
- **Keine Artikel-Nachricht** Eine Nachricht anzeigen oder ausblenden, wenn keine Artikel in der Kategorie vorhanden sind.
- **Unterkategorien-Überschrift** Die Unterkategorien als Unterüberschrift auf der Seite anzeigen oder ausblenden.
- **Unterkategorien-Beschreibungen** Die Beschreibungen der Unterkategorien anzeigen oder ausblenden.
- **\# Artikel in Kategorie** Die Anzahl der Artikel in jeder Kategorie anzeigen oder ausblenden.
- **Tags** Die Tags für die Kategorie anzeigen oder ausblenden.

### List Layouts-Tab

Diese Parameter steuern das Layout der Seite, die durch diesen Menüpunkt-Typ erzeugt wird.

![Menüpunkt Kategorie Liste - List Layouts-Tab](../../../de/images/menu-items/articles-category-list-list-layouts-tab.png)

- **Anzahl-Anzeige** Zeigt oder verbirgt die Steuerung zur Auswahl der Anzahl der anzuzeigenden Artikel.
- **Filterfeld** Zeigt oder verbirgt ein Textfeld im Frontend, in dem Benutzer Artikel filtern können.
  - *Ausblenden* Filterfeld nicht anzeigen.
  - *Titel* Nach Artikel-Titeln filtern.
  - *Autor* Nach Autorennamen filtern.
  - *Aufrufe* Nach der Anzahl der Aufrufe filtern.
  - *Tags* Nach Artikel-Tags filtern.
  - *Monat (veröffentlicht)* Nach Veröffentlichungsmonat filtern.
- **Tabellenüberschriften** Die Überschrift in der Artikelliste im Frontend anzeigen oder ausblenden.
- **Datum** Ein Datum in der Liste anzeigen.
  - *Ausblenden* Kein Datum anzeigen.
  - *Erstellt* Das Erstellungsdatum anzeigen.
  - *Geändert* Das Datum der letzten Änderung anzeigen.
  - *Veröffentlicht* Das Veröffentlichungsdatum anzeigen.
- **Datumsformat** Optionaler Format-String zur Steuerung des Datumsformats.
- **Aufrufe** Die Anzahl der Aufrufe von Artikeln anzeigen oder ausblenden.
- **Autor** Den Namen des Autors anzeigen oder ausblenden.
- **Kategorie-Reihenfolge**
  - *Keine Reihenfolge* Artikel werden nur nach der Artikelreihenfolge sortiert, unabhängig von der Kategorie.
  - *Titel alphabetisch* Kategorien werden alphabetisch (A bis Z) angezeigt.
  - *Titel umgekehrt alphabetisch* Kategorien werden in umgekehrter alphabetischer Reihenfolge (Z bis A) angezeigt.
  - *Kategorien-Reihenfolge* Kategorien werden entsprechend der in *Beiträge: Kategorien* eingegebenen Reihenfolge angezeigt.
- **Artikel-Reihenfolge**
  - *Reihenfolge vorgestellter Artikel* Artikel werden nach der in *Beiträge: Vorgestellt* angegebenen Reihenfolge sortiert.
  - *Neueste zuerst* Artikel werden von den neuesten zu den ältesten angezeigt.
  - *Älteste zuerst* Artikel werden von den ältesten zu den neuesten angezeigt.
  - *Titel alphabetisch* Artikel werden alphabetisch nach Titel (A bis Z) angezeigt.
  - *Titel umgekehrt alphabetisch* Artikel werden alphabetisch nach Titel (Z bis A) angezeigt.
  - *Autor alphabetisch* Artikel werden alphabetisch nach Autor (A bis Z) angezeigt.
  - *Autor umgekehrt alphabetisch* Artikel werden alphabetisch nach Autor (Z bis A) angezeigt.
  - *Meiste Aufrufe* Artikel werden nach der Anzahl der Aufrufe sortiert, beginnend mit den meisten.
  - *Wenigste Aufrufe* Artikel werden nach der Anzahl der Aufrufe sortiert, beginnend mit den wenigsten.
  - *Zufällige Reihenfolge* Artikel werden in zufälliger Reihenfolge angezeigt.
  - *Artikel-Reihenfolge* Artikel werden nach der in *Beiträge* eingegebenen Reihenfolge angezeigt.
  - *Umgekehrte Artikel-Reihenfolge* Artikel werden in umgekehrter Reihenfolge der in *Beiträge* eingegebenen Reihenfolge angezeigt.
- **Datum für Sortierung** Das Datum, das für die Sortierung der Artikel nach Datum verwendet wird.
  - *Erstellt* Verwendet das Erstellungsdatum des Artikels.
  - *Geändert* Verwendet das Datum der letzten Änderung des Artikels.
  - *Veröffentlicht* Verwendet das Datum der Veröffentlichung des Artikels.
- **Paginierung** Die Paginierung bietet Seitenlinks am Ende der Seite, mit denen der Benutzer zu weiteren Seiten navigieren kann. Diese werden benötigt, wenn die Artikel nicht auf eine Seite passen.
  - *Ausblenden* Paginierungs-Links werden nicht angezeigt. *Hinweis:* Benutzer können nicht zu weiteren Seiten navigieren.
  - *Anzeigen* Paginierungs-Links werden bei Bedarf angezeigt.
  - *Auto* Paginierungs-Links werden bei Bedarf automatisch angezeigt.
- **Paginierungszusammenfassung** Zeigt oder verbirgt die aktuelle Seitenzahl und die Gesamtseitenanzahl (z.B. "Seite 1 von 2") am Ende jeder Seite.
- **\# Artikel in der Liste** Anzahl der in der Liste angezeigten Artikel.
- **Vorgestellte Artikel**
  - *Anzeigen* Vorgestellte und nicht vorgestellte Artikel anzeigen.
  - *Ausblenden* Nur nicht vorgestellte Artikel anzeigen.
  - *Nur* Nur vorgestellte Artikel anzeigen.

## Tipps

- Das Layout der Kategorie-Liste ist eine bequeme Möglichkeit, ein kompaktes Verzeichnis von Artikeln in einer Kategorie anzuzeigen, das Filter- und Suchfunktionen enthalten kann.