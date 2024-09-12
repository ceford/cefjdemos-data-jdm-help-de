<!-- Filename: Help4.x:Templates:_Edit_Style / Display title: Templates: Stile bearbeiten -->

## Beschreibung

Die Seite *Templates: Stil bearbeiten* wird verwendet, um Template-Stile zu bearbeiten. Wenn ein Template zum ersten Mal installiert wird, wird ein Standardstil dafür erstellt. Der Standardstil des Templates hat denselben Namen wie das Template mit dem Suffix *- Default*. Um eine andere Variante des Standard-Template-Stils zu erstellen, markieren Sie das Kontrollkästchen des Standardstils und klicken Sie auf das *Duplizieren*-Symbol in der Werkzeugleiste. Anschließend können Sie das Duplikat bearbeiten.

### Allgemeine Elemente

Einige Elemente dieser Seite werden in separaten Hilfsartikeln behandelt:

* [Werkzeugleisten](jdocmanual?article=help/common-elements/toolbars).

## So greifen Sie darauf zu

- Wählen Sie **System → Vorlagen-Panel → Website-Template-Stile** aus dem Administrator-Menü. Oder...
- Wählen Sie **System → Vorlagen-Panel → Administrator-Template-Stile** aus dem Administrator-Menü. Dann...
  - Wählen Sie den Namen des zu bearbeitenden Template-Stils in der Spalte "Stil".

## Screenshot

![templates cassiopeia stil bearbeiten editor tab](../../../de/images/templates/templates-site-edit-style-details-tab.png)

## Formularfelder

- **Stilname** Der Name des Stils. Dieser Name wird in der Spalte "Stil" des Bildschirms *Template: Stile* angezeigt.

### Reiter Details

- **Informationen** Der Name des Templates, der Hinweis "Website" oder "Administrator" und eine kurze Beschreibung.

### Reiter Erweitert

![templates cassiopeia stil bearbeiten editor tab](../../../de/images/templates/templates-site-edit-style-advanced-tab.png)

Dieser Abschnitt ist möglicherweise nicht für alle Stile vorhanden. Wenn ein Template, von dem ein Stil abgeleitet ist, konfigurierbare Optionen enthält, werden diese hier angezeigt. Es sind diese zusätzlichen konfigurierbaren Optionen, die es ermöglichen, mehrere verschiedene Stile von Templates mit Variationen dieser Optionen zu erstellen. Die verfügbaren Optionen variieren je nach den vom Template-Entwickler bereitgestellten Möglichkeiten.

### Atum Farbeinstellungen

Das Standard-Administrator-Template ermöglicht es Ihnen, mit Farbvariationen zu experimentieren. Speichern und sehen Sie die Ergebnisse!

### Atum Bildeinstellungen

Sie können ein Bild auswählen, um das **Login-Logo** im Administrator-Login-Formular und das **Brand-Logo** in der Titelzeile des Administrators im erweiterten und kompakten Modus zu ersetzen. Standardmäßig sind dies die Joomla-Brand-Logos. In der Titelzeile ist im **Brand Large**-Modus das Wort Joomla! zu sehen, im **Brand Small**-Modus wird es weggelassen. Wählen Sie **Menü umschalten**, um die Änderung zu sehen.

Wenn Sie Ihr eigenes Brand Small-Logo bereitstellen, müssen Sie auch eine Breitenstil-Überschreibung hinzufügen. Erstellen Sie dazu eine user.css-Datei im Stammverzeichnis des Templates und fügen Sie folgendes ein, wobei Sie "3rem" durch eine geeignete Breite für Ihr Bild ersetzen:

       .header .logo.small {
           width: 3rem;
       }

### Reiter Menüzuweisung

![templates cassiopeia stil bearbeiten editor tab](../../../de/images/templates/templates-site-edit-style-menu-assignment-tab.png)

Dieser Abschnitt enthält alle Menüeinträge, die in Ihrer Joomla!-Website konfiguriert sind. Um den aktuellen Stil auf die entsprechende Webseite eines Menüeintrags anzuwenden, aktivieren Sie das Kontrollkästchen neben dem Menüeintrag. Sie können den Button *Auswahl umschalten* drücken, um die Auswahl der Menüeinträge zu invertieren.

**Hinweis** Wenn ein Kontrollkästchen ausgegraut ist und nicht aktiviert werden kann, könnte dies daran liegen, dass der Menüeintrag von einem anderen Benutzer verwendet wird. Sie können dies überprüfen, indem Sie zum Menümanager-Bildschirm für das entsprechende Menü gehen. Wenn neben dem Menüeintrag ein Schloss-Symbol angezeigt wird, wird er derzeit von einem anderen Benutzer verwendet.
