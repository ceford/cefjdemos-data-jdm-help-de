<!-- Filename: Help4.x:Menus / Display title: Menüs -->

## Beschreibung

Menüs ermöglichen es einem Benutzer, auf der Website zu navigieren. Ein Menü ist ein Objekt, das ein oder mehrere Menüpunkte enthält. Jeder Menüpunkt verweist auf eine logische Seite der Website. Um das Menü auf der Seite zu platzieren, ist ein Menümodul erforderlich. Ein Menü kann mehr als ein Modul haben. Zum Beispiel kann ein Modul nur die Menüpunkte der ersten Ebene anzeigen, während ein zweites Modul die Menüpunkte der zweiten Ebene zeigt.

Die Menüliste bietet einen Überblick über die auf einer Joomla-Website verfügbaren Menüs. Sie zeigt Details zu jedem einzelnen Menü, wie die Anzahl der veröffentlichten, nicht veröffentlichten und in den Papierkorb verschobenen Elemente sowie die Namen der verknüpften Module.

Der Prozess, um ein Menü auf der Website hinzuzufügen, verläuft normalerweise wie folgt:

1.  Erstellen Sie ein neues Menü (mithilfe dieser Seite).
2.  Erstellen Sie einen oder mehrere neue Menüpunkte für das Menü. Jeder Menüpunkt hat einen spezifischen Menüpunkttyp.
3.  Erstellen Sie ein oder mehrere Menümodule, um das Menü auf der Website anzuzeigen.
    - Wählen Sie die Menüpunkte (Seiten) aus, auf denen das Modul angezeigt wird.

### Allgemeine Elemente

Einige Elemente dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Listenfilter](jdocmanual?article=help/common-elements/list-filters).
* [Listenüberschriften](jdocmanual?article=help/common-elements/list-column-headers).
* [Listenreihenfolge](jdocmanual?article=help/common-elements/list-ordering).
* [Listenpaginierung](jdocmanual?article=help/common-elements/list-pagination).

## Zugriff

- Wählen Sie **Menüs → Verwalten** aus dem Administratormenü.

## Screenshot

![Menü-Liste](../../../de/images/menus/menus-list.png)

## Spaltenüberschriften

- **Titel** Der Name des Menüs.
- **Menüpunkte** Ein Link zu den Menüpunkten des Menüs.
- **\# Veröffentlicht** Anzahl der veröffentlichten Menüpunkte in diesem Menü.
- **\# Unveröffentlicht** Anzahl der nicht veröffentlichten Menüpunkte in diesem Menü.
- **\# Im Papierkorb** Anzahl der Menüpunkte, die sich im Papierkorb befinden.
- **Verknüpfte Module** Eine Dropdown-Liste zeigt den Namen, die Zugriffsebene und die Template-Position aller mit dem Menü verknüpften Menümodule.

## Tipps
- Die nummerierten Schaltflächen führen zu einer gefilterten Liste der Menüpunkte für das entsprechende Menü.
- Ein Menü sollte einen kurzen, beschreibenden Titel haben, der sich für die Verwendung in Listen und Dropdown-Listen eignet.
- Die *Beschreibung* ist eine nützliche Erinnerung an den Zweck, für den das Menü erstellt wurde.
- Wenn ein Menü keine verknüpften Module hat, ist die Schaltfläche in der Spalte *Verknüpfte Module* ein Link zu einem *Modul für dieses Menü hinzufügen* Dialog.
- Wenn Sie ein bestehendes Menü löschen, vergessen Sie nicht, dass auch alle Menüpunkte des jeweiligen Menüs gelöscht werden. Es erscheint eine Warnmeldung:

  **Sind Sie sicher, dass Sie diese Menüs löschen möchten? Durch die Bestätigung werden die ausgewählten Menütypen, alle ihre Menüpunkte und die zugehörigen Menümodule gelöscht.**
- Das Hauptmenü enthält den Standard-Menüpunkt der Website. Es **sollte nicht gelöscht werden**! Der Standard-Menüpunkt definiert die Seite, die beim Aufruf der Domain-URL der Website, wie `www.example.com`, angezeigt wird. Die Website wird nicht funktionieren, wenn dieser gelöscht wird. Normalerweise ist dies der Menüpunkt *Startseite*, aber er kann auf jeden Menüpunkt gesetzt werden, einschließlich eines Menüpunktes in einem versteckten Menü. Wenn der Standard-Menüpunkt geändert wird, stellen Sie sicher, dass auch dieser Menüpunkt nicht gelöscht wird!