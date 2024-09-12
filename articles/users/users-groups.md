<!-- Filename: Help4.x:Users:_Groups / Display title: Benutzer: Gruppen -->

## Beschreibung

Benutzergruppen steuern, welche Aktionen ein Benutzer auf einer Website ausführen kann. Zu den Aktionen gehören Dinge wie das Anzeigen eines Artikels, das Erstellen eines Artikels, das Ändern von Optionen für eine Komponente oder das Anmelden. Der Site-Administrator weist jeder Gruppe Berechtigungen für verschiedene Aktionen zu. Berechtigungen für Aktionen können an verschiedenen Stellen in der Komponentenhierarchie zugewiesen werden, z. B. in der globalen Konfiguration, den Komponentenoptionen oder den Moduloptionen. Wenn eine Benutzergruppe keine Berechtigung für eine bestimmte Aktion hat, kann der Benutzer in dieser Gruppe diese Aktion nicht ausführen.

Die Anzeigezugriffssteuerung wird durch die Verwendung von **Zugriffsleveln** implementiert, denen eine oder mehrere Benutzergruppen zugewiesen sind. Assets wie Artikel, Menüpunkte oder Module werden einem Zugriffslevel zugewiesen. Ein Benutzer, der Mitglied einer Gruppe ist, die einem bestimmten Zugriffslevel zugeordnet ist, kann jedes Asset anzeigen, das diesem Zugriffslevel zugewiesen ist.

Benutzergruppen können in einer Hierarchie angeordnet werden, in der alle Kindgruppen die Aktionsberechtigungen und Zugriffslevel einer Elterngruppe erben. Wenn diese Funktion weise genutzt wird, kann dies viel Zeit sparen, da die Duplizierung beim Einrichten eines Site-Sicherheitssystems vermieden wird.

Die Seite *Benutzer: Gruppen* listet die aktuellen Benutzergruppen in einer Hierarchie auf. Sie kann verwendet werden, um neue Benutzergruppen zu erstellen und nicht mehr benötigte Gruppen zu löschen. Löschen Sie keine der Standard-Benutzergruppen!

### Allgemeine Elemente

Einige Elemente dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Listenfilter](jdocmanual?article=help/common-elements/list-filters).
* [Listenspaltenüberschriften](jdocmanual?article=help/common-elements/list-column-headers).
* [Seitenumbruch in Listen](jdocmanual?article=help/common-elements/list-pagination).

## So greifen Sie darauf zu

- Wählen Sie **Benutzer → Gruppen** aus dem Administrator-Menü.

## Screenshot

![Benutzer Gruppen](../../../de/images/users/users-groups-list.png)

## Tipps

- Wählen Sie den Namen einer Gruppe, um die Eigenschaften der Gruppe zu bearbeiten.
- Wählen Sie das Berechtigungssymbol, um die Gruppenberechtigungen für den Zugriff auf jedes Asset zu überprüfen. Dies wird häufig verwendet, um Probleme mit den Zugriffsberechtigungen zu beheben.
- Wählen Sie eine Anzahl aktivierter Benutzer, um eine Liste der aktivierten Benutzer in dieser Gruppe anzuzeigen.
- Wählen Sie eine Anzahl blockierter Benutzer, um eine Liste der blockierten Benutzer in dieser Gruppe anzuzeigen.
