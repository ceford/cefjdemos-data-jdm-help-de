<!-- Filename: Help4.x:Menu_Item:_List_All_Categories / Display title: Menüeintrag: Alle Kategorien auflisten -->

## Beschreibung

Der Menüpunkt *Alle Kategorien in einem Artikelkategorienbaum auflisten* wird verwendet, um Kategorien in einer hierarchischen Liste anzuzeigen. Je nach den ausgewählten Optionen für dieses Layout können Sie auf einen Kategorietitel klicken, um die Artikel in dieser Kategorie anzuzeigen.

### Allgemeine Elemente

Einige Aspekte dieser Seite werden in separaten Hilfe-Artikeln behandelt:

* [Symbolleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Details-Tab](jdocmanual?article=help/menu-items-common/menu-item-details).
* [Der Kategorie-Tab](jdocmanual?article=help/menu-items-common/menu-item-category).
* [Der Blog-Layout-Tab](jdocmanual?article=help/menu-items-common/menu-item-blog-layout).
* [Der Optionen-Tab](jdocmanual?article=help/menu-items-common/menu-item-article-options).
* [Der Integrations-Tab](jdocmanual?article=help/menu-items-common/menu-item-integration).
* [Der Linktyp-Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [Der Seitendarstellung-Tab](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [Der Metadaten-Tab](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [Der Verknüpfungen-Tab](jdocmanual?article=help/common-elements/edit-associations).
* [Der Modulzuweisung-Tab](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## So greifen Sie darauf zu

Wählen Sie **Menüs → \[Name des Menüs\]** aus dem Administrator-Menü.

Um einen Menüpunkt hinzuzufügen:

1.  Wählen Sie die Schaltfläche **Neu** in der Symbolleiste.
2.  Wählen Sie die Schaltfläche **Auswählen** beim Menüpunkt-Typ.
3.  Wählen Sie den Eintrag **Beiträge**.
4.  Wählen Sie den Eintrag **Alle Kategorien in einem Artikelkategorienbaum auflisten**.

Um einen Menüpunkt zu bearbeiten:

- Wählen Sie einen **Titel** aus der Liste aus.

## Screenshot

![Menüpunkt Beiträge Alle Kategorien auflisten Details-Tab](../../../de/images/menu-items/articles-list-all-categories-details-tab.png)

## Formularfelder

- **Titel** Der Titel, der für diesen Menüpunkt angezeigt wird.
- **Alias** Der interne Name des Menüpunkts. Normalerweise können Sie dieses Feld leer lassen, und Joomla füllt einen Standardwert mit dem Titel in Kleinbuchstaben und Bindestrichen anstelle von Leerzeichen aus.

### Details-Tab

#### Linkes Panel

- **Menüpunkt-Typ** Der Menüpunkt-Typ, der beim Erstellen dieses Menüpunkts ausgewählt wurde. Dies kann einer der Standard-Menüpunkttypen oder ein Menüpunkttyp sein, der von einer installierten Erweiterung bereitgestellt wird.
- **Obere Kategorie auswählen**
  - *Stamm* Schließt alle Artikelkategorien ein.
  - Andernfalls wählen Sie die gewünschte oberste Kategorie aus. Alle untergeordneten Kategorien der ausgewählten Kategorie werden im Menüpunkt angezeigt.
- **Link** Der systemgenerierte Link für diesen Menüpunkt. Dieses Feld kann nicht geändert werden und dient nur zur Information.
- **Zielfenster** Auswahl aus der Dropdown-Liste.
- **Vorlagenstil** Auswahl aus der Dropdown-Liste.

#### Rechtes Panel

- **Menü** Zeigt an, in welchem Menü der Link erscheinen wird.

### Kategorie-Tab

![Menüpunkt Beiträge Alle Kategorien Kategorien-Tab](../../../de/images/menu-items/articles-list-all-categories-categories-tab.png)

- **Beschreibung der obersten Kategorie** Zeigt die Beschreibung der obersten Kategorie an.
- **Alternative Beschreibung** Geben Sie eine Beschreibung ein, um die Kategoriebeschreibung für den Menüpunkt zu überschreiben.
- **Unterkategorie-Ebenen** Steuerung, wie viele Ebenen von Unterkategorien angezeigt werden.
- **Leere Kategorien** Kategorien anzeigen, die keine Artikel oder Unterkategorien enthalten.
- **Beschreibungen der Unterkategorien** Zeigt die Beschreibung der Unterkategorien an.
- **Anzahl der Artikel in der Kategorie** Zeigt die Anzahl der Artikel in jeder Kategorie an.

### Blog-Layout-Tab

Die Blog-Layout-Optionen steuern das Erscheinungsbild, wenn das Herunterklicken auf eine Kategorie zu einem Blog-Layout führt.

Das Blog-Layout-Formular hat ein anderes Layout als das im Abschnitt „Allgemeine Elemente“, aber die Felder sind ähnlich.

### Listen-Layouts-Tab

Die Optionen steuern das Erscheinungsbild der Seite beim Herunterklicken, wenn diese als Kategorienliste angezeigt wird.

![Menüpunkt Beiträge Alle Kategorien Listen-Layouts-Tab](../../../de/images/menu-items/articles-list-all-categories-list-layouts-tab.png)

- **Anzeigeoption auswählen** Zeigt die Steuerung „Anzahl anzeigen“ an, mit der der Benutzer die Anzahl der anzuzeigenden Artikel auswählen kann.
- **Filterfeld** Zeigt ein Textfeld im Frontend an, in dem ein Benutzer die Artikel filtern kann. Optionen im Backend-Menüpunkt bearbeiten.
  - *Verbergen* Kein Filterfeld anzeigen.
  - *Titel* Nach Artikel-Titel filtern.
  - *Autor* Nach Autorennamen filtern.
  - *Aufrufe* Nach der Anzahl der Artikelaufrufe filtern.
- **Tabellenüberschriften** Zeigt eine Überschrift in der Artikelliste im Frontend an.
- **Datum** Zeigt ein Datum in der Liste an.
  - *Verbergen* Kein Datum anzeigen.
  - *Erstellt* Das Erstellungsdatum anzeigen.
  - *Geändert* Das Datum der letzten Änderung anzeigen.
  - *Veröffentlicht* Das Veröffentlichungsdatum anzeigen.
- **Datumsformat** Optionale Formatzeichenfolge, um das Datumsformat zu steuern.
- **Aufrufe** Zeigt die Anzahl der Aufrufe der Artikel an.
- **Autor** Zeigt den Namen des Autors an.
- **Anzahl der Artikel in der Liste** Anzahl der in der Liste angezeigten Artikel.

### Gemeinsame Optionen-Tab

Die gemeinsamen Optionen gelten für Blog, Liste und Hervorgehobene Artikel, es sei denn, sie werden durch die Menüeinstellungen geändert.

![Menüpunkt Beiträge Alle Kategorien Gemeinsame Optionen-Tab](../../../de/images/menu-items/articles-list-all-categories-shared-tab.png)

- **Seitennummerierung** Die Seitennummerierung bietet Links am unteren Rand der Seite, mit denen der Benutzer zu weiteren Seiten navigieren kann. Diese sind erforderlich, wenn die Artikel nicht auf eine Seite passen.
  - *Verbergen: Seitennummerierungs-Links nicht anzeigen. Hinweis* Benutzer können nicht zu weiteren Seiten navigieren.
  - *Anzeigen* Seitennummerierungs-Links bei Bedarf anzeigen.
  - *Automatisch* Seitennummerierungs-Links bei Bedarf anzeigen.
- **Zusammenfassung der Seitennummerierung** Zeigt die aktuelle Seitenzahl und die Gesamtseitenzahl an (z. B. „Seite 1 von 2“) am unteren Rand jeder Seite.

## Tipps

- Kategorien können in Ebenen „verschachtelt“ werden, ähnlich wie Ordner auf einer Festplatte. Theoretisch gibt es keine absolute Begrenzung der Ebenenanzahl. Aus praktischen Gründen wird jedoch empfohlen, die Ebenenanzahl möglichst gering zu halten. Das Layout „Alle Kategorien anzeigen“ funktioniert möglicherweise nicht korrekt, wenn die Anzahl der angezeigten Ebenen größer als 5 ist.
- Wenn Sie Kategorietitel als verlinkbar einrichten, kann der Benutzer auf die Kategorie klicken, um tiefer in die Kategorieansicht zu gelangen. Normalerweise sieht der Benutzer dann entweder einen Kategorienlisten- oder Kategorienblog-Menüpunkt, je nachdem, welche Option ausgewählt wurde. Wenn für diese Kategorie bereits ein Menüpunkt vorhanden ist (z. B. ein Kategorienblog-Menüpunkt), wird dieser Menüpunkt in der Kategorieansicht angezeigt, und die für diesen Menüpunkt festgelegten Optionen steuern die Seitendarstellung. Andernfalls steuern die für den aktuellen Menüpunkt „Alle Kategorien anzeigen“ festgelegten Optionen die Seitendarstellung.
- Sie können die Option zum Herunterklicken in eine Liste oder einen Blog an zwei Stellen festlegen.
  - In „Beiträge: Optionen“ können Sie den Standardwert für alle Kategorien festlegen.
  - In „Kategorie: Bearbeiten“ können Sie einen Wert für eine bestimmte Kategorie festlegen. Wenn dies festgelegt ist, überschreibt es den Standardwert.
- Um ein *Datumsformat* anzupassen, können Sie D M Y für Tag Monat Jahr oder d-m-y für eine Kurzversion verwenden, z. B. 17-08-05. Wenn das Feld leer bleibt, wird der Übersetzungsschlüssel DATE_FORMAT_LC1 aus Ihrer Sprachdatei verwendet.
