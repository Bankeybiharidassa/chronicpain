# Chronisch-Pijnmodel V2

## 1. Reikwijdte

Dit document definieert het chronische-pijnmodel als een deterministisch model van regelsystemen met expliciete regulatoire lagen. Het doel is de traceerbaarheid te behouden van mechanismehypothesen naar fysiologische uitlezing en pijnperceptie.

## 2. Conceptuele Basis

Chronische pijn wordt gemodelleerd als een meerlaags regulatiesysteem waarin inflammatoire mediatoren, neurovasculaire signalering en microcirculatie interageren via feedbacklus-dynamiek. Het model gaat ervan uit dat aanhoudende dysregulatie zich kan stabiliseren in maladaptieve setpoints.

## 3. Prostaglandine-Regulatiemodel

Het prostaglandine-regulatiemodel wordt gebruikt als de biochemische regellaag voor inflammatoire versterking en timing van resolutie.

### 3.1 Kernvariabelen

- Prostaglandinesynthesedruk
- Receptorgevoeligheidstoestand
- Lokale weefseloxygenatie
- Cytokine-activeringsbelasting

### 3.2 Regulatoire Aanname

De netto mediatorbelasting wordt weergegeven als een begrensde toestandsvariabele die stroomafwaartse adaptatie van de nociceptieve drempel aandrijft.

## 4. Regelsysteemmodel

Het regelsysteemmodel koppelt perifere input aan centrale modulatie met geneste regelaars en foutcorrectielussen.

### 4.1 Regellaagstructuur

1. Perifere inflammatoire regelaar
2. Vasculaire-microcirculatoire regelaar
3. Centrale modulatieregelaar

### 4.2 Toestandsovergangsregel

Een overgang van acuut naar chronisch gedrag treedt op wanneer compenserende correcties de langetermijnversterking verhogen in plaats van de fout te verminderen.

## 5. Viscero-Cutane Reflex en Microcirculatie

De viscero-cutane reflex wordt behandeld als een koppelingspad tussen stress van inwendige organen en cutane/musculaire pijnzones. Microcirculatie wordt gemodelleerd als een begrensd transportnetwerk dat gevoelig is voor mediatorconcentratie.

```text
[Inflammatory mediators] --> [Microcirculation shift] --> [Tissue stress]
          ^                                               |
          |------------------- [feedback loop] -----------|
```

## 6. Fysiologische Uitlezingslaag

Fysiologische uitlezing integreert meetbare indicatoren die worden gebruikt voor modelkalibratie.

- Huidtemperatuurgradiënt
- Variatie in lokale perfusie
- Drukpijndrempel
- Rustende autonome balans

## 7. Pijnperceptielaag

Pijnperceptie wordt weergegeven als de output van gewogen nociceptieve input, contextuele modulatie en adaptatiegeschiedenis.

```text
Pain perception = f(nociceptive input, contextual modulation, adaptation history)
```

## 8. Referenties

1. Basbaum AI, Bautista DM, Scherrer G, Julius D. Cellular and Molecular Mechanisms of Pain. https://www.cell.com/cell/fulltext/S0092-8674(09)01488-3 (2009)
2. Tracey I, Bushnell MC. How Neuroimaging Studies Have Challenged Us to Rethink: Is Chronic Pain a Disease? https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4058737/ (2009)
3. Woolf CJ. Central sensitization: Implications for the diagnosis and treatment of pain. https://pubmed.ncbi.nlm.nih.gov/15262125/ (2011)
