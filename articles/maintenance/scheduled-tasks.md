<!-- Filename: Help5.x:Scheduled_Tasks / Display title: Geplante Aufgaben -->

## Beschreibung

Geplante Aufgaben werden verwendet, um routinemäßige Wartungsaufgaben der Website auszuführen, als Alternative zu Server-Cron-Jobs. Die Aufgaben werden in Plugins in der Aufgabengruppe definiert. Eine Reihe von Aufgaben-Plugins wird bereitgestellt und kann als Beispiele für die Erstellung anderer spezialisierter Aufgaben verwendet werden.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfebeiträgen behandelt:

* [Symbolleisten](jdocmanual?article=help/common-elements/toolbars).
* [Listenfilter](jdocmanual?article=help/common-elements/list-filters).
* [Listenspaltenüberschriften](jdocmanual?article=help/common-elements/list-column-headers).
* [Listenpaginierung](jdocmanual?article=help/common-elements/list-pagination).

## Wie man auf Beiträge zugreift

Ausgehend vom Administrator-Menü:

- Wählen Sie **System → Panel verwalten → Geplante Aufgaben**

Die anfängliche Liste geplanter Aufgaben enthält drei Beiträge.

## Screenshot

![scheduled tasks list](../../../de/images/maintenance/scheduled-tasks-list.png)

## Spaltenüberschriften

Spalten, die nur bei geplanten Aufgaben einzigartig sind:

- **Aufgabentyp** Aufgaben werden aus einer verfügbaren Liste von Typen erstellt.
- **Letztes Ausführungsdatum** Das Datum und die Uhrzeit des letzten Aufgabenlaufs.
- **Nächstes Ausführungsdatum** Das Datum und die Uhrzeit des nächsten Aufgabenlaufs.
- **Aufgabe testen** Eine Schaltfläche, um die Aufgabe manuell auszuführen.
- **Aufgabenpriorität** Die Priorität kann Niedrig, Normal oder Hoch sein. Aufgaben mit höherer Priorität können möglicherweise Aufgaben mit niedrigerer Priorität blockieren.

## Ausführungshistorie

Wählen Sie die Schaltfläche in der Symbolleiste, um eine Liste der einzelnen Aufgabeausführungen zu sehen.

![task execution history list](../../../de/images/maintenance/scheduled-tasks-logs.png)

## Verfügbare Aufgaben

Der folgende Screenshot zeigt eine Liste der verfügbaren Aufgaben. Einige sind Demonstrationen, einige sind nützlich.

![Scheduled Tasks Available](../../../de/images/maintenance/scheduled-tasks-types.png)

Jede Aufgabe hat ihre eigenen aufgabenbezogenen Parameter, die selbsterklärend sein sollten. Zum Beispiel macht die Aufgabe **Site Offline** nur Sinn, wenn die **Aufgabe bearbeiten → Basisfelder → Ausführungsregel** auf **Manuelle Ausführung** eingestellt ist.

*Übersetzt von openai.com*
