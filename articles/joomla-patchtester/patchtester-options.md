<!-- Filename: Help4.x:Components_Patch_Tester_Options / Display title: Patch Tester Optionen -->

## Beschreibung

Der *Joomla! Patch Tester* wird von Testern verwendet, um zu überprüfen, ob von Entwicklern erstellte Code-Patches tatsächlich das tun, was sie sollen, ohne unerwünschte Nebenwirkungen. Die *Optionen*-Seite wird verwendet, um die Verbindung zu Github einzurichten.

### Allgemeine Elemente

Einige Elemente dieser Seite werden in separaten Hilfe-Artikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Berechtigungen-Tab](jdocmanual?article=help/common-elements/edit-permissions).

Weitere Informationen: [A Dummies Guide to Joomla Bug Testing](https://brian.teeman.net/joomla/873-a-dummies-guide-to-joomla-bug-testing)

## Zugriff

- Wähle **Komponenten → Patch Tester** im Administrator-Menü.
  - Wähle die Schaltfläche *Optionen* in der Werkzeugleiste.

## Screenshot

![Patchtester Optionen Formular](../../../en/images/joomla-patchtester/patchtester-options-github-repository-tab.png)

## Formularfelder

### GitHub Repository Tab

- **GitHub Repository** Standardmäßig ist `Joomla! CMS` voreingestellt. Verwende es.

### GitHub-Authentifizierung Tab

Du benötigst ein Github-Konto und ein Github-Token. Alles kostenlos – Details findest du im GitHub-Authentifizierung Tab.

![Patchtester Optionen Github Authentifizierung Tab](../../../en/images/joomla-patchtester/patchtester-options-github-authentication-tab.png)

- **GitHub-Authentifizierungsmethode** Wähle die Token-Methode. Die Methode mit Anmeldedaten wird ab September 2020 nicht mehr funktionieren.
- **GitHub Token** Füge das von GitHub erhaltene Token hier ein.

### CI-Server-Einstellungen Tab

Diese Einstellungen werden für automatisiertes Testen verwendet. Verwende die Standardwerte für manuelles Testen.

![Patchtester Optionen CI-Server-Einstellungen Tab](../../../en/images/joomla-patchtester/patchtester-options-ci-server-settings-tab.png)

- **CI-Server-Adresse** Standard: `https://ci.joomla.org`
- **CI-Integration umschalten** Standard: Aus
