<!-- Filename: Help4.x:Users:_Edit_Viewing_Access_Level / Display title: Benutzer: Zugriffsebenen anzeigen und bearbeiten -->

## Beschreibung

Zugriffslevel steuern, welche Benutzer welche Assets auf einer Seite anzeigen können. Zu den Assets gehören Menüpunkte, Module, Kategorien und Komponentenobjekte (Artikel, Kontakte usw.). Jedes Asset auf der Seite ist einem Zugriffslevel zugeordnet. Benutzergruppen werden ebenfalls jedem Zugriffslevel zugewiesen.

Wenn ein Benutzer Mitglied einer Gruppe ist, die über Berechtigungen für ein Zugriffslevel verfügt, kann dieser Benutzer alle Assets anzeigen, die diesem Zugriffslevel zugewiesen sind. Es ist wichtig zu verstehen, dass Benutzergruppen in einer Eltern-Kind-Hierarchie angeordnet sein können. In diesem Fall hat eine Kindgruppe Zugriff auf alle Zugriffslevel, auf die die Elterngruppe ebenfalls Zugriff hat. Sie müssen also der Kindgruppe keinen Zugriff auf Level gewähren, auf die die Elterngruppe bereits Zugriff hat.

### Allgemeine Elemente

Einige Elemente dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).

## So greifen Sie darauf zu

- Wählen Sie **Benutzer → Zugriffslevel** aus dem Administrator-Menü. Dann...
  - Wählen Sie einen Link aus der Spalte **Level Name** aus, um ein bestehendes Level zu bearbeiten. Oder...
  - Wählen Sie die Schaltfläche "Neu", um ein neues Zugriffslevel zu erstellen.

## Screenshot

![Benutzer Ansicht Zugriffslevel](../../../de/images/users/users-edit-viewing-access-level-details-tab.png)

### Reiter "Level-Details"

- **Titel des Levels** Geben Sie einen Titel für dieses Zugriffslevel ein.
- **Benutzergruppen mit Anzeigezugriff** Wählen Sie alle Gruppen aus, die Zugriff auf dieses Zugriffslevel haben sollen.

### Reiter "Benutzergruppen mit Anzeigezugriff"

![Benutzer Ansicht Zugriffslevel](../../../de/images/users/users-edit-viewing-access-level-ugwva-tab.png)

Wählen Sie ein Kontrollkästchen, um einer Benutzergruppe Zugriff auf ein Ansichtslevel zu gewähren. Im gezeigten Beispiel sind alle Gruppen Kinder von "Public", daher ist es nicht erforderlich, eine der Kindgruppen auszuwählen. Sie erben die Zugriffsrechte der "Public"-Gruppe. Diese Funktion sollte nur für benutzerdefinierte Gruppen verwendet werden!

## Tipps

- Wenn Sie eine neue Gruppe hinzufügen, müssen Sie möglicherweise die Zugriffslevel bearbeiten, auf die diese Gruppe zugreifen soll.
