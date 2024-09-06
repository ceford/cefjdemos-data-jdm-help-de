<!-- Filename: Help4.x:Menu_Item:_Category_Blog / Display title: Menüeintrag: Kategorieblog -->
<!-- Dateiname: Help4.x:Menu_Element:_Kategorie_Blog / Titel anzeigen: Kategorie Blog -->

## Beschreibung

Ein *Kategorie-Blog* Menüpunkt zeigt typischerweise einen oder zwei führende Artikel an, die die volle Breite des Inhaltsbereichs einnehmen. Darunter folgen weitere Artikel in ein, zwei oder drei Spalten sowie zusätzliche Links zu weiteren Artikeln derselben Kategorie.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Symbolleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Details-Tab](jdocmanual?article=help/menu-items-common/menu-item-details).
* [Der Optionen-Tab](jdocmanual?article=help/menu-items-common/menu-item-article-options).
* [Der Integration-Tab](jdocmanual?article=help/menu-items-common/menu-item-integration).
* [Der Linktyp-Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [Der Seitendarstellung-Tab](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [Der Metadaten-Tab](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [Der Zuordnungen-Tab](jdocmanual?article=help/common-elements/edit-associations).
* [Der Modulzuweisung-Tab](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Zugriff

Wählen Sie **Menüs → \[Name des Menüs\]** aus dem Administrationsmenü.

Um einen Menüpunkt hinzuzufügen:

1. Wählen Sie die Schaltfläche **Neu** in der Symbolleiste.
2. Wählen Sie die Schaltfläche **Auswählen** beim *Menüpunkt-Typ*.
3. Wählen Sie den Eintrag **Beiträge** im Popup-Dialog.
4. Wählen Sie den Eintrag **Kategorie-Blog**.

Um einen Menüpunkt zu bearbeiten:

- Wählen Sie einen **Titel** aus der Liste.

## Screenshot

![Menüpunkt Kategorie-Blog](../../../de/images/menu-items/articles-category-blog-details-tab.png)

## Formularfelder

- **Titel** Der Titel, der für diesen Menüpunkt angezeigt wird.
- **Alias** Der interne Name des Menüpunkts. Normalerweise kann dieses Feld leer gelassen werden, und Joomla generiert automatisch einen Alias basierend auf dem Titel in Kleinbuchstaben und mit Bindestrichen anstelle von Leerzeichen.

### Details-Tab

#### Linke Spalte

- **Menüpunkt-Typ** Der bei der Erstellung dieses Menüpunkts gewählte Menüpunkt-Typ. Dies kann einer der Joomla-Kernmenütypen oder ein Menütyp einer installierten Erweiterung sein.
- **Kategorie wählen** Die Artikel innerhalb dieser Kategorie werden angezeigt.
- **Tags** Optional kann die Anzeige auf Artikel mit den ausgewählten Tags eingeschränkt werden.
- **Link** Der systemgenerierte Link für diesen Menüpunkt. Dieses Feld kann nicht geändert werden und dient nur zur Information.
- **Ziel-Fenster** Auswahl aus der Dropdown-Liste.
- **Vorlagen-Stil** Auswahl aus der Dropdown-Liste.

#### Rechte Spalte

- **Menü** Zeigt, in welchem Menü der Link erscheinen wird.

### Kategorie-Tab

Diese Parameter steuern die Anzeige der Kategoriedaten auf der Seite, die durch diesen Menüpunkt-Typ erzeugt wird.

![Kategorie-Tab für Menüelement](../../../de/images/menu-items/articles-category-blog-category-tab.png)

- **Kategorietitel** Zeigt den Titel der Kategorie an oder blendet ihn aus.
- **Kategoriebeschreibung** Zeigt die Beschreibung der Kategorie an oder blendet sie aus.
- **Kategorie-Bild** Zeigt das Bild der Kategorie an oder blendet es aus.
- **Unterkategorien-Ebenen** Bestimmt, wie viele Ebenen von Unterkategorien angezeigt werden.
- **Leere Kategorien** Zeigt Kategorien an oder blendet sie aus, die keine Artikel oder Unterkategorien enthalten.
- **Keine Artikel-Meldung** Zeigt oder blendet eine Nachricht *Es gibt keine Artikel in dieser Kategorie* ein.
- **Unterkategorien-Überschrift** Zeigt oder blendet die Unterkategorien als Unterüberschrift auf der Seite ein.
- **Unterkategorien-Beschreibungen** Zeigt oder blendet die Beschreibungen der Unterkategorien ein.
- **\# Artikel in der Kategorie** Zeigt oder blendet die Anzahl der Artikel in jeder Kategorie ein.
- **Tags** Zeigt oder blendet die Tags der Kategorie ein.

### Blog-Layout-Tab

Diese Parameter steuern das Layout der Seite, die durch diesen Menüpunkt-Typ erzeugt wird.

![Blog-Layout-Tab für Menüelement](../../../de/images/menu-items/articles-category-blog-blog-layout-tab.png)

- **\# Führende Artikel** Die Anzahl der Artikel, die in voller Breite im Hauptanzeigebereich angezeigt werden. `0` bedeutet, dass keine Artikel in voller Breite angezeigt werden. Wenn ein Artikel einen *Weiterlesen...*-Trenner enthält, wird nur der Teil des Textes vor dem Trenner (der Einführungstext) angezeigt.
- **Führender Artikel CSS-Klasse** Sie können eine beliebige CSS-Klasse für eigene Gestaltungsideen hinzufügen. Beispiel: boxed für eine obere Umrandung. Für die Position des Bildes verwenden Sie z. B. image-start oder image-end. Fügen Sie image-alternate für eine wechselnde Anordnung von Vorschaubildern hinzu.
- **\# Einleitungsartikel** Bestimmt die Anzahl der Artikel, die nach dem führenden Artikel angezeigt werden. Diese Artikel werden in der im Parameter „Spalten“ festgelegten Anzahl von Spalten angezeigt. Wenn ein Artikel einen *Weiterlesen...*-Trenner enthält, wird nur der Text vor dem Trenner (Einleitungstext) angezeigt, gefolgt von einem *Weiterlesen...*-Link. Die Reihenfolge, in der die Artikel angezeigt werden, wird durch die Parameter „Kategorien-Reihenfolge“ und „Artikel-Reihenfolge“ unten festgelegt.
- **Artikel CSS-Klasse** Sie können eine beliebige CSS-Klasse für eigene Gestaltungsideen hinzufügen.
- **\# Spalten** Die Anzahl der Spalten, die im Bereich der Einleitungsartikel verwendet werden sollen. Normalerweise liegt dies zwischen 1 und 3 (abhängig vom verwendeten Template). Wenn 1 verwendet wird, werden die Einleitungsartikel über die gesamte Breite des Anzeigebereichs angezeigt, genau wie die führenden Artikel.
- **Mehrspaltige Richtung** In mehrspaltigen Blog-Layouts kann gewählt werden, ob die Artikel nach unten oder über die Spalten hinweg angeordnet werden sollen.
  - *Nach unten* Artikel werden in der ersten Spalte nach unten angeordnet und wechseln dann zur nächsten Spalte.
  - *Über die Spalten* Artikel werden über die Spalten hinweg angeordnet und kehren dann zur ersten Spalte zurück.
- **\# Links** Die Anzahl der Links, die im Link-Bereich der Seite angezeigt werden. Diese Links ermöglichen es dem Benutzer, zu zusätzlichen Artikeln zu verlinken, wenn es mehr Artikel gibt, als auf die erste Seite des Blog-Layouts passen.
- **Hervorgehobene Artikel**
  - *Anzeigen* Zeigt hervorgehobene und nicht hervorgehobene Artikel an.
  - *Verbergen* Zeigt nur nicht hervorgehobene Artikel an.
  - *Nur* Zeigt nur hervorgehobene Artikel an.
- **Verlinktes Einleitungsbild** Wenn auf *Ja* gesetzt, zeigt ein Klick auf das Einleitungsbild den Artikel an.
- **Unterkategorien einbeziehen**
  - *Keine* Nur Artikel aus der aktuellen Kategorie werden angezeigt.
  - *Alle* Alle Artikel aus der aktuellen Kategorie und allen Unterkategorien werden angezeigt.
  - *1-5* Alle Artikel aus der aktuellen Kategorie und Unterkategorien bis einschließlich dieser Ebene werden angezeigt.
- **Kategorien-Reihenfolge**
  - *Keine Reihenfolge* Artikel werden nur nach der Artikel-Reihenfolge und ohne Berücksichtigung der Kategorie sortiert.
  - *Alphabetisch* Kategorien werden alphabetisch (A bis Z) angezeigt.
  - *Alphabetisch rückwärts* Kategorien werden in umgekehrter alphabetischer Reihenfolge (Z bis A) angezeigt.
  - *Kategorien-Reihenfolge* Kategorien werden gemäß der Reihenfolge sortiert, die in *Beiträge: Kategorien* festgelegt wurde.
- **Artikel-Reihenfolge**
  - *Reihenfolge der hervorgehobenen Artikel* Artikel werden gemäß der Reihenfolge sortiert, die in *Beiträge: Hervorgehoben* festgelegt wurde.
  - *Neueste zuerst* Artikel werden von den neuesten bis zu den ältesten angezeigt.
  - *Älteste zuerst* Artikel werden von den ältesten bis zu den neuesten angezeigt.
  - *Alphabetisch* Artikel werden alphabetisch nach Titel sortiert (A bis Z).
  - *Alphabetisch rückwärts* Artikel werden alphabetisch rückwärts nach Titel sortiert (Z bis A).
  - *Autor alphabetisch* Artikel werden alphabetisch nach Autor sortiert (A bis Z).
  - *Autor alphabetisch rückwärts* Artikel werden alphabetisch rückwärts nach Autor sortiert (Z bis A).
  - *Meiste Klicks* Artikel werden nach der Anzahl der Klicks sortiert, beginnend mit den meisten Klicks.
  - *Wenigste Klicks* Artikel werden nach der Anzahl der Klicks sortiert, beginnend mit den wenigsten Klicks.
  - *Zufällige Reihenfolge* Artikel werden in zufälliger Reihenfolge angezeigt.
  - *Artikel-Reihenfolge* Artikel werden gemäß der Reihenfolge sortiert, die in *Beiträge*
  