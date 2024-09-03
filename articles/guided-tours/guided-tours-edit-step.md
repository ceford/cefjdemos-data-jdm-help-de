<!-- Filename: Help4.x:Guided_Tours:_New_or_Edit_Step / Display title: Geführte Touren: Schritt bearbeiten -->

## Beschreibung

Diese Seite wird verwendet, um einen neuen Schritt hinzuzufügen oder einen vorhandenen Schritt einer Tour zu bearbeiten.

### Gemeinsame Elemente

Einige Aspekte dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).
* [Der Veröffentlichungs-Tab](jdocmanual?article=help/common-elements/edit-publishing).

## Zugriffsmethode

- Wählen Sie **System -> Verwalten -> Geführte Touren** aus dem Administrator-Menü.
- Wählen Sie die nummerierte **Schritte**-Schaltfläche für eine Tour, um die Tour-Schritte-Seite zu öffnen.
- Wählen Sie die **Neu**-Schaltfläche in der Werkzeugleiste, um einen Schritt hinzuzufügen.
- Wählen Sie einen **Titel** aus der Liste, um einen Schritt zu bearbeiten.

## Screenshot

![Geführte Touren Schritt bearbeiten](../../../de/images/guided-tours/guided-tours-edit-step.png)

## Formularfelder

- **Titel** Der Titel für diesen Schritt. In der Regel ist es eine Aufforderung zur Aktion, z. B. `Geben Sie einen Titel ein`, wenn der Schritt eine Benutzerinteraktion erfordert. Wenn der Titel ein Sprachschlüssel ist, wird ein zusätzliches Feld angezeigt, das die Übersetzung dieses Schlüssels für die Benutzersprache darstellt.

### Bearbeiten Schritt Tab

#### Linkes Panel

- **Beschreibung** Hier geben Sie die Beschreibung des Schritts ein, normalerweise eine detaillierte Erklärung oder Hilfe für den Schritt. Die Schrittbeschreibung kann ein Sprachschlüssel sein. In diesem Fall wird ein sekundäres Feld angezeigt, das die übersetzte Beschreibung dieses Schlüssels für die Benutzersprache enthält.

#### Rechtes Panel

- **Position** Die Position des Schritts relativ zu der Information, auf die er zeigt.
  - **Unten** Der Schritt wird unterhalb des Ziels angezeigt.
  - **Mitte** Der Schritt wird in der Mitte des Bildschirms angezeigt. Wenn ein Ziel fehlt, ist dies die Standardposition.
  - **Links** Der Schritt wird links vom Ziel angezeigt.
  - **Rechts** Der Schritt wird rechts vom Ziel angezeigt.
  - **Oben** Der Schritt wird oberhalb des Ziels angezeigt.
- **Ziel** Das Element auf dem Bildschirm, auf das der Schritt zeigt. Es verwendet CSS-Syntax.

  Zum Beispiel wird *.button-new* die Schaltfläche auf der Seite anvisieren, die die Klasse *button-new* hat.

  Wenn das Ziel nicht eindeutig ist, wird das erste gefundene Ziel verwendet. Stellen Sie bei der Erstellung interaktiver Schritte sicher, dass das Ziel für die Barrierefreiheit fokussierbar ist. Sie können mehrere Selektoren verwenden, durch Kommas getrennt. Der erste gültige wird zum Ziel (ein Selektor ist gültig, wenn er: auf der Seite gefunden wird, nicht deaktiviert, nicht schreibgeschützt und nicht versteckt ist). Wenn ein Ziel festgelegt, aber nicht gefunden oder ungültig ist, wird die Tour nicht unterbrochen, sondern zeigt den Schritt in der Mitte des Bildschirms an.
- **Typ** Der Typ des Schritts.
  - **Nächster** Der Benutzer, der die Tour durchführt, wird zum nächsten Schritt weitergeleitet.
  - **Weiterleitung** Der Schritt wird zu einer anderen Seite weitergeleitet.
  - **Interaktiv** Der Schritt erfordert eine Benutzerinteraktion, wie z. B. die Eingabe von Daten.
- **URL** Die URL, zu der ein Schritt des Typs *Weiterleitung* weitergeleitet wird.
  Zum Beispiel wird *administrator/index.php?option=com_users&view=user&layout=edit* den Schritt zum Benutzerbearbeitungsbildschirm weiterleiten.
- **Interaktiver Typ** Der Interaktionstyp für einen interaktiven Schritt.
  - **Formularabsendung** Das Ziel ist eine Schaltfläche, die ein Formular absendet.
  - **Textfeld** Das Ziel ist ein Eingabetextfeld. Wenn das Feld erforderlich ist, kann die Person, die die Tour durchführt, nicht zum nächsten Schritt weitergehen, bis Daten eingegeben wurden.
  - **Schaltfläche** Das Ziel ist eine Schaltfläche auf dem Bildschirm.
  - **Andere** Das Ziel ist ein anderes Formularelement.

### Optionen Tab

![Geführte Touren Schritt bearbeiten Optionen-Tab](../../../de/images/guided-tours/guided-tours-edit-step-options-tab.png)

## Tipps

- Verwenden Sie **GUIDEDTOUR** in Sprachschlüsseln als Konvention, wo immer Sprachschlüssel verwendet werden (für Titel und Beschreibung).
