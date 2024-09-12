<!-- Filename: Help4.x:Users:_Options / Display title: Benutzer: Optionen -->

## Beschreibung

Die Seite *Benutzer: Optionen* wird verwendet, um globale Optionen für alle Benutzer festzulegen, darunter:

- Captcha,
- Registrierung erlaubt und Registrierungsart,
- Standard-Benutzergruppe für neue Benutzer,
- Zurücksetzungszähler für Passwort oder Benutzernamen,
- Benachrichtigung über neue Benutzerregistrierungen an die Administration und mehr.

## So greifen Sie darauf zu

* Wählen Sie **Website → Benutzer** aus dem *Home Dashboard*. Oder...
* Wählen Sie **Benutzer → Verwalten** aus dem Administrator-Menü. Dann...
* Wählen Sie die Schaltfläche **Optionen** in der Werkzeugleiste.

## Screenshot

![Benutzer Optionen Benutzer Optionen Tab](../../../de/images/users/users-options-user-options-tab.png)

## Formularfelder

### Benutzeroptionen-Tab

- **Benutzerregistrierung erlauben**
  - *Ja* Benutzer können sich über das Frontend der Website registrieren, indem sie den Link *Ein Konto erstellen* im Anmeldeformular nutzen.
  - *Nein* Der Link *Ein Konto erstellen* wird nicht angezeigt.
- **Gruppe für neue Benutzerregistrierungen** Die Gruppe, der Benutzer standardmäßig zugewiesen werden, wenn sie sich auf der Website registrieren. Standardwert ist *Registriert*.
- **Gast-Benutzergruppe** Die Gruppe, der Gäste zugewiesen werden (Gäste sind Besucher der Website, die nicht angemeldet sind). Es ist möglich, Inhalte auf der Website zu erstellen, die für Gäste sichtbar sind, aber nicht für angemeldete Benutzer.
- **Passwort senden** Wenn auf *Ja* gesetzt, wird das erste Passwort des Benutzers in der Registrierungs-E-Mail an den Benutzer gesendet.
- **Aktivierung des neuen Benutzerkontos**
  - *Keine* Das Benutzerkonto wird sofort aktiv, ohne dass eine Aktion erforderlich ist.
  - *Selbst* Der Benutzer erhält eine E-Mail mit einem Aktivierungslink. Das Konto wird aktiviert, wenn der Benutzer den Aktivierungslink auswählt.
  - *Administrator* Der Benutzer erhält eine E-Mail mit einem Aktivierungslink. Wenn der Benutzer diesen Link auswählt, wird der Website-Administrator per E-Mail benachrichtigt und aufgefordert, das Benutzerkonto zu aktivieren.
- **E-Mail an Administratoren senden** E-Mail-Benachrichtigung an Administratoren senden, wenn die *Aktivierung des neuen Benutzerkontos* auf *Keine* oder *Selbst* gesetzt ist.
- **Captcha** Das Captcha-Plugin für die Registrierung von Benutzerkonten, Passworterinnerung und Benutzernamen-Erinnerung.
- **Frontend-Benutzerparameter**
  - *Anzeigen* Benutzer können grundlegende Einstellungen über das Frontend der Website ändern.
  - *Ausblenden* Benutzer können diese Einstellungen nicht ändern.
- **Frontend-Sprache** Website-Sprache anzeigen oder ausblenden.
- **Benutzername ändern** Benutzer dürfen ihren Benutzernamen ändern.

### E-Mail-Domain-Optionen-Tab

![Benutzer Optionen E-Mail-Domains Tab](../../../de/images/users/users-options-email-domain-options-tab.png)

- **Domain-Name** Geben Sie eine Liste der erlaubten und nicht erlaubten E-Mail-Domains ein. Standardmäßig sind alle Domains erlaubt. Platzhalter (\*) werden unterstützt. Zum Beispiel:
  - \* (Sternchen): Erlaubt oder verbietet alle Domains
  - \*.com: Erlaubt oder verbietet alle '.com'-Domains
  - \*.joomla.org: Erlaubt oder verbietet alle 'joomla.org'-Subdomains.
- **Regel** Wählen Sie aus, ob die Domain erlaubt oder verboten wird.

### Passwortoptionen-Tab

![Benutzer Optionen Passwortoptionen Tab](../../../de/images/users/users-options-password-options-tab.png)

