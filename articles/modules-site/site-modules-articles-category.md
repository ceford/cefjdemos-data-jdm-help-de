<!-- Filename: Help4.x:Site_Modules:_Articles_-_Category / Display title: Module: Beiträge – Kategorie -->

## Beschreibung

Der Modultyp *Artikel - Kategorie* zeigt eine Liste veröffentlichter
Artikel aus einer oder mehreren Kategorien an.

### Allgemeine Elemente

Einige Elemente dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Module-Tab](jdocmanual?article=help/modules/modules-module-tab).
* [Der Menüzuweisung-Tab](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [Der Erweiterte-Tab](jdocmanual?article=help/modules/modules-advanced-tab).
* [Der Berechtigungen-Tab](jdocmanual?article=help/common-elements/edit-permissions).

<!-- ToDo: Ein Tutorial zur Verwendung dieses Moduls -->

## Zugriff

- Wählen Sie **System → Verwaltungsbereich → Seitenmodule** aus dem Administratormenü. Dann...
  - Um ein neues Modul zu erstellen: Wählen Sie die Schaltfläche **Neu** in der Werkzeugleiste. Dann...
    - Wählen Sie den gewünschten Modultyp aus.
  - Um ein vorhandenes Modul zu bearbeiten:
    - Suchen Sie das Modul in der Liste der installierten Module und wählen Sie den Titel-Link in der Spalte **Titel**.

## Screenshot

![articles category module tab](../../../de/images/modules-site/modules-articles-category-module-tab.png)

## Formularfelder

- **Titel** Der Titel des Moduls. Dies ist auch der Titel, der für das Modul abhängig vom Formularfeld *Titel anzeigen* angezeigt wird.

### Modul-Tab

#### Linkes Panel

- **Modus** Wählen Sie den Modus aus. Wenn der *Normale Modus* gewählt wird, konfigurieren Sie das Modul einfach, und es wird eine statische Liste von Artikeln auf den Menüelementen anzeigen, denen Sie das Modul zuweisen. Wenn *Dynamischer Modus* gewählt wird, können Sie das Modul weiterhin normal konfigurieren. Allerdings wird die Kategorieoption nicht mehr verwendet. Stattdessen erkennt das Modul dynamisch, ob Sie sich auf einer Kategorieseite befinden, und zeigt entsprechend die Artikelliste dieser Kategorie an. Im dynamischen Modus ist es am besten, das Modul so einzustellen, dass es auf allen Seiten angezeigt wird, da es dynamisch entscheidet, ob etwas angezeigt wird oder nicht.
- **Auf Artikelseiten anzeigen** Dieser Punkt erscheint, wenn der *Dynamische Modus* ausgewählt ist. Wählen Sie, ob eine Artikelliste auf Artikelseiten angezeigt oder ausgeblendet werden soll. Dies bedeutet, dass das Modul sich dynamisch nur auf Kategorieseiten anzeigt.

### Filteroptionen-Tab

![articles category filtering options tab](../../../en/images/modules-site/modules-articles-category-filtering-options-tab.png)

- **Hervorgehobene Artikel** Hervorgehobene Artikel anzeigen, ausblenden oder nur hervorgehobene Artikel auswählen.
- **Anzahl** Die Anzahl der anzuzeigenden Elemente. Der Standardwert von 0 zeigt alle Artikel an.
- **Kategorie-Filtertyp** Die ausgewählten Kategorien ein- oder ausschließen.
- **Kategorie** Wählen Sie eine oder mehrere Kategorien aus.
- **Artikel aus Unterkategorien** Artikel aus Unterkategorien ein- oder ausschließen.
- **Kategorietiefe** Die Anzahl der Ebenen der Unterkategorien, die zurückgegeben werden.
- **Autoren-Filtertyp** Artikel der ausgewählten Autoren ein- oder ausschließen.
- **Autoren** Wählen Sie einen oder mehrere Autoren aus der Liste aus.
- **Autor-Alias-Filtertyp** Die ausgewählten Autor-Aliase ein- oder ausschließen.
- **Autor-Aliase** Wählen Sie einen oder mehrere Autor-Aliase aus der Liste aus.
- **Artikel-IDs zum Ausschließen** Geben Sie jede Artikel-ID zum Ausschließen in einer neuen Zeile ein.
- **Datumsfilter** Wählen Sie den Datumsfiltertyp aus.
- **Datumsbereichsfeld** Wählen Sie das zu verwendende Datumsbereichsfeld.
- **Startdatum** Wenn oben *Datumsbereich* ausgewählt ist, geben Sie ein Startdatum ein.
- **Bis Datum** Wenn oben *Datumsbereich* ausgewählt ist, geben Sie ein Enddatum ein.
- **Relatives Datum** Wenn oben *Relatives Datum* ausgewählt ist, geben Sie einen numerischen Tageswert ein. Ergebnisse werden relativ zum aktuellen Datum und dem eingegebenen Wert abgerufen.

### Sortieroptionen-Tab

![articles category ordering options tab](../../../en/images/modules-site/modules-articles-category-ordering-options-tab.png)

- **Artikel-Feld zum Sortieren nach** Wählen Sie ein Feld aus der Liste aus. Die *Hervorgehobene Sortierung* sollte nur verwendet werden, wenn die Filteroption für hervorgehobene Artikel auf *Nur* gesetzt ist.
- **Sortierrichtung** Wählen Sie die Sortierrichtung der Artikel.

### Gruppierungsoptionen-Tab

![articles category grouping options tab](../../../en/images/modules-site/modules-articles-category-grouping-options-tab.png)

- **Artikelgruppierung** Wählen Sie eine Methode zur Gruppierung der Artikel aus der Liste.
- **Gruppierungsrichtung** Wählen Sie die Sortierrichtung der Gruppen.
- **Anzeigeformat für Monat und Jahr** Geben Sie ein gültiges Datumsformat ein.

### Anzeigeoptionen-Tab

![articles category display options tab](../../../en/images/modules-site/modules-articles-category-display-options-tab.png)

- **Verlinkte Titel** Zeigen Sie die Titel als Links zu den Artikeln an.
- **Datum** Zeigen Sie das Artikeldatum an oder blenden Sie es aus.
- **Datumsfeld** Wählen Sie das anzuzeigende Datumsfeld aus.
- **Datumsformat** Geben Sie ein gültiges Datumsformat ein.
- **Kategorie** Zeigen Sie den Namen der Artikelkategorie an oder blenden Sie ihn aus.
- **Aufrufe** Zeigen Sie die Anzahl der Artikelaufrufe an oder blenden Sie sie aus.
- **Autor** Zeigen Sie den Namen des Autors oder des Autor-Alias an oder blenden Sie ihn aus.
- **Introtext** Zeigen Sie den Einleitungstext des Artikels an oder blenden Sie ihn aus.
- **Introtext-Limit** Die maximale Anzahl an Zeichen, die angezeigt werden sollen.
- **"Weiterlesen" anzeigen** Zeigen oder blenden Sie den *Weiterlesen...*-Link ein, wenn der Haupttext des Artikels vorhanden ist.
- **Titel bei "Weiterlesen" anzeigen** Zeigen oder blenden Sie den Titel des Artikels im *Weiterlesen...*-Link ein.
- **Weiterlesen-Limit** Begrenzen Sie die Anzahl der Zeichen des Artikeltitels, die im *Weiterlesen...*-Link angezeigt werden.
