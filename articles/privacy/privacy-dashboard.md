<!-- Filename: Help4.x:Privacy_Dashboard / Display title: Datenschutz-Dashboard -->

## Beschreibung

Die Seite *Datenschutz-Dashboard* listet den Typ der Datenschutzanfragen, den Status und die Anzahl der Anfragen auf.

### Tutorials

- [Datenschutz-Übersicht – Inhalt und Workflow](https://docs.joomla.org/Help4.x:Components_Privacy_Outline/en)
- [Das Datenschutz-Toolset](https://docs.joomla.org/J3.x:Privacy/en)
  (Ausführliches Tutorial aus Joomla 3)
- [Informationsanfrage-Workflow](https://docs.joomla.org/J3.x:Information_Request_Workflow_in_Privacy_Component/en)
  (Ausführliches Tutorial aus Joomla 3)

## Zugriff

- Wählen Sie **Benutzer → Datenschutz-Dashboard-Symbol** aus dem Administrationsmenü.

## Screenshot

![Datenschutz-Dashboard](../../../de/images/privacy/privacy-dashboard.png)

## Dashboard-Panels

### Datenschutzstatus

- **Veröffentlichte Datenschutzerklärung** Zeigt an, ob eine Datenschutzerklärung verfügbar ist. Navigieren Sie zu *Plugins → System - Datenschutzeinwilligung* und wählen Sie Ihren Datenschutzartikel. Sobald er veröffentlicht ist, können Sie den Artikel von dieser Seite aus bearbeiten.
- **Veröffentlichtes Anfrageformular-Menüelement** Zeigt an, ob das Menüelement (mit dem Benutzer Anfragen senden können) veröffentlicht oder nicht veröffentlicht ist. Um es zu erstellen, navigieren Sie zu Ihrem Menü → Neues Menüelement hinzufügen → Menüelement-Typ: Anfrage erstellen. Sobald es veröffentlicht ist, können Sie das Menüelement von diesem Bildschirm aus bearbeiten.
- **Offene dringende Anfragen** Anzahl der dringenden Anfragen, die älter als die in den Komponentenoptionen festgelegte Anzahl von Tagen sind (von 10 bis 29 Tagen).
- **E-Mail-Versand aktiviert**
- **Datenbankverbindungsverschlüsselung**

### Datenschutzanfragen

- **Anfragetyp** Zeigt die zwei verschiedenen Anfragetypen an:
  - *Export* wenn ein Benutzer eine Anfrage zum Export seiner Daten gestellt hat.
  - *Löschen* wenn ein Benutzer eine Anfrage zur Löschung seiner Daten gestellt hat.
- **Status** Zeigt den Status der Anfrage an:
  - *Ungültig* ein Superuser hat die Anfrage als ungültig markiert.
  - *Ausstehend* wenn ein Benutzer eine Anfrage gestellt, diese aber noch nicht bestätigt hat. Benutzer haben zwei Möglichkeiten zur Bestätigung: durch Aufrufen der im E-Mail-Link angegebenen URL oder durch Kopieren des Tokens aus der E-Mail und Einfügen in das Formular auf der angegebenen URL. Das Token ist 24 Stunden gültig.
  - *Bestätigt* der Benutzer hat seine Anfrage bestätigt.
  - *Abgeschlossen* ein Superuser hat die Anfrage abgeschlossen.
- **\# der Anfragen** Zeigt die Anzahl der Anfragen für jeden Anfragetyp an. Dieser Block zeigt auch die Gesamtzahl der Anfragen und die Anzahl der aktiven Anfragen an.

## Tipps

- Wählen Sie einen Anfragetyp aus, um die Liste der Anfragen dieses Typs anzuzeigen.
