<!-- Filename: Help4.x:Glossary / Display title: Glossar -->

Das Joomla! Glossar ist hilfreich, um gängige Begriffe zu erklären, die in Joomla!-Anleitungen, Hilfebildschirmen und erweiterter Dokumentation verwendet werden.

## Access Control List (Zugriffskontrollliste)

## Alias

## Anker

Ein Anker wird im HTML mit dem `<a>`-Tag erstellt. Ein Anker ermöglicht es, ein Lesezeichen innerhalb einer HTML-Seite zu setzen. In Joomla! können Sie einen Anker in einem Artikel platzieren (z.B. mit dem TinyMCE-Editor). Dies ermöglicht es, einen Link zu erstellen, der direkt zu diesem Punkt im Artikel führt.

Der HTML-Quellcode für einen Anker sieht wie folgt aus:

```html
<a name="mein_anker" title="Mein Anker"></a>
```

Sie können innerhalb derselben Seite mit folgendem HTML-Code auf einen Anker verlinken:

```html
<a href="#mein_anker"></a>
```

Ein Klick auf diesen Link führt Sie direkt zur Position des Anker-Tags.

Sie können auf einen Anker auf einer anderen Seite verlinken, indem Sie "#" und den Namen des Ankers an das Ende der URL anhängen. Im obigen Beispiel, wenn die URL des Artikels `http://www.meineseite.com/mein_artikel.html` lautet, könnten Sie direkt mit der URL `http://www.meineseite.com/mein_artikel.html#mein_anker` auf den Anker verlinken.

## Artikel

## Cascading Style Sheet (CSS)

Ein Cascading Style Sheet oder CSS wird verwendet, um die Präsentation einer XHTML-Seite zu steuern. Beispielsweise steuert eine CSS-Datei oft die Schriftart, Abstände, Farben, Hintergrundgrafiken und andere Aspekte des Aussehens einer Webseite. CSS ermöglicht es, den Inhalt einer XHTML-Seite von ihrem Erscheinungsbild zu trennen. In Joomla! sind CSS-Dateien (z. B. template.css) normalerweise Teil des Templates.

**Siehe auch:** Template, Seitenklassensuffix, Modulklassensuffix

## Kategorie

Jede Joomla!-Webseite oder jede CMS-Webseite benötigt eine Methode, um ihre Inhalte logisch anzuzeigen und zu speichern. Die übliche Methode erfolgt über Kategorien und Unterkategorien. Joomla! ermöglicht mehrere Wege, Inhalte basierend auf der Kategorisierung anzuzeigen und zu verwenden. Einige der Inhaltstypen, die eine Kategorisierung haben, sind Artikel (der Hauptinhalt von Webseiten), Banner und Kontakte.

Eine Kategorie namens *Nicht kategorisiert* ist die Standardkategorie, die den meisten Inhaltstypen zugewiesen wird. Die *Nicht kategorisiert* Kategorie ist nicht beschreibend und sollte nur bei Bedarf für Inhaltstypen verwendet werden, die keiner bestimmten Kategorie zugeordnet sind.

Bei der Erstellung und Zuweisung von Kategorien sollten Sie eine geplante Struktur haben. Hier ist ein Beispiel, wie Sie mehrere Artikel über Vögel kategorisieren können:

- Erstellen Sie zwei Hauptartikelkategorien mit den Namen *Tiere* und *Pflanzen*.
- Unter der Kategorie *Tiere* erstellen Sie Unterkategorien mit den Namen *Vögel* und *Säugetiere*.
- Unter der Unterkategorie *Vögel* erstellen Sie Kategorien mit den Titeln *Falken*, *Papageien* und *Sperlinge*. Dies ist die resultierende Kategoriestruktur:

```
- Tiere
  - Vögel
    - Falken
    - Papageien
    - Sperlinge
  - Säugetiere
```

Nun können Sie mehrere Artikel in den Unterkategorien Falken, Papageien und Sperlinge erstellen, indem Sie die verschiedenen Gattungs- oder allgemeinen Namen der spezifischen Vogelarten verwenden.

## Chrome

Die sichtbaren grafischen Benutzeroberflächenfunktionen einer Anwendung werden manchmal als *Chrome* bezeichnet.

## Komponente

## Core (Kern)

Das Wort *Kern* in Joomla! bezieht sich auf die verteilten Dateien, die benötigt werden, um eine Joomla CMS-Website zu erstellen und zu verwalten. Der Joomla-Kern enthält alle notwendigen Funktionen, um schnell und einfach eine neue Website zu erstellen und zu verwalten.

## Datenbank-Tabellenpräfix

Das Datenbank-Tabellenpräfix ist eine Zeichenfolge (einige Zeichen lang), die den Namen von Joomla!-Tabellen vorangestellt wird. Durch die Verwendung eines Präfixes können Sie mehrere Joomla!-Installationen mit einer einzigen Datenbank betreiben.

Das Datenbank-Tabellenpräfix kann während der Installation festgelegt werden. Eine spätere Änderung ist möglich, erfordert jedoch den Zugriff auf die Datenbank über ein nicht Joomla-Medium oder eine Joomla-Erweiterung wie Akeeba Admin Tools und führt zu einer kurzen Ausfallzeit.

