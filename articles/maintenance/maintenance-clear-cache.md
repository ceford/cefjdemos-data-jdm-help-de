<!-- Filename: Help4.x:Maintenance:_Clear_Cache / Display title: Wartung: Cache leeren -->

## Beschreibung

Cache-Dateien sind temporäre Dateien, die erstellt werden, um die Leistung der Website zu verbessern, wenn dies in den globalen Konfigurationseinstellungen der Website aktiviert ist. Cache-Dateien können veraltet sein und Rendering-Probleme verursachen, die durch das Löschen *aller* Cache-Dateien behoben werden können. Nach dem Löschen kann die Website etwas langsamer sein, bis die Cache-Dateien durch Nutzung wieder erstellt werden.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Listenfilter](jdocmanual?article=help/common-elements/list-filters).
* [Listenspaltenüberschriften](jdocmanual?article=help/common-elements/list-column-headers).
* [Listenpaginierung](jdocmanual?article=help/common-elements/list-pagination).

## Zugriff

- Wählen Sie **System → Wartungspanel → Cache leeren** aus dem Administrator-Menü.

## Screenshot

![Wartung Cache leeren](../../../de/images/maintenance/maintenance-clear-cache.png)

## Spaltenüberschriften

- **Cache-Gruppe** Der Typ des Elements, das in dieser Datei zwischengespeichert wird. Dies ist auch der Name des Unterverzeichnisses, in dem diese Art von Cache-Datei gespeichert wird. Die Cache-Dateien werden im Verzeichnis `\<Pfad-zu-Joomla!\>/cache/\<Cache-Gruppenname\>` gespeichert.
- **Anzahl der Dateien** Die Anzahl der Dateien, die sich derzeit in dieser Cache-Gruppe befinden.
- **Größe** Die Gesamtgröße der Cache-Dateien in dieser Gruppe.

## Tipps

- Normalerweise möchten Sie alle Cache-Dateien löschen. Um dies zu tun, klicken Sie auf das Kontrollkästchen in der Spaltenüberschrift, um alle Dateien auszuwählen, und klicken Sie dann auf das Löschsymbol in der Werkzeugleiste.