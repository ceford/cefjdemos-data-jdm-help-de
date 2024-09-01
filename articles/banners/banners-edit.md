<!-- Filename: Help4.x:Banners:_Edit / Display title: Banner: Bearbeiten -->

## Beschreibung

Wird verwendet, um Banner hinzuzufügen oder zu bearbeiten, die auf Ihrer Joomla!-Website angezeigt werden können. Denken Sie daran, mindestens einen Banner-Kunden und eine Banner-Kategorie zu erstellen, bevor Sie Banner erstellen.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfe-Artikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Veröffentlichungs-Tab](jdocmanual?article=help/common-elements/edit-publishing).

## Zugriff

Aus dem Administrator-Menü:
- Wählen Sie **Komponenten → Banner** aus, um zur Banner-Listen-Seite zu gelangen.
- Wählen Sie die **Neu**-Schaltfläche in der Werkzeugleiste, um ein neues Banner zu erstellen.
- Wählen Sie einen Banner-**Namen** aus der Spalte *Name*, um ein vorhandenes Banner zu bearbeiten.

## Screenshot

Ein Banner kann ein klickbares Bild oder ein benutzerdefinierter Code sein. Der Bildtyp wird im folgenden Screenshot angezeigt. Der benutzerdefinierte Typ ersetzt das Bildauswahlfeld durch ein Code-Textfeld.

![Banner bearbeiten Details-Tab](../../../de/images/banners/banners-edit-details-tab.png)

## Formularfelder

- **Name** Der Name des Banners. Dies ist der Name, der in der Spalte *Name* der Bannerliste angezeigt wird.
- **Alias** Der interne Name des Elements. Normalerweise können Sie dieses Feld leer lassen, und Joomla wird einen Standardwert aus dem Namen generieren, jedoch in Kleinbuchstaben und mit Bindestrichen anstelle von Leerzeichen.

## Details-Tab

### Linkes Panel

- **Typ** Der Anzeigetyp des Banners. Optionen sind eine Bilddatei oder benutzerdefinierter HTML-Code.
  - **Bild** Bilddatei zur Anzeige für das Banner. Klicken Sie auf die *Auswählen*-Schaltfläche, um die Bilddatei zu durchsuchen und auszuwählen, die verwendet werden soll. Verwenden Sie die Medienseite, um Bannerbilddateien auf Ihre Website hochzuladen. Bilder für Banner müssen sich im Verzeichnis /images/banners/ befinden.
    - **Breite** Die feste Breite, auf die das Bannerbild skaliert werden soll. Lassen Sie dieses Feld leer, wenn Sie die tatsächliche Breite der Bannerbilddatei verwenden möchten.
    - **Höhe** Die feste Höhe, auf die das Bannerbild skaliert werden soll. Lassen Sie dieses Feld leer, wenn Sie die tatsächliche Höhe der Bannerbilddatei verwenden möchten.
    - **Alternativer Text** Text, der anstelle des Bannerbildes angezeigt wird, falls das Bild nicht angezeigt werden kann.
    - **Alternativer Text** Alternativer Text für das Bild des Banners.
  - **Benutzerdefiniert** Wählen Sie Benutzerdefiniert, wenn Sie einen benutzerdefinierten Code für Ihr Banner eingeben möchten.
    - **Benutzerdefinierter Code** Verwenden Sie {CLICKURL} und {NAME}, um die Werte 'Klick-URL' und 'Name' in Ihren benutzerdefinierten Code einzufügen. Zum Beispiel:<br>
    `<a href=`&#34;`{CLICKURL}"><img src=`&#34;`Bild-URL eingeben" alt="{NAME}" title="{NAME}"></a>`
    Eine andere Möglichkeit ist das Eingeben eines benutzerdefinierten HTML-Codes. Zum Beispiel:<br>
    `<div class="yourclass"><a href=`&#34;`https://yourdomain.com"><img src=`&#34;`Pfad Ihres Bildes"></a></div>`