Entwickler von Erweiterungen müssen die Zeichenfolge `#__` verwenden, um das Präfix darzustellen. Diese wird zur Laufzeit durch das tatsächliche Präfix ersetzt.

## Erweiterung

## LDAP

## Sprache

Sprachen sind vielleicht der grundlegendste und kritischste Erweiterungstyp. Sprachen werden entweder als Kern-Sprachpaket oder als Erweiterungs-Sprachpaket bereitgestellt. Diese Pakete bestehen aus INI-Dateien, die Schlüssel/Wert-Paare enthalten, um die Übersetzung statischer Textzeichenfolgen im Joomla!-Quellcode zu ermöglichen. Dies ermöglicht sowohl die Internationalisierung des Joomla!-Kerns als auch von Drittanbieter-Komponenten und -Modulen. Kern-Sprachpakete enthalten auch eine XML-Metadatei, die die Sprache beschreibt und Informationen über die zu verwendenden Schriftarten für die PDF-Erstellung liefert.

## Menü

In Joomla! ist ein **Menü** ein Modul, das eine Reihe von **Menüelementen** enthält, die zur Navigation verwendet werden. Jedes Menüelement definiert eine URL zu einer Seite auf der Website. Es enthält Einstellungen, die die Anzeige des Seiteninhalts und den Stil steuern.

## Model-View-Controller

Joomla! nutzt intensiv das 
<a href="http://de.wikipedia.org/wiki/Model-View-Controller"
class="external text" target="_blank"
rel="nofollow noreferrer noopener">Model-View-Controller</a> Designmuster.

Wenn Joomla gestartet wird, um eine Anfrage eines Benutzers zu verarbeiten, wie z. B. eine GET-Anfrage für eine bestimmte Seite oder eine POST-Anfrage mit Formulardaten, analysiert Joomla zunächst die URL, um zu bestimmen, welche Komponente für die Verarbeitung der Anfrage zuständig ist, und übergibt die Kontrolle an diese Komponente.

Wenn die Komponente nach dem MVC-Muster entwickelt wurde, übergibt sie die Kontrolle an den Controller. Der Controller ist dafür verantwortlich, die Anfrage zu analysieren und zu bestimmen, welches Modell bzw. welche Modelle benötigt werden, um die Anfrage zu erfüllen, und welche Ansicht verwendet werden soll, um die Ergebnisse an den Benutzer zurückzugeben.

Das Modell kapselt die von der Komponente verwendeten Daten. In den meisten Fällen stammen diese Daten aus einer Datenbank, entweder der Joomla-Datenbank oder einer externen Datenbank, aber es ist auch möglich, dass das Modell Daten aus anderen Quellen erhält, z. B. über eine Webservice-API auf einem anderen Server. Das Modell ist auch dafür verantwortlich, die Datenbank gegebenenfalls zu aktualisieren. Ziel des Modells ist es, den Controller und die Ansicht von den Details der Datenbeschaffung oder -änderung zu isolieren.

Die Ansicht ist dafür verantwortlich, die Ausgabe zu generieren, die von der Komponente an den Browser gesendet wird. Sie ruft die benötigten Informationen vom Modell ab und formatiert sie entsprechend. Zum Beispiel könnte eine Liste von Daten, die vom Modell abgerufen wird, in einer HTML-Tabelle von der Ansicht eingebettet werden.

Da Joomla so modular aufgebaut ist, ist die Ausgabe der Komponente normalerweise nur ein Teil der gesamten Webseite, die der Benutzer letztendlich sieht. Nachdem die Ansicht die Ausgabe generiert hat, gibt die Komponente die Kontrolle an das Joomla-Framework zurück, das dann das Template lädt und ausführt. Das Template kombiniert die Ausgabe der Komponente und aller Module, die auf der aktuellen Seite aktiv sind, sodass es als eine einzige Seite an den Browser geliefert werden kann.

Um Webdesignern, die sich möglicherweise nur mit dem Erstellen neuer Designs befassen und nicht mit dem zugrunde liegenden Code, zusätzliche Möglichkeiten und Flexibilität zu bieten, teilt Joomla die traditionelle Ansicht in eine separate Ansicht und ein Layout auf. Die Ansicht holt die Daten aus dem Modell, wie in einem traditionellen MVC-Muster, macht diese Daten dann aber nur für das Layout verfügbar, das für die Formatierung der Daten zur Präsentation an den Benutzer verantwortlich ist. Der Vorteil dieser Trennung besteht darin, dass das Joomla-Templatesystem eine einfache Möglichkeit bietet, Layouts im Template zu überschreiben. Diese Layout-Überschreibungen (oft als "Template-Überschreibungen" bezeichnet, da sie Teil des Templates sind, obwohl eigentlich das Layout überschrieben wird) sind im Template gebündelt und geben dem Template-Designer die volle Kontrolle über die gesamte Ausgabe des Joomla-Kerns und aller installierten Drittanbieter-Erweiterungen, die dem MVC-Designmuster entsprechen.

