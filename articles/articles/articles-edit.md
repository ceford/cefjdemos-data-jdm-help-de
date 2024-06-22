<!-- Filename: Help4.x:Articles:_Edit / Display title: Beiträge: Bearbeiten -->

## Beschreibung

Diese Seite dient zum Hinzufügen eines neuen oder Bearbeiten eines
bestehenden Beitrags, üblicherweise mit einem Wysiwyg-Editor. Der
Standardeditor ist TinyMCE, falls jedoch andere Editoren installiert
sind, kann der Standardeditor für die Site als Ganzes oder für einzelne
Benutzer geändert werden.

Die meisten Parameter haben die geeigneten Standardwerte, aber es könnte
sein, dass eine bestimmte Kategorie oder beitragsspezifische Metadaten
festgelegt werden sollen.

## Wie darauf zugreifen

Wählen **Inhalt → Beiträge**

Einen Beitrag hinzufügen:

- auf den Button **Neu** der Werkzeugleiste klicken.

Einen Beitrag bearbeiten:

- einen **Titel** aus der Liste wählen.

## Bildschirmfoto

![Articles edit screenshot](../../../de/images/articles/articles-edit-content-tab.png "Articles edit")

## Formular Felder

- **Titel**. Der Titel des Beitrages.
- **Alias**. Der interne Name des Beitrages. Das Feld kann leergelassen
  werden und Joomla wird den Standardwert Titel in Kleinbuchstaben und
  Bindestrichen statt Leerzeichen eintragen.

### Inhalt

#### Linke Seite

- **Beitragsinhalt**. Den Inhalt des Beitrages eingeben. Joomla hat 3
  Editoren, der Standard-Editor - TinyMCE
  wird hier gezeigt.

  Die Dropdown-Liste 'CMS Inhalt' ermöglicht Links auf einen Beitrag,
  Felder, Kontakt, Medien, Menü oder Modul.
- **Editor an/aus**. Der Button wird unterhalb des Editor-Fensters
  gezeigt. Damit kann zwischen TinyMCE und Editor -
  Keiner
  gewechselt werden.

#### Rechte Seite

- **Status**. Der Veröffentlichungs-Status des Beitrages.
  - Veröffentlicht: Der Beitrag ist im Frontend der Seite sichtbar.
  - Versteckt: Der Beitrag ist im Frontend der Seite für Besucher nicht
    sichtbar.
  - Archiviert: Der Beitrag wird nicht mehr in
    Kategorieblog-
    oder
    Kategorieliste-Menüs
    angezeigt.
  - Papierkorb: Der Beitrag ist gelöscht, befindet sich aber noch in der
    Datenbank. - **Kategorie**. Die Kategorie des Beitrags wählen.
- **Hauptbeitrag**. 'Ja' wählen, um den Beitrag in einem Menüeintrag
  Hauptbeiträge
  anzuzeigen.
- **Zugriffsebene**. Die Zugriffsebene des Beitrags wählen. Sie werden
  in Benutzer:
  Zugriffsebenen
  eingerichtet.
- **Sprache**. Die Sprache des Beitrags wählen. Den Standard 'Alle'
  beibehalten, wenn
  Mehrsprachigkeit
  nicht verwendet wird.
- **Schlagwörter**. Dem Beitrag Schlagwörter zuordnen. Dazu ein
  Schlagwort aus einer vordefinierten
  Liste
  wählen oder ein neues Schlagwort im Feld eingeben und 'Eingabe'
  drücken.
- **Notiz**. Die Notiz wird meist vom Administrator verwendet, um zum
  Beispiel Informationen über den Beitrag zu notieren. Die Notiz wird
  nicht im Frontend gezeigt.
- **Versionshinweis**. Optionales Feld, um diese Version des Beitrages
  im
  Versionsverlauf
  zu identifizieren.

### Bilder und Links

**Hinweis**: Dieser Abschnitt kann von einem Benutzer mit
Administrator-Rechten in Beiträge: Optionen ausgeblendet werden.
Dieser Teil zeigt in Beiträgen, Bilder und Links in standardisierten
Layouts.

![Articles edit images and links tab](../../../de/images/articles/articles-edit-images-tab.png "Articles edit images and links tab")

#### Einleitungsbild

