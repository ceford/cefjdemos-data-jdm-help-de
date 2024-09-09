<!-- Filename: Help6.x:Modules / Display title: Module -->

## Beschreibung

Module sind leichte und flexible Erweiterungen, die verwendet werden, um Informationsschnipsel in Boxen darzustellen, die um eine Komponente auf einer Seite angeordnet sind. Ein bekanntes Beispiel ist das *Login*-Modul. Module werden pro Menüpunkt zugewiesen, sodass Sie entscheiden können, ein Modul abhängig von der Seite, die der Benutzer gerade ansieht, anzuzeigen oder auszublenden.

Einige Module sind mit Komponenten verknüpft. Zum Beispiel ist das *Neueste Nachrichten*-Modul mit der Inhaltskomponente verbunden, um Links zu den neuesten Artikeln anzuzeigen. Module müssen jedoch nicht mit Komponenten verknüpft sein. Sie müssen sogar gar nicht mit irgendetwas verknüpft sein und können einfach statisches HTML oder Text sein.

Es können mehrere Instanzen desselben Moduls existieren. Beispielsweise können Sie eine Instanz des *Zufallsbild*-Moduls für einige Seiten und eine andere Instanz für andere Seiten verwenden, wobei jede Instanz einen anderen Bilderordner zur Auswahl von Bildern nutzt.

Die Listen *Module (Seite)* und *Module (Administrator)* zeigen die aktuell installierten Module in den jeweiligen Schnittstellen an und bieten Zugriff auf das Hinzufügen neuer oder das Bearbeiten bestehender Module.

### Allgemeine Elemente

Einige Elemente dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Symbolleisten](jdocmanual?article=help/common-elements/toolbars).
* [Listenfilter](jdocmanual?article=help/common-elements/list-filters).
* [Listenspaltenüberschriften](jdocmanual?article=help/common-elements/list-column-headers).
* [Listenreihenfolge](jdocmanual?article=help/common-elements/list-ordering).
* [Listenpaginierung](jdocmanual?article=help/common-elements/list-pagination).
* [Stapelverarbeitung für Listen](jdocmanual?article=help/common-elements/list-batch-process).

Um Listen der installierten und verfügbaren Module zu sehen, wählen Sie eine der folgenden Optionen:

* [Seitenmodule](jdocmanual?article=help/modules-site/site-modules-site)
* [Administratormodule](jdocmanual?article=help/modules-admin/admin-modules-administrator)

## Zugriffsmethode

- Wählen Sie **Inhalt → Seitenmodule** aus dem Administrator-Menü. Oder...
- Wählen Sie **Inhalt → Administratormodule** aus dem Administrator-Menü.

## Listenfilter

* **Seite oder Administrator** Wählt entweder Seiten- oder Administratormodule aus.

## Spaltenüberschriften

Dies ist eine kurze Liste der Überschriften, die für Modullisten einzigartig sind.

- **Position** Die Position auf der Seite, an der dieses Modul angezeigt wird.
- **Typ** Der Systemname des Moduls.
- **Seiten** Die Menüpunkte, auf denen dieses Modul angezeigt wird. Dieser Punkt ist in Administratormodullisten nicht vorhanden.
  - *Alle* Wird auf allen Seiten angezeigt
  - *Keine* Wird auf keiner Seite angezeigt
  - *Ausgewählte* Wird nur auf den ausgewählten Seiten angezeigt
  - *Alle außer ausgewählte* Wird auf allen Seiten außer den ausgewählten angezeigt
- **Zugriff** Die Zugriffsebene für dieses Modul.
- **Sprache** Die Sprache des Moduls, Standard ist *Alle*. Dieser Punkt ist in Administratormodullisten nicht vorhanden.

### Modulpositionen

Um Modulpositionen auf einer Live-Site anzuzeigen, gehen Sie zu **System → Vorlagen** und wählen die **Optionen**-Schaltfläche in der Symbolleiste. Setzen Sie *Vorschau Modulpositionen* auf aktiviert und *Speichern*. Diese Einstellung gilt sowohl für Seiten- als auch für Administratorvorlagen. Fügen Sie dann `?tp=1` an das Ende einer URL an, die noch keine Abfragezeichenfolge enthält, oder `&tp=1` an eine URL, die bereits eine Abfragezeichenfolge enthält. Die Seite zeigt alle verfügbaren Modulpositionen an, auch solche, denen keine Module zugewiesen sind. Positionen werden auch im Modulbearbeitungsformular angezeigt.

## Tipps

- Joomla-Websites benötigen mindestens ein Menümodul.
- Andere Modultypen (z. B. Banner) sind optional.
- Einige Module sind mit Komponenten verknüpft. Zum Beispiel ist jedes Menümodul mit einem Menü verbunden.
- Andere Module (z. B. Breadcrumbs) hängen von keinem anderen Inhalt ab.
- Mehrere Vorkommen eines Moduls sind zulässig und üblich.