## Modul

## Modulklassensuffix

Ein Modulklassensuffix ist ein Parameter, der in Modulen verwendet wird, um eine neue CSS-Klasse zu einem Modul hinzuzufügen. Es wird in Verbindung mit Stilen verwendet, die in einer user.css-Datei definiert sind, um das Standardaussehen eines Moduls zu ändern.

Der neue Klassenname kann verwendet werden, um beliebige Stile zum Modul hinzuzufügen, ohne den gesamten vorhandenen CSS-Code neu erstellen zu müssen. Beachten Sie, dass, wenn Sie einen neuen Klassenn

amen erstellen, dieser einen eindeutigen Namen haben sollte und nicht mit bereits bestehenden Klassennamen in Konflikt geraten darf.

## Modulposition

## Modul-Chrome

## PHP

PHP ist eine Skriptsprache, die für die Erstellung dynamischer Webseiten entwickelt wurde. PHP wird weitgehend für die Webentwicklung verwendet und kann in HTML eingebettet werden. Es wird im Allgemeinen auf einem Webserver ausgeführt, der PHP-Code als Eingabe nimmt und Webseiten als Ausgabe erzeugt. Joomla! ist hauptsächlich in der PHP-Sprache geschrieben.

## Seitenklassensuffix

Ein Seitenklassensuffix ist ein Parameter, der in Inhaltsmenüpunkten verwendet wird, um eine neue CSS-Klasse zum Seitenlayout hinzuzufügen. Es wird in Verbindung mit Stilen verwendet, die in einer user.css-Datei definiert sind, um das Standardaussehen eines Moduls zu ändern.

Der neue Klassenname kann verwendet werden, um beliebige Stile zur Seite hinzuzufügen, ohne den gesamten vorhandenen CSS-Code neu erstellen zu müssen. Beachten Sie, dass, wenn Sie einen neuen Klassennamen erstellen, dieser einen eindeutigen Namen haben sollte und nicht mit bereits bestehenden Klassennamen in Konflikt geraten darf.

## Patch

## Plugin

## Suchmaschinenfreundliche URLs

Suchmaschinenfreundliche URLs ist ein Begriff, der häufig als SEF-URLs oder SEF abgekürzt wird. Normale Joomla! URLs sehen etwa so aus:

```html
http://www.ihreseite.org/index.php?option=com_content&view=section&id=3&Itemid=41
```

Sie können optional URLs so anzeigen lassen, dass sie wie statische HTML-Seiten aussehen:

```html
http://www.ihreseite.org/faq.html
```

Es gibt integrierte Optionen zum Generieren von SEF-URLs. Diese sind in den *SEO-Einstellungen* (Suchmaschinenoptimierung) im Reiter "Site" der globalen Konfigurationsseite aktiviert. Es gibt auch Drittanbieter-Erweiterungen, die SEF-URLs für Joomla! erstellen.

## Split-Menüs

Ein Split-Menü zeigt verschiedene Ebenen eines einzigen Menüs an zwei oder mehr Stellen auf einer einzigen Webseite an.

Ein häufiges Beispiel ist, dass ein Menü mit obersten Elementen oben auf der Seite angezeigt wird. Wenn eines dieser Elemente angeklickt wird, gelangt der Benutzer zu einer Seite, auf der ein sekundäres Menü, z. B. auf der linken Seite der Seite, zweite Ebene Elemente im Rahmen des obersten Elements anzeigt.

Die Menüs erscheinen an verschiedenen Stellen auf der Seite, sind jedoch miteinander verbunden, da eines nur oberste Elemente anzeigt, während das andere Elemente der zweiten Ebene anzeigt. Dieses Konzept kann auf Menüs für Elemente der dritten Ebene und darüber hinaus erweitert werden.

Dies kann in Joomla! implementiert werden, indem ein einziges mehrstufiges Menü erstellt wird und dann mehr als ein Menümodul erstellt wird, das sich auf eine andere Ebene bezieht.

## Template

Ein Template ist eine Art Joomla!-Erweiterung, die das Erscheinungsbild der Seite steuert.
- Ein Site-Template steuert das öffentliche Erscheinungsbild der Seiteninhalte.
- Ein Administrator-Template steuert das Erscheinungsbild der Seite für administrative Aufgaben wie: Benutzer-, Menü-, Artikel-, Kategorie-, Modul-, Komponenten-, Plugin- und Template-Verwaltung.

## Template-Stil

## Upgrade-Paket

Ein Upgrade-Paket in Joomla! ist ein Paket von Dateien, die die zwischen Joomla!-Versionen geänderten Dateien enthalten. Wenn dieses Archiv entpackt wird, ersetzt es die alte Version der geänderten Dateien durch die neue Version. Beispielsweise würde das Upgrade-Paket, wenn fünfzig Dateien zwischen Version 5.1 und 5.2 geändert wurden, diese fünfzig Dateien und Anweisungen zur Ausführung des Upgrades enthalten. Manchmal sind auch Datenbankaktualisierungen und das Entfernen nicht mehr verwendeter Dateien erforderlich.
