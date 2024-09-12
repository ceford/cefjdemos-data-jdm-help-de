<!-- Filename: Help4.x:Users:_Edit_Profile / Display title: Benutzer: Profil bearbeiten -->

## Beschreibung

Die Seite *Benutzer: Neu oder Bearbeiten* wird verwendet, um einen neuen Benutzer zu erstellen oder einen bestehenden Benutzer zu bearbeiten.

### Allgemeine Elemente

Einige Elemente dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).

## So greifen Sie darauf zu

Um einen bestehenden Benutzer zu bearbeiten:

- Wählen Sie **Benutzer → Verwalten** aus dem Administrator-Menü. Dann...
  - Suchen Sie den gewünschten Benutzer und wählen Sie den Namenslink in der
    Spalte **Name** aus.

Um einen neuen Benutzer zu erstellen:

- Wählen Sie **Benutzer → Verwalten** aus dem Administrator-Menü. Dann...
  - Wählen Sie die Schaltfläche **Neu** in der Werkzeugleiste.
- Oder... Wählen Sie **Benutzer → Verwalten → Plus-Symbol** aus dem
  Administrator-Menü.
- Oder... Wählen Sie **Benutzer → Dashboard-Symbol** aus dem Administrator-Menü. Dann...
  - Wählen Sie das **Plus-Symbol** im Benutzer-Panel.
- Oder... Wählen Sie **Home Dashboard → Site Panel → Benutzer Plus-Symbol**
  im Administrator-Menü.

## Screenshot

![Benutzer bearbeiten Details-Tab](../../../de/images/users/users-edit-account-details-tab.png)

## Formularfelder

### Kontodetails