- **Klick-URL** Die URL, zu der der Benutzer navigiert, wenn er auf das Banner klickt.
- **Beschreibung** Geben Sie eine Beschreibung für das Banner ein.

### Rechtes Panel

- **Status** Der Veröffentlichungsstatus des Elements.
- **Angepinnt** Ob das Banner *angeheftet* ist oder nicht. Wenn ein oder mehrere Banner in einer Kategorie als *Sticky* markiert sind, haben sie Vorrang vor nicht als Sticky markierten Bannern.
    - Zum Beispiel: Wenn zwei Banner in einer Kategorie angeheftet sind und ein drittes Banner nicht, wird das dritte Banner nicht angezeigt, wenn die Banneranzeigemodul-Einstellung *Angepinnt, zufällig* oder *Angepinnt, Sortierung* lautet. Nur die beiden angehefteten Banner werden angezeigt. Wenn die angehefteten Banner eine feste Anzahl von Impressionen haben, werden die nicht angehefteten Banner automatisch angezeigt, sobald diese Impressionen aufgebraucht sind.
- **Sprache** Sprache des Elements.
- **Versionshinweis** Optionales Feld zur Identifizierung dieser Version des Elements im Versionsverlauf des Elements.

### Banner-Details-Tab

![Banner bearbeiten Banner-Details-Tab](../../../de/images/banners/banners-edit-banner-details-tab.png)

- **Max. Impressionen** Die Anzahl der für dieses Banner gekauften Impressionen. Impressionen sind die Anzahl der Male, die ein Banner auf einer Seite angezeigt wird. Aktivieren Sie das Kontrollkästchen 'Unbegrenzt', wenn eine unbegrenzte Anzahl von Impressionen erlaubt ist.
- **Gesamtimpressionen** Die Anzahl der Male, die dieses Banner einem Benutzer auf einer Webseite angezeigt wurde. Keine Eingabe erlaubt. Sie können diese Zahl auf 0 zurücksetzen, indem Sie die Schaltfläche 'Impressionen zurücksetzen' drücken.
- **Gesamtanzahl Klicks** Die Anzahl der Male, die auf dieses Banner geklickt wurde. Keine Eingabe erlaubt. Sie können diese Zahl auf 0 zurücksetzen, indem Sie die Schaltfläche *Klicks zurücksetzen* drücken.
- **Kunde** Der Kunde für dieses Banner. Wählen Sie einen aus der Dropdown-Liste der vorhandenen Kunden aus.
- **Kaufart:** Die Kaufart des Banners. Dies wird verwendet, um anzugeben, wie der Bannerkunde die Anzeigedauer für das Banner erworben hat.
- **Impressionen verfolgen** Ob die Anzahl der Male, die das Banner den Besuchern der Website angezeigt wird, verfolgt werden soll oder nicht.
- **Klicks verfolgen** Ob die Anzahl der Male, die das Banner von den Besuchern der Website angeklickt wird, verfolgt werden soll oder nicht.

## Tipps

- Banner werden auf bestimmten Seiten platziert, indem Module vom Typ 'Banner' über die Modulliste hinzugefügt werden.
- Wenn Sie eine Reihe von Bannern haben, die Sie auf einer oder mehreren Seiten in zufälliger Reihenfolge anzeigen möchten:
  1.  Erstellen Sie die Banner, die Sie einfügen möchten, und stellen Sie sicher, dass sie denselben Kunden und dieselbe Kategorie haben.
  2.  Erstellen Sie ein Banner-Modul für diesen Kunden und diese Kategorie, und wählen Sie in der Menüzuweisung die Menüpunkte aus, auf denen das Modul angezeigt werden soll.
  3.  Stellen Sie im Banner-Modul den Wert *Zufällig* auf *Sticky, zufällig*.

  Mit diesen Einstellungen werden die verschiedenen Banner für diesen Kunden und diese Kategorie auf den ausgewählten Seiten in zufälliger Reihenfolge angezeigt.

<!-- Translated from English with ChatGPT 2024-09-01 -->
