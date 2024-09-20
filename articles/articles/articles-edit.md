<!-- Filename: Help4.x:Articles:_Edit / Display title: Beiträge: Bearbeiten -->

## Beschreibung

Diese Seite wird verwendet, um einen neuen Beiträge hinzuzufügen oder einen bestehenden Beiträge zu bearbeiten, normalerweise mit einem WYSIWYG-Editor. Der Standardeditor ist TinyMCE, aber wenn andere Editoren installiert sind, kann der Standardeditor für die gesamte Website oder für einzelne Benutzer auf etwas anderes eingestellt werden.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Die Schema-Registerkarte](jdocmanual?article=help/common-elements/edit-schema).
* [Die Veröffentlichungs-Registerkarte](jdocmanual?article=help/common-elements/edit-publishing).
* [Die Zuordnungs-Registerkarte](jdocmanual?article=help/common-elements/edit-associations).
* [Die Berechtigungs-Registerkarte](jdocmanual?article=help/common-elements/edit-permissions).
* [Das Versionsverlauf-Popup](jdocmanual?article=help/common-elements/edit-version-history).

Oder in Benutzerartikeln:

* [Ein Bild zu einem Beiträge hinzufügen](jdocmanual?article=user/articles/adding-an-image-to-an-article)

## Zugriff

* Wählen Sie **Inhalt → Beiträge** im Administrator-Menü. Oder...
* Wählen Sie **Beiträge** aus dem Start-Dashboard. Dann...
    * Wählen Sie einen bestehenden Beiträge **Titel** aus der Liste, um ihn zu bearbeiten. Oder...
    * Wählen Sie die Schaltfläche **Neu** in der Werkzeugleiste, um einen neuen Beiträge zu erstellen. Sie können auch einen neuen Beiträge erstellen, indem Sie das **+**-Symbol im Menü oder im Start-Dashboard auswählen.

## Screenshot

![Beiträge bearbeiten Screenshot](../../../de/images/articles/articles-edit-content-tab.png)

## Formularfelder

- **Titel** Der Titel dieses Beiträges.
- **Alias** Der interne Name dieses Beiträges. Normalerweise können Sie dieses Feld leer lassen, und Joomla wird basierend auf dem Titel einen Standardwert in Kleinbuchstaben und mit Bindestrichen anstelle von Leerzeichen einfügen.

### Inhalt-Registerkarte

#### Linkes Panel

- **Beitragsinhalt** Hier geben Sie den Inhalt des Beiträges ein. Joomla enthält 3 Editoren, der Standardeditor - TinyMCE - wird hier angezeigt.

    Die CMS-Inhaltsauswahlliste bietet Zugriff auf Links zu einem Beiträge, Kontakt, Feld, Medienbild, Menü, Modul, Seitenumbruch oder "Mehr lesen"-Umbruch.

    Das Ellipsen-Symbol (<span class="icon-ellipsis-h"></span>) schaltet die Sichtbarkeit zusätzlicher Werkzeuge um.
- **Editor an/aus** Die Schaltfläche unter dem Bearbeitungsfenster ermöglicht es Ihnen, zwischen dem TinyMCE-Editor und keinem Editor zu wechseln. Dies ermöglicht es Ihnen, den HTML-Code zu sehen und manchmal zu korrigieren.

#### Rechtes Panel

- **Status** Der Veröffentlichungsstatus dieses Beiträges.
  - *Veröffentlicht* Der Beiträge ist im Frontend der Website sichtbar.
  - *Nicht veröffentlicht* Der Beiträge wird nicht für Gäste im Frontend der Website angezeigt. Er kann jedoch für eingeloggte Benutzer sichtbar sein, die die Berechtigung zum Bearbeiten des Zustands für den Beiträge haben.
  - *Archiviert* Der Beiträge wird nicht mehr auf Menüpunkten oder Kategorielisten angezeigt.
  - *Gelöscht* Der Beiträge ist von der Website gelöscht, aber noch in der Datenbank gespeichert.
