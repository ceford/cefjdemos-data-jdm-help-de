<!-- Filename: Help4.x:Maintenance:_Global_Check-in / Display title: Wartung: Globales Freigeben -->

## Beschreibung

Ein Datensatz, beispielsweise ein Artikel, kann von einem Benutzer gesperrt werden, der ihn zur Bearbeitung geöffnet hat und die Bearbeitungssitzung nicht beendet hat. In solchen Fällen können andere Benutzer den Datensatz nicht bearbeiten. Durch die Durchführung eines globalen Check-ins werden alle solchen Datensätze in ausgewählten Erweiterungstabellen freigegeben.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Listenfilter](jdocmanual?article=help/common-elements/list-filters).
* [Listenspaltenüberschriften](jdocmanual?article=help/common-elements/list-column-headers).
* [Listenpaginierung](jdocmanual?article=help/common-elements/list-pagination).

## Zugriff

- Wählen Sie **System → Wartungspanel → Globaler Check-in** aus dem Administrator-Menü.

## Screenshot

![Wartung globaler Check-in](../../../de/images/maintenance/maintenance-global-check-in.png)

## Tipps

- Joomla-Artikel werden in der Tabelle `#__content` gespeichert (`#_` ist ein Platzhalter für das Tabellenpräfix).
- Stellen Sie sicher, dass niemand gerade Artikel bearbeitet, bevor Sie einen globalen Check-in durchführen. Beim globalen Check-in werden *alle* Artikel eingecheckt, einschließlich derjenigen, die gerade bearbeitet werden.
