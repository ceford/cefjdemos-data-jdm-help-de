<!-- Filename: Help4.x:Redirects:_Links / Display title: Weiterleitungen: Links -->

## Beschreibung

Die Seite *Weiterleitungen: Links* zeigt eine Liste der aktuellen Weiterleitungen Ihrer Website.

Die Weiterleitungskomponente wird verwendet, um URLs für Webseiten, die nicht mehr auf Ihrer Website existieren, auf funktionierende Webseiten weiterzuleiten. Die URL, von der Sie weiterleiten möchten, darf nicht funktionieren und tatsächlich keine Seite laden. Es kann die URL einer Webseite sein, die Sie deaktiviert haben.

Die *Abgelaufene URL*, die Sie beim Erstellen der Weiterleitung angeben, sollte die vollständige URL sein, wie Sie sie in Ihrem Webbrowser eingeben würden. Die Komponente zeigt in der Weiterleitungsliste nur den letzten Teil der Quell-URL an.

Die *Neue URL*, die Sie beim Erstellen einer Weiterleitung angeben, muss ebenfalls die vollständige URL sein. Sie müssen die Option *URL-Umschreibung verwenden* in den *Globalen Konfigurationseinstellungen* Ihrer Joomla!-Installation aktiviert haben, damit die erstellten Weiterleitungen funktionieren.

### Gemeinsame Elemente

Einige Elemente dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Listenfilter](jdocmanual?article=help/common-elements/list-filters).
* [Spaltenüberschriften der Liste](jdocmanual?article=help/common-elements/list-column-headers).
* [Seitennummerierung der Liste](jdocmanual?article=help/common-elements/list-pagination).

## Zugriff

- Wählen Sie **System → Verwaltungspanel → Weiterleitungen** aus dem Administrator-Menü.

## Screenshot

![Weiterleitungen Links](../../../de/images/redirects/redirects-links.png)

## Spaltenüberschriften

- **Abgelaufene URL** Die URL, die auf Ihrer Website weitergeleitet wird.
  In dieser Liste wird nur der Webseitenteil der URL angezeigt.
- **Neue URL** Die Ziel-URL der Weiterleitung.
- **Verweisende Seite** Die verweisende Webseite für die Weiterleitung.
- **Erstellungsdatum** Datum, an dem der Artikel (Artikel, Kategorie, etc.) erstellt wurde.
- **404-Treffer** Anzahl der 404-Treffer, die auf dieser URL verzeichnet wurden.
- **Statuscode** Der Statuscode der Seite.

## Tipps

- Damit Ihre Weiterleitungen funktionieren, müssen Sie die Option **URL-Umschreibung verwenden** in den **Globalen Konfigurationseinstellungen** Ihrer Joomla!-Installation aktivieren. Beachten Sie auch, dass das Aktivieren der *URL-Umschreibung verwenden*-Option allein nicht ausreicht. Sie müssen zusätzlich die Datei `htaccess.txt` im Verzeichnis Ihrer Joomla!-Installation in `.htaccess` umbenennen oder in den Dateinamen, den Ihr Apache-Webserver für zusätzliche Konfigurationsanweisungen benötigt. In der Apache-Konfigurationsdatei wird diese Einstellung als `AccessFileName` bezeichnet, und standardmäßig ist sie auf `.htaccess` gesetzt.
