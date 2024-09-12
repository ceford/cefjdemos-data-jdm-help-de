<!-- Filename: Help4.x:Site_Global_Configuration / Display title: Konfiguration -->

## Beschreibung

Der Bildschirm *Globale Konfiguration* ermöglicht es Ihnen, die Joomla-Website mit Ihren persönlichen Einstellungen zu konfigurieren. Einstellungen, die in diesem Bildschirm vorgenommen werden, gelten für die gesamte Website.

### Allgemeine Elemente

Einige Aspekte dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Berechtigungs-Tab](jdocmanual?article=help/common-elements/edit-permissions).

## So greifen Sie zu

- Wählen Sie **System-Panel → Globale Konfiguration** vom Start-Dashboard. Oder...
- Wählen Sie **System → Setup-Panel → Globale Konfiguration** im Administrator-Menü.

## Screenshot

![Globale Konfiguration Site-Tab](../../../de/images/site/global-configuration-site-tab.png)

## Formularfelder

### Site-Tab

#### Site-Panel

- **Websitename** Geben Sie den Namen der Website ein. Dieser wird an verschiedenen Stellen verwendet (z.B. im Titel des Backend-Browsers und auf Offline-Seiten der Website).
- **Website offline** Wählen Sie, ob der Zugriff auf das Frontend verfügbar ist.
- **Offline-Nachricht**
    - *Verstecken*
    - *Benutzerdefinierte Nachricht verwenden* Die Nachricht verwendet den Wert, der im Feld *Benutzerdefinierte Nachricht* definiert ist.
    - *Standardeinstellung der Website-Sprache verwenden* Die Nachricht verwendet den Wert, der in der Sprach-INI-Datei der Website definiert ist.
- **Offline-Bild** Wählen Sie ein Bild aus, das auf der Offline-Seite angezeigt wird. Achten Sie darauf, dass das Bild weniger als 400px breit ist.
- **Frontend-Bearbeitung** Wählen Sie die Bearbeitung für Module und Menüelemente.
- **Standard-Editor** Wählen Sie den Standard-Texteditor. Registrierte Benutzer können ihre Präferenz in ihren persönlichen Daten ändern.
- **Standard-Captcha** Wählen Sie das Standard-Captcha für Ihre Website. Möglicherweise müssen Sie erforderliche Informationen im Captcha-Plugin eingeben.
- **Standard-Zugriffsebene** Wählen Sie die Standard-Zugriffsebene für neue Elemente.
- **Standardlisten-Limit** Legt die Standardlänge von Listen im Backend für alle Benutzer fest.
- **Standard-Feed-Limit** Wählen Sie die Anzahl der Inhaltsartikel aus, die in den Feeds angezeigt werden sollen.
- **Feed-E-Mail-Adresse** Die RSS- und Atom-Newsfeeds enthalten die E-Mail-Adresse des Autors.
  - *Autor-E-Mail* Die E-Mail-Adresse des Autors des Artikels aus dem Benutzerprofil in den Newsfeed aufnehmen.
  - *Seiten-E-Mail* Verwenden Sie die E-Mail-Adresse *Von der Website* für jeden Artikel.

#### Metadaten-Panel

- **Meta-Beschreibung der Website** Geben Sie eine Beschreibung der gesamten Website ein, die von Suchmaschinen verwendet wird.
- **Robots** Anweisungen für Suchmaschinenroboter.
  - *index, follow* Diese Seite indexieren und den Links auf dieser Seite folgen.
  - *noindex, follow* Diese Seite nicht indexieren, aber den Links auf der Seite folgen. Zum Beispiel für eine Sitemap-Seite, bei der Sie möchten, dass die Links indexiert werden, aber diese Seite nicht in den Suchmaschinen angezeigt wird.
  - *index, nofollow* Diese Seite indexieren, aber keinen Links auf der Seite folgen. Zum Beispiel für einen Veranstaltungskalender, bei dem Sie möchten, dass die Seite in den Suchmaschinen angezeigt wird, aber nicht jedes Ereignis indexiert wird.
  - *noindex, nofollow* Diese Seite nicht indexieren und keinen Links auf der Seite folgen.
- **Nutzungsrechte** Beschreiben Sie, welche Rechte andere an diesem Inhalt haben. Dies wird den Suchmaschinen über das `rights`-Meta-Tag im HTML-Kopf übermittelt.
- **Autor-Meta-Tag** Zeigen Sie das Autor-Meta-Tag beim Ansehen von Artikeln an.
- **Joomla-Version** Steuert, ob das `generator`-Meta-Tag im HTML-Kopf des Frontends und in Atom-Feeds die genaue Joomla-Version der Website enthält. Aus Sicherheitsgründen wird empfohlen, diese auszublenden.