- **Maximale Anzahl an Zurücksetzungen** Die maximale Anzahl an Passwortzurücksetzungen innerhalb des Zeitraums. Null bedeutet keine Begrenzung.
- **Zurücksetzungszeitraum** Der Zeitraum in Stunden, in dem der Zurücksetzungszähler gilt.
- **Minimale Länge** Legen Sie die Mindestlänge für ein Passwort fest.
- **Minimale Anzahl an Ziffern** Legen Sie die minimale Anzahl an Ziffern fest, die in einem Passwort enthalten sein müssen.
- **Minimale Anzahl an Symbolen** Legen Sie die minimale Anzahl an Symbolen (z.B. !@#\$) fest, die in einem Passwort erforderlich sind.
- **Minimale Anzahl an Großbuchstaben** Legen Sie die minimale Anzahl an Großbuchstaben fest, die in einem Passwort enthalten sein müssen.
- **Minimale Anzahl an Kleinbuchstaben** Legen Sie die minimale Anzahl an Kleinbuchstaben fest, die in einem Passwort enthalten sein müssen.

### Multi-Faktor-Authentifizierungs-Tab

![Benutzer Optionen Multi-Faktor-Authentifizierung Tab](../../../de/images/users/users-options-multi-factor-authentication-tab.png)

- **Erlaubte Frontend-Modulpositionen** Beim Anzeigen der Multi-Faktor-Authentifizierungsseite im Frontend werden alle Module außer denen in den hier ausgewählten Positionen ausgeblendet.
- **Titel im Frontend anzeigen** Einen Titel auf der Frontend-Multi-Faktor-Authentifizierungsseite anzeigen? Beachten Sie, dass der Titel im Backend immer angezeigt wird. Wenn Sie den Titel ändern müssen, überschreiben Sie den Sprachschlüssel `COM_USERS_HEADING_MFA` mit *Languages: Overrides*.
- **Erlaubte Backend-Modulpositionen** Beim Anzeigen der Multi-Faktor-Authentifizierungsseite im Backend werden alle Module außer denen in den hier ausgewählten Positionen ausgeblendet. Beachten Sie, dass Module in der `title`-Position immer angezeigt werden: Dies ist erforderlich, um das Symbol und den Titel der Backend-Seite anzuzeigen.
- **Multi-Faktor-Authentifizierung deaktivieren** Jeder Benutzer, der einer *beliebigen* der ausgewählten Benutzergruppen angehört, ist von der Multi-Faktor-Authentifizierung ausgenommen. Auch wenn sie Methoden zur Multi-Faktor-Authentifizierung eingerichtet haben, werden sie nicht aufgefordert, diese zu verwenden, wenn sie sich anmelden, und sie können diese Methoden weder anzeigen noch entfernen oder ihre Konfiguration ändern.
- **Multi-Faktor-Authentifizierung erzwingen** Jeder Benutzer, der einer *beliebigen* der ausgewählten Benutzergruppen angehört, muss die Multi-Faktor-Authentifizierung aktivieren, bevor er die Website nutzen kann.
- **Frontend-Template-Stil** Wählen Sie den Frontend-Template-Stil für die Multi-Faktor-Authentifizierungsseite. Wählen Sie *Standard verwenden*, um den Standard-Website-Template-Stil zu verwenden.
- **Multi-Faktor-Authentifizierung nach stillem Login** Muss der Benutzer die Multi-Faktor-Authentifizierung nach einem stillen Benutzer-Login durchlaufen? Stille Logins sind solche, bei denen kein Benutzername und Passwort erforderlich sind, z. B. die Funktion *Erinnere mich*, WebAuthn usw.
- **Antworttypen für stille Login-Authentifizierung (für Experten)** Für Experten. Eine durch Kommas getrennte Liste von Joomla-Authentifizierungsantworttypen, die als stille Logins gelten. Der Standard ist `cookie` (die Funktion *Erinnere mich*) und `passwordless` (WebAuthn).
- **Neue Benutzer an Bord holen** Wenn der Benutzer die Multi-Faktor-Authentifizierung noch nicht eingerichtet hat und diese Option aktiviert ist, wird er auf die Seite zur Einrichtung der Multi-Faktor-Authentifizierung weitergeleitet oder auf die unten festgelegte benutzerdefinierte URL weitergeleitet. Dies soll eine einfache Möglichkeit bieten, Ihre Benutzer darüber zu informieren, dass Multi-Faktor-Authentifizierung auf Ihrer Website eine Option ist.
- **Benutzerdefinierte Weiterleitungs-URL** Wenn dieses Feld nicht leer ist, wird stattdessen zu dieser URL umgeleitet, wenn die obige Option aktiviert ist. Warnung: Dies muss eine URL innerhalb Ihrer Website sein. Sie können sich nicht auf einen externen Link oder eine andere Subdomain einloggen.

### Benutzernotizen-Verlauf-Tab

![Benutzer Optionen Benutzernotizen-Verlauf Tab](../../../de/images/users/users-options-user-notes-history-tab.png)

- **Versionen aktivieren** Versionsverlauf für Benutzernotizen speichern.
- **Maximale Versionen** Die maximale Anzahl von Versionen, die für eine Benutzernotiz gespeichert werden. Wenn eine Benutzernotiz gespeichert wird und die maximale Anzahl von Versionen erreicht wurde, wird die älteste Version automatisch gelöscht. Wenn auf 0 gesetzt, werden Versionen nie automatisch gelöscht.

### Massenmail-Benutzer-Tab

![Benutzer Optionen Massenmail-Benutzer Tab](../../../de/images/users/users-options-mass-mail-users-tab.png)

- **Betreff-Präfix** Geben Sie optionalen Text ein, der automatisch vor dem Betreff der Massen-E-Mail eingefügt wird.
- **E-Mail-Suffix** Geben Sie optionalen Text ein, der automatisch nach dem Text der E-Mail eingefügt wird (z. B. eine Signatur).

### Integrations-Tab

![Benutzer Optionen Integrations-Tab](../../../de/images/users/users-options-integration-tab.png)

- **Benutzerdefinierte Felder aktivieren** Aktivieren Sie die Erstellung von benutzerdefinierten Feldern.

## Tipps

Wenn Sie ein unerfahrener Benutzer sind, belassen Sie die Standardwerte, bis Sie mehr über die Verwendung der globalen Optionen erfahren.
