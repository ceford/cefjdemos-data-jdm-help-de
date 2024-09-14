<!-- Filename: Help4.x:Articles:_Options / Display title: Beiträge: Optionen -->

## Beschreibung

Die Seite *Beiträge: Optionen* wird verwendet, um globale Standardwerte für Beiträge festzulegen. Diese werden verwendet, wenn für eine Option in einem Beiträgemenüpunkt *Global verwenden* ausgewählt ist. Zum Beispiel, um das *Erstellungsdatum* eines Beiträges in Ihren Beiträgemenüpunkten anzuzeigen, setzen Sie diese Option hier auf *Anzeigen*, und es wird der Standardwert.

### Allgemeine Elemente

Einige Aspekte dieser Seite werden in separaten HilfsBeiträgen behandelt:

* [Symbolleisten](jdocmanual?article=hilfe/gemeinsame-elemente/symbolleisten).
* [Der Berechtigungs-Tab](jdocmanual?article=hilfe/gemeinsame-elemente/bearbeiten-berechtigungen).

## Zugriff

Wählen Sie die Schaltfläche **Optionen** in der Symbolleiste einer beliebigen *Beiträge* Listen-Seite.

## Screenshot

![Beiträge Optionen Screenshot](../../../de/images/articles/articles-options-articles-tab.png)

## Formularfelder

### Beiträge-Tab

Diese Einstellungen gelten für Beiträgelayouts, es sei denn, sie werden für einen bestimmten Menüpunkt oder Beiträge geändert.

- **Layout wählen** Wählen Sie den Standardwert für EinzelBeiträge-Menüpunkte.
- **Titel** Zeigt den Titel des Beiträges an.
- **Verlinkte Titel** Zeigt den Titel als Link zum Beiträge.
- **Intro-Text**
  - **Anzeigen** Der Intro-Text des Beiträges wird im vollständigen Beiträge angezeigt.
  - **Ausblenden** Nur der Teil des Beiträges nach dem „Weiterlesen“-Umbruch wird im vollständigen Beiträge angezeigt.
- **Position der Beiträgeinfo**
  - **Oben** Platziert den Informationsblock des Beiträges über dem Text.
  - *Unten* Platziert den Informationsblock des Beiträges unter dem Text.
  - *Geteilt* Teilt den Informationsblock des Beiträges in zwei separate Blöcke. Ein Block befindet sich über dem Text, der andere darunter.
- **Beiträgeinfo-Titel** Zeigt das Wort *Details* über dem Informationsblock des Beiträges an.
- **Kategorie** Zeigt den Titel der Kategorie des Beiträges an.
  - **Kategorie verlinken** Zeigt den Titel als Link zu dieser Kategorie an. Hinweis: Dies kann entweder für ein Blog- oder Listenlayout mit der Option *Layout wählen* im Kategoriereiter festgelegt werden.
- **Übergeordnete Kategorie** Zeigt den Titel der übergeordneten Kategorie des Beiträges an.
  - **Übergeordnete Kategorie verlinken** Zeigt den Titel als Link zu dieser Kategorie an. Hinweis: Dies kann entweder für ein Blog- oder Listenlayout mit der Option *Layout wählen* im Kategoriereiter festgelegt werden.
- **Verknüpfungen** Zeigt die verknüpften Flaggen oder Sprachcodes an. Nur für Mehrsprachigkeit.
  - **Bild-Flaggen verwenden** Zeigt die Sprachwahl als Bildflaggen an, wenn Verknüpfungen auf *Anzeigen* gesetzt ist.
- **Autor** Zeigt den Autor des Beiträges an.
  - **Link zur Kontaktseite des Autors** Zeigt es als Link zu einem Kontaktlayout für diesen Autor an. Hinweis: Der Autor muss als Kontakt eingerichtet sein. Ein Link wird nicht angezeigt, wenn ein Autor-Alias für den Kontaktwert vorhanden ist.