- **Kategorie** Wählen Sie die Kategorie für diesen Beiträge.
- **Hervorgehoben** Wählen Sie "Ja", wenn der Beiträge im hervorgehobenen Menüpunkten angezeigt werden soll.
- **Zugriff** Wählen Sie die Ansichtsebene für diesen Beiträge. Die Zugriffsebenen hängen von den in den Benutzereinstellungen festgelegten Zugriffsebenen ab.
- **Sprache** Wählen Sie die Sprache für diesen Beiträge. Lassen Sie die Standardeinstellung "Alle", wenn Sie die Mehrsprachenfunktion nicht verwenden.
- **Tags** Weisen Sie diesem Beiträge Tags zu. Sie können ein Tag aus einer vordefinierten Liste auswählen oder ein neues Tag hinzufügen, indem Sie den Namen in das Feld eingeben und die Eingabetaste drücken.
- **Hinweis** Normalerweise für die Verwendung durch den Administrator gedacht (z. B. um Informationen über diesen Beiträge zu dokumentieren) und wird nicht im Frontend angezeigt.
- **Versionshinweis** Ein optionales Feld, um die Version dieses Beiträges in der Versionshistorie des Beiträges zu kennzeichnen.

### Bilder und Links-Registerkarte

**Hinweis:** Diese Registerkarte kann in den *Beiträgeoptionen* von einem Benutzer mit Administratorrechten ausgeblendet werden. Sie ermöglicht die Anzeige von Bildern und Links in Beiträgen unter Verwendung standardisierter Layouts.

![Beiträge bearbeiten: Bilder und Links-Registerkarte](../../../de/images/articles/articles-edit-images-tab.png)

#### Einleitungsbild

- **Einleitungsbild** Klicken Sie auf die Schaltfläche Auswählen, um ein Bild auszuwählen, das an einer festen Position im Einleitungstext dieses Beiträges angezeigt wird. Dies öffnet ein Fenster, in dem Sie ein Bild aus dem Bildordner auswählen können.
- **Bildbeschreibung (Alt-Text)** Legen Sie das alt-Attribut für dieses Bild fest. Einige beschreibende Wörter für Bildschirmlesegeräte.
- **Keine Beschreibung** Aktivieren Sie dies im seltenen Fall eines rein dekorativen Bildes. Beachten Sie, dass das Bild nicht den Barrierefreiheitskriterien entspricht, wenn die Bildbeschreibung leer ist und das Kontrollkästchen "Keine Beschreibung" deaktiviert ist. Wenn eine Bildbeschreibung vorhanden ist, hat dieses Kontrollkästchen keine Auswirkung.
- **Bildklasse** Fügen Sie eine CSS-Klasse für benutzerdefinierte Stile hinzu. Zum Beispiel für die Bildposition verwenden Sie float-start oder float-end.
- **Bildunterschrift** Erstellen Sie eine Bildunterschrift für dieses Bild.

#### Komplettes Beitragsbild

- **Komplettes Beitragsbild** Klicken Sie auf die Schaltfläche Auswählen, um ein Bild auszuwählen, das an einer festen Position im Haupttext dieses Beiträges angezeigt wird. Dies öffnet ein Fenster, in dem Sie ein Bild aus dem Bildordner auswählen können.
- **Bildbeschreibung (Alt-Text)** Legen Sie das alt-Attribut für dieses Bild fest. Einige beschreibende Wörter für Bildschirmlesegeräte.
- **Keine Beschreibung** Aktivieren Sie dies im seltenen Fall eines rein dekorativen Bildes. Beachten Sie, dass das Bild nicht den Barrierefreiheitskriterien entspricht, wenn die Bildbeschreibung leer ist und das Kontrollkästchen "Keine Beschreibung" deaktiviert ist.
- **Bildklasse** Fügen Sie eine CSS-Klasse für benutzerdefinierte Stile hinzu.
- **Bildunterschrift** Fügen Sie eine optionale Bildunterschrift hinzu.