#### SEO-Panel

- **Suchmaschinenfreundliche URLs** Wählen Sie, ob die URLs für Suchmaschinen optimiert sind.
- **URL-Umschreibung verwenden**
  - *Apache und Litespeed* Benennen Sie `htaccess.txt` in `.htaccess` um.
  - *IIS* Benennen Sie `web.config.txt` in `web.config` um.
  - *NginX* Sie müssen Ihren Server konfigurieren.
  - *Andere* Wenn Sie sich unsicher sind, konsultieren Sie bitte Ihren Hosting-Anbieter.
- **Suffix zur URL hinzufügen** Wenn ja, wird das System einen Suffix zur URL basierend auf dem Dokumenttyp hinzufügen.
- **Unicode-Aliase** Wählen Sie zwischen Transliteration und Unicode-Aliassen. Die Transliteration ist der Standard.
- **Website-Name in Seitentiteln** Beginnen oder beenden Sie alle Seitentitel mit dem Website-Namen (z.B. *Mein Seitenname - Mein Artikelname*).

#### Cookie-Panel

- **Cookie-Domain** Domain, die verwendet wird, wenn Sitzungscookies gesetzt werden. Vor der Domain ein '.' einfügen, wenn das Cookie für alle Subdomains gültig sein soll.
- **Cookie-Pfad** Pfad, für den das Cookie gültig sein soll.

### System-Tab

![Globale Konfiguration System-Tab](../../../de/images/site/global-configuration-system-tab.png)

#### Debug-Panel

- **System-Debug** Wenn aktiviert, werden diagnostische Informationen, Sprachübersetzungen und SQL-Fehler (falls vorhanden) angezeigt. Die Informationen werden am Fuß jeder Seite angezeigt, die Sie im Joomla-Backend und -Frontend aufrufen. Es wird nicht empfohlen, den Debug-Modus bei einer Live-Website aktiviert zu lassen.
- **Sprach-Debug** Aktivieren, um die Debug-Indikatoren `**...**` oder `??...??` in der Seitenausgabe zu sehen, wo Joomla-Sprachdateien verwendet werden, um Zeichenfolgen in ihre übersetzten Werte zu übersetzen. Das erste Format zeigt an, dass die Zeichenfolge erfolgreich übersetzt wurde. Das zweite zeigt an, dass der Text in einfacher Sprache eingegeben wurde und nicht übersetzt werden kann.
  - **Sprachanzeige** Wählen Sie aus, ob beim Debuggen der Sprachzeichenfolgen die Sprachkonstante oder der Sprachwert angezeigt werden soll.

#### Cache-Panel

- **System-Cache** Cache aktivieren und Cache-Stufe festlegen.
  - *Konservative Stufe* kleinerer System-Cache.
  - *Progressive Stufe* schnellerer, größerer System-Cache, einschließlich Modul-Renderer-Cache. Nicht geeignet für extrem große Websites.
  - **Cache-Handler**
    - *Datei* Der native Cache-Mechanismus ist dateibasiert. Stellen Sie sicher, dass die Cache-Ordner beschreibbar sind.
  - **Plattformspezifisches Caching** Aktivieren, wenn die HTML-Ausgabe auf mobilen Geräten von anderen Geräten abweicht.
  - **Cache-Zeit (Minuten)** Die maximale Zeit in Minuten, die eine Cache-Datei gespeichert wird, bevor sie aktualisiert wird.
  - **Pfad zum Cache-Ordner** Geben Sie einen beschreibbaren Ordner an, in dem Cache-Dateien gespeichert werden sollen, wenn Sie den Standardordner nicht verwenden möchten.

#### Sitzungs-Panel

