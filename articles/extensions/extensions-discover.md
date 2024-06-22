<!-- Filename: Help4.x:Extensions:_Discover / Display title: Erweiterungen: Überprüfen -->

## Beschreibung

Diese Übersicht erlaubt es, Erweiterungen zu finden, die nicht über die
normale Joomla!-Installation installiert wurden. Auf diese Weise können
große Erweiterungen installiert werden, die auf normalem Weg nicht zu
installieren sind. Als Beispiel sind hier zu große (Dateigröße)
Erweiterungen zu nennen, die nicht einfach über das Webformular
hochgeladen werden können. Dies liegt häufig an den Einschränkungen der
Hosting-Umgebung. Mit dieser Funktion können die Erweiterungen direkt
via FTP oder SFTP auf den Webspace in das passende Verzeichnis
hochgeladen werden. Anschließend kann die „Überprüfen“-Funktion genutzt
werden, um neu hochgeladene Erweiterungen in Joomla! zu nutzen. Durch
die Nutzung der „Überprüfen“-Funktion können sogar mehrere Erweiterungen
gleichzeitig installiert werden. Dafür müssen nur folgende Schritte
ausgeführt werden:

1.  Die entpackten Dateien der Erweiterung in das passende Verzeichnis
    der Joomla!-Installation hochladen. Wenn beispielsweise eine
    Template-Erweiterung in die Joomla!-Installation aufgenommen werden
    soll, muss ein Verzeichnis für diese Template-Erweiterung im
    Unterverzeichnis /templates der Joomla!-Installation erstellt
    werden. Dann könnten die Dateien der Template-Erweiterung in dieses
    Verzeichnis hochgeladen werden.
2.  Nach dem Hochladen der Erweiterungsdateien die „Überprüfen“-Seite
    aufrufen und den „Überprüfen“-Button in der Werkzeugleiste
    anklicken. Dadurch wird die Suchfunktion gestartet, welche die
    Joomla!-Erweiterungsverzeichnisse nach nicht installierten
    Erweiterungen durchforsten wird.
3.  Falls die hochgeladene Erweiterung mit der Joomla!-Version
    kompatibel und noch nicht installiert ist, wird sie in der Liste der
    gefundenen Erweiterungen auf diesem Bildschirm erscheinen.
4.  Das Kontrollkästchen (Checkbox) links neben der entdeckten
    Erweiterung markieren und dann auf die Schaltfläche **Installieren**
    in der Symbolleiste klicken. Dadurch wird die Erweiterung in der
    Joomla!-Installation eingerichtet.

## Wie darauf zugreifen

- Im Administrator-Menü die Option
  **System → Installierenen → Überprüfen** wählen.

## Bildschirmfoto

<img
src="https://docs.joomla.org/images/thumb/5/5a/Help-4x-Extensions-Extension-Manager-Discover-screen-de.png/800px-Help-4x-Extensions-Extension-Manager-Discover-screen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/5/5a/Help-4x-Extensions-Extension-Manager-Discover-screen-de.png 1.5x"
data-file-width="1000" data-file-height="308" width="800" height="246"
alt="Extensions Extension Manager Discover screen" />

## Spalten-Überschriften

- **Checkbox**. Dieses Kästchen markieren, um einen oder mehrere
  Einträge auszuwählen. Um alle Einträge auszuwählen, das Kästchen im
  Spaltenkopf markieren. Nachdem ein oder mehrere Kästchen markiert
  sind, auf eine Schaltfläche in der Werkzeugleiste klicken, um eine
  Aktion für den ausgewählten Eintrag oder die ausgewählten Einträge
  durchzuführen. Viele Aktionen, wie z.B. Veröffentlichen und
  Verstecken, können mit mehreren Einträgen arbeiten. Andere, wie z.B.
  Bearbeiten, funktionieren gleichzeitig jeweils nur mit einem Eintrag.
  Wenn mehrere Einträge markiert sind und Sie auf „Bearbeiten“ drücken,
  wird der erste der markierten Einträge zur Bearbeitung geöffnet.
- **Name.** Der Name der Erweiterung.
- **Bereich.** Zeigt an, ob es eine Site- oder Administrator-Erweiterung
  ist.
- **Typ.** Der Erweiterungstyp – Modul, Plugin, Template, Sprache.
- **Version.** Die Versionsnummer der Erweiterung.
- **Datum.** Das Veröffentlichungsdatum der Erweiterung.
- **Autor.** Der Autor der Erweiterung.
- **Verzeichnis.** Falls die Erweiterung ein Plugin ist, befindet sich
  das Unterverzeichnis im Verzeichnis /plugins der Joomla!-Installation,
  in dem sich die Erweiterung befindet. Standardmäßig verfügt Joomla! im
  Plugins-Verzeichnis über die folgenden Unterverzeichnisse, die jeweils
  die verschiedenen Arten von definierten Plugins darstellen:
  authentication, content, editors, editors-xtd, extension, search,
  system, user.