- **Einleitungsbild**. Auf den Auswählen-Button klicken, um das Bild an
  eine fixen Stelle im Einleitungstext des Beitrages anzuzeigen. Ein
  Fenster wird geöffnet, in dem ein Bild aus dem Bilder-Verzeichnis
  gewählt wird. Mehr
  erfahren.
- **Bildbeschreibung (Alternativer Text)**. Das Alt-Attribut für das
  Bild mit einigen beschreibenden Wörtern für Screenreader festlegen.
- **Keine Beschreibung**. Im seltenen Fall eines rein dekorativen Bildes
  markieren. Das Bild erfüllt nicht die Barrierefreiheit, wenn
  'Bildbeschreibung (Alternativer Text)' leer und das Kontrollkästchen
  'Keine Beschreibung' nicht markiert sind. Ist eine Bildbeschreibung
  vorhanden, hat das Kontrollkästchen keine Auswirkung.
- **CSS-Klasse Bild**. Es kann eine beliebige CSS-Klasse für eigene
  Styling-Ideen hinzugefügt werden. Für die Bildposition kann zum
  Beispiel „float-start“ und „float-end“ verwendet werden.
- **Bildunterschrift**. Eine Bildunterschrift für das Bild eingeben.

#### Komplettes Beitragsbild

- **Komplettes Beitragsbild**. Auf den Auswählen-Button klicken, um das
  Bild an eine fixen Stelle des Beitrages anzuzeigen. Ein Fenster wird
  geöffnet, in dem ein Bild aus dem Bilder-Verzeichnis gewählt wird.
  Mehr
  erfahren.
- **Bildbeschreibung (Alternativer Text)**. Das Alt-Attribut für das
  Bild mit einigen beschreibenden Wörtern für Screenreader festlegen.
- **Keine Beschreibung**. Im seltenen Fall eines rein dekorativen Bildes
  markieren. Das Bild erfüllt nicht die Barrierefreiheit, wenn
  'Bildbeschreibung (Alternativer Text)' leer und das Kontrollkästchen
  'Keine Beschreibung' nicht markiert sind. Ist eine Bildbeschreibung
  vorhanden, hat das Kontrollkästchen keine Auswirkung.
- **CSS-Klasse Bild**. Es kann eine beliebige CSS-Klasse für eigene
  Styling-Ideen hinzugefügt werden. Für die Bildposition kann zum
  Beispiel „float-start“ und „float-end“ verwendet werden.
- **Bildunterschrift**. Eine Bildunterschrift für das Bild eingeben.

#### Link A

- **Link A**. Die URL des ersten Links, der an einer fixen Stelle eines
  Beitrages angezeigt wird. Es muß eine absolute, keine relative URL
  sein. Zum Beispiel beginnt sie mit `https:`.
- **Linktext A**. Der Text des Link A. Wenn leer, wird die URL
  angezeigt.
- **URL-Zielfenster**. Bestimmt den Standard-Wert für das Ziel des
  ersten Links im Beitrag. Zur Auswahl stehen:
  - In gleichem Fenster öffnen: Öffnet den Link im gleichen
    Browser-Fenster und ersetzt den aktuellen Joomla-Beitrag.
  - In neuem Fenster öffnen: Öffnet den Link in einem neuen
    Browser-Fenster.
  - Als Pop-up-Fenster öffnen: Öffnet den Link in einem
    Pop-up-Browser-Fenster (ohne Navigations-Elementen).
  - Modalfenster: Öffnet den Link in einem Modal-Pop-up-Browser-Fenster.

#### Link B, Link C

- Dieselben Optionen wie Link A.

### Optionen Abschnitt

**Hinweis**: Dieser Abschnitt kann von einem Benutzer mit
Administrator-Rechten in Beiträge: Optionen ausgeblendet werden.
Optionen, um das Aussehen eines Beitrages im Frontend einzustellen.

![Options tab](../../../de/images/articles/articles-edit-options-tab.png "Options Tab")

#### Layout

- **Layout**. Unterschiedliche Layouts der Beitragsansicht oder
  Override im
  Template
  wählen.
- **Titel**. Den Titel des Beitrages zeigen.
- **Titel verlinken**. Den Titel als Link zeigen.
- **Schlagwörter anzeigen**. Ein oder mehrere Schlagwörter für den
  Beitrag eingeben. Man kann vorhandene Schlagwörter nach Eingabe der
  ersten Buchstaben auswählen oder neue Schlagwörter eingeben. Mehr
  erfahren.
