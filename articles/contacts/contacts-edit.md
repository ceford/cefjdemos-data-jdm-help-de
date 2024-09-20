<!-- Filename: Help4.x:Contacts:_New_or_Edit / Display title: Kontakte: Bearbeiten -->

## Beschreibung

Das *Kontakte: Bearbeitungsformular* wird verwendet, um einen neuen Kontakt hinzuzufügen oder einen bestehenden Kontakt zu bearbeiten.

**Beachten Sie:** Wenn ein Kontakt ein Menüelement hat, überschreiben die Kontakte-Menüeinstellungen einige hier verfügbare Einstellungen. Achten Sie darauf, keine persönlichen Informationen versehentlich preiszugeben!

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Schema-Tab](jdocmanual?article=help/common-elements/edit-schema).
* [Der Veröffentlichungs-Tab](jdocmanual?article=help/common-elements/edit-publishing).
* [Der Verknüpfungs-Tab](jdocmanual?article=help/common-elements/edit-associations).
* [Das Versionsverlauf-Popup](jdocmanual?article=help/common-elements/edit-version-history).

## Zugriff

- Wählen Sie **Komponenten → Kontakte → Kontakte** im Administrator-Menü.
- Um einen neuen Kontakt **hinzuzufügen**:
  - Wählen Sie die **Neu**-Schaltfläche in der Werkzeugleiste.
- Um einen bestehenden Kontakt **zu bearbeiten**:
  - Wählen Sie einen Kontakttitel in der **Titel**-Spalte aus.

## Screenshot

![Kontakte bearbeiten Kontakt-Tab](../../../de/images/contacts/contacts-edit-contact-tab.png)

## Formularfelder

In diesem Abschnitt können Sie Informationen über den Kontakt eingeben, wie Name, Adresse, E-Mail usw. Die Optionen ermöglichen es Ihnen, Einstellungen zu steuern, wie die Informationen für jeden Kontakt angezeigt werden.

- **Name** Der vollständige Name des Kontakts.
- **Alias** Der interne Name des Elements. Normalerweise können Sie dieses Feld leer lassen, und Joomla füllt einen Standardwert aus, der auf dem Titel basiert, in Kleinbuchstaben und mit Bindestrichen anstelle von Leerzeichen.

### Kontakt bearbeiten-Tab

Hier geben Sie die grundlegenden Informationen über den Kontakt ein.

- **Verknüpfter Benutzer** Wenn dieser Kontakt mit einem Benutzer verknüpft ist, wählen Sie das *Benutzer auswählen* Symbol, um ein Popup-Formular anzuzeigen, in dem Sie einen der registrierten Benutzer auswählen können. Ein verknüpfter Benutzer kann mit der Schaltfläche *- Kein Benutzer -* im Benutzer auswählen Popup-Formular entfernt werden.
- **Bild** Bild, das für diesen Kontakt angezeigt werden soll. Wählen Sie eine Bilddatei aus der Dropdown-Liste aus. Diese Liste zeigt Bilder im Ordner 'images/stories' an. Bilder können mit der Medien-Komponente hochgeladen werden.
- **Position:** Die aktuelle Position des Kontakts.
- **E-Mail** Die E-Mail-Adresse des Kontakts. Beachten Sie, dass E-Mail-Adressen in Joomla! vor „Spambots“ geschützt werden können, indem das Plugin „Content-Email Cloaking“ aktiviert wird. Dies ist standardmäßig aktiviert.
- **Adresse** Die Straßenadresse des Kontakts.
- **Stadt oder Vorort** Die Stadt oder der Vorort des Kontakts.
- **Bundesland oder Provinz** Das Bundesland oder der Landkreis des Kontakts.
- **Postleitzahl** Die Postleitzahl des Kontakts.
- **Land** Das Land des Kontakts.
- **Telefon** Die Telefonnummer des Kontakts.
- **Mobiltelefon** Die Mobiltelefonnummer des Kontakts.
- **Fax** Die Faxnummer des Kontakts.
- **Webseite** Die Webadresse des Kontakts.
- **Sortierfelder** Um Sortierfelder für Kategorienlisten zu aktivieren, gehen Sie zu **Kontakte → Optionen** und setzen **Listenlayouts → Sortieren nach** auf **Sortiername**. Anschließend müssen Sie reale Wörter zum Sortieren verwenden. Beispiel: Setzen Sie das erste Sortierfeld auf **Doe**, das zweite Feld auf **John** für den ersten Kontakt; dann das erste Sortierfeld auf **Doe**, das zweite Feld auf **Jane** für den zweiten Kontakt. Das dritte Feld wird in diesem Fall nicht verwendet. Die Sortierfelder sind Zeichenfelder, daher müssen Sie, wenn Sie nach Alter sortieren möchten, 0x für Alter unter 10 eingeben, z.B. 08.
  - **Erstes Sortierfeld** Der Name, der als erstes Sortierfeld verwendet wird.
  - **Zweites Sortierfeld** Der Name, der als zweites Sortierfeld verwendet wird.
  - **Drittes Sortierfeld** Der Name, der als drittes Sortierfeld verwendet wird.
