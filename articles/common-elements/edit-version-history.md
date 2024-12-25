<!-- Filename: Help4.x:Components_Version_History / Display title: Versionsverlauf bearbeiten -->

## Beschreibung

Ein Versionsverlauf-Popup zeigt frühere Versionen des bearbeiteten Elements an. Es ist
verfügbar für Artikel, Banner, Kunden, Kontakte, Newsfeeds, Benutzernotizen
und alle Kategorien.

Jedes Mal, wenn ein Element gespeichert wird, wird automatisch eine neue Version erstellt. Die Anzahl
der zu speichernden Versionen für jedes Element wird in den Optionen der Komponente festgelegt. Eine oder
mehrere Versionen können markiert werden, um für immer erhalten zu bleiben. Solche Versionen werden nicht automatisch
gelöscht, selbst wenn die in den Optionen festgelegte maximale Anzahl an Versionen überschritten wird.

**Hinweis:** Wenn das Versionierungssystem verwendet wird, werden benutzerdefinierte Felder nicht in verschiedenen Versionen gespeichert.

## Zugriff

Wählen Sie die Schaltfläche **Versionen** in der Symbolleiste einer Elementbearbeitungsseite aus.

## Screenshot

![Versionsverlauf-Popup](../../../en/images/common-elements/articles-edit-versions.png)

## Spaltenüberschriften

- **Kontrollkästchen** Aktivieren Sie dieses Kontrollkästchen, um ein oder mehrere Elemente auszuwählen. Um alle
Elemente auszuwählen, aktivieren Sie das Kästchen in der Spaltenüberschrift. Nachdem die Kästchen aktiviert wurden,
wählen Sie eine Schaltfläche in der Symbolleiste aus, um eine Aktion für die ausgewählten Elemente durchzuführen.
- **Datum** Das Datum und die Uhrzeit, zu der die Version gespeichert wurde. Wenn Sie auf diesen
Link klicken, wird die Vorschau dieser Version in einem Popup-Fenster geöffnet. Beachten Sie, dass eines
der Daten von einem Sternsymbol gefolgt wird. Dies zeigt an, dass dies
die aktuell gespeicherte und bearbeitete Version ist.
- **Versionsnotiz** Eine Versionsnotiz kann verwendet werden, um die Art der
Änderungen von einer Version zur nächsten zu identifizieren. Eine vor dem Speichern eines
Elements eingegebene Versionsnotiz wird in dieser Spalte angezeigt.
- **Für immer behalten** Diese Spalte zeigt, ob die Version als
„Für immer behalten“ markiert wurde. Normalerweise wird jede Version gemäß den
Einstellungen auf der Optionsseite der Komponente gespeichert. Die Standardeinstellung ist,
ein Maximum von 10 früheren Versionen eines Elements zu speichern. Wenn ein Element gespeichert wird, das
bereits 10 gespeicherte Versionen hat, wird die älteste Version gelöscht. Wenn eine Version
als „Für immer behalten“ markiert ist, wird sie nicht als eine der gespeicherten Versionen gezählt und
wird nicht gelöscht, wenn die maximale Anzahl erreicht ist.
  - Um den Status „Für immer behalten“ ein- oder auszuschalten, wählen Sie entweder die Schaltfläche *Nein* oder *Ja* oder aktivieren
das Kontrollkästchen der Version und dann die Schaltfläche „Für immer Ein/Aus“ in der Symbolleiste.
- **Autor** Der Benutzer, der diese Version gespeichert hat.
- **Zeichenanzahl** Die Gesamtzahl der in dieser Version gespeicherten Zeichen. Beachten Sie,
dass dies auch die Datenbank-Spaltennamen sowie die tatsächlich
eingegebenen Zeichen umfasst.

## Symbolleiste

- **Wiederherstellen** Die aktuelle Version des Elements ist rechts neben dem Datum mit einem Stern markiert. Um eine der anderen gespeicherten
Versionen wiederherzustellen, aktivieren Sie das Kontrollkästchen der gewünschten Version und wählen Sie die
Schaltfläche „Wiederherstellen“. Die aktuelle Version des Elements wird durch
die ausgewählte Version ersetzt, und der Bearbeitungsbildschirm wird mit der wiederhergestellten
Version im Editor neu geladen.
- **Vorschau** Um eine Version in der Vorschau anzuzeigen, wählen Sie entweder die Spalte „Datum“ der gewünschten
Version oder aktivieren Sie das Kontrollkästchen und dann die Schaltfläche „Vorschau“. Ein separates Popup-
Fenster wird geladen, das die ausgewählte Version des Elements anzeigt.
- **Vergleichen** Um zwei Versionen zu vergleichen und die Änderungen zu sehen, aktivieren Sie die
Kontrollkästchen der jeweiligen Versionen und klicken Sie dann auf die Schaltfläche „Vergleichen“. Ein
neues Browserfenster wird geöffnet, das eine Liste der geänderten Felder und die darin vorgenommenen Änderungen anzeigt.
  - Die erste Spalte zeigt den Feldnamen, die zweite die ältere Version,
die dritte die neuere Version, und die letzte Spalte hebt die
Unterschiede zwischen den beiden Versionen hervor.
- **Für immer Ein/Aus** Diese Schaltfläche schaltet die Funktion „Für immer behalten“ für eine
Version ein oder aus. Normalerweise wird die älteste Version eines Elements automatisch gelöscht,
wenn die maximale Anzahl von Versionen (festgelegt in den Optionen der Komponente) überschritten wurde.
Wenn Sie die Eigenschaft „Für immer behalten“ für eine Version festlegen, wird sie
niemals automatisch gelöscht.
- **Löschen** Mit dieser Schaltfläche können Sie eine oder mehrere Versionen manuell löschen. Aktivieren Sie
das Kontrollkästchen der zu löschenden Versionen und klicken Sie dann auf die Schaltfläche „Löschen“. Beachten Sie, dass dies *nicht* das bearbeitete Element löscht. Es wird nur der Versionsverlauf des Elements gelöscht.
