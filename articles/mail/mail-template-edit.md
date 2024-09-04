<!-- Filename: Help4.x:Mail_Template:_Edit / Display title: Mail-Vorlage Bearbeiten -->

## Beschreibung

Die Seite *Mail-Vorlage: Bearbeiten* wird verwendet, um den Standardtext für 
den Betreff, den Nachrichtentext und/oder den HTML-Text einer E-Mail-Nachricht 
zu ändern.

### Gemeinsame Elemente

Ein Element dieser Seite wird in einem separaten Hilfeartikel behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).

## Zugriff

- Wählen Sie **System → Vorlagen-Panel → Mail-Vorlagen** aus dem
  Administrator-Menü. Dann...
  - Wählen Sie den Titel der Vorlage, die Sie bearbeiten möchten, oder 
    wählen Sie die Flagge der Sprachversion, die Sie bearbeiten möchten.

## Screenshot

![Mail-Vorlage Bearbeiten](../../../de/images/mail/edit-mail-template.png)

Die Mail-Optionen ermöglichen den Versand von Nur-Text- oder HTML-Nachrichten oder beides. 
Wenn nur eine Methode ausgewählt ist, wird die Alternative im Nachrichtenbearbeitungsformular 
nicht angezeigt.

Dieser Screenshot zeigt das Bearbeitungsformular für eine Nur-Text-Nachricht. 
Wenn die HTML-Option aktiviert ist, verwendet das entsprechende Eingabefeld denselben 
WYSIWYG-Editor wie bei Artikeln.

## Formularfelder

### Mail-Tab

Der erste Teil des Formulars enthält Informationen über den Namen und den Zweck 
der Vorlage.

- **Betreff** Dies kann eine Zeichenkette, ein Platzhalter oder eine Mischung 
  aus beiden im Klartext anzeigen.
- **Nachrichtentext** Der Inhalt der Nur-Text-Nachricht.
- **HTML** Der Inhalt der HTML-Nachricht.

Elemente in geschweiften Klammern sind Platzhalter, die beim Versenden einer Nachricht 
ersetzt werden. Sie sollten nicht geändert werden. Zum Beispiel ist `{SITENAME}` 
ein Platzhalter, der beim Versenden einer Nachricht durch den Namen Ihrer Website 
ersetzt wird. Die Platzhalter werden als *Einfügetags* rechts neben dem Formular 
aufgelistet. Die verfügbaren Platzhalter variieren je nach Nachricht.
