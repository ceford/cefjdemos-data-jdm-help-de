<!-- Filename: Help4.x:Extensions_Module_Manager_Edit / Display title: Erweiterungen: Module bearbeiten -->

## Beschreibung

Der Erweiterungs-Manager „Modul Bearbeiten“ ermöglicht die Bearbeitung
eines vorhandenen Moduls oder die Erstellung eines neuen Moduls
entsprechend dem gewählten Modultyp.

## Wie darauf zugreifen

- Im Administrator-Menü die Option **System → Verwalten → Site
  Module** wählen oder ...
- im Administrator-Menü die Option
  **System → Verwalten → Administrator Module** wählen. Dann ...
  - die Schaltfläche **„+ Neu“** in der Symbolleiste wählen, um ein
    neues Modul zu erstellen
    oder ...
  - einen Modulnamen in der Spalte **Titel** auswählen, um dieses Modul
    zu bearbeiten.

Bei einem neuen Modul wird eine Liste mit allen installierten Modulen
für das Frontend (Site) oder das Backend (Administrator) angezeigt, die
zur Auswahl stehen:

<img
src="https://docs.joomla.org/images/thumb/3/37/Help-4x-extensions-module-manager-new-de.png/800px-Help-4x-extensions-module-manager-new-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/3/37/Help-4x-extensions-module-manager-new-de.png/1200px-Help-4x-extensions-module-manager-new-de.png 1.5x, https://docs.joomla.org/images/thumb/3/37/Help-4x-extensions-module-manager-new-de.png/1600px-Help-4x-extensions-module-manager-new-de.png 2x"
data-file-width="1647" data-file-height="1029" width="800" height="500"
alt="extensions module manager new" />

Eines davon auswählen, um zum Bearbeitungsbildschirm zu wechseln.

## Bildschirmfoto