- **Einleitungstext**.
  - Anzeigen: Der Beitrag wird inklusive Einleitungstext gezeigt.
  - Verbergen: Der Beitrag wird ohne Einleitungstext gezeigt.
- **Position der Beitragsinfo**.
  - Darüber: Der Block mit den Beitragsinformationen steht oberhalb des
    Beitrags.
  - Darunter: Der Block mit den Beitragsinformationen steht unterhalb
    des Beitrags.
  - Aufteilen: Die Beitragsinformationen werden in einen Block oberhalb
    und einen Block unterhalb des Beitrags aufgeteilt.
- **Beitragsinfotitel**. Zeigt 'Details' über dem Block der
  Beitragsinformation an.

#### Kategorie

- **Kategorie**. Den Kategorietitel des Beitrags zeigen.
- **Kategorie verlinken**. Den Kategorietitel als Link zeigen.
- **Übergeordnete Kategorie**. Den Titel der übergeordneten Kategorie
  des Beitrages zeigen.
- **Übergeordnete Kategorie verlinken**. Den Kategorietitel als Link
  zeigen.

#### Verknüpfungen

- **Verknüpfungen**. Zeigt verknüpfte Flaggen oder den Sprachcode.

#### Autor

- **Autor**. Zeigt den Autor des Beitrags.
- **Autor verlinken**. Zum Kontakt des Autors verlinken.Hinweis: Der
  Autor muss als
  Kontakt
  angelegt sein.

#### Datum

- **Erstellungsdatum**. Das Erstellungsdatum des Beitrages zeigen.
- **Bearbeitungsdatum**. Das Bearbeitungsdatum des Beitrages zeigen.
- **Veröffentlichungsdatum**. Das Veröffentlichungsdatum des Beitrages
  zeigen.

#### Optionen

- **Seitennavigation**. Zeigt die Navigationslinks 'Zurück' oder
  'Weiter', wenn der Beitrag gezeigt wird.
- **Zugriffe**. Zeigt, wie oft der Beitrag von Benutzern aufgerufen
  wurde.
- **Nicht zugängliche Links**. Ja: Der Einleitungstext wird angezeigt.
  Nach Klick auf den Link "Weiterlesen" muss sich der Besucher anmelden,
  um den vollständigen Beitrag zu sehen.
- **Linkpositionierung.**
  - Darüber: Links werden oberhalb des Inhalts angezeigt.
  - Darunter: Links werden unterhalb des Inhalts angezeigt.
- **Eigener "Weiterlesen"-Text**. Einen eigenen Text anstelle von
  'Weiterlesen' zeigen.
- **Seitentitel im Browser**. Text für den 'Seitentitel im Browser',
  wenn der Beitrag nicht mit einem Beitrags-Menü anzeigt wird. Ist das
  Feld leer, wird der Titel des Beitrags verwendet.

### Felder

Dieser Teil zeigt für den Beitrag definierte Felder.

![Fields tab](../../../de/images/articles/articles-edit-fields-tab.png "Filds Tab")

### Schema tab

![Schema tab](../../../de/images/articles/articles-edit-schema-tab.png "Schema Tab")

The schema mechanism allows you to enter metadata for individual articles,
choosing from the following schema types:

* None
* Article
* BlogPosting
* Book
* Event
* JobPosting
* Organisation
* Person
* Recipe
* Custom

Each is a plugin which can disable or enable as required. More schmema types
my be added later or available from third oarty sources.

### Veröffentlichung Abschnitt

**Hinweis**: Dieser Abschnitt kann von einem Benutzer mit
Administrator-Rechten in Beiträge: Optionen ausgeblendet werden.
Dieser Teil erlaubt die Eingabe von Parametern und Metadaten des Beitrages.

![Publishing tab](../../../de/images/articles/articles-edit-publishing-tab.png "Publishing Tab")

#### Veröffentlichung

- **Veröffentlichung starten**. Datum und Uhrzeit, um die
  Veröffentlichung zu starten. Der Beitrag kann vor der Zeit erstellt
  und später automatisch veröffentlicht werden.
- **Veröffentlichung beenden**. Datum und Uhrzeit, um die
  Veröffentlichung zu beenden. Dem Beitrag wird automatisch der Status
  'Versteckt' zugewiesen.