- **ID.** Die ID-Nummer. Einmalig vergebene Identifikations-Nummer für
  diesen Eintrag. Sie wird automatisch von Joomla! vergeben und wird zur
  internen Identifikation des Eintrags verwendet. Man kann die Nummer
  nicht verändern.

## Listen-Filter

**Suchleiste**. Das Bildschirmfoto zeigt die Suchleiste
im oberen Bereich.

- **Suche nach Text**. Einen Teil des Suchbegriffs eingeben, auf das
  Symbol für Suche klicken. Wird der Mauszeiger *über das Eingabefeld
  bewegt*, zeigt ein *Hilfetext* durchsuchbare Bereiche.Um 'Nach der ID'
  zu suchen, "id:x" eingeben ("x" ist die ID-Nummer, z.B. "id:19").
- **Filter-Optionen**. Durch Anklicken zusätzliche Filter zeigen.
- **Zurücksetzen**. Durch Klicken werden Filter zurückgesetzt und die
  Liste im ungefilterten Zustand gezeigt.
- **Reihenfolge**. Zeigt das aktuelle Feld für die Reihenfolge an. Es
  gibt 2 Möglichkeiten, die Reihenfolge zu ändern:
  - Im Dropdown-Menü wählen. Die Reihenfolge ist aufsteigend oder
    absteigend möglich.
  - Eine Spaltenüberschrift anklicken. Ein Klick auf die
    Spaltenüberschrift wechselt zwischen aufsteigender und absteigender
    Reihenfolge.
- **Anzuzeigende Anzahl**. Zeigt die Anzahl der Einträge an. Zur
  Änderung in der Dropdown-Liste die gewünschte Anzahl wählen.Der
  Standardwert für die Site ist '20', er kann in der
  Konfiguration
  geändert werden.

#### Filter-Optionen

Ein oder mehrere Filter können kombiniert werden, um die Anzeige der
Erweiterungen zu begrenzen.

- **- Bereich wählen -** Einen Bereich aus der Dropdown-Liste wählen.
- **- Typ wählen -** Den Typ der Erweiterungen aus der Dropdown-Liste
  wählen.
- **- Verzeichnis wählen -** Ein Plugin-Verzeichnis aus der
  Dropdown-Liste wählen. Für jeden Plugin-Typ gibt es ein eigenes
  Verzeichnis.

**Seitenkontrolle**. Gibt es mehr Einträge als auf der Seite gezeigt,
wird im unteren Bereich die Seitenkontrollleiste wie auf dem
Bildschirmfoto eingeblendet. Die aktuelle Seitenzahl ist
mit dunkler Farbe unterlegt.

- **Start**. Anklicken, um die erste Seite anzuzeigen.
- **Vorherige**. Anklicken, um die vorherige Seite anzuzeigen.
- **Seitennummer**. Anklicken, um die anzuzeigende Seite auszuwählen.
- **Weiter**. Anklicken, um die nächste Seite anzuzeigen.
- **Ende**. Anklicken, um die letzte Seite anzuzeigen.

## Werkzeugleiste

Das [Bildschirmfoto](#Bildschirmfoto) am Anfang der Seite zeigt die
Werkzeugleiste im oberen Bereich. Die Funktionen sind:

- **Installieren.** Die gewählte Erweiterung installieren.
- **Überprüfen.** Durchsucht die Joomla! Installationsverzeichnisse nach
  nicht installierten Erweiterungen. Gefundene Erweiterungen werden
  angezeigt. Resultate werden zwischengespeichert und bei neuerlichem
  Aufrufen angezeigt.
- **Optionen.** Öffnet das Optionen-Fenster, in dem Einstellungen, wie
  die Standard-Parameter, bearbeitet werden können.
- **Hilfe**. Öffnet die Hilfeseite.

## Tipps

- Wenn viele Erweiterungen zu installieren sind, können alle in die
  entsprechenden Verzeichnisse der Joomla!-Installation hochgeladen
  werden und dann über diesem Bildschirm in einem Arbeitsgang erkannt
  werden. So können alle Erweiterungen in einem Schritt installiert
  werden, wobei man alle auswählt und auf die Schaltfläche
  **Installieren** in der Symbolleiste klickt.
