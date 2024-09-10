<!-- Filename: Help4.x:Plugins:_Name_of_Plugin / Display title: Plugins: Name des Plugins -->

## Beschreibung

Die Seite *Plugin* bietet Zugriff auf die Bearbeitung der Details und Optionen aller Plugins. Allgemeine Optionen für alle Plugins befinden sich im rechten Teil des *Plugin-Tabs*, wie unten beschrieben.

### Plugin-Gruppen

Es gibt eine große Anzahl an Kern-Plugins. Diese sind nach Gruppen aufgelistet und mit Links zu separaten Dokumentationen versehen:

* [Aktionsprotokoll-Gruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_Action_Log_Group) (1 Plugin)
* [API-Authentifizierungsgruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_API_Authentication_Group) (2 Plugins)
* [Authentifizierungsgruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_Authentication_Group) (3 Plugins)
* [Verhaltensgruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_Behaviour_Group) (3 Plugins)
* [Inhaltsgruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_Content_Group) (10 Plugins)
* [Editoren-Gruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_Editor_Group) (3 Plugins)
* [Editor-Button-Gruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_Button_Group) (8 Plugins)
* [Erweiterungsgruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_Extension_Group) (3 Plugins)
* [Feld-Gruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_Fields_Group) (16 Plugins)
* [Dateisystem-Gruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_FileSystem_Group) (1 Plugin)
* [Finder-Gruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_Smart_Search_Group) (5 Plugins)
* [Installer-Gruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_Installer_Group) (5 Plugins)
* [Medien-Aktionsgruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_Media_Action_Group) (3 Plugins)
* Multi-Faktor-Authentifizierungsgruppe (5 Plugins)
* [Datenschutzgruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_Privacy_Group) (6 Plugins)
* [Quick-Icon-Gruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_Quick_Icon_Group) (7 Plugins)
* [Beispieldaten-Gruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_Sample_Data_Group) (2 Plugins, 3 Plugins für Entwicklungsinstallationen)
* Schema.org-Gruppe (9 Plugins)
* [System-Gruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_System_Group) (24 Plugins)
* Aufgaben-Gruppe (9 Plugins)
* [Benutzergruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_User_Group) (5 Plugins)
* [Webdienst-Gruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_Web_Services_Group) (17 Plugins)
* [Workflow-Gruppe.](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_Workflow_Group) (3 Plugins)

Die vollständige Liste der Plugins ist in einer [einzelnen langen Liste](https://docs.joomla.org/Chunk4x:List_of_Plugins) verfügbar.

### Allgemeine Elemente

Einige Elemente dieser Seite werden in separaten Hilfedokumenten behandelt:

* [Symbolleisten](jdocmanual?article=help/common-elements/toolbars).

## Zugriff

Ausgehend vom Administrationsmenü:

- Wählen Sie **Start-Dashboard → Plugins** oder...
- Wählen Sie **System → Verwaltungsbereich → Plugins**. Dann...
  - Wählen Sie den Namen des Plugins aus der Plugin-Liste.

## Screenshot

![Plugins Plugin-Tab](../../../de/images/plugins/plugins-plugin-tab.png)

## Formularfelder

### Plugin-Tab

#### Linkes Panel

- **Plugin-Titel** als `<h2>` Überschrift festgelegt.
- **Typ/Datei** als *Badges* dargestellt, um die Plugin-Dateien im Quellcode zu finden.
- **Beschreibung** Eine kurze Beschreibung dessen, was dieses Plugin macht. Sie kann nicht geändert werden, da sie vom Entwickler des Plugins festgelegt wird. Sie kann leer sein, wenn der Entwickler keine Beschreibung für das Plugin angegeben hat.

Wenn das Plugin konfigurierbare Optionen hat, werden diese hier angezeigt. Viele Plugins haben keine konfigurierbaren Optionen.

#### Rechtes Panel

Das rechte Panel ist bei allen Plugins gleich und enthält die folgenden Felder:

- **Status** Ob das Plugin aktiviert ist oder nicht.
- **Zugriff** Die Benutzer-*Zugriffsebenen* für dieses Plugin.
- **Reihenfolge** Ein Dropdown-Menü mit Plugins desselben Typs. Die Liste der Plugins ist nach der aktuellen Reihenfolge sortiert. Sie können die Reihenfolge dieses Plugins im Verhältnis zu den anderen Plugins ändern, indem Sie das Plugin im Dropdown-Menü auswählen, unter dem dieses Plugin einsortiert werden soll.
- **Plugin-Typ** Der Typ des Plugins. Dieser Wert kann nicht geändert werden.
- **Plugin-Datei** Der Name der Plugin-Datei. Jedes Plugin hat zwei Dateien mit diesem Namen: Eine mit der Dateierweiterung '.php' und eine mit der Erweiterung '.xml'.

## Tipps

- Konfigurierbare Plug-in-Einstellungen werden als *Optionen* bezeichnet. Sie können in Hilfedokumentationen und Tutorials, auf die Sie stoßen, auf die Begriffe *Optionen* und *Parameter* stoßen, die austauschbar verwendet werden.
