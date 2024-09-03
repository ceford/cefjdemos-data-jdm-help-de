<!-- Filename: Help4.x:Component:_New_or_Edit_Field_Group / Display title: Komponente: Feldgruppe bearbeiten -->

## Beschreibung

Feldgruppen werden verwendet, um verwandte Felder unter einem benannten Reiter in einem Dateneingabeformular zu sammeln. Die Seite *Komponente: Feldgruppe bearbeiten* ist für alle Komponenten, die Felder implementieren, ähnlich, aber der Seitentitel ändert sich je nach Kontext: *Artikel: Feldgruppe bearbeiten*, *Kontakte: Feldgruppe bearbeiten* oder *Benutzer: Feldgruppe bearbeiten*.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Veröffentlichungsreiter](jdocmanual?article=help/common-elements/edit-publishing).
* [Der Berechtigungsreiter](jdocmanual?article=help/common-elements/edit-permissions).

## Zugriff

* Wählen Sie **Inhalt → Feldgruppen** aus dem Administrator-Menü. Oder...
* Wählen Sie **Kontakt → Feldgruppen** aus dem Administrator-Menü. Oder...
* Wählen Sie **Benutzer → Feldgruppen** aus dem Administrator-Menü. Dann...
  * Klicken Sie auf die **Neu**-Schaltfläche in der Werkzeugleiste, um eine neue Feldgruppe zu erstellen. Oder...
  * Wählen Sie einen **Titel** aus der Liste, um eine bestehende Feldgruppe zu bearbeiten.

**Hinweis:** Es gibt eine Dropdown-Liste, die die Erstellung von Feldern für eine Kategorie und Mail im Kontaktmodul ermöglicht. Dies erfordert einige Programmierkenntnisse, um geeignete Template-Overrides vorzubereiten.

## Screenshot

Dieses Beispiel zeigt die Seite *Artikel: Feldgruppe bearbeiten*. Die Seiten *Kontakte: Feldgruppe bearbeiten* und *Benutzer: Feldgruppe bearbeiten* sind ähnlich.

![Artikel Feldgruppe bearbeiten](../../../de/images/fields/articles-edit-field-group.png)

## Formularfelder

- **Titel** Der Titel für diese Feldgruppe.

### Allgemein

#### Linkes Panel

- **Beschreibung** Ein Text, der als Tooltip angezeigt wird, wenn man beim Erstellen eines Artikels, Kontakts oder einer Drittanbieter-Komponente, die benutzerdefinierte Felder unterstützt, über das Textfeld fährt. Dieser Text ist nicht übersetzbar und wird nicht im Frontend angezeigt.

#### Rechtes Panel

- **Status** Der Veröffentlichungsstatus dieser Feldgruppe.
  - *Veröffentlicht* Die Feldgruppe ist sichtbar, während ein Artikel oder ein Kontakt bearbeitet wird. Sie ist auch im Frontend sichtbar.
  - *Unveröffentlicht* Die Feldgruppe wird beim Bearbeiten eines Artikels oder Kontakts für Benutzer nicht sichtbar sein.
  - *Archiviert* Die Feldgruppe wird nicht mehr beim Bearbeiten eines Artikels oder Kontakts angezeigt. Sie kann in den Feldgruppen angezeigt werden, wenn der Filter auf archivierte Elemente gesetzt ist.
  - *Papierkorb* Die Feldgruppe wurde gelöscht, ist aber noch in der Datenbank. Sie kann dauerhaft aus der Datenbank gelöscht werden, indem die Papierkorb-Funktion in den Feldgruppen verwendet wird.
- **Zugriff** Wählen Sie die Zugriffsebene für diese Feldgruppe. Die Zugriffsebenen hängen davon ab, was in *Benutzer: Zugriffsebenen* eingerichtet wurde.
- **Sprache** Wählen Sie die Sprache für diese Feldgruppe. Wenn Sie die Mehrsprachigkeitsfunktion von Joomla nicht verwenden, lassen Sie die Standardeinstellung *Alle*.
- **Notiz** Ein optionales Feld, um persönliche Notizen zur Feldgruppe zu machen.

### Optionen

- **Anzeigen, wenn nur Leserechte vorhanden sind** Falls die Feldgruppe nur lesbar ist (möglicherweise hat der Benutzer nicht die benötigte Zugriffsebene), soll die Feldgruppe angezeigt oder ausgeblendet werden.