- **Hauptbeitrag von**. Datum und Uhrzeit, um die Veröffentlichung als
  Hauptbeitrag zu starten. Der Beitrag kann vor der Zeit erstellt und
  später automatisch als Hauptbeitrag definiert werden.
- **Hauptbeitrag bis**. Datum und Uhrzeit, um die Veröffentlichung als
  Hauptbeitrag zu beenden. Den Beitrag vor der Zeit erstellen und später
  automatisch den Status als Hauptbeitrag entziehen.
- **Erstellungsdatum**. Das Erstellungsdatum des Beitrages. Ein anderes
  Datum oder Uhrzeit eingeben oder auf das Kalender-Symbol klicken.
- **Autor**. Der Name des Benutzers, der den Beitrag erstellt hat.
  Standard ist der aktuell eingewählte Benutzer. Um einen anderen
  Benutzer auszuwählen, auf den Button 'Benutzer auswählen' klicken.
- **Autoralias**. Einen Alias für den Autor dieses Beitrags eingeben.
  Ein anderer Autorennamen wird für diesen Beitrag angezeigt.
- **Bearbeitungsdatum**. Datum der letzten Bearbeitung.
- **Bearbeitet von**. Benutzer, der die letzte Bearbeitung ausgeführt
  hat.
- **Überarbeitung**. Anzahl der Überarbeitungen des Beitrags.
- **Zugriffe**. Anzahl der Aufrufe eines Beitrags.
- **ID**. Einmalig vergebene Identifikations-Nummer für den Beitrag, die
  nicht geändert werden kann. Beim Erstellen eines neuen Beitrags zeigt
  das Feld „0“ an, bis man speichert.

#### Metadaten

- **Meta-Beschreibung**. Ein Absatz zur Beschreibung der Seite. Mehr
  erfahren.
- **Schlüsselwörter**. Eintrag für Schlüsselwörter. Mehr
  erfahren.
- **Robots**. Anweisungen für Web-'Robots', die diese Seite durchsuchen.
  „Globale Einstellung“ in
  Konfiguration
  einstellen.
- **Autor**. Eintrag des Autorennamens in den Metadaten.
- **Inhaltsrechte**. Legt fest, welche Rechte andere Personen beim
  Gebrauch dieses Beitragsinhalts haben.

### Verknüpfungen Abschnitt

**Hinweis**: Dieser Abschnitt kann von einem Benutzer mit
Administrator-Rechten in Beiträge: Optionen ausgeblendet werden.
Der Tab wird nur bei Mehrsprachigen Seiten gezeigt.

![Associations tab](../../../de/images/articles/articles-edit-associations-tab.png "Associations Tab")

### Konfigurieren des Editorfensters

**Hinweis**: Dieser Abschnitt kann von einem Benutzer mit
Administrator-Rechten in Beiträge: Optionen ausgeblendet werden.

![Configure edit screen tab](../../../de/images/articles/articles-edit-editor-tab.png "Configure edit screen Tab")

- **Veröffentlichungsparameter anzeigen**. Ist 'Verbergen' gewählt, wird
  der Tab Veröffentlichung
  im Backend nicht gezeigt. Benutzer des Backends können die Felder des
  Tabs nicht bearbeiten. Den Feldern werden immer Standardwerte
  zugeordnet.
- **Beitragseinstellungen anzeigen**. Ist 'Verbergen' gewählt, wird der
  Tab Optionen im Backend nicht gezeigt. Benutzer des Backends können die
  Felder des Tabs nicht bearbeiten. Den Feldern werden immer Standardwerte
  zugeordnet.
- **Bilder und Links im Backend**. Ist 'Ja' gewählt, wird der Tab
  Bilder und Links gezeigt.
- **Bilder und Links im Frontend**. Ist 'Ja' gewählt, wird der 'Bilder
  und Links'-Tab im Frontend-Editor des Beitrages angezeigt.

### Berechtigungen

**Hinweis**: Dieser Abschnitt kann von einem Benutzer mit
Administrator-Rechten in Beiträge: Optionen ausgeblendet werden.
Hier können die Berechtigungen für den Beitrag eingegeben werden. Mehr
erfahren.

![Permissions tab](../../../de/images/articles/articles-edit-permissions-tab.png "Permissions Tab")

Um Berechtigungen dieses Beitrages zu ändern:

1.  Die **Gruppe** durch Anklicken des Namens auf der linken Seite
    auswählen.
2.  Die gewünschte **Aktion** aussuchen.
    - **Löschen**. Benutzer können diesen Beitrag löschen.
    - **Bearbeiten**. Benutzer können diesen Beitrag bearbeiten.
    - **Status bearbeiten**. Benutzer können den Status dieses Beitrags
      ändern.
3.  Die Berechtigungen der gewählten Aktion wählen.
    - **Vererbt**. Berechtigungen für Benutzer der Gruppe werden von der
      Konfiguration, den Beitrags-Optionen oder der Beitrags-Kategorie
      vererbt.
    - **Erlaubt**. Für Benutzer dieser Gruppe erlaubt.Hinweis: Wenn die
      Aktion auf einer höheren Ebene 'Verweigert' wird, ist die
      'Erlaubt'-Berechtigung hier dadurch überschrieben. Eine
      'Verweigert'-Einstellung kann nicht überschrieben werden.
    - **Verweigert**. Für Benutzer dieser Gruppe verweigert.
4.  Auf **Speichern** in der **Werkzeugleiste** oben klicken. Danach
    aktualisiert sich die Anzeige, erst dann werden die errechneten
    Einstellungen angezeigt.

## Werkzeugleiste

Das Bildschirmfoto zeigt die Werkzeugleiste im oberen Bereich.

- **Speichern**. Speichert den Beitrag und bleibt auf der aktuellen
  Seite.
- **Speichern & Schließen**. Speichert den Beitrag und schließt die
  aktuelle Seite.
  - **Speichern & Neu**. Speichert den Eintrag und hält die Seite offen,
    damit ein neuer Beitrag erstellt werden kann.
  - **Im Menü speichern**. Speichert den Beitrag in einem Menüeintrag
    und öffnet den Bildschirm für den Menüeintrag.
  - **Als Kopie speichern**. Speichert Änderungen in einer Kopie des
    aktuellen Beitrags. Der aktuelle Beitrag wird davon nicht
    beeinflusst.
- **Schließen**. Schließt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Änderungen zurück.
- **Versionen**. Öffnet den Versionsverlauf, der ältere Versionen des
  Beitrags zeigt. Damit können ältere Versionen des Beitrags gezeigt und
  wiederhergestellt werden.
- **Vorschau**. Zeigt die Seitenansicht des Beitrages. Benötigt
  Gemeinsame Sitzungen oder die Anmeldung im Frontend.
- **Barriere-Check**. Öffnet ein Fenster mit den Ergebnissen der
  Barrierefreiheitsprüfung des Beitrags.
- **Verknüpfungen**. Den Beitrag mit seiner festgelegten Sprache
  parallel in einer weiteren Sprache bearbeiten. Dieses Symbol wird nur
  bei Mehrsprachigen Seiten gezeigt.
- **Inline-Hilfe umschalten**. Hilfetext unter einigen Optionen ein-
  oder ausschalten.
- **Hilfe**. Öffnet die Hilfeseite.

## Tipps

- Es gibt 2 Methoden, um mit dem TinyMCE-Editor ein Bild in einen
  Beitrag einzufügen.
  1.  Die Dropdown-Liste CMS Inhalt ermöglicht den Zugriff auf die Seite
      Medien, in der Bilddateien durchsucht und Bilder hochgeladen werden
      können.
  2.  Die Dropdown-Liste 'Einfügen' öffnet ein einfaches
      Eingabeformular, für das die Bild-URL benötigt wird. Es wird für
      externe Bilder verwendet.
- Weiterlesen-Umbrüche
  sparen Platz auf der Startseite und Blog-Layout-Seiten, weil nur der
  erste Teil des Beitrages gezeigt wird. Die
  Seitennavigation
  teilt lange Beiträge in mehrere Seiten auf. Beides kann im selben
  Beitrag verwendet werden.Zum Beispiel könnte ein 'Weiterlesen'-Umbruch
  nach dem ersten Absatz eines mehrseitigen Artikels eingefügt werden
  und nach jeder Seite ein Seitenumbruch. Auf der Titelseite würde keine
  Seitennavigation angezeigt, bis der Benutzer den Link 'Weiterlesen'
  anklickt. Dann wird das Inhaltsverzeichnis des Artikels mit den Links
  zu den einzelnen Seiten angezeigt.