#### Link A

- **Link A** Die URL für den ersten Link, der an einer festen Position im Beiträgetext angezeigt wird. Dies muss eine vollständige URL sein, nicht relativ. Normalerweise beginnt sie mit `https:`.
- **Link A Text** Der Text, der für Link A verwendet wird. Wenn leer, wird die URL angezeigt.
- **URL-Zielfenster** Legt den Standardwert für das Ziel des ersten Links in diesem Beiträge fest. Optionen sind:
  - *Im übergeordneten Fenster öffnen* Öffnet den Link im Hauptbrowserfenster und ersetzt den aktuellen Joomla-Beiträge.
  - *In einem neuen Fenster öffnen* Öffnet den Link in einem neuen Browserfenster.
  - *In einem Popup öffnen* Öffnet den Link in einem Popup-Browserfenster (ohne vollständige Navigationssteuerelemente).
  - *Modal* Öffnet den Link in einem modalen Popup-Fenster.

#### Link B, Link C

- Gleiche Optionen wie bei Link A.

### Optionen-Registerkarte

**Hinweis:** Diese Registerkarte kann von einem Benutzer mit Administratorrechten in den *Beiträgeoptionen* ausgeblendet werden. Sie enthält eine Reihe von Optionen, um zu steuern, wie dieser Beiträge im Frontend angezeigt wird.

![Optionen-Registerkarte](../../../de/images/articles/articles-edit-options-tab.png)

#### Layout

- **Layout** Verwenden Sie ein Layout aus der mitgelieferten Beiträgeansicht oder Vorlagen-Overrides.
- **Titel** Den Titel des Beiträges anzeigen.
- **Verknüpfte Titel** Den Titel als Link zum Beiträge anzeigen.
- **Tags** Geben Sie Tags für diesen Beiträge ein.
- **Einleitungstext**
  - *Anzeigen* Der Einleitungstext des Beiträges wird auf einer Seite mit dem vollständigen Beiträge angezeigt.
  - *Verbergen* Nur der Teil des Beiträges nach dem "Weiterlesen"-Umbruch wird auf einer Seite mit dem vollständigen Beiträge angezeigt.
- **Position der Beitragsinfo**
  - *Oben* Die Beiträgeinformationsblock wird oberhalb des Textes angezeigt.
  - *Unten* Der Block wird unterhalb des Textes angezeigt.
  - *Geteilt* Der Informationsblock wird in zwei Blöcke aufgeteilt – einen oberhalb und einen unterhalb des Textes.
- **Beiträgesinfo-Titel** Zeigt 'Details' oben auf dem Beiträgeinformationsblock an.

#### Kategorie

- **Kategorie** Zeigt den Kategorietitel des Beiträges an.
- **Verknüpfte Kategorie** Zeigt den Titel als Link zu dieser Kategorie an.
- **Übergeordnete Kategorie** Zeigt den Titel

 der übergeordneten Kategorie des Beiträges an.
- **Verknüpfte übergeordnete Kategorie** Zeigt den Titel als Link zu dieser Kategorie an.

#### Zuordnungen

- **Zuordnungen** Zeigt die zugeordneten Flaggen oder Sprachcodes an. Nur für Mehrsprachigkeit.

#### Autor

- **Autor** Zeigt den Autor des Beiträges an.
- **Link zur Kontaktseite des Autors** Zeigt einen Link zu einem Kontaktlayout für diesen Autor an. Hinweis: Der Autor muss als Kontakt eingerichtet sein.

#### Datum

- **Erstellungsdatum** Zeigt das Erstellungsdatum des Beiträges an.
- **Änderungsdatum** Zeigt das Änderungsdatum des Beiträges an.
- **Veröffentlichungsdatum** Zeigt das Veröffentlichungsdatum des Beiträges an.

#### Optionen

