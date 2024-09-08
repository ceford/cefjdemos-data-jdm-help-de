<!-- Filename: Help4.x:Menu_Item:_Login_Form / Display title: Anmeldeformular -->

## Beschreibung

Der Menüpunkt-Typ **Anmeldeformular** wird verwendet, um eine Seite mit einem Anmeldeformular zu erstellen.

### Allgemeine Elemente

Einige Aspekte dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Symbolleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Details-Tab](jdocmanual?article=help/menu-items-common/menu-item-details).
* [Der Link-Typ-Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [Der Seitendarstellung-Tab](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [Der Metadaten-Tab](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [Der Verknüpfungen-Tab](jdocmanual?article=help/common-elements/edit-associations).
* [Der Modul-Zuweisungs-Tab](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## So greifen Sie zu

Um einen neuen Menüpunkt **Anmeldeformular** zu erstellen:

- Wählen Sie **Menüs → \[Name des Menüs\]** aus dem Administrator-Menü (zum Beispiel **Menüs → Hauptmenü**). Dann...
  - Wählen Sie die Schaltfläche **Neu** in der Symbolleiste. Dann...
  - Wählen Sie die Schaltfläche zum Auswählen des Menüpunkt-Typs.
  - Im Dialogfeld wählen Sie den Punkt *Benutzer* aus, um eine Liste zu öffnen, und wählen dann den Menüpunkt **Anmeldeformular**.

Um einen bestehenden Menüpunkt Anmeldeformular zu bearbeiten:

- Wählen Sie dessen Titel in der Liste *Menüs: Elemente*.

## Screenshot

![Details-Tab Anmeldeformular](../../../de/images/menu-items/users-login-form-details-tab.png)

## Formularfelder

### Optionen-Tab

![Details-Tab Anmeldeformular](../../../de/images/menu-items/users-login-form-options-tab.png)

#### Anmeldebereich

- **Login-Umleitungsziel wählen** Dies kann ein *Menüpunkt* oder eine *Interne URL* sein. Die folgenden Felder ändern sich je nach Einstellung dieses Parameters. Für mehrsprachige Websites wird *Menüpunkt* empfohlen.
  - **Menüpunkt-Login-Umleitung** Wählen oder erstellen Sie einen Menüpunkt für die Seite, auf die nach erfolgreichem Login weitergeleitet wird. Wenn kein Menüpunkt ausgewählt ist, werden Benutzer nach der Anmeldung auf ihr Profil weitergeleitet.
  - **Login-Umleitung** Wählen Sie eine interne URL zur Umleitung nach dem Login.
- **Anmeldebeschreibung** Anmeldebeschreibung ein- oder ausblenden.
- **Anmeldebeschreibungstext** Geben Sie den Text ein, der auf der Anmeldeseite angezeigt wird.
- **Login-Bild** Wählen oder laden Sie ein Bild hoch, das auf der Anmeldeseite angezeigt wird.
- **Bildbeschreibung (Alt-Text)** Erforderlich für Bildschirmleser zur Barrierefreiheit.
- **Keine Beschreibung** Eine Checkbox, um auszuwählen, ob das Bild rein dekorativ ist und keine Erklärung erfordert.

#### Abmeldebereich

Dieser Bereich verwendet die gleichen Feldüberschriften, um den Abmeldeprozess zu steuern.

## Tipps

- Die **Login- und Logout-URL** kann verwendet werden, um einen Benutzer auf eine bestimmte Seite zu leiten, die Feedback gibt. Zum Beispiel eine Seite mit dem Titel *Sie sind jetzt eingeloggt* mit allgemeinen Informationen. Die Verwendung eines Benutzer-Moduls, um Links für das Aktualisieren oder Ansehen des Benutzerprofils und andere Funktionen anzuzeigen, kann das Benutzererlebnis auf der Seite verbessern.
