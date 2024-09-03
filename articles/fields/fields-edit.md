<!-- Filename: Help4.x:Fields:_Edit / Display title: Komponente: Feld bearbeiten -->

## Beschreibung

Die Seite *Komponente: Feld bearbeiten* ist für alle Komponenten, die Felder implementieren, ähnlich, aber der Seitentitel ändert sich je nach Kontext: *Artikel: Feld bearbeiten*, *Kontakte: Feld bearbeiten* oder *Benutzer: Feld bearbeiten*.

Die **Allgemein**-Registerkarte ändert sich je nach dem bearbeiteten Feldtyp, und sobald ein Feld gespeichert wurde, kann der Feldtyp nicht mehr geändert werden. Es ist jedoch einfach, Felder zu löschen und neue zu erstellen.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Die Veröffentlichungs-Registerkarte](jdocmanual?article=help/common-elements/edit-publishing).
* [Die Berechtigungs-Registerkarte](jdocmanual?article=help/common-elements/edit-permissions).

## Zugriff

* Wählen Sie **Inhalt → Felder** aus dem Administrator-Menü. Oder...
* Wählen Sie **Kontakt → Felder** aus dem Administrator-Menü. Oder...
* Wählen Sie **Benutzer → Felder** aus dem Administrator-Menü. Dann...
  * Klicken Sie auf die **Neu**-Schaltfläche in der Werkzeugleiste, um ein neues Feld zu erstellen. Oder...
  * Wählen Sie einen **Titel** aus der Liste, um ein bestehendes Feld zu bearbeiten.

**Hinweis:** Es gibt eine Dropdown-Liste, die die Erstellung von Feldern für eine Kategorie und Mail im Kontaktmodul ermöglicht. Dies erfordert jedoch einige Programmierkenntnisse, um geeignete Template-Overrides vorzubereiten.

## Screenshot

![Artikel Feld bearbeiten](../../../de/images/fields/articles-edit-field.png)

## Formularfelder

- **Titel** Der Titel für dieses Feld.

### Allgemein-Registerkarte

#### Linkes Panel

Parameter für alle Felder:

- **Typ** Wenn Sie ein Feld erstellen, können Sie einen der 16 Feldtypen auswählen. Sobald das Feld gespeichert ist, bleibt dieser Typ dauerhaft.
- **Name** Der Name wird verwendet, um das Feld zu identifizieren. Lassen Sie dieses Feld leer, und Joomla füllt automatisch einen Standardwert basierend auf dem Titel aus.
- **Beschriftung** Verwenden Sie einen beschreibenden Text für die Beschriftung des Feldes. Dieser Text ist nicht übersetzbar. Wenn Sie keinen Text für eine Beschriftung eingeben, wird der Titeltext auch als Beschriftungstext verwendet.
- **Beschreibung** Die Beschreibung des Feldes. Ein Text, der als Tooltip angezeigt wird, wenn der Benutzer die Maus über das Textfeld bewegt, während er es im Backend verwendet, um einen Artikel oder einen Kontakt oder eine Drittanbieter-Komponente, die Felder unterstützt, zu erstellen. Dieser Text ist nicht übersetzbar. Diese Beschreibung wird im Frontend nicht angezeigt.
- **Erforderlich** Ist dieses Feld ein Pflichtfeld? In diesem Fall muss das Feld ausgefüllt werden, bevor ein Artikel, ein Kontakt oder eine Drittanbieter-Komponente, die Felder unterstützt, übermittelt werden kann.

#### Rechtes Panel

- **Status** Der Veröffentlichungsstatus dieses Feldes.
  - *Veröffentlicht* Das Feld ist beim Bearbeiten eines Artikels oder Kontakts sichtbar und es wird im Frontend angezeigt.
  - *Nicht veröffentlicht* Das Feld wird beim Bearbeiten eines Artikels oder Kontakts für Benutzer nicht sichtbar sein.
  - *Archiviert* Das Feld wird beim Bearbeiten eines Artikels oder Kontakts nicht mehr angezeigt. Sie können es in den Feldern öffnen, wenn Sie den Filter auf archiviert setzen.
  - *Papierkorb* Das Feld ist gelöscht, aber noch in der Datenbank vorhanden. Es kann dauerhaft aus der Datenbank in den Feldern mit der Funktion *Papierkorb leeren* gelöscht werden.
- **Feldgruppe** Sie können ein Feld einer Feldgruppe zuweisen.
- **Kategorie** Sie können ein Feld einer oder mehreren Kategorien zuweisen. Beachten Sie, dass die Standardoption *Alle* keine *Nicht kategorisierten* Artikel enthält.
- **Zugriff** Wählen Sie die Ansichtsebene für dieses Feld aus. Die Zugriffsebenen hängen davon ab, was in den *Benutzern: Zugriffsebenen* eingerichtet wurde.
- **Sprache** Wählen Sie die Sprache für dieses Feld aus. Wenn Sie die Mehrsprachigkeitsfunktion von Joomla nicht verwenden, belassen Sie die Standardeinstellung *Alle*.
- **Notiz** Ein optionales Feld, um Ihre persönlichen Notizen zu diesem Feld zu machen.