- **Name** Geben Sie den Namen des Benutzers ein.
- **Anmeldename** Geben Sie den Anmeldenamen (Benutzername) für den Benutzer ein.
- **Passwort** Geben Sie ein (neues) Passwort ein. Obwohl dieses Feld nicht erforderlich ist, kann sich der Benutzer nicht anmelden, wenn kein Passwort festgelegt ist.
- **Passwort bestätigen** Geben Sie das Passwort aus dem obigen Feld erneut ein, um es zu überprüfen. Dieses Feld ist erforderlich, wenn Sie das neue Passwortfeld ausgefüllt haben.
- **E-Mail** Geben Sie eine E-Mail-Adresse für den Benutzer ein.
- **Registrierungsdatum** Registrierungsdatum des Benutzers.
- **Letzter Besuch** Datum, an dem der Benutzer die Website zuletzt besucht hat.
- **Letztes Zurücksetzungsdatum** Datum und Uhrzeit der letzten Passwortzurücksetzung.
- **Passwort-Zurücksetzungszähler** Anzahl der Passwortzurücksetzungen seit Beginn der letzten Zurücksetzung.
- **System-E-Mails empfangen** (*Ja*/*Nein*) Wenn auf Ja gesetzt, erhält der Benutzer System-E-Mails.
- **Benutzerstatus** (*Blockiert*/*Aktiviert*) Aktivieren oder blockieren Sie diesen Benutzer.
- **Passwort-Zurücksetzung erforderlich** (*Ja*/*Nein*) Wenn auf Ja gesetzt, muss der Benutzer bei der nächsten Anmeldung sein Passwort zurücksetzen.
- **ID** Datensatznummer in der Datenbank.

### Zugewiesene Benutzergruppen-Tab

![Benutzer bearbeiten zugewiesene Benutzergruppen-Tab](../../../de/images/users/users-edit-assigned-user-groups-tab.png)

Der Standardwert ist *Registriert*, kann jedoch auf der Seite *Benutzer: Optionen* geändert werden.

### Grundeinstellungen

![Benutzer bearbeiten Grundeinstellungen-Tab](../../../de/images/users/users-edit-basic-settings-tab.png)

- **Backend-Vorlagenstil** Wählen Sie einen Vorlagenstil für das Administrator-Backend. Dies wirkt sich nur auf diesen Benutzer aus.
- **Backend-Sprache** Wählen Sie die Sprache für das Administrator-Backend. Dies wirkt sich nur auf diesen Benutzer aus.
- **Frontend-Sprache** Wählen Sie die Sprache für das Frontend. Dies wirkt sich nur auf diesen Benutzer aus.
- **Editor** Wählen Sie einen Editor für diesen Benutzer. Der Standardwert ist TinyMCE, sofern dies nicht in der globalen Konfiguration geändert wurde.
- **Zeitzone** Es gibt eine lange Liste von Zeitzonen, die nach Kontinenten geordnet sind, wobei Europa am Ende steht. Die Standardzeitzone der Website ist in der globalen Konfiguration festgelegt.

### Barrierefreiheitseinstellungen

![Benutzer bearbeiten Barrierefreiheitseinstellungen-Tab](../../../de/images/users/users-edit-accessibility-settings-tab.png)

- **Monochrom** Ja/Nein
- **Hoher Kontrast** Ja/Nein
- **Links hervorheben** Ja/Nein
- **Schriftgröße erhöhen** Ja/Nein

### Optionen für das Benutzeraktionsprotokoll

Dieser Tab ist nur für Super-Benutzer verfügbar!

- **Benachrichtigungen für Benutzeraktionsprotokoll senden** Wenn auf Ja gesetzt, erhält der Benutzer Benachrichtigungen über das Benutzeraktionsprotokoll per E-Mail.
- **Zu benachrichtigende Ereignisse auswählen** Wählen Sie die Benachrichtigungen aus dem Benutzeraktionsprotokoll, die per E-Mail gesendet werden sollen.

### W3C-Web-Authentifizierung (WebAuthn) Anmeldung

Dieser Tab ist nur vorhanden, wenn die Website über HTTPS aufgerufen wird. Um eine passwortlose Anmeldung einzurichten, benötigen Sie ein Hardwaregerät, das bei Amazon und ähnlichen Anbietern für etwa 15 £ erhältlich ist, oder ein Gerät mit Fingerabdruck-, Gesichtserkennung oder ähnlicher biometrischer Software. Sie können mehr als einen Authentifikator hinzufügen. Sobald es eingerichtet ist, können Sie sich anmelden, indem Sie im Anmeldeformular auf die Schaltfläche Web-Authentifizierung klicken und dann den Knopf auf dem Gerät drücken, wenn Sie dazu aufgefordert werden.

Dieser Tab ist vorhanden, kann jedoch im Benutzerbearbeitungsformular nicht verwendet werden, da die passwortlose Anmeldung nur vom einzelnen Benutzer über das Profilbearbeitungsformular eingerichtet werden kann.

### Joomla API-Token

Dieser Tab dient zur Verwaltung der Sicherheitstoken für die Authentifizierung der Joomla-API-Anwendung (Fernzugriff auf Ihre Website). Wenn Sie nicht sicher sind, was das bedeutet, benötigen Sie es wahrscheinlich nicht und können diese Einstellungen sicher ignorieren.

Der Token ist nur für Ihr eigenes Konto sichtbar.

### Multi-Faktor-Authentifizierung

![Benutzer bearbeiten Multi-Faktor-Authentifizierung-Tab](../../../de/images/users/users-edit-multi-factor-authentication-tab.png)

Dieser Tab ermöglicht es Ihnen, eine oder mehrere Methoden festzulegen, um nach der Anmeldung mit Benutzername und Passwort auf Ihr Konto zuzugreifen. Er ist nur beim Bearbeiten des eigenen Profils vorhanden. Es stehen mehrere Methoden zur Verfügung. Wenn Sie aus irgendeinem Grund den Zugriff auf eine Methode verlieren, können Sie auf dem Bildschirm zur Überprüfung nach der Anmeldung eine andere Methode auswählen. Die alternativen Methoden müssen im Voraus eingerichtet worden sein!

#### Backup-Codes

Diese Methode generiert eine Reihe von Zahlen, die Sie speichern oder ausdrucken können. Jede Zahl kann nur einmal verwendet werden, also denken Sie daran, Ihre Liste nach der Nutzung zu aktualisieren.

#### Verifizierungscode

Ein zusätzliches Formular zum Ausfüllen mit alternativen Methoden zur Einrichtung des Codes. Sehen Sie sich das an und klicken Sie auf die Schaltfläche Abbrechen, wenn Sie sich entscheiden, nicht fortzufahren.

#### Yubi-Key

Dies ist für eine andere Art von Hardware-Schlüssel, der einen Code auf einem Bildschirm anzeigt. Sehen Sie sich das an und wählen Sie Abbrechen, wenn Sie sich entscheiden, nicht fortzufahren.

#### Web-Authentifizierung

Für ein Hardwaregerät mit einem Knopf zum Drücken. Sehen Sie sich das an und wählen Sie Abbrechen, wenn Sie sich entscheiden, nicht fortzufahren. Beachten Sie, dass diese Methode umgangen wird, wenn Sie die separate WebAuthn-Anmeldemethode verwenden.

#### Code per E-Mail

Bei dieser Methode wird ein Code an Ihre E-Mail-Adresse gesendet. Sie werden aufgefordert, diesen Code einzugeben, um Zugriff auf die Website zu erhalten. Es handelt sich um einen einmaligen Code. Für jede Anmeldung wird ein neuer gesendet. Sehen Sie sich das an und wählen Sie Abbrechen, wenn Sie sich entscheiden, nicht fortzufahren.

## Tipps

- Name, Anmeldename und E-Mail sind erforderlich.
- Wenn Sie keine bestimmte Sprache, keinen Editor, keine Hilfeseite und/oder keine Zeitzone ausgefüllt haben, werden die Standardeinstellungen aus der globalen Konfiguration, dem Sprachmanager und/oder dem Vorlagenmanager verwendet.