- **Sitzungs-Handler** Der Mechanismus, mit dem Joomla einen Benutzer identifiziert, sobald er mit der Website über nicht persistente Cookies verbunden ist.
  - *Datenbank* Der Datenbank-Sitzungs-Handler ist der Standard-Handler, da Joomla ihn vollständig konfigurieren und selbst steuern kann.
  - *Dateisystem* Der Dateisystem-Handler ist etwas performanter als der Datenbank-Handler, erfordert jedoch eine ordnungsgemäße PHP-Konfiguration. Andernfalls wird es abstürzen und Joomla wird vollständig unbenutzbar.
    - **Pfad zum Sitzungs-Speicherort** Geben Sie einen vollständigen Dateisystempfad ein. Stellen Sie sicher, dass der Pfad die entsprechenden Berechtigungen zum Lesen und Schreiben von Dateien durch PHP hat, und wenn die `session garbage collection` aktiviert ist, um Dateien daraus zu löschen. Wenn dieser Pfad nicht festgelegt ist, verlässt sich Joomla auf die PHP-Konfiguration `session.save_path INI` oder auf das temporäre Systemverzeichnis (wie durch die Funktion sys_get_temp_dir() in PHP definiert). Wenn keiner dieser Pfade konfiguriert oder die Berechtigungen falsch sind, ist das Spiel vorbei. Um sich zu erholen, bearbeiten Sie die Datei `configuration.php` und setzen Sie `$session_handler = 'database'`.
  - *Andere Handler* APCu, Memcached, Redis und WinCache hängen alle von optionalen PHP-Erweiterungen ab und sind möglicherweise verfügbar, wenn Ihr System sie unterstützt. APCu oder WinCache bieten möglicherweise keine bessere Leistung als die *einfache* Dateisystem-Option. Die Memcached- und Redis-Handler sind in einer typischen Shared-Hosting-Umgebung für Joomla überdimensioniert. Diese Handler sind nützlich, wenn Sie Joomla in einer Load-Balanced-Umgebung einsetzen, in der mehrere Server beteiligt sind und die Sitzungsdaten für die Anwendung auf allen Servern verfügbar sein müssen.
