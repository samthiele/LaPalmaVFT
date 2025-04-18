
# Hilfe

[Übersetzt mit DeepL]

Die virtuellen Exkursionen von RockHopper sollten (hoffentlich!) recht intuitiv zu navigieren sein, aber diese Seite hilft Ihnen, die Funktionsweise zu verstehen.

## 3D-Steuerung

Verwenden Sie die folgenden Steuerelemente, um im 3D-Viewer zu navigieren.
| Steuerelement |     Aktion     |
|----------|----------|
| `Linke Maustaste` | Ansicht drehen   |
| `Rechte Maustaste` | Ansicht verschieben   |
| `Scrollrad` | Zoomen   |
| `Doppelklick` | Drehpunkt festlegen oder angeklickte Anmerkung löschen  |
| `Umschalt+Linksklick` | Ansicht verschieben |
| `Strg+Linksklick` | Punkt zur aktuellen Anmerkung hinzufügen |

## Steuerelemente für Anmerkungen

Anmerkungspunkte können mit `Strg+Linksklick` hinzugefügt werden (diese sollten zunächst als kleine gelbe Kugeln erscheinen). Wenn eine Anmerkung fertig ist, drücken Sie die `Eingabetaste`, um sie zu übernehmen, oder `Esc`, um sie zu löschen.

Die Art der hinzuzufügenden Anmerkung wird anhand der Anzahl der Punkte festgelegt, wenn die `Eingabetaste` gedrückt wird:

1 Punkt: Fügen Sie ein `Label`-Objekt mit Text (oder beliebigem HTML-Code) hinzu.
2 Punkte: Fügen Sie ein „Vektor“-Objekt hinzu und fügen Sie dessen „Trend“, „Einbruch“ und „Länge“ zur Registerkarte „Notizen“ hinzu.
3 Punkte: Fügen Sie ein „Ebene“-Objekt hinzu und fügen Sie dessen „Streichung“, „Neigung“ und „Neigungsrichtung“ zur Registerkarte „Notizen“ hinzu.
4+ Punkte: Fügen Sie ein „Polylinie“-Objekt hinzu. Diese können beispielsweise zum Hervorheben linearer Merkmale (oder zum Einkreisen interessanter Objekte) nützlich sein.

---

**Wichtiger Hinweis**: *Anmerkungen gehen verloren, wenn die Seite aktualisiert wird (es sei denn, Sie führen RockHopper auf einem lokalen Entwicklungsserver aus); das bedeutet, dass alle Änderungen über die Schaltfläche „⬇ Notizen“ unten links heruntergeladen werden müssen.*

---

Anmerkungen (und HTML-Beschriftungen) können über die entsprechenden Umschaltflächen unten links im 3D-Viewer ein- und ausgeblendet werden. Die Farbe der (aktuell gezeichneten) Anmerkungen kann auch durch Klicken auf das Farbauswahl-Widget geändert werden.

## Visualisierungssteuerung
Eine wesentliche Stärke von RockHopper besteht darin, dass mehrere Attribute von Punktwolken-Datensätzen gestreamt und auf unterschiedliche Weise visualisiert werden können. Diese Visualisierungsstile werden definiert, wenn die Punktwolke in ein streambar Format konvertiert und (hoffentlich) verständliche Namen erhalten wird. 

**Verwenden Sie die Schaltflächen oben links in der 3D-Ansicht, um den Ansichtsstil zu ändern**. In der oberen Zeile wird die Farbauflösung geändert, die zur Definition der Punktfarben verwendet wird. In der zweiten Zeile können Sie bestimmte Teilmengen der Punkte (basierend auf einer zugrunde liegenden Klassifizierung) hervorheben oder ausblenden. Dies kann nützlich sein, um verschiedene Datenpunkte in einem Zeitreihendatensatz zu visualisieren oder bestimmte Teile einer Punktwolke hervorzuheben.
