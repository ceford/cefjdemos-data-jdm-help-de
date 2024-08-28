<!-- Filename: Help6.x:List_Ordering / Display title: Listenreihenfolge -->

## Wo es auf die Bestellung ankommt

Die Reihenfolge der Elemente in einer Liste spielt bei der Anzeige von der Site aus eine Rolle
vorderes Ende. Angenommen, Sie haben eine Reihe von Artikeln, die vorgestellt werden
sie präsentieren in einem Layout für vorgestellte Artikel. Das Menü-Dateneingabeformular dafür
layout bietet eine Reihe von *Artikelreihenfolge*-Alternativen, von denen eine ist
**Bestellung ausgewählter Artikel**. Die Standardreihenfolge ist die Reihenfolge, in der die
artikel werden hinzugefügt. Aber was ist, wenn Sie möchten, dass ein bestimmter Artikel an erster Stelle steht
in der Liste. Wenn Sie einen Ausschuss mit Artikeln zu jedem Mitglied haben, möchten Sie vielleicht
der Vorsitzende soll im Layout der Titelseite an erster Stelle stehen.

Das gleiche Prinzip gilt für Kategorie-Blog-Layouts. Sie können mehrere haben
Ausschüsse, jeweils in einer anderen Kategorie. In diesem Fall filtern Sie die Artikel
listen Sie nach Kategorie auf und machen Sie den Artikel über den Vorsitzenden an die erste Stelle in der Liste.

## Die Bestellspalte

In einer Komponentenlistenansicht ist die Sortierungsspalte normalerweise die zweite von links
(in Sprachen von links nach rechts) direkt neben der Kontrollkästchenspalte. Wenn die
die Liste ist nicht nach der Sortierungsspalte sortiert, sie ist leer. In diesem Fall Sie
sie müssen das Symbol für die Bestellspalte auswählen, einen doppelten Chevron
(<span class="ms-1 icon-sort"></span>). Jedes Mal, wenn das Symbol
ist ausgewählt, wechselt die Reihenfolge von aufsteigend nach absteigend. Du brauchst aufsteigend
reihenfolge (<span class="ms-1 icon-caret-up"></span>) zum Ziehe Ziehen eines
element nach oben zum Anfang der Liste. Dies wird in der Sortierreihenfolge angezeigt
feld der Suchleiste.

## Ziehen und Ablegen

Wenn die Bestellspalte zur Verwendung festgelegt ist, enthält jeder Artikel eine vertikale
ellipsen-Symbol (<span class="icon-ellipsis-v"></span>). Dieses Symbol kann sein
ziehen Sie nach oben oder unten, um die Listenreihenfolge zu ändern. Die neue Listenreihenfolge lautet
mit einem JavaScript-Aufruf in die Datenbank setzen. Es wird keine Seite neu geladen.

Es ist knifflig! Du musst üben. Und dies ist eine der Gelegenheiten, bei denen
sie können das Listenlimit auf *Alle* setzen