- **Erstellungsdatum** Zeigt das Erstellungsdatum des Beiträges an.
- **Änderungsdatum** Zeigt das Änderungsdatum des Beiträges an.
- **Veröffentlichungsdatum** Zeigt das Startdatum der Veröffentlichung des Beiträges an.
- **Navigation** Zeigt einen Navigationslink *Vorheriger* oder *Nächster* an.
- **"Weiterlesen"-Link** Zeigt den „Weiterlesen“-Link an, um von dem Teil des Beiträges vor dem Umbruch „Weiterlesen“ zum Rest des Beiträges zu verlinken.
- **Weiterlesen mit Titel**
  - *Anzeigen* Der Titel des Beiträges ist Teil des „Weiterlesen“-Links. Der Link wird im Format "Weiterlesen: \[Beiträge-Titel\]" angezeigt.
  - *Ausblenden* Der Link wird "Weiterlesen" lauten.
- **Weiterlesen-Limit (Zeichen)** Die maximale Anzahl von Zeichen, die aus dem Titel eingeschlossen werden soll. Hinweis: Dies kann verhindern, dass der „Weiterlesen“-Text zu lang wird, wenn der Beiträge einen sehr langen Titel hat.
- **Tags** Zeigt die Tags für jeden Beiträge an.
- **Aufrufe aufzeichnen** Zeichnet die Anzahl der Aufrufe des Beiträges auf.
- **Aufrufe** Zeigt die Anzahl der Aufrufe des Beiträges durch Benutzer an.
- **Unautorisierte Links**
  - *Ja* Der Intro-Text für eingeschränkte Beiträge wird angezeigt. Durch Klicken auf den „Weiterlesen“-Link müssen sich Benutzer anmelden, um den vollständigen Beiträgeinhalt anzuzeigen.
  - *Nein* Beiträge, die der Benutzer nicht sehen darf (basierend auf der Zugriffsebene des Beiträges), werden nicht angezeigt.
- **Position der Links**
  - *Oben* Links werden über dem Inhalt angezeigt.
  - *Unten* Links werden unter dem Inhalt angezeigt.

### Bearbeitungs-Layout-Tab

Diese Optionen steuern das Layout der Beiträgeseite zur Bearbeitung.

![Beiträge Optionen Bearbeitungs layout tab](../../../de/images/articles/articles-options-editing-layout-tab.png)

- **Captcha bei Übermittlung zulassen** Wählen Sie das Captcha-Plugin, das im Formular zur Beiträgeübermittlung verwendet wird. Wenn *Global verwenden* ausgewählt ist, stellen Sie sicher, dass in den globalen Konfigurationen ein Captcha-Plugin ausgewählt ist.
- **Veröffentlichungsoptionen** Blendet den Veröffentlichungsoptionen-Tab im Backend bei der Bearbeitung von Beiträgen aus. Das bedeutet, dass Backend-Benutzer die Felder in diesem Tab nicht bearbeiten können. Diese Felder werden immer auf ihre Standardwerte gesetzt.
- **Beiträgeoptionen** Blendet den Beiträgeoptionen-Tab im Backend bei der Bearbeitung von Beiträgen aus. Das bedeutet, dass Backend-Benutzer die Felder in diesem Tab nicht bearbeiten können. Diese Felder werden immer auf ihre Standardwerte gesetzt.
- **Bearbeiten-Bildschirmoptionen** Blendet den Konfigurations-Bearbeiten-Bildschirm-Tab bei der Bearbeitung von Beiträgen aus.
- **Beiträge-Berechtigungen** Blendet den Berechtigungen-Tab bei der Bearbeitung von Beiträgen aus.
- **Mehrsprachige Verknüpfungen** Blendet den Verknüpfungen-Tab bei der Bearbeitung von Beiträgen aus.
- **Versionen aktivieren** Speichert Versionsverläufe für Beiträge und Kategorien.
- **Maximale Versionen** Die maximale Anzahl von Versionen, die für einen Beiträge oder eine Kategorie gespeichert werden. Wenn ein Beiträge oder eine Kategorie gespeichert wird und die maximale Anzahl an Versionen erreicht ist, wird die älteste Version automatisch gelöscht. Wenn auf „0“ gesetzt, werden Versionen niemals automatisch gelöscht.
- **Frontend-Bilder und Links** Blendet den Bilder- und Links-Tab im Frontend-Beiträge-Editor aus.
- **Administrator-Bilder und Links** Blendet den Bilder- und Links-Tab im Backend bei der Bearbeitung von Beiträgen aus.
- **URL A Ziel-Fenster** Legt den Standardwert für das Ziel des ersten Links im Beiträge fest. Optionen sind:
  - *Im übergeordneten Fenster öffnen* Öffnet den Link im Hauptbrowserfenster und ersetzt den aktuellen Joomla-Beiträge.
  - *In neuem Fenster öffnen* Öffnet den Link in einem neuen Browserfenster.
  - *Im Popup öffnen* Öffnet den Link in einem Popup-Browserfenster (ohne vollständige Navigationssteuerung).
  - *Modal* Öffnet den Link in einem modalen Popup-Fenster.
