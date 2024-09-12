<!-- Filename: Help4.x:Smart_Search:_Indexed_Content / Display title: Suchindex: Indizierte Inhalte -->

## Beschreibung

Die Seite *Smart Search: Indizierte Inhalte* zeigt eine Liste aller Inhalte, die in Smart Search indiziert wurden.

### Gemeinsame Elemente

Einige Elemente dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Listenfilter](jdocmanual?article=help/common-elements/list-filters).
* [Listenspaltenüberschriften](jdocmanual?article=help/common-elements/list-column-headers).
* [Listenreihenfolge](jdocmanual?article=help/common-elements/list-ordering).
* [Listenpaginierung](jdocmanual?article=help/common-elements/list-pagination).

### Tutorial

* Wenn Sie neu bei Smart Search sind, sollten Sie den 
  [Smart Search Schnellstart-Leitfaden](https://docs.joomla.org/Smart_Search_quickstart_guide) lesen.

## Zugriff

- Wählen Sie **Komponenten → Smart Search → Index** aus dem Administrator-Menü.

## Screenshot

![Smart Search indizierte Inhalte](../../../de/images/smart-search/smart-search-indexed-content.png)

## Index erstellen

Wählen Sie die **Index**-Schaltfläche in der Werkzeugleiste. Dies öffnet ein Fenster, das den Fortschritt des Indizierungsvorgangs anzeigt. Die Indizierung kann je nach Anzahl der Inhaltsobjekte auf der Website und der darin enthaltenen Suchwörter und -phrasen einige Zeit in Anspruch nehmen. Ein Fortschrittsbalken zeigt an, wie viel des Indizierungsprozesses bereits abgeschlossen wurde. Schließen Sie dieses Fenster nicht, bevor der Vorgang abgeschlossen ist. Bei Websites mit einer großen Menge an Inhalten kann dies lange dauern (mehrere Minuten).

Sie sollten den Indexer ausführen, nachdem neue Inhalte zur Website hinzugefügt wurden, die die Smart Search-Funktion nicht automatisch erkennt. Beispielsweise beim Batch-Import von Inhalten, bei dem der Importer nicht automatisch Smart Search dazu veranlasst, jeden neuen Inhalt zu indizieren. HINWEIS: Der Smart Search Indexer kann auch über die Kommandozeile (CLI) ausgeführt werden, falls erforderlich. Siehe Einrichtung der automatischen Smart Search-Indizierung.

## Werkzeugleiste

- **Index** Führt den Smart Search Indexer aus. Ein kleines Popup-Fenster erscheint mit einem Fortschrittsbalken, der den Fortschritt des Indizierungsprozesses anzeigt.
- **Aktionen** Wählen Sie ein Kontrollkästchen aus, um die Dropdown-Liste zu aktivieren.
  - **Veröffentlichen** Macht die ausgewählten Elemente für Besucher der Website verfügbar.
  - **Verbergen** Macht die ausgewählten Elemente für Besucher der Website nicht verfügbar.
- **Löschen** Löscht die ausgewählten Inhaltselemente. Dies betrifft nur den Index und nicht das eigentliche Inhaltselement.
- **Wartung**
  - **Optimieren**
  - **Index leeren** Löscht den Smart Search Index, indem alle Index-Tabellen geleert werden. Um Smart Search weiter zu verwenden, wählen Sie nach dem Leeren die Index-Schaltfläche in der Werkzeugleiste. WARNUNG: Das Leeren des Index löscht auch die Inhaltsfilter. Diese müssen nach einem Löschzyklus manuell neu eingegeben werden.
- **Statistiken** Zeigt einige grundlegende Statistiken zu Smart Search an.

## Tipps

- Wenn Sie den Indexer ausführen und einen *undefined null*-Fehler erhalten, überprüfen Sie die Berechtigungen des Joomla-`/logs`-Verzeichnisses. Der Webserver benötigt Schreibrechte für dieses Verzeichnis, damit der Indexer funktioniert.
- Wenn die Liste leer ist, stellen Sie sicher, dass das Smart Search-Plugin aktiviert wurde.
