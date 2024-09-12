<!-- Filename: Help4.x:Smart_Search:_Content_Maps / Display title: Suchindex: Inhaltsgruppen -->

## Beschreibung

Diese Seite zeigt die Inhaltszuordnungen, die sich derzeit im Smart Search-Index befinden. Inhaltszuordnungen ermöglichen es Ihnen, Ihre indizierten Inhalte (Artikel usw.) mit zugehörigen Metainformationen wie der Kategorie, in der sie sich befinden, zu verknüpfen. Jedes Inhaltselement, das von Smart Search indiziert wird, wird zu einer oder mehreren Inhaltszuordnungen hinzugefügt, die als Filter beim Durchsuchen des Indexes verwendet werden können.

Inhaltszuordnungen sind in zwei Teile unterteilt:

- **Zuordnungsgruppe**: Diese sind Super-Container für eine bestimmte Art von Information. Zum Beispiel könnte eine Zuordnungsgruppe *Typ*, *Kategorie*, *Ereignis*, *Sprache* oder *Autor* sein.
- **Inhaltszuordnung**: Inhaltszuordnungen sind die tatsächlichen Werte der Metainformationen in einer bestimmten Zuordnungsgruppe. Die Inhaltszuordnungen sind beispielsweise die Namen der Kategorien oder Autoren.

Diese Zuordnungsgruppen und Inhaltszuordnungen bilden das erweiterte Suchfeld auf der Frontend-Seite. Für jede Zuordnungsgruppe kann es eine Dropdown-Auswahlliste geben, und die Inhaltszuordnungen werden als Werte in die jeweilige Liste eingefügt. Fortgeschrittene Website-Entwickler können die Standardlayouts überschreiben und Mehrfachauswahllisten oder Kontrollkästchen verwenden.

Es ist wichtig zu beachten, dass Zuordnungsgruppen und Inhaltszuordnungen aus verschiedenen Inhaltstypen in einer Liste zusammengeführt werden. Ein Joomla-Artikel in einer Kategorie namens *News* und ein Nachrichtenfeed oder Kontakt in einer Kategorie mit demselben Namen werden in derselben Inhaltszuordnung in derselben Zuordnungsgruppe zusammengefasst. Dies ähnelt dem Markieren verschiedener Inhaltstypen mit demselben Label. Der Effekt ist, dass der Besucher Ihrer Website nicht wissen muss, wie Ihre Inhalte klassifiziert sind, um die richtigen Filter zu setzen und sie zu finden.

Der Inhaltszuordnungsbildschirm zeigt alle Zuordnungsgruppen im Smart Search-Index zusammen mit einer Zahl, die die Anzahl der Inhaltszuordnungen innerhalb dieser Zuordnungsgruppe und die Elemente innerhalb einer Inhaltszuordnung anzeigt. Durch Klicken auf die Zahl einer Zuordnungsgruppe können Sie die Inhaltszuordnungen innerhalb dieser Gruppe sowie die Anzahl der Inhaltselemente anzeigen, die zu dieser Inhaltszuordnung gehören. Ein Inhaltselement kann mehreren Inhaltszuordnungen innerhalb einer Zuordnungsgruppe sowie mehreren Zuordnungsgruppen zugeordnet sein.

### Allgemeine Elemente

Einige Elemente dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Listenfilter](jdocmanual?article=help/common-elements/list-filters).
* [Listenspalten-Header](jdocmanual?article=help/common-elements/list-column-headers).
* [Listenreihenfolge](jdocmanual?article=help/common-elements/list-ordering).
* [Seitennummerierung in Listen](jdocmanual?article=help/common-elements/list-pagination).

### Tutorial

* Wenn Sie neu bei Smart Search sind, sollten Sie den [Smart Search Schnellstart-Guide](https://docs.joomla.org/Smart_Search_quickstart_guide) lesen.

## Zugriff

- Wählen Sie **Komponenten → Smart Search → Inhaltszuordnungen** aus dem Administrator-Menü.

## Screenshot

![smart search content maps](../../../de/images/smart-search/smart-search-content-maps.png)

## Spaltenüberschriften

- **Status** Der Status des Inhaltselements innerhalb von Smart Search. Eine Statusänderung betrifft nur die Verfügbarkeit des Inhaltselements in den Suchergebnissen und nicht das Inhaltselement selbst.
- **Titel** Der Titel der Zuordnungsgruppe oder der Inhaltszuordnung.
- **Zuordnungen** Die Anzahl der Zuordnungen innerhalb der Zuordnungsgruppe. Durch Auswahl der Zahl werden die Zuordnungen in der Zuordnungsgruppe angezeigt.
- **Veröffentlichte indizierte Inhalte** Die Anzahl der veröffentlichten Inhaltselemente in der Zuordnungsgruppe. Durch Auswahl der Zahl werden die veröffentlichten Inhaltselemente innerhalb der Zuordnungsgruppe angezeigt.
- **Unveröffentlichte indizierte Inhalte** Die Anzahl der unveröffentlichten Inhaltselemente in der Zuordnungsgruppe. Durch Auswahl der Zahl werden die unveröffentlichten Inhaltselemente innerhalb der Zuordnungsgruppe angezeigt.

## Werkzeugleiste

- **Aktionen** Zeigt eine Liste von Aktionen für ausgewählte Elemente. Aktivieren Sie ein oder mehrere Kontrollkästchen, um die Liste zu aktivieren.
  - **Veröffentlichen** Macht die ausgewählten Zuordnungsgruppen oder Inhaltszuordnungen für Besucher Ihrer Website verfügbar.
  - **Verbergen** Macht die ausgewählten Zuordnungsgruppen oder Inhaltszuordnungen für Besucher Ihrer Website nicht verfügbar. Eine unveröffentlichte Zuordnungsgruppe wird nicht als Auswahlliste im Frontend angezeigt. Eine unveröffentlichte Inhaltszuordnung wird nicht in der Auswahlliste der Zuordnungsgruppe angezeigt, in der sie vorkommt. Das erneute Indizieren ändert den Veröffentlichungsstatus der Zuordnungsgruppen oder Inhaltszuordnungen nicht.
- **Löschen** Löscht die ausgewählten Zuordnungsgruppen oder Inhaltszuordnungen. Funktioniert mit einer oder mehreren ausgewählten Zuordnungsgruppen oder Inhaltszuordnungen. Sie können gelöschte Zuordnungsgruppen oder Inhaltszuordnungen wiederherstellen, indem Sie den Smart Search Indexer erneut ausführen.
- **Statistiken** Zeigt einige grundlegende Statistiken zu Smart Search an.