- **URL B Ziel-Fenster** Legt den Standardwert für das Ziel des zweiten Links im Beiträge fest. Gleiche Optionen wie URL A.
- **URL C Ziel-Fenster** Legt den Standardwert für das Ziel des dritten Links im Beiträge fest. Gleiche Optionen wie URL A.
- **Intro-Bild-Klasse** Legt das Klassenattribut für ein Intro-Bild fest, das im Feld Intro-Bild ausgewählt wurde.
- **Volltext-Bild-Klasse** Legt das Klassenattribut für ein Volltext-Bild fest, das im Feld Vollständiger Beiträge-Bild ausgewählt wurde.

### Kategorie-Tab

Diese Einstellungen gelten für die Optionen der Beiträge-Kategorie, sofern sie nicht durch die individuellen Kategorie- oder Menüeinstellungen geändert werden.

![Beiträgeoptionen Kategorie-Tab](../../../de/images/articles/articles-options-category-tab.png)

- **Layout auswählen** Wählen Sie das Standardlayout, das angezeigt wird, wenn ein Kategorienlink ausgewählt wird.
- **Kategorietitel** Zeigt den Titel der Kategorie an.
- **Kategoriebeschreibung** Zeigt die Beschreibung der Kategorie an.
- **Kategoriebild** Zeigt das Kategoriebild an.
- **Unterkategorie-Ebenen** Steuern Sie, wie viele Ebenen von Unterkategorien angezeigt werden.
- **Leere Kategorien** Zeigen Sie Kategorien an, die keine Beiträge oder Unterkategorien enthalten.
- **Keine Beiträge-Nachricht** Zeigen Sie die Nachricht „Es gibt keine Beiträge in dieser Kategorie“ an.
- **Unterkategorien-Überschrift** Zeigt die Unterkategorien als Unterüberschrift auf der Seite an.
- **Unterkategorie-Beschreibungen** Zeigen Sie die Beschreibungen für die Unterkategorien an.
- **\# Beiträge in der Kategorie** Zeigt die Anzahl der Beiträge in jeder Kategorie an.
- **Tags** Zeigen Sie die Tags für die Kategorie an.

### Kategorien-Tab

Diese Einstellungen gelten für die Optionen der Beiträge-Kategorien, sofern sie nicht durch die individuellen Kategorie- oder Menüeinstellungen geändert werden.

![Beiträgeoptionen Kategorien-Tab](../../../de/images/articles/articles-options-categories-tab.png)

