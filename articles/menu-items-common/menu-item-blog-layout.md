<!-- Filename: Help6.x:Menu_Item_Blog_Layout / Display title: Menüpunkt Blog Layout -->

## Beschreibung

Alle Menüeinträge haben ein ähnliches Layout, aber einige Formularfelder und Tabs ändern sich je nach Typ. Diese Seite beschreibt den **Blog Layout**-Tab, der für Beitragslayouts verwendet wird.

## So greifen Sie darauf zu

* Wählen Sie ein beliebiges **Website-Menü** aus dem Administrator-Menü aus.
* Wählen Sie die Schaltfläche **Neu** in der Symbolleiste.
* Wählen Sie einen Komponententyp-Menüpunkt, der einen *Blog Layout*-Tab enthält.
* Wählen Sie den **Blog Layout**-Tab.

## Screenshot

![Menüpunkt Blog Layout Tab](../../../de/images/menu-items-common/articles-category-blog-blog-layout-tab.png)

## Formularfelder

### Blog Layout Tab

- **\# Einleitende Artikel** Anzahl der Artikel, die unter Verwendung der vollen Breite des Hauptanzeigebereichs angezeigt werden. `0` bedeutet, dass keine Artikel mit voller Breite angezeigt werden. Wenn ein Artikel einen *Weiterlesen...*-Abschnitt hat, wird nur der Teil des Textes vor diesem Abschnitt (der Einleitungstext) angezeigt.
- **Einleitende Artikelklasse** Sie können eine beliebige CSS-Klasse für eigene Stilideen hinzufügen. Fügen Sie eine obere Umrandung mit der Klasse "boxed" hinzu. Für die Bildpositionierung verwenden Sie beispielsweise "image-start", "image-end". Fügen Sie "image-alternate" für abwechselnde Anordnung der Einleitungsbilder hinzu.
- **\# Einführungsartikel** Bestimmt die Anzahl der Artikel, die nach dem einleitenden Artikel angezeigt werden. Diese Artikel werden in der unten festgelegten Anzahl von Spalten angezeigt. Wenn ein Artikel einen *Weiterlesen...*-Abschnitt hat, wird nur der Text vor dem Abschnitt (Einleitungstext) angezeigt, gefolgt von einem *Weiterlesen...*-Link. Die Reihenfolge, in der die Artikel angezeigt werden, wird durch die unten stehenden Parameter *Kategoriebestellung* und *Artikelbestellung* bestimmt.
- **Artikelklasse** Sie können eine beliebige CSS-Klasse für eigene Stilideen hinzufügen. Fügen Sie eine obere Umrandung mit der Klasse "boxed" hinzu. Für die Bildpositionierung verwenden Sie beispielsweise "image-start", "image-end". Fügen Sie "image-alternate" für abwechselnde Anordnung der Einleitungsbilder hinzu.
- **\# Spalten** Die Anzahl der Spalten, die im Bereich der Einführungsartikel verwendet werden sollen. Dies liegt normalerweise zwischen 1 und 3 (abhängig von Ihrem Template). Bei 1 werden die Einführungsartikel in voller Breite des Anzeigebereichs wie die einleitenden Artikel dargestellt.
- **Mehrspaltige Richtung** Bei mehrspaltigen Blog-Layouts, ob die Artikel spaltenweise nach unten oder quer über die Spalten angeordnet werden sollen.
  - *Nach unten* Artikel werden in der ersten Spalte nach unten und dann in die nächste Spalte geordnet.
  - *Quer* Artikel werden quer über die Spalten und dann wieder in die erste Spalte geordnet.
- **\# Links** Die Anzahl der Links, die im Link-Bereich der Seite angezeigt werden. Diese Links ermöglichen es dem Benutzer, auf zusätzliche Artikel zuzugreifen, falls mehr Artikel vorhanden sind, als auf der ersten Seite des Blog-Layouts Platz finden.
- **Hervorgehobene Artikel**
  - *Anzeigen* Zeigt sowohl hervorgehobene als auch nicht hervorgehobene Artikel an.
  - *Verbergen* Zeigt nur nicht hervorgehobene Artikel an.
  - *Nur* Zeigt nur hervorgehobene Artikel an.
