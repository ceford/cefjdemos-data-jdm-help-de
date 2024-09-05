<!-- Filename: Help4.x:Information:_Database / Display title: Wartung: Datenbank -->

## Beschreibung

Diese Seite überprüft, ob die Datenbanktabellenstruktur auf dem neuesten Stand ist, und versucht, gefundene Probleme zu beheben. Bei einem normalen Joomla-Update werden Änderungen an der Datenbanktabellenstruktur (auch `Schema` genannt) automatisch ausgeführt, um die Datenbankversion mit der Joomla-Version zu synchronisieren. Wenn ein Update manuell durchgeführt wird oder ein Teil eines automatischen Updates fehlschlägt, wird das Datenbankschema möglicherweise nicht an die Version der Joomla-Programmdaten angepasst. In diesem Fall listet die Seite alle festgestellten Datenbankprobleme auf. Es ist oft möglich, Probleme zu beheben, indem man die Schaltfläche *Struktur aktualisieren* auswählt.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Listenfilter](jdocmanual?article=help/common-elements/list-filters).
* [Listenspaltenüberschriften](jdocmanual?article=help/common-elements/list-column-headers).
* [Listenpaginierung](jdocmanual?article=help/common-elements/list-pagination).

## Zugriff

- Wählen Sie **System → Wartungspanel → Datenbank** aus dem Administrator-Menü.

## Screenshot

![Wartung Datenbank](../../../de/images/maintenance/maintenance-database.png)

## Spaltenüberschriften

- **Probleme** Hier werden alle Probleme aufgeführt. Ein Tooltip beim Darüberfahren bietet weitere Informationen.
- **Datenbankversion** Die Versionsnummer der Datenbank.
- **Manifest-Version** Die Versionsnummer von Joomla oder der Erweiterung.
- **Ordner** Wenn die Erweiterung ein Plugin ist, das Unterverzeichnis des Plugin-Verzeichnisses der Joomla!-Installation, in dem sich die Erweiterung befindet.

## Tipps

- Wenn während eines Updates Probleme auftreten, verwenden Sie diese Datenbankprüfung, um zu sehen, ob die Datenbank korrekt aktualisiert wurde.
- Es wird dringend empfohlen, die Joomla-Update-Komponente für Updates der Website zu verwenden, damit die Datenbankänderungen automatisch ausgeführt werden.