- **Beschreibung der obersten Kategorieebene** Zeigen Sie die Beschreibung für die oberste Kategorieebene an.
- **Unterkategorie-Ebenen** Steuern Sie, wie viele Ebenen von Unterkategorien angezeigt werden.
- **Leere Kategorien** Zeigen Sie Kategorien an, die keine Beiträge oder Unterkategorien enthalten.
- **Unterkategorie-Beschreibungen** Zeigen Sie die Beschreibung für Unterkategorien an.
- **\# Beiträge in der Kategorie** Zeigt die Anzahl der Beiträge in jeder Kategorie an.

### Blog/Feature-Layouts-Tab

Diese Einstellungen gelten für Blog- oder Feature-Layouts, sofern sie nicht für einen spezifischen Menüpunkt geändert werden.

![Beiträgeoptionen Blog und Feature Layout-Tab](../../../de/images/articles/articles-options-blog-layouts-tab.png)

- **# LeitBeiträge** Anzahl der Beiträge, die in voller Breite des Hauptanzeigebereichs angezeigt werden. „0“ bedeutet, dass keine Beiträge in voller Breite angezeigt werden. Wenn ein Beiträge einen „Weiterlesen...“-Trennzeichen hat, wird nur der Teil des Textes vor dem Trennzeichen (der Introtext) angezeigt.
- **LeitBeiträge-Klasse** Fügen Sie eine CSS-Klasse hinzu, um das Layout anzupassen. Fügen Sie zum Beispiel mit der Klasse „boxed“ einen Rahmen oben hinzu. Für die Bildposition verwenden Sie beispielsweise „image-left“, „image-right“. Fügen Sie „image-alternate“ hinzu, um eine abwechselnde Reihenfolge der Intro-Bilder zu erzielen.
- **# EinführungsBeiträge** Bestimmt die Anzahl der Beiträge, die nach dem LeitBeiträge angezeigt werden. Diese Beiträge werden in der Anzahl der in der Spalten-Option unten festgelegten Spalten angezeigt. Wenn ein Beiträge einen „Weiterlesen...“-Trennzeichen hat, wird nur der Text vor dem Trennzeichen (Introtext) angezeigt, gefolgt von einem „Weiterlesen...“-Link. Die Reihenfolge, in der die Beiträge angezeigt werden, wird durch die Parameter „Kategorienreihenfolge“ und „Beiträgereihenfolge“ unten bestimmt.
- **Beiträge-Klasse** Fügen Sie eine CSS-Klasse für individuelles Styling hinzu. Fügen Sie einen Rahmen oben mit der Klasse „boxed“ hinzu. Für die Bildposition verwenden Sie zum Beispiel „image-left“, „image-right“. Fügen Sie „image-alternate“ hinzu, um eine abwechselnde Reihenfolge der Intro-Bilder zu erreichen.
- **# Spalten** Die Anzahl der Spalten, die im Bereich der EinführungsBeiträge verwendet werden. Dies liegt normalerweise zwischen 1 und 3 (abhängig von der verwendeten Vorlage). Wenn 1 verwendet wird, werden die EinführungsBeiträge wie die LeitBeiträge in voller Breite des Anzeigebereichs dargestellt.
- **Mehrspalten-Richtung** In mehrspaltigen Blog-Layouts, ob die Beiträge nach unten oder über die Spalten hinweg sortiert werden sollen.
  - *Nach unten* Beiträge werden in der ersten Spalte nach unten geordnet und dann in die nächste Spalte verschoben.
  - *Quer* Beiträge werden quer über die Spalten geordnet und dann zurück zur ersten Spalte.
- **# Links** Die Anzahl der Links, die im Linksbereich der Seite angezeigt werden. Diese Links ermöglichen es einem Benutzer, auf zusätzliche Beiträge zu verlinken, falls mehr Beiträge vorhanden sind, als auf die erste Seite des Blog-Layouts passen.
- **Unterkategorien einbeziehen**
  - *Keine* Es werden nur Beiträge aus der aktuellen Kategorie angezeigt.
  - *Alle* Es werden alle Beiträge aus der aktuellen Kategorie und allen Unterkategorien angezeigt.
  - *1-5* Es werden alle Beiträge aus der aktuellen Kategorie und den Unterkategorien bis einschließlich dieser Ebene angezeigt.
