<!-- Filename: Help4.x:Site_System_Information / Display title: SySysteminformationen -->
## Beschreibung

Die Seite *Systeminformationen* liefert Informationen über die Umgebung des Host-Servers. Es gibt fünf verschiedene Tab-Panel: Systeminformationen, PHP-Einstellungen, Konfigurationsdatei, Ordnerberechtigungen und PHP-Informationen. Jedes Panel bietet detaillierte Informationen zu diesem Aspekt der Website. Dies ist hilfreich bei der Fehlersuche bei Setup-Problemen.

- Beachten Sie, dass keine dieser Einstellungen über diese Panels geändert werden kann. Dies muss an verschiedenen Stellen der Joomla!-Installation erfolgen, abhängig von der spezifischen Einstellung.
- Einige Einstellungen können über die Seite Globale Konfiguration geändert werden. Andere hängen von der Serverkonfiguration des Hosts ab und können nicht innerhalb von Joomla! geändert werden.

### Allgemeine Elemente

Einige Aspekte dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).

## Zugriff

- Wählen Sie **System → Informations-Panel → Systeminformationen** aus dem Administrator-Menü.

## Screenshot

![Home Dashboard](../../../de/images/site/system-information-tab.png)

## Formular-Tabs

### Systeminformationen-Tab

- **PHP Built on** Liefert Details zum Betriebssystem, auf dem der Webserver läuft, auf dem Joomla ausgeführt wird.
- **Datenbanktyp** Liefert den Typ der Datenbank, die in der Joomla-Installation verwendet wird.
- **Datenbankversion** Liefert die aktuelle Version der MySQL-Datenbank, die von der Joomla-Installation verwendet wird.
- **Datenbank-Collation** Wie die MySQL-Datenbank für die von Joomla verwendeten Informationen strukturiert ist.
- **Datenbank-Verbindungs-Collation** Zeichensatz und Collation der Datenbankverbindung.
- **PHP-Version** Liefert die aktuelle Version des PHP-Server-Skripts, das für diese Joomla-Installation verwendet wird.
- **Webserver** Liefert den aktuellen Typ und die Version des Webservers, auf dem Joomla ausgeführt wird.
- **Webserver-zu-PHP-Schnittstelle** Das Skript, das die Interaktion zwischen dem Webserver (meist Apache) und der PHP-Skriptsprache ermöglicht.
- **Joomla!-Version** Liefert die aktuelle Version von Joomla. Es wird empfohlen, immer die aktuelle stabile Version zu verwenden.
- **User Agent** Eine Zusammenfassung des Betriebssystems und der Browserinformationen der lokalen Maschine des aktuellen Benutzers, die zur Erstellung einer eindeutigen Sitzungs-ID für den Zugriff und die Funktionalität auf der Joomla!-Website verwendet werden.

### PHP-Einstellungen-Tab

![Home Dashboard](../../../de/images/site/php-settings-tab.png)

Diese Ansicht zeigt PHP-Einstellungen an. Wenn eine dieser Einstellungen als falsch hervorgehoben ist, sollten sie korrigiert werden.

- **Safe Mode** Empfohlene Einstellung: AUS
- **Open basedir** Empfohlene Einstellung: Abhängig von der Website
- **Fehler anzeigen** Empfohlene Einstellung: AUS
- **Short Open Tags** Empfohlene Einstellung: EIN
- **Datei-Uploads** Empfohlene Einstellung: EIN
- **Magic Quotes** Empfohlene Einstellung: AUS
- **Register Globals** Empfohlene Einstellung: AUS
- **Output Buffering** Empfohlene Einstellung: AUS
- **Sitzungsspeicherpfad** Empfohlene Einstellung: Abhängig von der Website
- **Session Auto Start** Empfohlene Einstellung: 0
- **XML aktiviert** Empfohlene Einstellung: JA
- **Zlib aktiviert** Empfohlene Einstellung: JA
- **Native ZIP aktiviert** Empfohlene Einstellung: JA
- **Deaktivierte Funktionen** Empfohlene Einstellung: Abhängig von der Website
- **Multibyte String (mbstring) aktiviert** Empfohlene Einstellung: JA
- **Iconv verfügbar** Empfohlene Einstellung: JA
- **Maximale Eingabevariablen** Empfohlene Einstellung: 2500

