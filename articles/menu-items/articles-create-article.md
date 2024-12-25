<!-- Filename: Help4.x:Menu_Item:_Create_Article / Display title: Menüeintrag: Beitrag erstellen -->

## Beschreibung

Der Menüpunkt *Artikel erstellen* ermöglicht es Benutzern, einen Artikel über die Website-Oberfläche einzureichen. Normalerweise ist dies nur für Benutzer verfügbar, die sich im Frontend der Website angemeldet haben. Benutzer müssen die Berechtigung haben, Artikel zu erstellen.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfe-Artikeln behandelt:

* [Symbolleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Details-Tab](jdocmanual?article=help/menu-items-common/menu-item-details).
* [Der Link-Typ-Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [Der Seitendarstellung-Tab](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [Der Metadaten-Tab](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [Der Verknüpfungen-Tab](jdocmanual?article=help/common-elements/edit-associations).
* [Der Modulzuweisung-Tab](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Zugriff

Wählen Sie **Menüs → \[Name des Menüs\]** im Administrator-Menü.

Um einen Menüpunkt hinzuzufügen:

1. Wählen Sie die Schaltfläche **Neu** in der Symbolleiste.
2. Wählen Sie die Schaltfläche **Auswählen** beim *Menüpunkt-Typ*.
3. Wählen Sie im Popup-Dialog den Eintrag **Beiträge** aus.
4. Wählen Sie den Eintrag **Artikel erstellen**.

Um einen Menüpunkt zu bearbeiten:

- Wählen Sie einen **Titel** aus der Liste.

## Screenshot

![Menüpunkt Artikel erstellen Details-Tab](../../../de/images/menu-items/articles-create-article-details-tab.png)

## Formularfelder

- **Titel** Der Titel, der für diesen Menüpunkt angezeigt wird.
- **Alias** Der interne Name des Menüpunkts. Normalerweise kann dieses Feld leer gelassen werden, und Joomla füllt einen Standardwert basierend auf dem Titel in Kleinbuchstaben und mit Bindestrichen anstelle von Leerzeichen aus.

### Details

#### Linkes Panel

- **Menüpunkt-Typ** Der Menüpunkt-Typ, der ausgewählt wurde, als dieser Menüpunkt erstellt wurde. Dies kann einer der Kern-Menüpunkt-Typen oder ein Menüpunkt-Typ sein, der von einer installierten Erweiterung bereitgestellt wird.
- **Link** Der systemgenerierte Link für diesen Menüpunkt. Dieses Feld kann nicht geändert werden und dient nur zur Information.
- **Ziel-Fenster** Wählen Sie aus der Dropdown-Liste.
- **Template-Stil** Wählen Sie aus der Dropdown-Liste.

#### Rechtes Panel

- **Menü** Zeigt an, in welchem Menü der Link erscheinen wird.

### Optionen

![Menüpunkt Artikel erstellen Optionen-Tab](../../../de/images/menu-items/articles-create-article-options-tab.png)

- **Spezifische Kategorie**
  - *Ja* Artikel werden der angegebenen Kategorie zugeordnet. Der Benutzer kann keine Kategorie auswählen.
  - *Nein* Der Benutzer kann die Kategorie aus der Liste auswählen. Es werden nur Kategorien angezeigt, für die der Benutzer die *Erstellen*-Berechtigung hat.
- **Weiterleitung nach Übermittlung/Abbruch** Wählen Sie die Seite, auf die der Benutzer nach erfolgreicher Artikelerstellung weitergeleitet wird.
- **Benutzerdefinierte Weiterleitung bei Abbruch**
  - *Ja* Legen Sie eine Seite fest, zu der weitergeleitet wird, wenn der Benutzer die Artikelerstellung abbricht.
  - *Nein* Wenn der Benutzer die Artikelerstellung abbricht, wird der Benutzer zur Seite *Weiterleitung nach Übermittlung/Abbruch* weitergeleitet.

## Beispiel-Screenshot im Frontend

Dieser Screenshot zeigt das Joomla-Kern-Frontend-Template **Cassiopeia** mit allen Bearbeitungs-Layout-Optionen auf „Ausblenden“ gesetzt.

![articles-create-article-frontend.png](../../../en/images/menu-items/articles-create-article-frontend.png)

## Tipps

Ein nicht autorisierter Benutzer erhält normalerweise einen Fehler, wenn er einen Menüpunkt *Artikel erstellen* auswählt. Aus diesem Grund ist es üblich, dem Menüpunkt eine Zugriffsebene zuzuweisen, die nur von Benutzern gesehen werden kann, die berechtigt sind, Artikel hinzuzufügen.
