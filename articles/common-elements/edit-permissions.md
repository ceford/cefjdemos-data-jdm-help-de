<!-- Filename: Help4.x:Edit_Permissions / Display title: Berechtigungen bearbeiten -->

## Zweck

Viele Erweiterungen verfügen über Bearbeitungsbildschirme mit einer Registerkarte Berechtigungen, auf der die den Benutzergruppen zugewiesenen Berechtigungen geändert werden. Die Anzahl der Benutzergruppen kann variieren, da benutzerdefinierte Benutzergruppen für spezielle Zwecke hinzugefügt werden können. Die Anzahl der Aktionen, die geändert werden können, variiert auch je nach Erweiterung. Dieser Artikel enthält eine kurze Beschreibung der Berechtigungsbildschirme für solche speziellen Zwecke.

Stellen Sie sich vor, es gibt einen Benutzer, der sich um Medien (Bilder und Dateien) kümmert, aber keine anderen Verantwortlichkeiten hat. Eine Gruppe mit dem Namen Oddjob wurde erstellt und der speziellen Zugriffsebene zugewiesen. Ein Benutzer mit dem Namen Oddjob wurde erstellt und der Oddjob-Gruppe zugewiesen.

Für detailliertere Informationen zu Benutzergruppen, Zugriffsebenen und Berechtigungen gibt es ein separates Tutorial zu [Zugriffskontrolle](jdocmanual?article=user/users/access-control).

## Globale Konfigurationsberechtigungen

In diesem Beispiel wurde Benutzern in der Oddjob-Gruppe die globale Berechtigung zum Anmelden an der Administratoroberfläche zugewiesen, aber sonst nichts.

![Screenshot der Berechtigungen](../../../de/images/common-elements/global-configuration-permissions-tab.png)

## Berechtigungen für die Komponentenkonfiguration

Um auf eine bestimmte Komponente zuzugreifen, müssen Berechtigungen in den Komponentenoptionen festgelegt werden. In diesem Beispiel die Optionen der Medienkomponente.

![Medien-Screenshot](../../../de/images/common-elements/media-options-permissions-tab.png)

Sie werden feststellen, dass für diese Komponente weniger Aktionen verfügbar sind und die Oddjob-Gruppe gerade genug Berechtigungen hat, um den Job auszuführen.

So ändern Sie die Berechtigungen für diese Komponente:

* Wählen Sie die Gruppe aus, indem Sie auf den Titel links klicken.<br>
    Finden Sie die gewünschte Aktion.
    * Löschen. Benutzer können diesen Artikel löschen.
    * Bearbeiten. Benutzer können diesen Artikel bearbeiten.
    * Status bearbeiten. Der Benutzer kann den veröffentlichten Status und die zugehörigen Informationen für diesen Artikel ändern.
* Wählen Sie die gewünschte Berechtigung für die Aktion aus, die Sie ändern möchten.
    * Geerbt. Geerbt für Benutzer in dieser Gruppe aus der globalen Konfiguration, den Artikeloptionen oder der Artikelkategorie.
    * Dürfen. Für Benutzer in dieser Gruppe zulässig.Hinweis: Wenn diese Aktion auf einer der höheren Ebenen verweigert wird, wird die hier erlaubte Berechtigung nicht wirksam. Eine abgelehnte Einstellung kann nicht überschrieben werden.
    * Leugnen. Für Benutzer in dieser Gruppe abgelehnt.
* Klicken Sie oben in der Symbolleiste auf Speichern. Wenn der Bildschirm aktualisiert wird, zeigt die Spalte Berechnete Einstellung die effektive Berechtigung für diese Gruppe und Aktion an.

## Die Benutzererfahrung

Nach der Anmeldung sieht ein Benutzer in der Oddjob-Gruppe, welche Home-Dashboard-Module **Spezielle** Zugriffseinstellungen haben, und einen Menüpunkt-Link zur Medienkomponente.

![Start-Dashboard für Oddjob](../../../de/images/common-elements/home-dashboard-for-oddjob.png)

Und der Medienbildschirm für Benutzer Oddjob ist wie erwartet:

![Medienbildschirm für Oddjob](../../../de/images/common-elements/media-screen-for-oddjob.png)