### Konfigurationsdatei-Tab

![Home Dashboard](../../../de/images/site/configuration-file-tab.png)

Dieser Tab zeigt den Inhalt der aktuellen Joomla! *configuration.php*-Datei, die im `path-to-joomla-root`-Verzeichnis gespeichert ist. Diese Datei wird automatisch erstellt, wenn Sie Joomla! zum ersten Mal installieren, und die meisten Änderungen der Sektion Globale Konfiguration von Joomla! werden hier aufgezeichnet. Beachten Sie, dass keine Einstellungen von dieser Seite aus geändert werden können. Verwenden Sie die Globale Konfiguration, um mehr Informationen über diese Einstellungen zu sehen und Änderungen vorzunehmen.

### Ordnerberechtigungen-Tab

![Home Dashboard](../../../de/images/site/folder-permissions-tab.png)

Dieser Tab zeigt eine Liste der Verzeichnisse, auf die der Webserver Schreibzugriff haben sollte. Beachten Sie, dass alle auf dieser Seite aufgeführten Verzeichnisse **Beschreibbar** anzeigen sollten. Falls nicht, müssen Sie möglicherweise die Berechtigungen ändern, um Joomla! erfolgreich installieren und verwenden zu können. Die Konfigurationsdatei *configuration.php* wird angezeigt und als **Nicht beschreibbar** markiert.

### PHP-Informationen-Tab

![Home Dashboard](../../../de/images/site/php-information-tab.png)

Dieser Tab zeigt die Konfigurationseinstellungen der PHP-Server-Skriptsprache, die von Joomla! verwendet wird, zusammen mit allen zugehörigen Systeminformationen, die zur Erstellung des Webservers beitragen. Es ist die Ausgabe eines integrierten php.info-Skripts, das in Joomla! eingebaut ist.

PHP ist auf dem Server installiert und läuft dort (daher der oben genannte Server-Seiten-Hinweis), und alle Einstellungen werden auf dem Server vorgenommen. Der Besucher der Website muss nichts Besonderes auf seinem lokalen Rechner ausführen, um die von PHP bereitgestellten zusätzlichen Funktionen der Website zu sehen oder zu nutzen.

Alle jemals benötigten Einstellungen werden hier angezeigt. Änderungen werden in der *php.ini* und anderen Konfigurationsdateien auf dem Webserver vorgenommen.

Wie viel Kontrolle ein Website-Besitzer über diese Informationen hat, hängt davon ab, ob er den Server besitzt oder ob der Server-Host flexibel im Umgang mit seinen Kunden ist.

Es ist eine gute Praxis, die Einschränkungen einer bestimmten Server-Installation zu kennen. Diese Bildschirmausgabe wird verwendet, um detaillierte Informationen darüber zu finden, wie PHP auf dem Server implementiert ist.

Für vollständige Details zu den Informationen im PHP-Info-Tab besuchen Sie: [http://php.net/phpinfo](http://php.net/phpinfo).

## Tipps

- Wenn Sie Probleme bei der Installation von Erweiterungen, dem Hochladen von Dateien oder dem Ändern von Konfigurationsoptionen haben, überprüfen Sie den Tab **Ordnerberechtigungen**, um sicherzustellen, dass Sie Schreibrechte für Dateien auf Ihrem Webserver haben. Der *Status* der Verzeichnisse sollte *Beschreibbar* sein. Andernfalls können Sie möglicherweise keine Dateien in diesen Verzeichnissen hochladen oder bearbeiten.
- Wenn Sie Hilfe bei Setup-Problemen suchen, z. B. in einem Joomla! Webforum, ist es sehr hilfreich, spezifische Informationen über Ihre Joomla!-Installation zu posten. Diese Seite bietet eine einfache Möglichkeit, alle diese Informationen an einem Ort zu finden. Noch besser – verwenden Sie den **Forum Post Assistant**, der oben auf einzelnen Joomla-Foren-Seiten dokumentiert ist, wie z. B. im [Allgemeine Fragen](https://forum.joomla.org/viewforum.php?f=834)-Forum.