- **Sitzungsdauer (Minuten)** Automatisches Abmelden eines Benutzers, nachdem er für die eingegebene Anzahl von Minuten inaktiv war. Nicht zu hoch einstellen.
- **Gemeinsame Sitzungen** Wenn aktiviert, wird die Sitzung eines Benutzers zwischen dem Frontend und dem Backend der Website geteilt. Beachten Sie, dass das Ändern dieses Werts alle bestehenden Sitzungen auf der Website ungültig macht. Dies ist nicht verfügbar, wenn die Option [HTTPS erzwingen](#forcehttps) auf *Nur Administrator* gesetzt ist.
- **Sitzungs-Metadaten verfolgen**
  - *Ja* Zusätzliche Metadaten zur Sitzung eines Benutzers (einschließlich Benutzername, Benutzer-ID und in welcher Anwendung er eingeloggt ist) werden in die Sitzungs-Datenbanktabelle protokolliert.
  - *Nein* Funktionen, die auf diesen Daten basieren, sind nicht verfügbar.

### Server-Tab

![Global Configuration Server Tab](../../../de/images/site/global-configuration-server-tab.png)

#### Server-Panel

- **Pfad zum Temp-Ordner** Bitte geben Sie einen beschreibbaren Ordner an, in dem temporäre Dateien gespeichert werden.
- **Gzip-Seitenkomprimierung**
  - *Ja* Komprimiert die generierten HTML-Seiten automatisch mit Gzip, wodurch sie kleiner werden und die Geschwindigkeit Ihrer Website erhöht wird.
  - *Nein* Wenn Ihr Server dies bereits übernimmt oder wenn es zu Konflikten mit Erweiterungen von Drittanbietern kommt.
- **Fehlerberichterstattung** Dieser Parameter legt das Fehlerberichtslevel fest, das von PHP auf der Joomla-Website verwendet wird.
  - *System-Standard* Überlässt das Fehlerberichtslevel der Serverkonfiguration.
  - *Keine* Schaltet die Fehlerberichterstattung aus.
  - *Einfach* Überschreibt die Servereinstellung und gibt ein einfaches Fehlerberichtslevel an.
  - *Maximal* Überschreibt die Servereinstellung und erlaubt die Berichterstattung aller Fehler. Sollte Ihre Joomla-Seite so stark beeinträchtigt sein, dass es nicht möglich ist, die Administratorseite zur Aktivierung der Fehlerberichterstattung zu nutzen, können Sie die vollständige Fehlerberichterstattung aktivieren, indem Sie die Datei `configuration.php` bearbeiten. Das Setzen von `$error_reporting = 'maximum'` entspricht dem Setzen von *Fehlerberichterstattung* auf *Maximal*.
- **HTTPS erzwingen** Erzwingt den Zugriff auf die ausgewählten Bereiche der Website ausschließlich über HTTPS (verschlüsselte HTTP-Verbindungen mit dem https://-Protokoll) und zwingt die Verwendung von sicheren Cookies. Beachten Sie, dass Sie HTTPS auf Ihrem Server aktiviert haben müssen, um diese Option nutzen zu können.

#### Standort-Panel

- **Zeitzone der Website** Wählen Sie eine Stadt aus der Liste aus, um Datum und Uhrzeit für die Anzeige zu konfigurieren.

#### Webdienst-Panel

- **CORS aktivieren** Cross-Origin Resource Sharing oder 
  [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS) ermöglicht es, dass Skripte, die in einem Browser laufen, mit Ressourcen von einer anderen Quelle interagieren.
  - **Access-Control-Allow-Origin** Gibt die Ursprungsquelle an, die auf die Webdienste dieser Seite zugreifen darf. Diese Information wird als Antwort auf eine Preflight-Anfrage zurückgesendet. Standard: `*` (=alle).
  - **Access-Control-Allow-Headers** Gibt die Header(s) an, die als Antwort auf eine Preflight-Anfrage zurückgesendet werden. Standard: `Content-Type,X-Joomla-Token`.
  - **Access-Control-Allow-Methods** Gibt die auf dieser Seite erlaubten Webdienst-Methoden an, die als Antwort auf eine Preflight-Anfrage zurückgesendet werden. Standard: Alle verfügbaren Methoden für die angeforderte Route.

#### Proxy-Panel

- **Hinter Load Balancer** Wenn Ihre Website hinter einem Load Balancer oder einem Reverse Proxy liegt, aktivieren Sie diese Einstellung, damit IP-Adressen und andere Konfigurationen innerhalb von Joomla dies automatisch berücksichtigen.
- **Ausgehenden Proxy aktivieren** Einige Hosts erlauben standardmäßig keinen Netzwerkzugriff von Ihrer Website auf die Außenwelt und erfordern, dass Sie einen ausgehenden Proxy manuell konfigurieren.
  - **Proxy-Host (ausgehend)** Host (Domainname) oder IP-Adresse.
  - **Proxy-Port (ausgehend)** Portnummer.
  - **Proxy-Benutzername (ausgehend)** Lassen Sie dieses Feld leer, wenn der ausgehende Proxy keine Authentifizierung erfordert.
  - **Proxy-Passwort (ausgehend)**

#### Datenbank-Panel

- **Datenbanktyp** Der während des Installationsprozesses ausgewählte Datenbanktyp. Bearbeiten Sie dieses Feld nur, wenn unbedingt erforderlich (z. B. bei der Übertragung der Datenbank zu einem neuen Hosting-Anbieter).
- **Host** Der Hostname Ihrer Datenbank, der während des Installationsprozesses eingegeben wurde. Bearbeiten Sie dieses Feld nur, wenn unbedingt erforderlich (z. B. bei der Übertragung der Datenbank zu einem neuen Hosting-Anbieter).
- **Datenbank-Benutzername** Der Benutzername für den Zugriff auf Ihre Datenbank, der während des Installationsprozesses eingegeben wurde. Bearbeiten Sie dieses Feld nur, wenn unbedingt erforderlich (z. B. bei der Übertragung der Datenbank zu einem neuen Hosting-Anbieter).
- **Datenbank-Passwort** Das Passwort, das für den Zugriff auf die Datenbank verwendet wird. Bearbeiten Sie dieses Feld nur, wenn unbedingt erforderlich (z. B. bei der Übertragung der Datenbank zu einem neuen Hosting-Anbieter).
- **Datenbankname** Der Name Ihrer Datenbank, der während des Installationsprozesses eingegeben wurde. Bearbeiten Sie dieses Feld nur, wenn unbedingt erforderlich (z. B. bei der Übertragung der Datenbank zu einem neuen Hosting-Anbieter).
- **Tabellenpräfix der Datenbank** Das Präfix, das für Ihre Datenbanktabellen verwendet wird und während des Installationsprozesses erstellt wurde. Bearbeiten Sie dieses Feld nur, wenn unbedingt erforderlich (z. B. bei der Übertragung der Datenbank zu einem neuen Hosting-Anbieter).
- **Verbindungssicherheit**
  - Standard (servergesteuert)
  - Einseitige Authentifizierung
    - **Serverzertifikat überprüfen**
      - **Pfad zur CA-Datei** Dateisystempfad.
  - Zweiseitige Authentifizierung
    - **Pfad zur privaten Schlüsseldatei** Dateisystemstandort.
    - **Pfad zur Zertifikatsdatei** Dateisystemstandort.
    - **Serverzertifikat überprüfen**
      - **Pfad zur CA-Datei** Dateisystempfad.
    - **Unterstützte Chiffersuite (optional)** Keine Eingabe erforderlich (nur empfohlen für erfahrene Benutzer). Weitere Details finden Sie in der Dokumentation Ihrer Datenbank.

#### Mail-Panel

- **E-Mails senden**
  - *Ja* Aktiviert das Versenden von E-Mails.
  - *Nein* Deaktiviert das Versenden von E-Mails. Es wird empfohlen, die Website offline zu schalten, wenn die Mail-Funktion deaktiviert wird.
- **Massen-E-Mail deaktivieren**
  - *Ja* Deaktiviert die Funktion "Massen-E-Mails an Benutzer senden".
  - *Nein* Macht die Funktion "Massen-E-Mails an Benutzer senden" aktiv.
- **Von-E-Mail-Adresse** Die E-Mail-Adresse, die zum Senden von E-Mails der Website verwendet wird.
- **Von-Name** Der Text, der im *Von:* Feld im Header angezeigt wird, wenn eine Website-E-Mail gesendet wird. In der Regel der Name der Website.
- **Antwort-E-Mail-Adresse** Die E-Mail-Adresse, an die die Antworten der Benutzer gesendet werden.
- **Antwort-Name** Der Text, der im *An:* Feld im Header angezeigt wird, wenn Benutzer auf empfangene E-Mails antworten.
- **Mailer** Wählen Sie den Mailer aus, der für die Zustellung der E-Mails der Website verwendet wird.

### Protokollierung-Tab

![Global Configuration Logging Tab](../../../de/images/site/global-configuration-logging-tab.png)

#### Protokollierungs-Panel

- **Pfad zum Protokollordner** Joomla kann optional ein Protokoll seiner eigenen und von Drittanbieter-Erweiterungen durchgeführten Vorgänge führen. Geben Sie den absoluten Pfad zu einem Ordner an, der von PHP beschreibbar ist. Falls der Ordner fehlt oder nicht beschreibbar ist, wird Joomla überhaupt nicht geladen. Aus Sicherheitsgründen sollten Sie keinen Ordner mit systemweitem Zugriff wie `/tmp` verwenden.
- **Fast alles protokollieren** Protokolliert alles, außer veraltete APIs.
- **Veraltete API protokollieren** Protokolliert veraltete APIs.

#### Benutzerdefiniertes Protokollierungs-Panel

- **Protokoll-Prioritäten** Kann verwendet werden, um die benutzerdefinierte Protokollierung zu verwalten. Wählen Sie die Ereignisse aus, die Sie im Protokoll sehen möchten. Standard ist *Alle*. Die Elemente können durch Klicken auf die Dropdown-Liste ausgewählt oder abgewählt werden.
- **Protokoll-Kategorien** Eine durch Kommas getrennte Liste von Protokollkategorien, die eingeschlossen oder ausgeschlossen werden sollen. Häufige Protokollkategorien umfassen, sind aber nicht beschränkt auf: `database`, `databasequery`, `database-error`, `deprecated` und `jerror`. Wenn das Feld leer ist, ist die benutzerdefinierte Protokollierung deaktiviert.
- **Protokoll-Kategoriemodus** Legt den Modus für die obige Liste der Protokollkategorien fest.

### Textfilter-Tab

![Global Configuration Text Filters Tab](../../../de/images/site/global-configuration-text-filters-tab.png)

Diese Textfilter-Einstellungen werden auf alle Texteingabefelder angewendet, die von Benutzern in den ausgewählten Gruppen übermittelt werden.

Diese Filteroptionen bieten mehr Kontrolle über das HTML, das Ihre Inhaltsanbieter einreichen. Sie können die Regeln so streng oder locker gestalten, wie es die Anforderungen Ihrer Website erfordern. Die Filterung ist eine Opt-in-Option, und die Standardeinstellungen bieten einen guten Schutz vor Markup, das häufig mit Website-Angriffen in Verbindung gebracht wird.

## Tipps

- Die meisten dieser Einstellungen können einmal festgelegt und dann in Ruhe gelassen werden.
- Wenn wesentliche Änderungen vorgenommen werden müssen, sollten Sie in Erwägung ziehen, die Website offline zu schalten, um sie zu testen und sicherzustellen, dass alles ordnungsgemäß funktioniert.
- Die Einstellungen werden in der Datei `configuration.php` im Stammverzeichnis der Website gespeichert. Die Berechtigungen dieser Datei werden nach Änderungen über die Seite Globale Konfiguration auf schreibgeschützt (444) gesetzt und müssen auf Schreibberechtigung für den Eigentümer (644) geändert werden, bevor sie mit einem Texteditor bearbeitet werden können.
