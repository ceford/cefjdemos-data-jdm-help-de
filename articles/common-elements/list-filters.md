<!-- Filename: Help6.x:List_Filters / Display title: Listenfilter -->

## Zweck¶

Die meisten Komponenten verfügen über Listenansichten, die Elemente aus der Datenbank anzeigen. Dort
kann Hunderte von Gegenständen sein, vielleicht Tausende oder sogar Millionen. Also listen Sie Filter auf
werden verwendet, um die angezeigte Liste auf diejenigen zu reduzieren, die wahrscheinlich die von Ihnen
ich muss daran arbeiten.

Beispielsweise werden Papierkorb-Elemente normalerweise standardmäßig nicht angezeigt. Wenn Sie es wünschen
um Ihre Papierkorbartikel anzuzeigen, müssen Sie den Filter ** - Select Status - ** auf setzen
** Weggeworfen **. Der folgende Screenshot zeigt die Filter für die Artikelseite.

## Filteroptionen für Artikellisten¶

![Artikelliste](../../../de/images/common-elements/articles-list-filter-options.png)

Um die Optionen **anzuzeigen** oder **auszublenden**, wählen Sie die Schaltfläche **Filteroptionen**. Beachten
dass die Optionen immer angezeigt werden, wenn Sie zu einer Seite zurückkehren, auf der eine Option angezeigt wird
ausgewählt wurde.

Die Anzahl der angezeigten Optionen variiert je nach Komponente. Sogar der Inhalt
komponente, die die Artikelliste anzeigt, kann zusätzliche Filter haben. Für
beispiel: Ein **- Select Stage -**-Filter wird angezeigt, wenn die Inhaltskomponente
hat ** Workflows ** aktiviert.

## Die Suchleiste

### Suche nach Text

* Bewegen Sie den Mauszeiger* oder *wählen Sie* das *Suchfeld* aus, um einen *Tooltip* anzuzeigen oder ein *Audio zu hören*
äquivalent, das angibt, welche Felder durchsucht werden. Standardverhalten
ist es, nach dem eingegebenen Text innerhalb des Titeltextes zu suchen.

Die Inhaltskomponente ermöglicht die Suche nach einem Präfix innerhalb der ID, des Autors oder
Inhalt. Jeder dieser Begriffe benötigt einen Doppelpunkt, kann aber in jedem *Fall* sein, Z
beispiel *ID:19* oder *Autor: John* oder *Inhalt: lorem ipsum*.

Um eine Suche durchzuführen, geben Sie einen Teil des Suchbegriffs ein und wählen Sie die **Suche**
symbol (<span class="filter-search-bar__button-icon icon-search" aria-hidden="true"></span>).

### Filteroptionen und Löschen

Die Schaltfläche **Filteroptionen** wird verwendet, um die Ansicht der verschiedenen Filter umzuschalten. Wenn
es gibt keine Filter für eine Komponente, für die diese Schaltfläche fehlt.

Die Schaltfläche **Löschen** wird verwendet, um alle Filter zu löschen und die Liste wiederherzustellen
ungefilterter Zustand. Wenn für eine Komponente keine Filter vorhanden sind, wird diese Schaltfläche angezeigt
abwesend.

### Reihenfolge der Ergebnisse

Die Reihenfolge, in der die Ergebnisse präsentiert werden, ist vom Benutzer wählbar. Für Artikel, die
die Standardreihenfolge ist *ID absteigend*, wodurch die neuesten Artikel an die
ganz oben auf der Liste. Vielleicht möchten Sie aber nach Artikeln mit den meisten Treffern suchen,
*Treffer absteigend* oder Artikel, die bald verschwinden werden,
*Veröffentlichung aufsteigend beenden*.

Die Ergebnisreihenfolge kann durch Auswahl eines Bestellsymbols in der Liste geändert werden
Spaltenüberschriften. Das Standardsymbol *ID absteigend* wird durch a dargestellt
Einfügemarke nach unten (<span class="ms-1 icon-caret-down" aria-hidden="true"></span>).
Es ändert sich in ein Aufwärts-Caret, wenn die Sortierreihenfolge umgekehrt wird, *ID aufsteigend*.

### Anzahl der Ergebnisse

Die Anzahl der Ergebnisse in einer Liste wird auf der globalen Konfigurationsseite Site festgelegt
registerkarte, Feld Standardlistenlimit. Der Standardwert für eine Neuinstallation ist 20.

Es gibt Gelegenheiten, in denen dies nicht bequem ist. Vielleicht möchten Sie *50* sehen oder
*100*. Seien Sie vorsichtig, wenn Sie *Alle* auswählen. Das Abrufen kann lange dauern
ergebnisse und rendern der Seite. Der Server mein Speicherlauf oder Zeit und Trigger
ein fataler Fehler. Und Ihr Browser kann lange brauchen, um die Seite anzuzeigen.

Der Standardwert für diesen Dokumentationssatz wurde auf 5 festgelegt, da dies der Fall ist
ausreichend für anschauliche Screenshots.

## Verwendung von Filtern

Der Zweck jedes Filters sollte aus seinem ungefilterten Selektor ersichtlich sein
Etikett. Zum Beispiel bietet der Filter Artikel **- Status auswählen -** fünf
auswahlmöglichkeiten: *Papierkorb*, *Unveröffentlicht*, *Veröffentlicht*, *Archiviert* und *Alle*. Der letzte
ist funktional äquivalent zu ungefiltert (*- Status auswählen -*).

Wenn eine Filteroption geändert wird, wird die Seite automatisch mit der neuen neu geladen
ergebnisse, die mit der neuen Filteroption gefiltert wurden.

## Spalten ausblenden

Einige Komponentenlisten haben viele Spalten und sind möglicherweise zu breit für Ihren Bildschirm. Dieser
gilt insbesondere für einige Übersetzungen des Spaltenüberschriftentextes. Am meisten
ärgerliches Ergebnis ist, dass die Titel möglicherweise umgebrochen werden und schwer zu lesen sind.

Um mehr Platz für den Titel zu schaffen, können Sie die Dropdown-Liste Spalten öffnen und
wählen Sie weniger wichtige Spalten zum Ausblenden aus. Schließen Sie dann die Spaltenliste wieder. Der
effekt ist sofort, da JavaScript verwendet wird, um die ausgewählten Spalten in der auszublenden
Layout. Sie sind immer noch auf der Seite vorhanden.

Ihre Einstellungen werden von Ihrem Browser gespeichert und werden so lange verwendet, bis Sie sie ändern
auch wenn Sie sich abmelden und erneut anmelden.