Die Registerkarte „Modul“ eines Bildschirmes zur Modulbearbeitung ist
abhängig vom Modultyp. Das Site-Modul "Breadcrumbs" (Navigationspfad)
ist hier abgebildet. Für andere Module siehe **[Verwandte
Informationen](#Verwandte_Informationen)** unten für Links zu bestimmten
Modultypen.

<img
src="https://docs.joomla.org/images/thumb/8/84/Help-4x-extensions-module-manager-edit-de.png/800px-Help-4x-extensions-module-manager-edit-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/84/Help-4x-extensions-module-manager-edit-de.png/1200px-Help-4x-extensions-module-manager-edit-de.png 1.5x, https://docs.joomla.org/images/8/84/Help-4x-extensions-module-manager-edit-de.png 2x"
data-file-width="1378" data-file-height="1254" width="800" height="728"
alt="extensions module manager edit" />

## Formular Felder

- **Titel**. Der Titel des Eintrages. Er kann auf der Seite abhängig von
  den gewählten Parameterwerten angezeigt werden.

### Modul

#### Linke Seite

Der Aufbau des linken Bereichs hängt vom Modultyp ab und wird hier nicht
beschrieben.

#### Rechte Seite

Der rechte Bereich ist bei allen Modulen gleich.

- **Titel anzeigen**. Anzeigen oder Verbergen des Modultitels im
  Frontend.
- **Position**. Die
  Modul-Position
  wählen, auf der dieses Modul angezeigt werden soll. Eine
  benutzerdefinierte Modulposition kann unter Verwendung mit dem
  Load-Position-Plugin
  eingegeben werden. Alternativ kann die Positionstaste gedrückt werden,
  um eine Modulposition aus dem Template auszuwählen.
- **Status**. Der Veröffentlichungs-Status des Eintrages.
  - *Veröffentlicht:* Der Eintrag ist im Frontend der Seite sichtbar.
  - *Versteckt:* Der Eintrag ist im Frontend der Seite für Besucher
    nicht sichtbar. Es kann für angemeldete Benutzer sichtbar sein, die
    eine Berechtigung zur Bearbeitung des Eintrags haben.
  - *Archiviert:* Der Eintrag wird nicht länger in Blog- oder
    Listen-Menüs angezeigt.
  - *Papierkorb:* Der Eintrag wurde gelöscht, befindet sich aber noch in
    der Datenbank. Dauerhaft wird es über den Button 'Papierkorb leeren'
    der Symbolleiste gelöscht (siehe auch
- **Veröffentlichung starten**. Datum und Uhrzeit, um die
  Veröffentlichung zu starten. Dieses Feld verwenden, um Inhalt vor der
  Zeit zu erstellen und ihn später automatisch zu veröffentlichen.
- **Veröffentlichung beenden**. Datum und Uhrzeit, um die
  Veröffentlichung zu beenden. Dieses Feld verwenden, um dem Inhalt
  automatisch den Status „Versteckt“ zuzuweisen (zum Beispiel, wenn der
  Inhalt nicht mehr aktuell ist).
- **Zugriffsebene**. Die angezeigte Zugriffsebene für diesen Eintrag aus
  dem Listenfeld auswählen. Welche Zugriffsebenen angezeigt werden,
  hängt davon ab, was für diese Site in Benutzer →
  Zugriffsebenen
  eingerichtet wurde. Bitte beachten, dass Zugriffsebenen nicht mit
  ACL-Berechtigungen gleichzusetzen sind. Zugriffsebenen steuern, was
  ein Benutzer sehen kann. ACL-Berechtigungen steuern, welche Aktionen
  ein Benutzer durchführen kann.
- **Reihenfolge.** Die Reihenfolge eines Eintrags innerhalb einer Liste
  kann wie folgt geändert werden:
  - Wenn die Liste Filter-Optionen einen Positions-Filter enthält, dann
    wählt man die gewünschte Position aus. Dadurch wird die Liste auf
    Positionen beschränkt, die dieser Position zugeordnet sind.
  - Das Reihenfolge-Symbol <img
    src="https://docs.joomla.org/images/e/ee/Help30-Ordering-colheader-icon.png"
    decoding="async" data-file-width="12" data-file-height="23" width="12"
    height="23" alt="Ordering column header icon" /> in der
    Tabellenüberschrift anklicken, um diese Spalte zur aktiven
    Sortierung zu machen. Die Ordnungssymbole in jeder Zeile ändern sich
    von hellgrau zu dunkelgrau, und der Mauszeiger verwandelt sich beim
    Überfahren in einen Ziehpfeil.
  - Eines der Reihenfolge-Symbole <img
    src="https://docs.joomla.org/images/8/87/Help30-Ordering-colheader-grab-bar-icon.png"
    decoding="async" data-file-width="10" data-file-height="21" width="10"
    height="21" alt="Ordering drag icon" />
    wählen und es nach oben oder unten ziehen, um die Position dieser
    Zeile in der Liste zu ändern. Die Einträge werden in der neuen
    Reihenfolge innerhalb der Position angezeigt.
- **Sprache**. Die Sprache für diesen Eintrag wählen. Wird die Funktion
  Mehrsprachigkeit nicht verwendet, den Standardwert 'Alle' beibehalten.
- **Notiz**. Die Notiz wird meist vom Site-Administrator verwendet, um
  beispielsweise Informationen über den Eintrag zu notieren. Die Notiz
  wird nicht im Frontend der Seite angezeigt.

### Menüzuweisung

Diese Registerkarten-Ansicht enthält alle Menüeinträge, die auf der
Joomla!-Website konfiguriert sind. Dadurch kann man auswählen, wo ein
Modul auf der mit dem Menüeintrag verbundenen Inhaltsseite angezeigt
werden soll.

<img
src="https://docs.joomla.org/images/thumb/e/ee/Help-4x-Module-Manager-Edit-menu-assignment-de.png/600px-Help-4x-Module-Manager-Edit-menu-assignment-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/ee/Help-4x-Module-Manager-Edit-menu-assignment-de.png/900px-Help-4x-Module-Manager-Edit-menu-assignment-de.png 1.5x, https://docs.joomla.org/images/thumb/e/ee/Help-4x-Module-Manager-Edit-menu-assignment-de.png/1200px-Help-4x-Module-Manager-Edit-menu-assignment-de.png 2x"
data-file-width="1232" data-file-height="1058" width="600" height="515"
alt="Module Manager Edit menu assignment" />

#### Modulzuweisung

- **Modulzuweisung**. Zur Auswahl der Modulzuordnung einfach hier
  klicken.
- **Auf allen Seiten.** Das Modul wird auf allen Seiten in der gewählten
  Position gezeigt.
- **Auf keinen Seiten**. Module werden **auf keiner Seite** an der
  gewählten Modulposition angezeigt.
- **Nur auf den gewählten Seiten**. Das Modul wird nur auf den Seiten in
  der ausgewählten Modulposition angezeigt, wie sie durch den
  Menüeintragstyp (Titel) festgelegt wurde. Siehe **Menüauswahl** unten.
- **Auf allen, außer den gewählten Seiten**. Das Modul wird auf allen
  Seiten in der gewählten Position gezeigt, ausgenommen der in der
  Menüauswahl gewählten Seiten. Siehe **Menüauswahl** unten.

#### Menüauswahl

- **Menüauswahl**. Wird nur angezeigt, wenn in der **Modulzuweisung**,
  wie oben gezeigt, **Nur auf den gewählten Seiten** oder **Auf allen,
  außer den gewählten Seiten** eingestellt ist.

Um das Modul der entsprechenden Webseite (Titel) eines Menüeintrags
zuzuordnen, muss das Kontrollkästchen neben dem Menüeintrag aktiviert
werden.

- Zuordnen zu Menüeinträgen: *Alle* oder *Keine* anklicken, um die
  Auswahl der Menüeinträge zu verändern.
- Untermenüs aufklappen: *Alle* oder *Keine* anklicken, um die
  Strukturansicht für die Auswahl der Menüeinträge anzuzeigen.

**Hinweis**: Wenn ein Kontrollkästchen ausgegraut ist und nicht
angekreuzt werden kann, könnte es daran liegen, dass der Menüeintrag von
einem anderen Benutzer verwendet wird. Um das zu überprüfen, die
Menü-Manager-Seite für das betreffende
Menü
aufrufen. Wenn sich neben dem Menüeintrag ein Schloss-Symbol befindet,
wird der Menüeintrag gerade von einem anderen Benutzer verwendet.

### Erweitert

<img
src="https://docs.joomla.org/images/thumb/c/ce/Help-4x-Module-Manager-Edit-advanced-de.png/600px-Help-4x-Module-Manager-Edit-advanced-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/ce/Help-4x-Module-Manager-Edit-advanced-de.png/900px-Help-4x-Module-Manager-Edit-advanced-de.png 1.5x, https://docs.joomla.org/images/thumb/c/ce/Help-4x-Module-Manager-Edit-advanced-de.png/1200px-Help-4x-Module-Manager-Edit-advanced-de.png 2x"
data-file-width="1253" data-file-height="635" width="600" height="304"
alt="Module Manager Edit advanced" />

### Modulberechtigungen

<img
src="https://docs.joomla.org/images/thumb/8/86/Help-4x-Module-Manager-Edit-permissions-de.png/600px-Help-4x-Module-Manager-Edit-permissions-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/86/Help-4x-Module-Manager-Edit-permissions-de.png/900px-Help-4x-Module-Manager-Edit-permissions-de.png 1.5x, https://docs.joomla.org/images/thumb/8/86/Help-4x-Module-Manager-Edit-permissions-de.png/1200px-Help-4x-Module-Manager-Edit-permissions-de.png 2x"
data-file-width="1258" data-file-height="788" width="600" height="376"
alt="Module Manager Edit permissions" />

## Werkzeugleiste

Das [Bildschirmfoto](#Bildschirmfoto) am Anfang der Seite zeigt die
Werkzeugleiste im oberen Bereich. Die Funktionen sind:

- **Speichern**. Speichert den Eintrag und bleibt auf der aktuellen
  Seite.
- **Speichern & Schließen**. Speichert den Eintrag und schließt die
  aktuelle Seite.
- **Speichern & Neu**. Speichert den Eintrag und hält die Seite offen,
  damit ein neuer Eintrag erstellt werden kann.
- **Als Kopie speichern**. Speichert Änderungen in einer Kopie des
  aktuellen Eintrags. Der aktuelle Eintrag wird davon nicht beeinflusst.
  Dieses Symbol wird nicht angezeigt, wenn ein neuer Eintrag erstellt
  wird.
- **Abbrechen**. Schließt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Änderungen zurück. Oder
- **Schließen**. Schließt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Änderungen zurück. Dieses Symbol wird nicht
  angezeigt, wenn ein neuer Eintrag erstellt wird.
- **Hilfe**. Öffnet die Hilfeseite.
