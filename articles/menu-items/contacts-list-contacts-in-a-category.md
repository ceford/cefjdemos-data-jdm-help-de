<!-- Filename: Help4.x:Menu_Item:_List_Contacts_in_a_Category / Display title: Kontakte in einer Kategorie auflisten -->

## Beschreibung

Der Menüpunkt-Typ **Kontakte in einer Kategorie auflisten** wird verwendet, um Kontakte in einer bestimmten Kategorie in einem Listenlayout anzuzeigen. Einstellungen umfassen: Kontaktdetails, Kontaktformular, Darstellung (Slider, Registerkarten, einfache Ansicht) sowie Filter für Betreff und Nachricht der E-Mail.

### Allgemeine Elemente

Einige Aspekte dieser Seite werden in separaten Hilfe-Artikeln behandelt:

* [Symbolleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Details-Tab](jdocmanual?article=help/menu-items-common/menu-item-details).
* [Der Integration-Tab](jdocmanual?article=help/menu-items-common/menu-item-integration).
* [Der Linktyp-Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [Der Seitendarstellungs-Tab](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [Der Metadaten-Tab](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [Der Verknüpfungs-Tab](jdocmanual?article=help/common-elements/edit-associations).
* [Der Modulzuweisungs-Tab](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## So greifen Sie darauf zu

Um einen neuen Menüpunkt **Kontakte in einer Kategorie auflisten** zu erstellen:

- Wählen Sie **Menüs → \[Name des Menüs\]** aus dem Administrator-Menü (zum Beispiel **Menüs → Hauptmenü**).
  - Wählen Sie die Schaltfläche **Neu** in der Symbolleiste. Dann...
  - Wählen Sie die Schaltfläche **Menüpunkt-Typ auswählen**.
  - Im Modal-Dialog wählen Sie den Punkt **Kontakte** aus, um eine Liste zu öffnen, und dann den Menüpunkt **Kontakte in einer Kategorie auflisten**.

Um einen bestehenden Menüpunkt **Kontakte in einer Kategorie auflisten** zu bearbeiten:

- Wählen Sie den Titel in der Liste *Menüs: Einträge*.

## Screenshot

![Menüpunkt Kontakte in einer Kategorie auflisten Details-Tab](../../../de/images/menu-items/contacts-list-contacts-in-a-category-details-tab.png)

## Formularfelder

- **Menütitel** Der Titel, der für diesen Menüpunkt angezeigt wird.
- **Alias** Der interne Name des Elements. Normalerweise können Sie dieses Feld leer lassen und Joomla füllt einen Standardwert aus, indem der Titel in Kleinbuchstaben und mit Bindestrichen anstelle von Leerzeichen verwendet wird.

### Kategorie-Tab

Die Kategorie-Optionen steuern, wie die Kategoriedaten im Layout angezeigt werden. Das Kategorien-Listenlayout enthält die folgenden Kategorien-Optionen, wie unten dargestellt.

![Menüpunkt Kontakte in einer Kategorie auflisten Kategorie-Tab](../../../de/images/menu-items/contacts-list-contacts-in-a-category-category-tab.png)

- **Kategorie-Titel** Zeigt oder verbirgt den Titel der Kategorie, der als Unterüberschrift auf der Seite angezeigt wird. Die Unterüberschrift wird normalerweise im "H2"-Tag angezeigt.
- **Kategorie-Beschreibung** Zeigt oder verbirgt die Beschreibung der ausgewählten Kategorie.
- **Kategoriebild** Zeigt oder verbirgt das Kategoriebild.
- **Unterkategorien-Ebenen** Die Anzahl der Unterkategorien-Ebenen, die im Layout angezeigt werden. Wählen Sie *Alle*, um alle Ebenen in der Unterkategorien-Hierarchie anzuzeigen.
- **Leere Kategorien** Zeigt oder verbirgt die Kategorien, die keine Inhalte oder Unterkategorien enthalten.
- **Beschreibungen der Unterkategorien** Zeigt oder verbirgt die Beschreibung der Unterkategorien.
- **\# Kontakte in der Kategorie** Zeigt oder verbirgt die Anzahl der Kontakte in einer Kontaktkategorie.

### Listenlayouts-Tab

Die Listenlayout-Optionen steuern das Erscheinungsbild des Listenlayouts.

![Menüpunkt Kontakte in einer Kategorie auflisten Listenlayouts-Tab](../../../de/images/menu-items/contacts-featured-contacts-list-layouts-tab.png)

- **Filterfeld** Zeigt oder verbirgt das Filterfeld, das ein Textfeld für den Frontend-Benutzer erstellt, um einen Teil eines Kontaktnamens einzugeben und danach zu suchen.
- **Anzeigeauswahl** Zeigt oder verbirgt die Steuerung zur Auswahl der Anzahl der anzuzeigenden Elemente.
    Wenn mehr Elemente vorhanden sind, als diese Anzahl zulässt, können Sie die Seitennavigationsschaltflächen (Start, Zurück, Weiter, Ende und Seitenzahlen) verwenden, um zwischen den Seiten zu navigieren. Beachten Sie, dass es bei einer großen Anzahl von Elementen hilfreich sein kann, die Filteroptionen oberhalb der Spaltenüberschriften zu verwenden, um die angezeigten Elemente einzuschränken.
- **Tabellenüberschriften** Zeigt oder verbirgt die Tabellenüberschriften über einer Liste.
- **Bild** Zeigt oder verbirgt eine Bildspalte in der Kontaktliste.
- **Position** Zeigt oder verbirgt die Position, die dieser Kontakt in der Organisation innehat. Zum Beispiel Geschäftsführer, Sekretär, Hausmeister.
- **E-Mail** Zeigt oder verbirgt die E-Mail-Adresse des Kontakts in der Liste.
- **Telefon** Zeigt oder verbirgt die Telefonnummer des Kontakts in der Liste.
- **Mobil** Zeigt oder verbirgt die Mobiltelefonnummer des Kontakts in der Liste.
- **Fax** Zeigt oder verbirgt die Faxnummer des Kontakts in der Liste.
- **Stadt oder Vorort** Zeigt oder verbirgt die Stadt oder den Vorort des Kontakts in der Liste.
- **Bundesland oder Landkreis** Zeigt oder verbirgt das Bundesland oder den Landkreis des Kontakts in der Liste.
- **Land** Zeigt oder verbirgt das Land des Kontakts in der Liste.
- **Seitennummerierung** Zeigt oder verbirgt die Unterstützung für Seitennummerierung. Die Seitennummerierung stellt Links am Seitenende bereit, mit denen der Benutzer zu weiteren Seiten navigieren kann. Diese werden benötigt, wenn die aufgelisteten Elemente nicht auf eine Seite passen.
    Die folgenden Optionen sind verfügbar.
    - *Global verwenden* Verwendet den Standardwert aus den Komponenteneinstellungen.
    - *Auto* Seitennummerierung wird bei Bedarf angezeigt.
    - *Anzeigen* Seitennummerierung wird bei Bedarf angezeigt.
    - *Ausblenden* Seitennummerierung wird nicht angezeigt. Hinweis: In diesem Fall können Benutzer nicht zu weiteren Seiten navigieren.
- **Seitenergebnisse** Zeigt oder verbirgt die aktuelle Seitenzahl und die Gesamtseitenzahl (z. B. "Seite 1 von 2") am Seitenende jeder Seite.

### Kontaktanzeige-Tab

Die Kontaktanzeige-Optionen steuern das Erscheinungsbild des Listenlayouts.
![Menüpunkt Kontakte in einer Kategorie auflisten Kontaktanzeige-Tab](../../../de/images/menu-items/contacts-featured-contacts-form-tab.png)

- **Layout auswählen** Wählen Sie aus der Liste der Vorlagen.
- **Kontakt-Kategorie** Zeigt oder verbirgt die Anzeige der Kontaktkategorie.
    Die folgenden Optionen sind verfügbar.
    - *Global verwenden* Verwendet den Standardwert aus den Kontakteinstellungen.
    - *Ausblenden* Zeigt den Kategorienamen der Kontakte nicht an.
    - *Anzeigen ohne Link* Zeigt den Kategorienamen der Kontakte als nur mit Text formatierte Überschrift an.
    - *Anzeigen mit Link* Zeigt den Kategorienamen der Kontakte als mit Text formatierte und verlinkte Überschrift an.
- **Kontaktauswahlliste** Zeigt oder verbirgt die Möglichkeit, eine Dropdown-Liste aller Kontakte in einer Kontaktkategorie zu verwenden.
- **Name** Zeigt oder verbirgt den *Namen* des Kontakts.
- **Tags** Zeigt oder verbirgt die *Tags* des Kontakts.
- **Kontaktinformationen** Wenn auf Anzeigen gesetzt, sind folgende Felder verfügbar:
  - **Position des Kontakts** Zeigt oder verbirgt die *Position des Kontakts*.
  - **E-Mail** Zeigt oder verbirgt die *E-Mail-Adresse* des Kontakts.
  - **Straßenadresse** Zeigt oder verbirgt die *Straßenadresse* des Kontakts.
  - **Stadt oder Vorort** Zeigt oder verbirgt die *Stadt oder den Vorort* des Kontakts.
  - **Bundesland oder Landkreis** Zeigt oder verbirgt das *Bundesland oder den Landkreis* des Kontakts.
  - **Postleitzahl** Zeigt oder verbirgt die *Postleitzahl* des Kontakts.
  - **Land** Zeigt oder verbirgt das *Land* des Kontakts.
  - **Telefon** Zeigt oder verbirgt die *Telefonnummer* des Kontakts.
  - **Mobiltelefon** Zeigt oder verbirgt die *Mobiltelefonnummer* des Kontakts.
  - **Fax** Zeigt oder verbirgt die *Faxnummer* des Kontakts.
  - **Webseite** Zeigt oder verbirgt die *Webseite* des Kontakts.
  - **Bild** Zeigt oder verbirgt das *Bild* des Kontakts.
- **vCard** Zeigt oder verbirgt die
