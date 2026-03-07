# Chronisches-Schmerz-Modell V2

## 1. Geltungsbereich

Dieses Dokument definiert das Modell für chronischen Schmerz als deterministisches Kontrollsystemmodell mit expliziten Regulationsschichten. Das Ziel ist, die Rückverfolgbarkeit von Mechanismushypothesen zu physiologischem Indikator und Schmerzwahrnehmung zu erhalten.

## 2. Konzeptionelle Grundlage

Chronischer Schmerz wird als mehrschichtiges Regulationssystem modelliert, in dem entzündliche Mediatoren, neurovaskuläre Signalgebung und Mikrozirkulation über Rückkopplungsschleife-Dynamiken interagieren. Das Modell nimmt an, dass anhaltende Dysregulation sich in maladaptiven Sollwerten stabilisieren kann.

## 3. Prostaglandin-Regulationsmodell

Das Prostaglandin-Regulationsmodell wird als biochemische Kontrollebene für entzündliche Verstärkung und den zeitlichen Verlauf der Auflösung verwendet.

### 3.1 Kernvariablen

- Prostaglandin-Synthesedruck
- Rezeptor-Sensitivitätszustand
- Lokale Gewebeoxygenierung
- Zytokin-Aktivierungslast

### 3.2 Regulationsannahme

Die Netto-Mediatorlast wird als begrenzte Zustandsvariable dargestellt, die die nachgelagerte Anpassung der nozizeptiven Schwelle antreibt.

## 4. Kontrollsystemmodell

Das Kontrollsystemmodell verknüpft periphere Eingänge mit zentraler Modulation unter Verwendung verschachtelter Regler und Fehlerkorrekturschleifen.

### 4.1 Reglerschichten

1. Peripherer Entzündungsregler
2. Vaskulär-mikrozirkulatorischer Regler
3. Zentraler Modulationsregler

### 4.2 Zustandsübergangsregel

Ein Übergang von akutem zu chronischem Verhalten tritt auf, wenn kompensatorische Korrekturen den langfristigen Gain erhöhen, statt den Fehler zu reduzieren.

## 5. Viszerokutaner Reflex und Mikrozirkulation

Der viszerokutaner Reflex wird als Kopplungspfad zwischen internem Organstress und kutanen/muskulären Schmerzzonen behandelt. Mikrozirkulation wird als begrenztes Transportnetzwerk modelliert, das empfindlich auf Mediator-Konzentration reagiert.

```text
[Inflammatory mediators] --> [Microcirculation shift] --> [Tissue stress]
          ^                                               |
          |------------------- [feedback loop] -----------|
```

## 6. Physiologischer Indikator-Schicht

Der physiologische Indikator integriert messbare Marker, die für die Modellkalibrierung verwendet werden.

- Hauttemperaturgradient
- Lokale Perfusionsvariation
- Druckschmerzschwelle
- Ruhende autonome Balance

## 7. Schmerzwahrnehmungs-Schicht

Schmerzwahrnehmung wird als Output gewichteter nozizeptiver Eingabe, kontextueller Modulation und Adaptationshistorie dargestellt.

```text
Pain perception = f(nociceptive input, contextual modulation, adaptation history)
```

## 8. Referenzen

1. Basbaum AI, Bautista DM, Scherrer G, Julius D. Cellular and Molecular Mechanisms of Pain. https://www.cell.com/cell/fulltext/S0092-8674(09)01488-3 (2009)
2. Tracey I, Bushnell MC. How Neuroimaging Studies Have Challenged Us to Rethink: Is Chronic Pain a Disease? https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4058737/ (2009)
3. Woolf CJ. Central sensitization: Implications for the diagnosis and treatment of pain. https://pubmed.ncbi.nlm.nih.gov/15262125/ (2011)