- **Status**: Veröffentlichungsstatus des Elements. Mögliche Werte sind:
  - *Veröffentlicht*: Das Element ist veröffentlicht. Dies ist der einzige Zustand, der es normalen Website-Benutzern ermöglicht, dieses Element zu sehen.
  - *Unveröffentlicht*: Das Element ist unveröffentlicht.
  - *Archiviert*: Das Element wurde archiviert.
  - *Papierkorb*: Das Element wurde in den Papierkorb verschoben.
- **Kategorie** Die Kategorie, zu der dieses Element gehört.
- **Hervorgehoben** Ob das Element in der hervorgehobenen Ansicht angezeigt wird oder nicht.
- **Zugriff** Die Zugriffsberechtigung für die Anzeige dieses Elements.
- **Sprache** Die Sprache des Elements.
- **Tags** Geben Sie einen oder mehrere optionale Tags für dieses Element ein. Sie können vorhandene Tags auswählen, indem Sie die ersten Buchstaben eingeben. Sie können auch neue Tags erstellen, indem Sie sie hier eingeben. Tags ermöglichen es Ihnen, Listen verwandter Elemente über verschiedene Inhaltstypen hinweg anzuzeigen (z.B. Artikel, Kontakte und Kategorien).
- **Versionshinweis** Optionales Feld zur Kennzeichnung dieser Version des Elements im Versionsverlauf des Elements.

### Verschiedene Informationen-Tab

![Kontakte bearbeiten Kontakt-Tab](../../../de/images/contacts/contacts-edit-miscellaneous-tab.png)

Weitere Informationen zu diesem Kontakt können mit dem Editor eingegeben werden.

### Anzeige-Tab

![Kontakte bearbeiten Kontakt-Tab](../../../de/images/contacts/contacts-edit-display-tab.png)

- **Kategorie anzeigen** Kategorie des Kontakts anzeigen oder ausblenden.
- **Kontaktliste anzeigen** Kontaktliste anzeigen oder ausblenden.
- **Anzeigestil** Bestimmt den Stil, der zur Anzeige von Abschnitten des Kontaktformulars verwendet wird.
- **Tags** Ob Tags für dieses Element ausgeblendet oder angezeigt werden sollen.
- **Kontaktinformationen** Kontaktinformationen anzeigen oder ausblenden.
- **Verschiedene Informationen** Verschiedene Informationen anzeigen oder ausblenden.
- **vCard** Den vCard-Link für diesen Kontakt anzeigen oder ausblenden.
- **Benutzerartikel anzeigen** Wenn dieser Kontakt einem Benutzer zugeordnet ist und dies auf „Anzeigen“ gesetzt ist, wird eine Liste der von diesem Benutzer erstellten Artikel angezeigt.
- **\# Artikel anzeigen** Anzahl der anzuzeigenden Artikel.
- **Benutzerprofil** Wenn dieser Kontakt einem Benutzer zugeordnet ist und dies auf „Anzeigen“ gesetzt ist, wird das Profil dieses Benutzers angezeigt.
- **Benutzerdefinierte Feldgruppen anzeigen** Benutzerdefinierte Felder des Benutzers anzeigen, die zu allen oder nur ausgewählten Feldgruppen gehören.
- **Kontakt-Links** Kontakt-Links anzeigen oder ausblenden.
- **Link A Beschriftung** Beschriftung für einen zusätzlichen Link für diesen Kontakt.
- **Link A URL** Die zusätzliche Link-URL für diesen Kontakt.
- **Link B Beschriftung** Beschriftung für einen zusätzlichen Link für diesen Kontakt.
- **Link B URL** Die zusätzliche Link-URL für diesen Kontakt.
- **Link C Beschriftung** Beschriftung für einen zusätzlichen Link für diesen Kontakt.
- **Link C URL** Die zusätzliche Link-URL für diesen Kontakt.
- **Link D Beschriftung** Beschriftung für einen zusätzlichen Link für diesen Kontakt.
- **Link D URL** Die zusätzliche Link-URL für diesen Kontakt.
- **Link E Beschriftung** Beschriftung für einen zusätzlichen Link für diesen Kontakt.
- **Link E URL** Die zusätzliche Link-URL für diesen Kontakt.
- **Layout** Verwenden Sie ein anderes Layout als das mitgelieferte Komponentenlayout oder die Überschreibungen in den Vorlagen.

### Formular-Tab

![Kontakte bearbeiten Kontakt-Tab](../../../de/images/contacts/contacts-edit-form-tab.png)

- **Kontaktformular** Kontaktformular anzeigen oder ausblenden. Wenn „Anzeigen“ ausgewählt ist, wird ein Formular angezeigt, das es dem Benutzer ermöglicht, über die Website eine E-Mail an den Kontakt zu senden.
- **Kopie an Absender senden** Kontrollkästchen anzeigen oder ausblenden: *Eine Kopie dieser Nachricht an Ihre eigene Adresse senden.*
- **Sitzungsprüfung** Überprüfung auf das Vorhandensein eines Sitzungs-Cookies. Dies bedeutet, dass Benutzer ohne aktivierte Cookies keine E-Mails senden können.
- **Benutzerdefinierte Antwort** Schaltet die automatische Antwort aus und ermöglicht Plugins die Integration mit anderen Systemen.
- **Kontakt-Weiterleitung** Geben Sie eine alternative URL ein, zu der der Benutzer nach dem Absenden der E-Mail weitergeleitet wird.

<!-- Translated from English with ChatGPT 2024-09-02 ->
