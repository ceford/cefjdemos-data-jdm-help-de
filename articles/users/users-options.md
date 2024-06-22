<!-- Filename: Help4.x:Users:_Options / Display title: Benutzer: Optionen -->

## Beschreibung

Zu den Benutzeroptionen, die global für alle Benutzer festgelegt werden,
gehören

- Captcha,
- erlaubte Eigen-Registrierung und Art der Registrierung,
- die Standardbenutzergruppe für neue Benutzer,
- Zähler für ein zurückgesetztes Passwort oder Benutzernamen,
- E-Mail-Benachrichtigung an die Administration bei der Registrierung
  neuer Benutzer und mehr.

## Wie darauf zugreifen
Wählen **Benutzer → Verwalten**

- auf den Button **Optionen** der Werkzeugleiste klicken.

## Bildschirmfoto

<img
src="https://docs.joomla.org/images/thumb/4/47/Help-4x-Users-Options-screen-de.png/800px-Help-4x-Users-Options-screen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/47/Help-4x-Users-Options-screen-de.png/1200px-Help-4x-Users-Options-screen-de.png 1.5x, https://docs.joomla.org/images/thumb/4/47/Help-4x-Users-Options-screen-de.png/1600px-Help-4x-Users-Options-screen-de.png 2x"
data-file-width="2400" data-file-height="1500" width="800" height="500"
alt="Users Options screen" />

## Formular Felder

### Benutzeroptionen

- **Benutzerregistrierung**.
  - Ja: Benutzer können sich über das Frontend mit dem
    "Registrieren"-Link des Moduls
    Anmeldung
    registrieren.
  - Nein: Der 'Registrieren'-Link wird nicht angezeigt.
- **Gruppe für neue Benutzer**. Zu dieser
  Gruppe
  werden Benutzer automatisch hinzugefügt, die sich über das Frontend
  registrieren. Standard ist 'Registriert'.
- **Gast Benutzergruppe**. Zu dieser Standard-Benutzergruppe zählen alle
  als Gast bezeichneten (nicht angemeldeten) Benutzer. Inhalt kann für
  Gäste, aber nicht für eingewählte Benutzer sichtbar sein.
- **Passwort mitsenden**. Ist 'Ja' gewählt, enthält die E-Mail nach der
  Registrierung auch das vergebene Passwort.
- **Kontenaktivierung durch**.
  - Keine: Der Benutzer kann sich sofort selbst registrieren.
  - Benutzer: Dem Benutzer wird per E-Mail ein Link gesendet, mit dem er
    sein Benutzerkonto freischalten kann.
  - Administrator: Dem Benutzer wird per E-Mail ein Link gesendet, mit
    dem er seine eigene E-Mail-Adresse bestätigen kann, anschließend
    werden alle Benutzer, die System-E-Mails erhalten dürfen und die
    Berechtigung haben neue Benutzer anzulegen, über den neuen Benutzer
    informiert und gebeten, dessen Benutzerkonto freizuschalten.
- **Informationsmail an Administratoren**. Wenn 'Kontenaktivierung
  durch' auf 'Keine' oder 'Benutzer' eingestellt wurde, eine
  Informationsmail an Administratoren versenden.
- **Captcha**.
  Captcha
  für 'Registrieren', 'Passwort vergessen' und 'Benutzername vergessen'
  verwenden.
- **Einstellungen im Frontend**.
  - Anzeigen: Benutzer können die
    Basiseinstellungen
    im Frontend ändern.
  - Verbergen: Benutzer können diese Einstellungen nicht ändern.
  - Frontend-Sprache. Die Standard-Seitensprache.
- **Benutzername veränderbar**. Erlaubt Benutzern, ihren Benutzernamen
  zu ändern.

### E-Mail-Domainoptionen

<img
src="https://docs.joomla.org/images/thumb/8/86/Help-4x-Users-Options-email-domain-subscreen-de.png/600px-Help-4x-Users-Options-email-domain-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/86/Help-4x-Users-Options-email-domain-subscreen-de.png/900px-Help-4x-Users-Options-email-domain-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/8/86/Help-4x-Users-Options-email-domain-subscreen-de.png/1200px-Help-4x-Users-Options-email-domain-subscreen-de.png 2x"
data-file-width="2002" data-file-height="1073" width="600" height="322"
alt="Users Options email domain subscreen" />