- **Verknüpftes Einleitungsbild** Wenn *Ja*, wird beim Klicken auf das Einleitungsbild der Artikel angezeigt.
- **Unterkategorien einbeziehen**
  - *Keine* Es werden nur Artikel aus der aktuellen Kategorie angezeigt.
  - *Alle* Es werden alle Artikel aus der aktuellen Kategorie und allen Unterkategorien angezeigt.
  - *1-5* Es werden alle Artikel aus der aktuellen Kategorie und den Unterkategorien bis einschließlich dieser Ebene angezeigt.
- **Kategoriebestellung**
  - *Keine Bestellung* Artikel werden nur nach der Artikelbestellung geordnet, ohne Berücksichtigung der Kategorie.
  - *Titel alphabetisch* Kategorien werden in alphabetischer Reihenfolge angezeigt (A bis Z).
  - *Titel umgekehrt alphabetisch* Kategorien werden in umgekehrter alphabetischer Reihenfolge angezeigt (Z bis A).
  - *Kategoriebestellung* Kategorien werden entsprechend der in *Beiträge: Kategorien* eingegebenen Reihenfolge geordnet.
- **Artikelbestellung**
  - *Hervorgehobene Artikelbestellung* Artikel werden entsprechend der in *Beiträge: Hervorgehoben* eingegebenen Reihenfolge geordnet.
  - *Neueste zuerst* Artikel werden vom neuesten zum ältesten angezeigt.
  - *Älteste zuerst* Artikel werden vom ältesten zum neuesten angezeigt.
  - *Titel alphabetisch* Artikel werden nach Titel in alphabetischer Reihenfolge (A bis Z) angezeigt.
  - *Titel umgekehrt alphabetisch* Artikel werden nach Titel in umgekehrter alphabetischer Reihenfolge (Z bis A) angezeigt.
  - *Autor alphabetisch* Artikel werden nach Autor in alphabetischer Reihenfolge (A bis Z) angezeigt.
  - *Autor umgekehrt alphabetisch* Artikel werden nach Autor in umgekehrter alphabetischer Reihenfolge (Z bis A) angezeigt.
  - *Meiste Klicks* Artikel werden nach der Anzahl der Klicks sortiert, beginnend mit dem Artikel mit den meisten Klicks.
  - *Wenigste Klicks* Artikel werden nach der Anzahl der Klicks sortiert, beginnend mit dem Artikel mit den wenigsten Klicks.
  - *Zufällige Reihenfolge* Artikel werden in zufälliger Reihenfolge angezeigt.
  - *Artikelbestellung* Artikel werden gemäß der in *Beiträge* eingegebenen Reihenfolge geordnet.
  - *Umgekehrte Artikelbestellung* Artikel werden in umgekehrter Reihenfolge gemäß der in *Beiträge* eingegebenen Reihenfolge geordnet.
- **Datum zur Bestellung** Das Datum, das verwendet wird, wenn Artikel nach Datum sortiert werden.
  - *Erstellt* Verwendet das Erstellungsdatum des Artikels.
  - *Geändert* Verwendet das Änderungsdatum des Artikels.
  - *Veröffentlicht* Verwendet das Veröffentlichungsdatum des Artikels.
  - *Unveröffentlicht* Verwendet das Datum der Aufhebung der Veröffentlichung des Artikels.
- **Seitennummerierung** Die Seitennummerierung zeigt Seitenlinks am unteren Rand der Seite an, die es dem Benutzer ermöglichen, zu weiteren Seiten zu navigieren. Diese werden benötigt, wenn die Artikel nicht auf eine Seite passen.
  - *Verbergen* Seitennummerierungslinks werden nicht angezeigt. *Hinweis:* Benutzer können nicht zu weiteren Seiten navigieren.
  - *Anzeigen* Seitennummerierungslinks werden bei Bedarf angezeigt.
  - *Automatisch* Seitennummerierungslinks werden bei Bedarf angezeigt.
- **Seitennummerierungszusammenfassung** Zeigt die aktuelle Seitenzahl und die Gesamtzahl der Seiten (zum Beispiel *Seite 1 von 2*) am unteren Rand jeder Seite an.
