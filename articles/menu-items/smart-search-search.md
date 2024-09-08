<!-- Filename: Help4.x:Menu_Item:_Search / Display title: Suche -->

## Beschreibung

Der Menüpunkt **Suche** wird verwendet, um eine Seite für Smart-Suchergebnisse zu erstellen. Er kann in Verbindung mit einem Smart-Suchmodul verwendet werden, um das Layout der Suchergebnisseite zu steuern.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Symbolleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Details-Tab](jdocmanual?article=help/menu-items-common/menu-item-details).
* [Der Integration-Tab](jdocmanual?article=help/menu-items-common/menu-item-integration).
* [Der Link-Typ-Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [Der Seitendarstellungs-Tab](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [Der Metadaten-Tab](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [Der Zuordnungs-Tab](jdocmanual?article=help/common-elements/edit-associations).
* [Der Modulzuweisungs-Tab](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## So greifen Sie zu

Um einen neuen Suchmenüpunkt zu erstellen:

- Wählen Sie **Menüs → \[Name des Menüs\]** aus dem Administrator-Menü (zum Beispiel, **Menüs → Hauptmenü**). Dann...
  - Wählen Sie die Schaltfläche **Neu** in der Symbolleiste. Dann...
  - Wählen Sie die Schaltfläche zum Auswählen des Menüpunkt-Typs.
  - Wählen Sie im Dialogfeld den Punkt "Smart Search" aus, um eine Liste zu öffnen, und wählen Sie dann den Menüpunkt **Suche**.

Um einen bestehenden Suchmenüpunkt zu bearbeiten:

- Wählen Sie dessen Titel in der Liste der Menüpunkte.

## Screenshot

![Menüpunkt Smart Search Details-Tab](../../../de/images/menu-items/smart-search-search-details-tab.png)

## Formularfelder

Wenn *Global verwenden* für eine Option ausgewählt ist, wird der Standardwert aus den *Smart Search: Optionen* verwendet.

### Optionen-Tab

![Menüpunkt Smart Search Optionen-Tab](../../../de/images/menu-items/smart-search-search-options-tab.png)

- **Datumsfilter** Anzeigen oder Ausblenden der Start- und Enddatumsfilter in der erweiterten Suche.
- **Erweiterte Suche** Erweitertes Suchfeld anzeigen oder ausblenden.
- **Erweiterte Suche ausklappen** Die erweiterte Suche im ausgeklappten Zustand anzeigen oder ausblenden.
- **Ergebnis-Taxonomie** ...?
- **Ergebnisbeschreibung** Eine Beschreibung unter dem Link in den Suchergebnissen anzeigen oder ausblenden.
- **Beschreibungslänge** Die Anzahl der Zeichen der Beschreibung, die in den Suchergebnissen angezeigt werden soll. Der Standardwert ist 255.
- **Ergebnisdatum** ...?
- **Ergebnis-URL** Die URL des Ergebniselements in den Suchergebnissen anzeigen oder ausblenden. Die URL befindet sich unter der Beschreibung.

### Erweitert-Tab

![Menüpunkt Smart Search Erweitert-Tab](../../../de/images/menu-items/smart-search-search-advanced-tab.png)

- **Anzeigeauswahl** Zeigt oder versteckt die Anzeige # Kontrolle, die es dem Benutzer ermöglicht, die Anzahl der anzuzeigenden Elemente zu wählen.
- **Seitennavigation** Zeigt oder versteckt die Seitennavigation. Die Seitennavigation bietet Links am unteren Ende der Seite, die es dem Benutzer ermöglichen, zu weiteren Seiten zu navigieren. Diese werden benötigt, wenn die aufgelisteten Elemente nicht auf eine Seite passen.
    Folgende Optionen sind verfügbar:
    - *Global verwenden* Standardwert aus den Optionen des Moduls verwenden.
    - *Auto* Seitennavigationslinks werden bei Bedarf angezeigt.
    - *Anzeigen* Seitennavigationslinks werden bei Bedarf angezeigt.
    - *Ausblenden* Seitennavigationslinks werden nicht angezeigt. Hinweis: In diesem Fall können Benutzer nicht zu weiteren Seiten navigieren.
- **Seitennavigation-Ergebnisse** Zeigt oder versteckt die aktuelle Seitenzahl und die Gesamtseitenzahl (zum Beispiel *Seite 1 von 2*) am unteren Ende jeder Seite.
- **Leere Suche zulassen** Wenn ein Filter ausgewählt ist, erlaubt dies eine leere Suchzeichenfolge, um eine Suche mit den Filterbedingungen zu starten.
- **Meinten Sie** Gibt an, ob alternative Suchbegriffe vorgeschlagen werden sollen, wenn eine Suche keine Ergebnisse liefert.
- **Suchanfrage-Erklärung** Zeigt oder versteckt eine detaillierte Erklärung der angeforderten Suche.
- **Sortierfelder anzeigen** Zusätzliche Sortierfelder anzeigen oder ausblenden.
- **Zusätzliche Sortierfelder**: Wählen Sie eines oder mehrere Felder, nach denen die Suchergebnisse sortiert werden sollen:
  - *Relevanz* Ergebnisse nach Relevanz sortieren.
  - *Titel* Ergebnisse nach Titel sortieren.
  - *Datum* Ergebnisse nach Datum sortieren.
  - *Listenpreis* Ergebnisse nach Listenpreis sortieren.
  - *Verkaufspreis* Ergebnisse nach Verkaufspreis sortieren.
- **Sortierrichtung** Richtung zur Sortierung der Suchergebnisse.