- **Domainname**. Eine Liste der erlaubten und nicht erlaubten
  E-Mail-Domains eingeben. Standardmäßig sind alle Domains
  erlaubt.Wildcards (\*) werden unterstützt. Beispiele:
  - \* (Sternchen): Erlaubt oder nicht erlaubt alle Domains,
  - \*.com: Erlaubt oder nicht erlaubt alle '.com' Domains
  - \*.joomla.org: Erlaubt oder nicht erlaubt alle 'joomla.org'
    Subdomains.
- **Regel** Auswählen, ob die Domain erlaubt oder nicht erlaubt werden
  soll.

### Passwortoptionen

<img
src="https://docs.joomla.org/images/thumb/8/86/Help-4x-Users-Options-password-subscreen-de.png/600px-Help-4x-Users-Options-password-subscreen-de.png.jpeg"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/86/Help-4x-Users-Options-password-subscreen-de.png/900px-Help-4x-Users-Options-password-subscreen-de.png.jpeg 1.5x, https://docs.joomla.org/images/thumb/8/86/Help-4x-Users-Options-password-subscreen-de.png/1200px-Help-4x-Users-Options-password-subscreen-de.png.jpeg 2x"
data-file-width="2002" data-file-height="1257" width="600" height="377"
alt="Users Options password subscreen" />

- **Zurücksetzungsmaximum**. Die maximale Anzahl von
  Passwortrücksetzungen, die im angegebenen Zeitraum erlaubt sind. Bei
  *0* gibt es keine Einschränkungen.
- **Zurücksetzungsdauer (Stunden)**. Die Zeitspanne, innerhalb der die
  maximalen Passwortzurücksetzungen erlaubt sind.
- **Minimale Passwortlänge**. Legt die minimale Länge eines Passworts
  fest.
- **Minimal enthaltene Ziffern**. Legt die minimale Anzahl von Ziffern
  im Passwort fest.
