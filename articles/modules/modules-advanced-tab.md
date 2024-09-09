<!-- Filename: Help6.x:Modules_Advanced_Tab / Display title: Module: Erweitert-Tab -->

## Beschreibung

Der *Modul: Erweitert*-Tab wird mit geringfügigen Abweichungen in allen Modulbearbeitungsformularen verwendet.

## Screenshot

![Module Erweitert-Tab](../../../de/images/modules/modules-custom-advanced-tab.png)

## Formularfelder

### Erweitert-Tab

- **Layout** Wenn Sie für ein Modul eine oder mehrere alternative Layouts entweder im Template oder im Joomla! Core definiert haben, können Sie das Layout auswählen, das für dieses Modul verwendet werden soll.
- **Modul-Klasse** Ein Suffix, das auf die CSS-Klasse des Moduls angewendet wird. Dies ermöglicht es Ihnen, benutzerdefinierte CSS-Stile zu erstellen, die nur für dieses Modul gelten. Sie würden dann die `user.css`-Datei Ihres Templates anpassen, um Styling für diese neue Klasse anzuwenden. Geben Sie diesen Parameter mit einem führenden Leerzeichen ein, um eine neue CSS-Klasse für dieses Modul zu erstellen. Geben Sie den Parameter ohne führendes Leerzeichen ein, um den Namen der CSS-Klasse für dieses Modul zu ändern.
- **Automatischer Titel** In einigen Modulen vorhanden, um ...
- **Caching** Global verwenden/Kein Caching. Ob der Inhalt dieses Moduls zwischengespeichert werden soll oder nicht. Die Einstellung *Global verwenden* verwendet die Cache-Einstellungen von der Seite *Globale Konfiguration*.
- **Cache-Zeit** Die Anzahl der Sekunden, für die das Element lokal zwischengespeichert wird. Es kann sicher auf dem Standardwert belassen werden.
- **Modul-Stil** Sie können diese Option verwenden, um den Template-Stil für diese Position zu überschreiben.
- **Modul-Tag** Das HTML-Tag, in das das Modul eingebettet wird. Standardmäßig ist dies ein `div`-Tag, aber es können auch andere HTML5-Elemente verwendet werden.
- **Bootstrap-Größe** (Werte von 0 bis 12) Damit können Sie die Breite des Moduls über das in Bootstrap integrierte `span`-Element auswählen.
- **Header-Tag** Das HTML-Tag, das für die Kopfzeile oder den Titel des Moduls verwendet werden soll. Dies kann ein `h1`, `h2`, `h3`, `h4`, `h5`, `h6` oder ein `p`-Tag sein. Beachten Sie, dass Sie einen Modulstil (Chrome) im HTML5-Format verwenden oder Ihre benutzerdefinierten Modulstile in `<mytemplate>/html/modules.php` hinzufügen müssen.
- **Header-Klasse** Hier können Sie optionale CSS-Klassen hinzufügen, die dem Header oder dem Titel-Element des Moduls zugewiesen werden.
