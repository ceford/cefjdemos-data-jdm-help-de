<!-- Filename: Help4.x:Guided_Tours:_New_or_Edit_Tour / Display title: Geführte Touren: Tour bearbeiten -->

## Beschreibung

Diese Seite wird verwendet, um eine neue Tour hinzuzufügen oder eine bestehende Tour zu bearbeiten. Eine Tour muss mindestens einen Schritt enthalten. Sobald eine Tour neu erstellt wurde, gehen Sie zur Tourenliste und wählen Sie die Schaltfläche mit dem *0*-Label in der Spalte Schritte. Der erste Schritt der Tour wird automatisch aus dem Tour-Titel und der Beschreibung erstellt.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Veröffentlichungstab](jdocmanual?article=help/common-elements/edit-publishing).

## Zugriffsmethode

- Wählen Sie **System -> Verwalten -> Geführte Touren** aus dem Administrator-Menü.
- Wählen Sie die **Neu**-Schaltfläche in der Werkzeugleiste, um eine Tour hinzuzufügen.
- Wählen Sie einen **Titel** aus der Liste, um eine Tour zu bearbeiten.

## Screenshot

![Geführte Touren Tour bearbeiten](../../../de/images/guided-tours/guided-tours-edit-tour.png)

## Formularfelder

- **Titel** Der Titel dieser Tour. Wenn der Titel ein Sprachschlüssel ist, wird ein zusätzliches Feld angezeigt, das die Übersetzung dieses Schlüssels für die Benutzeroberfläche darstellt.
- **Tour-Identifikator** Ein eindeutiger Identifikator für die Tour. Beim *Speichern* oder *Speichern als Kopie* wird standardmäßig ein Wert vorgegeben. Ein vorgeschlagenes Format wäre *authorname-tourname*, *firmenname-tourname* oder *domain-tourname*. Dieser Identifikator hat mehrere Zwecke: Starten einer Tour von überall (nicht nur aus dem Modul für geführte Touren), Unterscheidung von Touren aus verschiedenen Quellen, und auf mehrsprachigen Websites bestimmt er die Struktur der Sprachdateinamen.

### Tour bearbeiten Tab

#### Linkes Panel

- **Relative URL** Der erforderliche relative Pfad, von dem aus die Tour startet. Zum Beispiel, um eine Tour von der Tour-Seite aus zu starten, geben Sie `administrator/index.php?option=com_guidedtours&view=tours` ein.
- **Beschreibung** Hier geben Sie die Beschreibung der Tour ein. Die Tourbeschreibung kann ein Sprachschlüssel sein. In diesem Fall wird ein zweites Feld angezeigt, das die Übersetzte Beschreibung dieses Schlüssels für die Benutzeroberfläche darstellt.

#### Rechtes Panel

- **Komponentenauswahl** Die Tour wird prioritär auf den Seiten der ausgewählten Erweiterungen sichtbar sein. Verwenden Sie *Alle*, um die Tour auf allen Seiten anzuzeigen. Wenn *Alle* ausgewählt ist, wird die Tour in der Liste der kontextuellen Touren im Dropdown-Menü des Moduls zuletzt angezeigt. Dies ist ein erforderliches Feld.
- **Auto-Start** Ermöglicht es, die Tour automatisch zu starten, wenn ein Benutzer den Kontext erreicht, in dem die Tour angezeigt werden soll.

## Tipps

- Es gibt 2 Methoden, um ein Bild in die Tourbeschreibung mit dem TinyMCE-Editor einzufügen.
  1. Die **CMS-Inhalt** Dropdown-Liste bietet Zugriff auf den **Medien**-Bildschirm, auf dem Sie Bilddateien durchsuchen und Bilder hochladen können.
  2. Die *Einfügen*-Dropdown-Liste ist ein einfaches Formular, für das Sie die Bild-URL kennen müssen. Es wird für externe Bilder verwendet.
- Es gibt 2 Möglichkeiten, Touren für mehrsprachige Umgebungen zu erstellen:
  1. Erstellen Sie eine Tour für jede unterstützte Sprache.
  2. Erstellen Sie nur eine Tour für alle Sprachen und verwenden Sie Sprachschlüssel für Titel und Beschreibung.
- Verwenden Sie **GUIDEDTOUR** in Sprachschlüsseln als Konvention, wo immer Sprachschlüssel verwendet werden (für Titel und Beschreibung).