- **Minimal enthaltene Sonderzeichen**. Legt die minimale Anzahl von
  Sonderzeichen (wie !@#\$) im Passwort fest.
- **Minimal enthaltene Großbuchstaben**. Legt die minimale Anzahl von
  Großbuchstaben im Passwort fest.
- **Minimal enthaltene Kleinbuchstaben**. Legt die minimale Anzahl von
  Kleinbuchstaben im Passwort fest.

### Multi-Faktor-Authentifizierung

<img
src="https://docs.joomla.org/images/thumb/7/7d/Help-4x-Users-Options-multi-factor-authentication-subscreen-de.png/600px-Help-4x-Users-Options-multi-factor-authentication-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/7d/Help-4x-Users-Options-multi-factor-authentication-subscreen-de.png/900px-Help-4x-Users-Options-multi-factor-authentication-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/7/7d/Help-4x-Users-Options-multi-factor-authentication-subscreen-de.png/1200px-Help-4x-Users-Options-multi-factor-authentication-subscreen-de.png 2x"
data-file-width="2002" data-file-height="1518" width="600" height="455"
alt="Users Options multi factor authentication subscreen" />

- **Erlaubte Site-Modulpositionen**. Auf der
  Multifaktor-Authentifizierungsseite der Website werden alle Module
  ausgeblendet, mit Ausnahme derjenigen, die sich an den hier
  ausgewählten Positionen befinden.
- **Titel im Frontend anzeigen**. Soll im Frontend der Titel zur
  Überprüfung der Multi-Faktor-Authentifizierung gezeigt werden?
  Hinweis: Der Titel wird im Backend immer angezeigt. Wenn der Titel
  geändert werden soll, muss der Sprachschlüssel 'COM_USERS_HEADING_MFA'
  in Sprachen:
  Overrides
  überschrieben werden.
- **Erlaubte Administrator-Modulpositionen**. Auf der
  Multifaktor-Authentifizierungsseite der Administration werden alle
  Module ausgeblendet, mit Ausnahme derjenigen, die sich an den hier
  gewählten Positionen befinden. Bitte beachten, dass Module an der
  Position 'title' immer gezeigt werden: Dies ist notwendig, um das
  Symbol und den Titel der Administration anzuzeigen.
- **Multi-Faktor-Authentifizierung deaktivieren**. Jeder Benutzer, der
  *einer* der gewählten Benutzergruppen angehört, wird von der
  Multi-Faktor-Authentifizierung ausgenommen. Selbst wenn diese Benutzer
  bereits die Multi-Faktor-Authentifizierung eingerichtet hatten, werden
  sie nicht aufgefordert, diese bei der Anmeldung zu verwenden. Die
  Benutzer können die Multi-Faktor-Authentifizierung weder anzeigen,
  entfernen noch ihre Konfiguration ändern.
- **Multi-Faktor-Authentifizierung erzwingen**. Jeder Benutzer, der
  *einer* der gewählten Benutzergruppen angehört, muss die
  Multi-Faktor-Authentifizierung aktivieren, bevor er die Website nutzen
  kann.
- **Site Template Stil**. Der Template-Stil für das Frontend, der auf
  der Seite der Multi-Faktor-Authentifizierung verwendet werden soll.
  Die Option "Standard verwenden" ermöglicht die Verwendung des
  Standard-Templates der Website.
- **Multi-Faktor-Authentifizierung nach stiller Anmeldung**. Soll der
  Benutzer nach einer stillen Anmeldung die
  Multi-Faktor-Authentifizierung durchlaufen müssen? Stille Anmeldungen
  sind Anmeldungen, die keinen Benutzernamen und kein Kennwort
  erfordern, zum Beispiel die Funktion 'Angemeldet bleiben', WebAuthn
  usw.
- **Antworttypen der unbeaufsichtigten (silent) Anmeldeauthentifizierung
  (für Experten)**. Eine durch Kommas getrennte Liste von
  Joomla-Authentifizierungsantworttypen, die als stille Anmeldungen
  gelten. Die Standardeinstellung ist 'cookie' (Funktion 'Angemeldet
  bleiben') und 'passwordless' (WebAuthn).
- **Einbindung neuer Benutzer**. Wenn der Benutzer die
  Multi-Faktor-Authentifizierung noch nicht eingerichtet hat und diese
  Option aktiviert ist, wird er zur Einrichtungsseite der
  Multi-Faktor-Authentifizierung oder zur unten eingerichteten URL
  weitergeleitet. Auf diese Weise kann den Nutzern auf einfache Weise
  mitgeteilt werden, dass die Multi-Faktor-Authentifizierung eine Option
  auf dieser Website ist.
- **Benutzerdefinierte Weiterleitungs-URL**. Wenn das Feld nicht leer
  ist, wird auf diese URL umgeleitet anstatt auf die Seite zur
  Einrichtung der Multi-Faktor-Authentifizierung, falls die Option oben
  aktiviert ist.Warnung!: Dies muss eine URL innerhalb der Website sein.
  Eine Anmeldung über einen externen Link oder in einer anderen
  Subdomain ist nicht möglich.

### Verlauf Benutzerhinweise

<img
src="https://docs.joomla.org/images/thumb/c/c3/Help-4x-Users-Options-user-notes-history-subscreen-de.png/600px-Help-4x-Users-Options-user-notes-history-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/c3/Help-4x-Users-Options-user-notes-history-subscreen-de.png/900px-Help-4x-Users-Options-user-notes-history-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/c/c3/Help-4x-Users-Options-user-notes-history-subscreen-de.png/1200px-Help-4x-Users-Options-user-notes-history-subscreen-de.png 2x"
data-file-width="2002" data-file-height="565" width="600" height="169"
alt="Users Options user notes history subscreen" />

- **Versionen speichern**. Versionen für Benutzerhinweise speichern.
- **Anzahl Versionen**. Maximale Anzahl der zu speichernden Versionen
  eines Benutzerhinweises. Wird ein Benutzerhinweise gespeichert und die
  maximale Anzahl der Versionen ist erreicht, wird die älteste Version
  automatisch gelöscht. Wird '0' eingetragen, werden die alten Versionen
  nicht gelöscht. Mehr
  erfahren.

### Serienmail-Benutzer

<img
src="https://docs.joomla.org/images/thumb/9/9e/Help-4x-Users-Options-mass-mail-users-subscreen-de.png/600px-Help-4x-Users-Options-mass-mail-users-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/9/9e/Help-4x-Users-Options-mass-mail-users-subscreen-de.png/900px-Help-4x-Users-Options-mass-mail-users-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/9/9e/Help-4x-Users-Options-mass-mail-users-subscreen-de.png/1200px-Help-4x-Users-Options-mass-mail-users-subscreen-de.png 2x"
data-file-width="2002" data-file-height="879" width="600" height="263"
alt="Users Options mass mail users subscreen" />

- **Betreffpräfix**. Dieser optionale Präfix wird vor jedem
  E-Mail-Betreff eingefügt.
- **Signatur**. Optionaler Text, der automatisch hinter dem Hauptteil
  der E-Mail eingefügt wird (z.B. eine Signatur).

### Integration

<img
src="https://docs.joomla.org/images/thumb/e/e9/Help-4x-Users-Options-integration-subscreen-de.png/600px-Help-4x-Users-Options-integration-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/e9/Help-4x-Users-Options-integration-subscreen-de.png/900px-Help-4x-Users-Options-integration-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/e/e9/Help-4x-Users-Options-integration-subscreen-de.png/1200px-Help-4x-Users-Options-integration-subscreen-de.png 2x"
data-file-width="2002" data-file-height="593" width="600" height="178"
alt="Users Options integration subscreen" />

- **Eigene Felder aktivieren**. Erstellen eigener Felder aktivieren.

### Berechtigungen

In diesem Teil werden die Standardwerte der
Zugriffskontrollliste
für alle Benutzer eingestellt.

<img
src="https://docs.joomla.org/images/thumb/3/32/Help-4x-Users-Options-permissions-subscreen-de.png/600px-Help-4x-Users-Options-permissions-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/3/32/Help-4x-Users-Options-permissions-subscreen-de.png/900px-Help-4x-Users-Options-permissions-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/3/32/Help-4x-Users-Options-permissions-subscreen-de.png/1200px-Help-4x-Users-Options-permissions-subscreen-de.png 2x"
data-file-width="2002" data-file-height="1510" width="600" height="453"
alt="Users Options permissions subscreen" />

Um Berechtigungen für Benutzer zu ändern:

1.  Die **Gruppe** durch Anklicken des Namens auf der linken Seite
    auswählen.
2.  Die gewünschte **Aktion** aussuchen.
    - **ACL & Optionen konfigurieren**. Benutzer können Optionen und
      Berechtigungen bearbeiten.
    - **Nur Optionen konfigurieren**. Benutzer können Optionen
      ausgenommen der Berechtigungen bearbeiten.
    - **Administrationszugriff**. Benutzer haben Zugriff auf die
      Administration.
    - **Erstellen**. Benutzer können Benutzer erstellen.
    - **Löschen**. Benutzer können Benutzer löschen.
    - **Bearbeiten**. Benutzer können Benutzer bearbeiten.
    - **Status bearbeiten**. Benutzer können den Status und verwandte
      Informationen bearbeiten.
    - **Inhalt von eigenen Feldern bearbeiten**. Benutzer können eigene
      Felder in Benutzern bearbeiten.
3.  Die Berechtigungen der gewählten Aktion wählen.
    - **Vererbt**. Für Benutzer dieser Gruppe von der
      Konfiguration
      vererbt .
    - **Erlaubt**. Für Benutzer dieser Gruppe erlaubt.Hinweis: Wenn die
      Aktion auf einer höheren Ebene 'Verweigert' wird, ist die
      'Erlaubt'-Berechtigung hier dadurch überschrieben. Eine
      'Verweigert'-Einstellung kann nicht überschrieben werden.
    - **Verweigert**. Verweigert für Benutzer dieser Gruppe.
4.  Auf **Speichern** in der **Werkzeugleiste** oben klicken. Danach
    aktualisiert sich die Anzeige, erst dann werden die errechneten
    Einstellungen angezeigt.

## Werkzeugleiste

Das Bildschirmfoto zeigt die Werkzeugleiste im oberen
Bereich.

- **Speichern**. Speichert die Benutzer-Optionen und bleibt auf der
  aktuellen Seite.
- **Speichern & Schließen**. Speichert die Benutzer-Optionen und
  schließt die aktuelle Seite.
- **Schließen**. Schließt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Änderungen zurück.
- **Inline-Hilfe umschalten**. Hilfetext unter einigen Optionen ein-
  oder ausschalten.
- **Hilfe**. Öffnet die Hilfeseite.

## Tipps

Unerfahrene Benutzer sollten die Standard-Werte belassen, bis sie mehr
über die Verwendung Globaler Einstellungen wissen.
