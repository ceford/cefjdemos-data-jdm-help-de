<!-- Filename: Help4.x:Joomla_Update:_Options / Display title: Joomla-Aktualisierung: Optionen -->

## Beschreibung

Die Seite *Joomla-Aktualisierung: Optionen* wird verwendet, um Parameter festzulegen, die den Aktualisierungsprozess des Joomla-Kerns steuern.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars)

## Zugriff

- Wähle **System → Update-Panel → Joomla** aus dem Administrator-Menü. Dann...
  - Wähle die Schaltfläche **Optionen** in der Werkzeugleiste.

## Screenshot

![Joomla Update Optionen](../../../en/images/joomla-update/joomla-update-options.png)

## Formularfelder

### Update-Quelle Tab

- **Update-Kanal**
  - **Standard** Diese Einstellung bewirkt, dass Joomla eine Benachrichtigung anzeigt, wenn eine neue Minor- oder Patch-Version für die aktuelle Hauptversion verfügbar ist.
  - **Joomla Next** Diese Einstellung bewirkt, dass Joomla eine Benachrichtigung anzeigt, wenn eine neue stabile Hauptversion verfügbar ist und alle bestehenden Minor-Versionen und Erweiterungen auf dem neuesten Stand sind.
  - **Testen** Für Joomla-Tester. Weitere Felder erscheinen.
  - **Benutzerdefinierte URL** Für Joomla-Entwickler. Weitere Felder erscheinen.
- **Minimale Stabilität** Die minimale Stabilität der Erweiterungsupdates, die du sehen möchtest. *Entwicklung* ist am wenigsten stabil, *Stabil* ist für Produktionsqualität. Wenn eine Erweiterung kein Niveau angibt, wird davon ausgegangen, dass sie stabil ist.
  - **Entwicklung** Für Joomla-Entwicklerseiten.
  - **Alpha** Für Alpha-Testseiten.
  - **Beta** Für Beta-Testseiten.
  - **Release Candidate** Für Release-Candidate-Seiten.
  - **Stabil** Für Produktionsseiten.
- **Potentiell inkompatible Erweiterungen Checkbox** Zeigt das Kontrollkästchen im Pre-Update-Check an, wenn eine der auf deiner Seite installierten Erweiterungen potentiell inkompatibel mit der Version von Joomla ist, auf die du aktualisierst. *Hinweis:* Das Kontrollkästchen wird angezeigt, wenn auf eine neue Joomla-Version (Minor- oder Hauptversion) aktualisiert wird.
- **Bestätigungs-Backup-Checkbox** Zeigt das Kontrollkästchen an, um zu bestätigen, dass du ein Backup gemacht hast und bereit bist, das Update im letzten Schritt vor der tatsächlichen Anwendung des Updates durchzuführen.