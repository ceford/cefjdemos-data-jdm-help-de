<!-- Filename: Help4.x:Component:_Fields / Display title: Komponente: Felder -->

## Beschreibung

Felder werden verwendet, um zusätzliche Attribute von Artikeln, Kontakten oder Benutzern anzuzeigen. Die Daten werden in einem Administrator-Bearbeitungsformular eingegeben und auf der Website angezeigt. Ein Beispiel:

Angenommen, Sie schreiben Artikel über Aspekte der Natur, manchmal über Blumen, manchmal über Tiere. Ein Feld, das Sie möglicherweise erfassen und anzeigen möchten, ist der lateinische Name, wofür ein Textfeld erforderlich ist. Ein weiteres könnte Lebensraum sein: Wald, Teich, Wiese usw., wofür eine Dropdown-Liste benötigt wird. Für Blumen möchten Sie vielleicht die Blütezeit mit 4 Kontrollkästchen erfassen, eines für jede Jahreszeit, oder mit 12 Kontrollkästchen, eines für jeden Monat.

Leere Felder im Eingabeformular werden in der Website-Ausgabe nicht angezeigt, sodass Sie alle Felder in einer langen Liste behalten könnten. Es ist jedoch normalerweise besser, Kategorien für Ihre Artikel zu verwenden, z. B. Blumen und Tiere. Felder können mehr als einer Kategorie zugewiesen werden. Daher würden die Felder Lateinischer Name und Lebensraum beiden Kategorien zugewiesen, während die Blütezeit nur der Kategorie Blumen zugewiesen würde.

Wenn ein Feld keiner Gruppe zugewiesen ist, wird es im Bearbeitungsformular auf einer Registerkarte *Felder* angezeigt. Wenn ein Feld einer Gruppe zugewiesen ist, wird es auf einer Registerkarte mit diesem Namen angezeigt. Für die Gruppe *Blumen* wäre es also sinnvoll, eine Gruppe namens *Blumendaten* (oder einfach *Blumen*) zu erstellen, obwohl die Verwendung desselben Namens für verschiedene Dinge verwirrend sein kann. Und für die anderen gemeinsamen Felder könnten Sie eine Gruppe *Natur* verwenden.

### Gemeinsame Elemente

Einige Elemente dieser Seite werden in separaten Hilfeartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Listenfilter](jdocmanual?article=help/common-elements/list-filters).
* [Listenspaltenüberschriften](jdocmanual?article=help/common-elements/list-column-headers).
* [Listenreihenfolge](jdocmanual?article=help/common-elements/list-ordering).
* [Listenpaginierung](jdocmanual?article=help/common-elements/list-pagination "List Pagination").
* [Listen-Batch-Prozess](jdocmanual?article=help/common-elements/list-batch-process "List Batch Process").

### Verwandter Artikel

* Es gibt ein ausführlicheres Beispiel zur Verwendung von [Feldern und Feldgruppen](jdocmanual?article=user/fields/fields-and-field-groups).
* Es gibt einen Artikel im Community-Magazin, der die Verwendung von benutzerdefinierten Feldern in einer Kategorie behandelt, um [Ein Banner aus der Kategorienbeschreibung von Joomla zu erstellen](https://magazine.joomla.org/all-issues/july-2024/create-a-banner-from-joomla-s-category-description).

## Zugriff

* Wählen Sie **Inhalt → Felder** aus dem Administratormenü.
* Wählen Sie **Artikel** aus der *Artikel/Kategorie*-Dropdown-Liste.
  * Wählen Sie die **Neu**-Schaltfläche in der *Werkzeugleiste*, um ein neues Feld hinzuzufügen.
  * Wählen Sie einen **Titel** aus der Liste, um ein bestehendes Feld zu bearbeiten.

**Hinweis:** Es gibt eine Dropdown-Liste, die die Erstellung von Feldern für eine Kategorie und Mail im Kontaktmodul ermöglicht. Dies erfordert jedoch einige Programmierkenntnisse, um geeignete Template-Overrides vorzubereiten.

## Screenshot

![Artikel-Felderliste](../../../de/images/fields/articles-fields-list.png)

Es sind 16 Feldtypen verfügbar, die jeweils als Plugin implementiert sind. In Zukunft werden wahrscheinlich weitere hinzukommen.

