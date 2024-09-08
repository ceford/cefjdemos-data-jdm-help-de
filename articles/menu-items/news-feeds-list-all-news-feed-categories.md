<!-- Filename: Help4.x:Menu_Item:_List_All_News_Feed_Categories / Display title: Alle News-Feed-Kategorien auflisten -->

## Beschreibung

Der Menüpunkt-Typ **Alle Kategorien in einem News-Feed-Kategoriebbaum auflisten** wird verwendet, um eine Liste aller RSS-News-Feed-Kategorien anzuzeigen. Die Kategorien werden in einer hierarchischen Liste dargestellt. Abhängig von den ausgewählten Optionen für dieses Layout kann ein Kategorietitel ausgewählt werden, um die News-Feeds in dieser Kategorie anzuzeigen.

### Allgemeine Elemente

Einige Aspekte dieser Seite werden in separaten Hilfe-Artikeln behandelt:

* [Symbolleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Details-Tab](jdocmanual?article=help/menu-items-common/menu-item-details).
* [Der Kategorie-Tab](jdocmanual?article=help/menu-items-common/menu-item-category).
* [Der Linktyp-Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [Der Seitendarstellungs-Tab](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [Der Metadaten-Tab](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [Der Verknüpfungs-Tab](jdocmanual?article=help/common-elements/edit-associations).
* [Der Modulzuweisungs-Tab](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## So greifen Sie darauf zu

Um einen neuen Menüpunkt **Alle Kategorien in einem News-Feed-Kategoriebbaum auflisten** zu erstellen:

- Wählen Sie **Menüs → \[Name des Menüs\]** aus dem Administrator-Menü
  (zum Beispiel **Menüs → Hauptmenü**). Dann...
  - Wählen Sie die Schaltfläche **Neu** in der Symbolleiste. Dann...
  - Wählen Sie die Schaltfläche **Menüpunkt-Typ auswählen**.
  - Im Modal-Dialog wählen Sie den Punkt **News Feeds** aus, um eine Liste zu öffnen, und dann den Menüpunkt **Alle News-Feed-Kategorien auflisten**.

Um einen bestehenden Menüpunkt **Alle News-Feed-Kategorien auflisten** zu bearbeiten:

- Wählen Sie den Titel in der Liste *Menüs: Einträge*.

## Screenshot

![Menüpunkt Alle News-Feed-Kategorien Details-Tab](../../../de/images/menu-items/news-feeds-list-all-categories-details-tab.png)

## Formularfelder

### Kategorien-Tab

![Menüpunkt Alle News-Feed-Kategorien Kategorien-Tab](../../../de/images/menu-items/news-feeds-list-all-categories-tree-categories-tab.png)

- **Beschreibung der obersten Kategorie** Zeigt oder verbirgt die Beschreibung der obersten Kategorie. Beachten Sie, dass diese Beschreibung für dieses Layout durch eine *alternative Beschreibung* überschrieben werden kann.
- **Alternative Beschreibung** Wenn Sie Text in dieses Feld eingeben, wird er die Beschreibung der obersten Kategorie ersetzen, falls diese vorhanden ist. Wenn die Option "Beschreibung der obersten Kategorie" auf *Anzeigen* gesetzt ist, wird diese Beschreibung anstelle der normalen Kategoriebeschreibung angezeigt.
- **Unterkategorien-Ebenen** Die Anzahl der Unterkategorien-Ebenen, die im Layout angezeigt werden. Wählen Sie *Alle*, um alle Ebenen in der Unterkategorie-Hierarchie anzuzeigen.
- **Leere Kategorien** Zeigt oder verbirgt Kategorien, die keine Inhalte oder Unterkategorien enthalten.
- **Unterkategorien-Beschreibungen** Zeigt oder verbirgt die Beschreibung der Unterkategorien.
- **\# Feeds in Kategorie** Zeigt oder verbirgt die Anzahl der News-Feeds in einer Kategorie.

### Listenlayouts-Tab

![Menüpunkt Alle News-Feed-Kategorien Listenlayouts-Tab](../../../de/images/menu-items/news-feeds-list-all-categories-tree-list-layouts-tab.png)

- **Filterfeld** Zeigt oder verbirgt ein Filterfeld für die Liste.
- **Anzeigeauswahl** Zeigt oder verbirgt die Steuerung *Anzahl anzeigen*, die es dem Benutzer ermöglicht, die Anzahl der anzuzeigenden Elemente in der Liste auszuwählen.
- **Tabellenüberschriften** Zeigt oder verbirgt Tabellenüberschriften über einer Liste.
- **\# Artikel** Zeigt oder verbirgt die Anzahl der Artikel in jedem News-Feed. Dieser Wert kann in jedem einzelnen News-Feed überschrieben werden.
- **Feed-Links** Zeigt oder verbirgt die URL-Links der Feeds.
- **Seitennummerierung** Verbirgt oder zeigt die Unterstützung für die Seitennummerierung. Die Seitennummerierung bietet Seitenlinks am unteren Rand der Seite, mit denen der Benutzer zu weiteren Seiten navigieren kann. Diese sind erforderlich, wenn die aufgelisteten Elemente nicht auf eine Seite passen.
    Die folgenden Optionen sind verfügbar:
    - *Global verwenden:* Verwendet den Standardwert aus dem Optionen-Bildschirm der Komponente.
    - *Automatisch:* Seitennummerierungs-Links werden bei Bedarf angezeigt.
    - *Anzeigen:* Seitennummerierungs-Links werden angezeigt, wenn erforderlich.
    - *Ausblenden:* Seitennummerierungs-Links werden nicht angezeigt. Hinweis: In diesem Fall können Benutzer nicht zu weiteren Seiten navigieren.
- **Seitennummerierungs-Ergebnisse** Zeigt oder verbirgt die aktuelle Seitenzahl und die Gesamtzahl der Seiten (zum Beispiel *Seite 1 von 2*) am unteren Rand jeder Seite. *Global verwenden* verwendet den Standardwert aus den Komponenten-Optionen.

### Feedanzeige-Optionen-Tab

![Menüpunkt Alle News-Feed-Kategorien Kategorien-Tab](../../../de/images/menu-items/news-feeds-list-all-categories-tree-feed-display-options-tab.png)

- **Feed-Bild** Zeigt oder verbirgt das Bild der News-Feeds.
- **Feed-Beschreibung** Zeigt oder verbirgt die Beschreibung der News-Feeds.
- **Feed-Inhalt** Zeigt oder verbirgt den Inhalt der News-Feeds.
- **Zeichenanzahl** Anzahl der Zeichen, die angezeigt werden, wenn der Feed-Inhalt der News-Feeds auf Anzeigen gesetzt ist.

## Tipps

- Kategorien können in Ebenen verschachtelt werden, ähnlich wie Ordner auf einer Festplatte. Theoretisch gibt es keine absolute Begrenzung für die Anzahl der Ebenen. Es wird jedoch aus praktischen Gründen empfohlen, die Ebenen auf ein Minimum zu beschränken. Das Layout *Alle Kategorien anzeigen* funktioniert möglicherweise nicht korrekt, wenn die angezeigte Ebenenzahl größer als fünf ist.
- Wenn Sie Kategorietitel als verlinkbar festlegen, kann der Benutzer zur Kategorie navigieren. Wenn ein vorab vorhandener Menüpunkt für diese Kategorie existiert (zum Beispiel ein Menüpunkt der Kategorie-Liste), steuern die Optionen dieses Menüpunkts die Anzeige der Seite. Andernfalls steuern die für den aktuellen Menüpunkt *Alle Kategorien anzeigen* festgelegten Optionen die Anzeige der Seite.
- Sie können die Option, auf eine Liste zu verlinken, an zwei Stellen festlegen:
  - In *News Feed: Optionen* können Sie den Standardwert für alle Kategorien festlegen.
  - In *Kategorie: Bearbeiten* für eine News-Feed-Kategorie können Sie einen Wert für eine bestimmte Kategorie festlegen. Wenn dies festgelegt ist, wird der Standardwert überschrieben.
