<!-- Filename: Help4.x:Extensions:_Install / Display title: Erweiterungen: Installieren -->

## Beschreibung

Erweiterungen sind Add-ons, die die Funktionalität von Joomla!
erweitern. Erweiterungen werden verwendet, um Joomla! Funktionen
hinzuzufügen, die im Standardpaket nicht vorhanden sind. Hunderte von
Erweiterungen sind für Joomla! verfügbar, wobei ständig weitere
entwickelt werden.

Erweiterungen sind in fünf Kategorien unterteilt, die sich wie folgt
zusammenfassen lassen:

- Eine *Komponente* ist eine Mini-Applikation, die den Hauptteil der
  Seite erzeugt. Beispiele sind Kontakte, die Hauptseite und Newsfeeds.
- Ein *Modul* ist eine kleinere Erweiterung, typischerweise zum Erzeugen
  kleiner Elemente über mehrere Seiten. Beispiele sind Menüs und
  ähnliche Beiträge.
- Ein *Plugin* wird bei einem vordefiniertem Ereignis innerhalb von
  Joomla! gestartet. Beispielsweise sind das Editoren, die gestartet
  werden, wenn ein Beitrag zum Bearbeiten geöffnet wird.
- Die *Sprachen*-Erweiterung kann im Front- und Backend von Joomla! jede
  verfügbare Sprache anzeigen. So kann Joomla!, ohne Änderungen im
  Kern-Programm, mit einer neuen Sprache veröffentlicht werden.
- Ein *Template* steuert die Art und Weise, wie der Inhalt einer Website
  angezeigt wird, einschließlich der Position und des Layouts von
  Elementen, Farben, Schriftarten und so weiter. Templates ermöglichen
  die Trennung des Erscheinungsbildes einer Website von ihrem Inhalt.

## Gemeinsame Elemente ¶

Einige Elemente dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Symbolleisten](jdocmanual?article=help/common-elements/toolbars).

## Wie darauf zugreifen

- Im Administrator-Menü die Option
  **System → Erweiterungen → Erweiterungen** wählen.

Es stehen vier Installationsmethoden zur Verfügung. Wenn **Install from Web** als erstes in der Liste steht oder als letzte Methode ausgewählt wurde, gibt es eine kurze Verzögerung, während Joomla eine erste Auswahl an Erweiterungsdaten aus dem Joomla Extensions Directory herunterlädt.

Die normale Registerkartenreihenfolge für die Installationsmethoden ist wie folgt:

* Paketdatei hochladen
* Aus Ordner installieren
* Von URL installieren
* Aus dem Web installieren

Es ist nur eine Methode erforderlich, um eine bestimmte Erweiterung zu installieren. Das übliche Verfahren zur Installation einer Joomla!-Erweiterung ist wie folgt:

1.  Download einer oder mehrerer Archiv-Dateien (meistens ".zip" oder
    "tar.gz") von der Herstellerseite der Erweiterung in ein lokales
    Computerverzeichnis. Einige Erweiterungen werden als einzelne Datei
    installiert (z.B. eine Komponente oder ein Modul), während andere
    Erweiterungen zwei oder mehr Dateien enthalten können (z.B. eine
    Komponente und ein Modul). Wenn es zwei oder mehr Teile gibt, hat
    jeder Teil seine eigene Archivdatei.
2.  Auswählen einer der unten beschriebenen Methoden (normalerweise
    **Paketdatei hochladen**)
3.  Nach Beendigung zeigt eine Meldung die *erfolgreiche Installation*.
    War die Installation nicht erfolgreich, wird eine Fehlermeldung
    angezeigt.
4.  Je nach Erweiterung kann es notwendig werden, die Erweiterung zu
    aktivieren (z.B. in der Liste der Module oder Liste der Plugins).

### Paketdatei hochladen

![Extension install upload package file tab](../../../de/images/extensions/install-upload-package-file.png)

- Per Drag & Drop die Archivdatei der Erweiterung in den Kasten ziehen
  oder auf die Schaltfläche klicken, um eine Datei zum Hochladen
  auszuwählen.