- **Verlinktes Intro-Bild** Wenn Ja, führt ein Klick auf das Intro-Bild zum Beiträge.

### Listen-Layouts-Tab

Diese Einstellungen gelten für Listen-Layouts-Optionen, sofern sie nicht für einen spezifischen Menüpunkt oder eine Kategorie geändert werden.

![Beiträgeoptionen Listen-Layouts-Tab](../../../de/images/articles/articles-options-list-layouts-tab.png)

- **Anzeigeauswahl** Zeigt die „Anzeige \#“-Steuerung an, die es dem Benutzer ermöglicht, die Anzahl der anzuzeigenden Beiträge auszuwählen.
- **Filterfeld** Zeigt ein Textfeld im Frontend an, in dem ein Benutzer die Beiträge filtern kann. Optionen im Backend-Menüpunkt bearbeiten.
  - *Ausblenden* Zeigen Sie kein Filterfeld an.
  - *Titel* Nach Beiträge-Titel filtern.
  - *Autor* Nach Autorennamen filtern.
  - *Zugriffe* Nach der Anzahl der Beiträge-Zugriffe filtern.
  - *Tags* Nach Beiträge-Tags filtern.
  - *Monat (veröffentlicht)* Nach dem Veröffentlichungsmonat der Beiträge filtern.
- **Tabellenüberschriften** Zeigen Sie eine Überschrift in der Beiträgeliste im Frontend an.
- **Datum** Zeigen Sie ein Datum in der Liste an.
  - *Ausblenden* Kein Datum anzeigen.
  - *Erstellt* Zeigt das Erstellungsdatum an.
  - *Geändert* Zeigt das Datum der letzten Änderung an.
  - *Veröffentlicht* Zeigt das Veröffentlichungsdatum an.
- **Zugriffe** Zeigen Sie die Anzahl der Zugriffe auf Beiträge an.
- **Autor** Zeigen Sie den Namen des Autors an.
- **\# Beiträge in der Liste** Anzahl der Beiträge, die in der Liste angezeigt werden.

### Gemeinsamer-Tab

Diese Einstellungen gelten für gemeinsame Optionen in Listen-, Blog- und Feature-Layouts, sofern sie nicht durch die Menüeinstellungen geändert werden.

![Beiträgeoptionen gemeinsamer-Tab](../../../de/images/articles/articles-options-shared-tab.png)

- **Kategorienreihenfolge**
  - *Keine Reihenfolge* Beiträge werden nur nach der Beiträgereihenfolge geordnet, ohne Rücksicht auf die Kategorie.
  - *Alphabetisch (Titel)* Kategorien werden alphabetisch (A bis Z) angezeigt.
  - *Umgekehrt Alphabetisch (Titel)* Kategorien werden in umgekehrter alphabetischer Reihenfolge (Z bis A) angezeigt.
  - *Kategorienreihenfolge* Kategorien werden nach der Reihenfolge der Spalte „Reihenfolge“ in „Beiträge: Kategorien“ sortiert.
