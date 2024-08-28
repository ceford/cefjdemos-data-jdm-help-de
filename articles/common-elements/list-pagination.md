<!-- Filename: Help6.x:List_Pagination / Display title: Listenseitenumbruch -->

## Zweck¶

Die meisten Komponenten verfügen über Listenansichten, die Elemente aus der Datenbank anzeigen. Dort
kann Hunderte von Gegenständen sein, vielleicht Tausende oder sogar Millionen. Standard
*Listenlimit*, die Anzahl der auf einer Ergebnisseite angezeigten Elemente, beträgt normalerweise 20.
Unter jeder Ergebnisseite, wenn mehr Ergebnisse als das aktuelle Limit vorhanden sind,
sie finden eine *Paginierungsleiste*:

![Artikelliste Paginierungsleiste](../../../de/images/common-elements/articles-list-pagination-bar.png)

Wenn die erste Zahl in der Paginierungsleiste ausgewählt ist, werden die ersten 20 Ergebnisse angezeigt
in der Liste angezeigt werden, oder welche Anzahl von Ergebnissen auch immer das Listenlimit war
einstellen auf. Wählen Sie die nächste Nummer oder das nächste Symbol
(<span class="icon-angle-right"></span>), um zur nächsten Seite der Elemente zu gelangen.ngen.

Die maximale Anzahl von Seiten, die in einer einzelnen Paginierungsleiste angezeigt werden, beträgt 10.
Es werden jedoch Seitenzahlen unterhalb und oberhalb der aktuellen Seite angezeigt, um
es ist einfach, eine Seite nach der anderen weiterzugehen oder zurückzugehen.

Hier ist ein Screenshot der Plugin-Liste, die auf Seite 10 mit dem verschoben wurde
Listenlimit auf 5 gesetzt:

![Plugins Liste Paginierungsleiste](../../../de/images/common-elements/plugins-list-pagination-bar.png)

### Symbol

* <span class="icon-angle-double-left"></span> Gehen Sie zur *Ersten* Seite.te.
* <span class="icon-angle-left"></span> Gehen Sie zur *Vorherigen*en* Seite.
* <span class="icon-angle-right"></span> Gehen Sie zur *Nä*Nächsten* Seite.
* <span class="icon-angle-double-right"></span> Geh> Gehe zur *Letzten* Seite

Auf Seite eins sind die Symbole *Erste* Seite und *Vorherige* Seite deaktiviert. Auf der
letzte Seite Die Symbole *Nächste* Seite und *Leaktiviert.