### Optionen-Registerkarte

![Artikel Feld Bearbeiten Optionen Registerkarte](../../../de/images/fields/articles-edit-field-options-tab.png)

#### Formularoptionen

- **Platzhalter** Ein Platzhaltertext, der als Hinweis für die Eingabe im Feld angezeigt wird. Der Platzhalter ist im Backend aktiv, wenn ein Artikel oder ein Kontakt oder eine Drittanbieter-Komponente, die Felder unterstützt, erstellt wird. Sie sehen ihn nicht im Frontend.
- **Feldklasse** Die Klassenattribute des Feldes, wenn das Feld gerendert wird. Wenn verschiedene Klassen benötigt werden, listen Sie sie mit Leerzeichen auf.
- **Beschriftungsklasse (Formular)** CSS-Klasse, die auf die Feldbeschriftung angewendet wird, wenn sich das Feld im Bearbeitungsmodus befindet (Eingabe in ein Feld).
- **Bearbeitbar In** In welchem Teil der Website sollte das Feld angezeigt werden? Im Backend, im Frontend oder in beiden?
- **Showon-Attribut** Bedingtes Anzeigen oder Ausblenden des Feldes, abhängig vom Wert anderer Felder. Die Syntax, die hier verwendet werden soll, lautet beispielsweise: `list-of-items:value1[OR]list-of-items:value2`
  - list-of-items: Der *Name* eines bereits erstellten Feldes, von dem dieses Feld abhängig ist, um angezeigt zu werden.
  - value1: Der Wert, der benötigt wird, um das Feld anzuzeigen, von dem es abhängt.
  - `[OR]`: Um eine Auswahl zwischen mehreren Feldern zu erstellen. In diesem Beispiel wird dieses Feld angezeigt, wenn das *list-of-items*-Feld den Wert *value1* ODER *value2* hat.
  - `[AND]`: Um mehrere Felder zu kombinieren. Dieses Feld wird nur angezeigt, wenn das *list-of-items*-Feld den Wert *value1* UND *value2* hat.
  - Sie können auch den Wert *ist nicht gleich* verwenden, wie in *list-of-items!:value1*. Die Syntax zeigt dieses Feld nur an, wenn *list-of-items* nicht gleich *value1* ist.
  - Um dieses Feld anzuzeigen, wenn das *list-of-items*-Feld ausgewählt wurde und keinen leeren Wert hat, verwenden Sie die Syntax *list-of-items!:* (ohne einen angegebenen Wert).

**Hinweis:** Unterformularfelder behandeln den Identifikator *name* von *list-of-items* anders. Wenn Sie ein benutzerdefiniertes Unterformularfeld erstellen und dieses bedingte Feld dort hinzufügen, müssen Sie *field\[ID\]* anstelle von *list-of-items* verwenden, wobei ID die ID des Feldes *list-of-items* ist. Daher muss das *showon*-Attribut für dieses bedingte Feld, das Sie erstellen, lauten: `field36:value1[OR]field36:value2`, wobei 36 die ID des Feldes *List of items* ist.

#### Anzeigeoptionen

- **Anzeigeklasse** Die Klasse des Feldcontainers in der Ausgabe.
- **Wertklasse** Die Klasse des Feldwerts in der Ausgabe.
- **Beschriftung** Zeigen Sie die Beschriftung an, wenn das Feld gerendert wird.
- **Beschriftungsklasse (Ausgabe)** CSS-Klasse, die auf die Feldbeschriftung angewendet wird, wenn sie angezeigt wird (Ausgabe eines Feldes).
- **Automatische Anzeige** Joomla bietet einige Inhaltsereignisse, die während des Inhalts-Erstellungsprozesses ausgelöst werden. Dies ist der Ort, an dem Sie definieren können, wie die Felder in Inhalte integriert werden sollen. Sie können wählen
  - Nach dem Titel
  - Vor dem Anzeigen des Inhalts
  - Nach dem Anzeigen des Inhalts
  - Nicht automatisch anzeigen
- **Präfix** Fester Text, der vor einem Feld angezeigt wird, z. B. £.
- **Suffix** Fester Text, der nach einem Feld angezeigt wird, z. B. €.
- **Layout** Wenn ein benutzerdefiniertes Layout vorhanden ist, würde es hier ausgewählt werden.
- **Anzeigen bei schreibgeschützt** Wenn das Feld schreibgeschützt ist (möglicherweise hat der Benutzer nicht die erforderliche Zugriffsebene), sollte das Feld angezeigt oder ausgeblendet werden.

#### Intelligente Suche

- **Suchindex**  Warnung: Wenn *Durchsuchbar machen* ausgewählt ist, wird der Inhalt des Feldes mit den Ansichtsebenen des Inhaltselements indiziert. Dies könnte zu unerwarteter Informationsfreigabe führen.
