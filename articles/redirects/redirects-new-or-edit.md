<!-- Filename: Help4.x:Redirects:_New_or_Edit / Display title: Weiterleitungen: Neu oder Bearbeiten -->

## Beschreibung

Die Seite *Weiterleitungen: Neu oder Bearbeiten* wird verwendet, um eine neue Weiterleitung hinzuzufügen oder eine bestehende zu bearbeiten. Die URL, von der Sie weiterleiten möchten, darf keine funktionierende URL auf Ihrer Website sein, die tatsächlich eine Webseite lädt. Es kann die URL einer Webseite sein, die Sie in der Joomla!-Administratoroberfläche deaktiviert haben. Die Quell-URL, die Sie beim Erstellen der Weiterleitung angeben, sollte die vollständige URL sein, wie Sie sie in Ihrem Webbrowser eingeben würden. Die Ziel-URL, die Sie beim Erstellen der Weiterleitung angeben, muss ebenfalls die vollständige URL sein.

### Gemeinsame Elemente

Einige Elemente dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).

## Zugriff

- Wählen Sie **System → Weiterleitungen** aus dem Administrator-Menü. Dann...
  - Um eine neue Weiterleitung zu erstellen, klicken Sie auf die Schaltfläche **Neu** in der Werkzeugleiste. Oder...
  - Um eine bestehende Weiterleitung zu bearbeiten, klicken Sie auf den Link in der Spalte **Abgelaufene URL**.

## Screenshot

![Weiterleitungen Links](../../../de/images/redirects/redirects-edit.png)

## Formularfelder

### Bearbeiten/Neuer Link \#1-Tab

- **Abgelaufene URL** Die URL, die weitergeleitet werden soll.
- **Neue URL** Die URL, zu der weitergeleitet wird.
- **Status** Veröffentlichungsstatus des Elements. Mögliche Werte sind:
  - *Aktivieren* Das Element ist aktiviert. Dies ist der einzige Status, der es regulären Website-Benutzern ermöglicht, dieses Element anzuzeigen.
  - *Deaktivieren* Das Element ist deaktiviert.
  - *Archiviert* Das Element wurde archiviert.
  - *Papierkorb* Das Element wurde in den Papierkorb verschoben.
- **Kommentar** Ein Kommentar, der nur für Administratoren sichtbar ist. Er ist hauptsächlich für die interne Referenz von Administratoren gedacht.
- **ID** Dies ist eine eindeutige Identifikationsnummer für dieses Element, die von Joomla automatisch zugewiesen wird. Sie dient zur internen Identifikation des Elements, und Sie können diese Nummer nicht ändern. Beim Erstellen eines neuen Elements zeigt dieses Feld "0" an, bis Sie den neuen Eintrag speichern, woraufhin eine neue ID zugewiesen wird.
- **Erstellungsdatum** Datum, an dem das Element (Artikel, Kategorie, etc.) erstellt wurde.
- **Letztes Aktualisierungsdatum** Zeigt das letzte Datum an, an dem das Element bearbeitet wurde.

## Wie man eine Weiterleitung erstellt

1.  Stellen Sie zunächst sicher, dass Sie die Option *URL-Umschreibung verwenden* in den globalen Konfigurationseinstellungen Ihrer Joomla!-Installation aktiviert haben. Beachten Sie, dass das Aktivieren der *URL-Umschreibung verwenden*-Option allein nicht ausreicht. Sie müssen außerdem den zusätzlichen Schritt unternehmen, die Datei `htaccess.txt` im Verzeichnis des Webservers, in dem Sie Joomla! installiert haben, in `.htaccess` oder in einen Dateinamen umzubenennen, den Ihr Apache-Webserver für zusätzliche Konfigurationsanweisungen benötigt. In der Apache-Konfigurationsdatei wird diese Einstellung `AccessFileName` genannt und ist standardmäßig auf `.htaccess` gesetzt.
2.  Öffnen Sie als Nächstes die Seite *Weiterleitungen: Links* und wählen Sie die Schaltfläche *Neu* in der Werkzeugleiste aus.
3.  Geben Sie auf der Seite *Weiterleitungen: Neu* die Weiterleitungsinformationen ein. Wenn Sie URLs in die Felder *Abgelaufene URL* und *Neue URL* eingeben, geben Sie die vollständige URL so ein, wie Sie sie in Ihrem Webbrowser eingeben würden. Die *Abgelaufene URL* sollte eine URL sein, die auf keine gültige Webseite auf Ihrer Website verweist. Sie können eine Quell-URL für eine Joomla!-Webseite angeben, die Sie im Administrator-Backend deaktiviert haben. Stellen Sie sicher, dass die *Status*-Option auf **Aktiviert** gesetzt ist.
4.  Wählen Sie die Schaltfläche **Speichern & Schließen** in der Werkzeugleiste, um Ihre neue Weiterleitung zu speichern und zu aktivieren.

## Tipps

- Wenn Sie URLs in die Felder *Abgelaufene/Quell-URL* und *Neue/Ziel-URL* eingeben, geben Sie die vollständige URL so ein, wie Sie sie in Ihrem Webbrowser eingeben würden, um die Webseite aufzurufen.