Der Upload beginnt automatisch. Dabei ist die **Maximale Hochladegröße:
X.00 MB** zu beachten, die für diese Installation definiert ist. Wenn
Sie keine Berechtigung haben um diesen Wert zu erhöhen, können Sie, bei
größeren Dateien, die Option *Aus Verzeichnis installieren* verwenden.

### Aus Verzeichnis installieren

![Extension install from folder tab](../../../de/images/extensions/install-from-folder.png)

1.  Ein temporäres Verzeichnis auf der lokalen Festplatte anlegen und
    die Archivdatei der Erweiterung in dieses temporäre Verzeichnis
    entpacken.
2.  Mit FTP den Inhalt dieses Verzeichnisses (einschließlich aller
    Dateien und Unterverzeichnisse) in ein Verzeichnis auf dem Server
    hochladen.
3.  Im Feld *Aus Verzeichnis installieren* das Serververzeichnis
    angeben, in das die Dateien und Unterverzeichnisse des Pakets
    hochgeladen wurden.
4.  Ein Klick auf die Schaltfläche *Überprüfen und installieren* dann
    startet Joomla! die Installation des Inhalts in dem angegebenen
    Verzeichnis.

Es ist üblich, das Verzeichnis, das die entpackte Erweiterung enthält,
in das tmp-Verzeichnis der Joomla Site zu legen.

### Von URL installieren

![Extension install from url tab](../../../de/images/extensions/install-from-url.png)

Anstatt die Archivdatei auf den lokalen Rechner herunterzuladen, kann
man die Ziel-URL der Archivdatei angeben. Danach auf die Schaltfläche
"Überprüfen und installieren" klicken und Joomla! installiert die
Erweiterung automatisch direkt von dieser URL. Hinweis: Bei dieser
Methode befindet sich keine Kopie der Archivdatei auf dem lokalen
Computer.

## Registerkarte "Vom Web installieren"

Um eine Erweiterung direkt aus dem Joomla Extension Directory (JED) zu installieren. Sie können Erweiterungen nach Kategorie auflisten oder nach einem Teilnamen suchen.

![Erweiterung vom Web installieren Registerkarte](../../../de/images/extensions/install-from-web.png)

## Tipps

- Es gibt vier unterschiedliche Möglichkeiten, eine Erweiterung zu
  installieren. Am gängigsten ist die „Paketdatei hochladen“ Methode.
- Soll ein Modul oder Plugin einer Komponente eines Drittherstellers
  installiert werden, muss meist auch die Komponente installiert werden.
  Die Dokumentation befindet sich meist in den Installations-Anweisungen
  der Website des Herstellers.
- Ähnliches gilt für das Deinstallieren der Komponente eines
  Drittherstellers, die eigene Module oder Plugins mitbringen; beides
  kann dann nicht mehr verwendet werden. Deswegen wird empfohlen, diese
  Module und Plugins ebenfalls zu deinstallieren.
- Einige Komponenten von Drittherstellern können ihre eigenen Module und
  Plugins im Installer enthalten. In dem Fall ist darauf zu achten, dass
  diese Modul- oder Plugin-Verzeichnisse beschreibbar sind. Andernfalls
  wird die Erweiterung nicht ordnungsgemäß laufen.
- **SICHERHEITSWARNUNG:** Es wird empfohlen, nur wirklich notwendige
  Erweiterungen von Drittherstellern zu verwenden. Eine Live-Site sollte
  nicht für Testzwecke benutzt werden, da sie oder der Server gefährdet
  werden kann. Neue Erweiterungen besser mit einer lokalen Website
  testen.
- Joomla!-Erweiterungen nicht von Warez-Sites herunterladen, das sie
  Schadsoftware enthalten können, die den Webserver oder die Computer
  der Site-Besucher gefährden!
- Die Installation von einer externen URL kann riskant sein. Aus diesem
  Grund wird allgemein empfohlen, bei der Installation neuer
  Erweiterungen die Optionen „Aus Webkatalog installieren“, „Paketdatei
  hochladen“ oder „Aus Verzeichnis installieren“ zu verwenden.

<!-- Translated from English with ChatGPT 2024-09-02 ->