- **Navigation** Zeigt Navigationslinks, *Vorherige* und/oder *Nächste*, wenn eine Seite mit dem vollständigen Beiträge angezeigt wird.
- **Zugriffe** Zeigt an, wie oft der Beiträge von einem Benutzer angezeigt wurde.
- **Nicht autorisierte Links** Wenn Ja, wird der Einleitungstext für eingeschränkte Beiträge angezeigt. Das Klicken auf den Weiterlesen-Link erfordert, dass sich Benutzer anmelden, um den vollständigen Beiträgeinhalt anzuzeigen.
- **Positionierung der Links**
  - *Oben* Links werden über dem Inhalt angezeigt.
  - *Unten* Links werden unter dem Inhalt angezeigt.
- **"Weiterlesen"-Text** Passen Sie den Text für die Standardformulierung "Weiterlesen" an.
- **Browser-Seitentitel** Text für den Seitentitel des Browsers, wenn der Beiträge mit einem Nicht-Beiträge-Menüpunkt angezeigt wird. Wenn leer, wird der Titel des Beiträges stattdessen verwendet.

### Felder-Registerkarte

Dieser Abschnitt zeigt die benutzerdefinierten Felder, die für diesen Beiträge definiert wurden. Dies sind Felder, die nicht einer Feldgruppe zugewiesen sind. Jede Feldgruppe, falls definiert, erscheint als separate Registerkarte.

![Felder-Registerkarte](../../../de/images/articles/articles-edit-fields-tab.png)


### Registerkarte "Bearbeitungsbildschirm konfigurieren"

**Hinweis:** Dies kann von einem Benutzer mit Administratorrechten in den *Beiträgeoptionen* ausgeblendet werden.

![Bearbeitungsbildschirm konfigurieren](../../../de/images/articles/articles-edit-editor-tab.png)

- **Veröffentlichungsoptionen** Wenn Ausblenden, wird die Veröffentlichungs-Registerkarte im Backend nicht angezeigt. Dies bedeutet, dass Backend-Benutzer die Felder in dieser Registerkarte nicht bearbeiten können. Diese Felder werden immer auf ihre Standardwerte gesetzt.
- **Beitragseinstellungen anzeigen** Wenn Ausblenden, wird die Beiträgeoptionen-Registerkarte im Backend nicht angezeigt. Dies bedeutet, dass Backend-Benutzer die Felder in dieser Registerkarte nicht bearbeiten können.
- **Administratorbilder und -links** Wenn Ja, wird die Bilder- und Links-Registerkarte angezeigt.
- **Frontend-Bilder und -Links** Wenn Ja, wird die Registerkarte "Bilder und Links" im Frontend-Beiträge-Editor-Bildschirm angezeigt.

## Tipps

- Es gibt 2 Methoden, um ein Bild mit dem TinyMCE-Editor in einen Beiträge einzufügen.
  1. Die *CMS-Inhaltsauswahlliste* bietet Zugriff auf den Medienbildschirm.
  2. Die *Einfügen*-Dropdown-Liste ist ein einfaches Formular, das die Bild-URL erfordert. Es wird für externe Bilder verwendet.
- Ein *Weiterlesen*-Eintrag spart Platz auf jeder hervorgehobenen oder Blog-Layout-Seite, indem nur der erste Teil eines Beiträges angezeigt wird. *Seitenumbruch*-Einträge bieten mehrseitige Navigation für lange Beiträge. Beide können in einem einzigen Beiträge verwendet werden, wenn gewünscht. Zum Beispiel könnte ein *Weiterlesen*-Umbruch nach dem ersten Absatz und *Seitenumbruch*-Umbrüche nach späteren Absätzen eingefügt werden, um einen mehrseitigen Beiträge zu erstellen. Auf der hervorgehobenen oder Blog-Seite würde keine Seitennavigation angezeigt, bis der Benutzer den Weiterlesen-Link auswählt. Zu diesem Zeitpunkt würde das Inhaltsverzeichnis des Beiträges angezeigt, das Links zu jeder Seite enthält.
