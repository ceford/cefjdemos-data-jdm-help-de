
<!-- Filename: Help4.x:Languages:_Edit_Override / Display title: Sprachen: Override bearbeiten -->

## Beschreibung

Im Joomla-Code werden Textzeichenfolgen, die in der Benutzeroberfläche erscheinen sollen, entweder in der Website-Oberfläche oder in der Administrator-Oberfläche, als Zeichenkettenkonstanten ausgedrückt. Zum Beispiel wird die Zeichenfolge *Ihre Sitzung ist abgelaufen. Bitte melden Sie sich erneut an.* als `JLIB_ENVIRONMENT_SESSION_EXPIRED` ausgedrückt. Die Textzeichenfolge kann in jede beliebige Sprache übersetzt werden. Die Standardsprache ist Britisches Englisch. In einer Joomla-Installation gibt es Tausende solcher Zeichenfolgen.

Wenn eine Zeichenfolge nicht zu Ihrer Website passt, können Sie die Funktion zum Sprach-Override verwenden, um das Original zu ersetzen. Die Seite *Sprachen: Overrides* zeigt eine Liste der vorhandenen Overrides an, sodass sie anfangs leer ist.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).

## Zugriff

- Wähle **System → Verwaltungs-Panel → Sprach-Overrides**. Dann...
  - Wähle eine **Sprache und Client** aus der Dropdown-Liste aus. Dann...
    - Wähle die Schaltfläche **Neu** in der Werkzeugleiste, um ein neues Override zu erstellen.
      Oder...
    - Wähle den Konstanten-Link in der Spalte **Konstante**, um ein vorhandenes Override zu bearbeiten.

## Screenshot

![Sprachen Override bearbeiten](../../../de/images/languages/languages-edit-override.png)

## Formularfelder

### Rechtes Panel: Suchen Sie den Text, den Sie ändern möchten

- **Suchen nach** Beginnen Sie hier! Es ist wahrscheinlicher, dass Sie den Wert (expired) als die Konstante (`_EXPIRED`) kennen. In beiden Fällen ist die Suche nach Teilzeichenfolgen nicht zwischen Groß- und Kleinschreibung unterscheidend.
- **Suchtext** Geben Sie den Text ein, nach dem Sie suchen möchten, und wählen Sie die Schaltfläche *Suchen*.
- **Suchergebnisse** Eine Liste von Zeichenfolgen, die den Suchbegriff enthalten, erscheint in einem separaten Ergebnisfeld unter dem rechten Panel. Wählen Sie diejenige aus, die Sie suchen. Die Konstante und der Text werden in das *linke Panel* kopiert, um dort aktualisiert und gespeichert zu werden.

### Linkes Panel: Erstellen Sie ein neues Override oder bearbeiten Sie dieses Override

- **Sprache** und **Ort** Diese wurden ausgewählt, bevor dieses Bearbeitungsformular geöffnet wurde, und können nicht geändert werden.
- **Sprachkonstante** Dies ist die Zeichenfolge, die vom Entwickler im Code verwendet wird. Wenn der Wert im Code nicht vorhanden ist, wird die Zeichenfolge nie verwendet.
- **Text** Hier überschreiben Sie den Standardbegriff mit Ihrer Version.
- **Für beide Standorte** Wählen Sie diese Option, um das Override sowohl im Frontend als auch im Backend anzuwenden.
- **Datei** Zeigt an, wo sich die Override-Datei im Dateisystem befindet. Dies könnte für die Fehlersuche nützlich sein.
