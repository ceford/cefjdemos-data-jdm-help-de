<!-- Filename: Help4.x:Mass_Mail_Users / Display title: Serienmail-Benutzer -->

## Beschreibung

Die Seite *Massenmail an Benutzer* ermöglicht es Mitgliedern der Gruppe *Super Users*, eine E-Mail-Nachricht an registrierte Benutzer der Website zu senden. Die Empfänger können basierend auf Benutzergruppen ausgewählt werden.

### Allgemeine Elemente

Einige Elemente dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).

## So greifen Sie darauf zu

Wählen Sie **Benutzer → Massenmail an Benutzer** aus dem Administrator-Menü.

## Screenshot

![Massenmail an Benutzer](../../../de/images/users/mass-mail-users.png)

## Details und Nachricht

- **E-Mail an untergeordnete Gruppen** Ob die E-Mail auch an Mitglieder aller untergeordneten Gruppen der ausgewählten Gruppe gesendet werden soll. Zum Beispiel: Wenn dieses Feld markiert ist und die Gruppe *Öffentlich* ausgewählt wird, wird die E-Mail an fast alle Benutzer gesendet, da die meisten Gruppen untergeordnete Gruppen von *Öffentlich* sind.
- **Im HTML-Modus senden** Ob die E-Mail mit Kopfzeilen gesendet werden soll, die sie als HTML-Dokument kennzeichnen. E-Mail-Clients, die dies unterstützen, stellen dann die HTML-Codes entsprechend dar.
- **An deaktivierte Benutzer senden** Wenn markiert, werden deaktivierte Benutzer in den E-Mail-Versand einbezogen.
- **Empfänger als BCC** Wenn markiert, werden alle Empfänger als BCC (Blindkopie) hinzugefügt, sodass keiner die E-Mail-Adressen der anderen Empfänger sieht. Da viele Mailserver E-Mails ohne *An:* Eintrag als Spam behandeln, wird die Website-E-Mail-Adresse für den *An:* Eintrag verwendet.
- **Gruppe** Wählen Sie die Gruppen aus, an die Sie die E-Mail senden möchten.
- **Betreff** Geben Sie den Betreff der E-Mail ein. Versuchen Sie, ihn so beschreibend wie möglich zu gestalten. Jeder Text, der im Parameter *Betreff-Präfix* in den Optionen (Benutzeroptionen → Massenmail) eingegeben wurde, wird vor dem hier eingegebenen Betreff eingefügt.
- **Nachricht** Geben Sie den Text der E-Mail ein. Jeder Text, der im Parameter *Nachrichts-Suffix* in den Optionen (Benutzeroptionen → Massenmail) eingegeben wurde, wird zu dem hier eingegebenen Text hinzugefügt.