- **Beiträgereihenfolge**
  - *Neueste zuerst* Beiträge werden von den neuesten zu den ältesten angezeigt.
  - *Älteste zuerst* Beiträge werden von den ältesten zu den neuesten angezeigt.
  - *Alphabetisch (Titel)* Beiträge werden alphabetisch nach Titel geordnet (A bis Z).
  - *Umgekehrt Alphabetisch (Titel)* Beiträge werden alphabetisch nach Titel in umgekehrter Reihenfolge (Z bis A) geordnet.
  - *Alphabetisch (Autor)* Beiträge werden alphabetisch nach Autor geordnet (A bis Z).
  - *Umgekehrt Alphabetisch (Autor)* Beiträge werden alphabetisch nach Autor in umgekehrter Reihenfolge (Z bis A) geordnet.
  - *Meiste Zugriffe* Beiträge werden nach der Anzahl der Zugriffe geordnet, beginnend mit dem Beiträge mit den meisten Zugriffen.
  - *Wenigste Zugriffe* Beiträge werden nach der Anzahl der Zugriffe geordnet, beginnend mit dem Beiträge mit den wenigsten Zugriffen.
  - *Reihenfolge* Beiträge werden nach der Reihenfolge der Spalte „Reihenfolge“ in „Beiträge“ geordnet.
  - *Umgekehrte Reihenfolge* Beiträge werden in umgekehrter Reihenfolge der Spalte „Reihenfolge“ in „Beiträge“ geordnet.
- **Datum für Sortierung** Das Datum, das verwendet wird, wenn Beiträge nach Datum sortiert werden.
  - *Erstellt* Verwenden Sie das Erstellungsdatum des Beiträges.
  - *Geändert* Verwenden Sie das Änderungsdatum des Beiträges.
  - *Veröffentlicht* Verwenden Sie das Veröffentlichungsdatum des Beiträges.
- **Paginierung** Paginierung bietet Seitenlinks am unteren Rand der Seite, die es dem Benutzer ermöglichen, zu weiteren Seiten zu navigieren. Diese werden benötigt,

 wenn die Beiträge nicht auf eine Seite passen.
  - *Ausblenden* Paginierungs-Links werden nicht angezeigt. Hinweis: Benutzer können nicht zu weiteren Seiten navigieren.
  - *Anzeigen* Paginierungs-Links werden bei Bedarf angezeigt.
  - *Automatisch* Paginierungs-Links werden bei Bedarf angezeigt.
- **Paginierungsübersicht** Zeigen Sie die aktuelle Seitenzahl und die Gesamtseitenzahl (z.B. „Seite 1 von 2“) am unteren Rand jeder Seite an.
- **Hervorgehobene Beiträge**
  - *Anzeigen* Zeigt hervorgehobene und nicht hervorgehobene Beiträge an.
  - *Ausblenden* Zeigt nur nicht hervorgehobene Beiträge an.
  - *Nur* Zeigt nur hervorgehobene Beiträge an.

### Integration-Tab

Diese Einstellungen bestimmen, wie die Beiträge-Komponente mit anderen Erweiterungen integriert wird.

![Beiträgeoptionen Integration-Tab](../../../de/images/articles/articles-options-integration-tab.png)

#### News-Feeds-Panel

- **RSS-Feed-Link** Wenn auf „Anzeigen“ gesetzt, wird ein Feed-Link als Feed-Symbol in der Adressleiste der meisten Browser angezeigt.
- **In Feed einbeziehen**
  - *Introtext* Nur der Introtext des Beiträges wird im Feed angezeigt.
  - *Volltext* Der gesamte Text des Beiträges wird im Feed angezeigt.
- **„Weiterlesen“-Link** Zeigt einen „Weiterlesen“-Link im Feed an.

#### Routing-Panel

- **IDs aus URLs entfernen** Entfernen Sie die Datenbank-IDs von Beiträgen in einem Link.

#### Benutzerdefinierte-Felder-Panel

- **Benutzerdefinierte Felder bearbeiten** Aktivieren Sie die Erstellung benutzerdefinierter Felder.

#### Workflow-Panel

- **Workflow aktivieren** Verwenden Sie angepasste Workflows zur Verwaltung von Beiträgen.

## Tipps

- Anfänger können die Standardwerte hier beibehalten.
- Erfahrene Benutzer können Zeit sparen, indem sie hier geeignete Standardwerte festlegen. Neue Menüpunkte und Beiträge können dann die Standardwerte für die meisten Optionen verwenden.
- Alle hier festgelegten Werte können auf Menüpunkt-, Kategorie- oder Beiträgeebene überschrieben werden.
