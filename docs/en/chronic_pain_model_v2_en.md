# Chronic Pain Model V2

## 1. Scope

This document defines the chronic pain model as a deterministic control systems model with explicit regulatory layers. The objective is to preserve traceability from mechanism hypotheses to physiological readout and pain perception.

## 2. Conceptual Foundation

Chronic pain is modeled as a multi-layer regulatory system where inflammatory mediators, neurovascular signaling, and microcirculation interact through feedback loop dynamics. The model assumes that persistent dysregulation can stabilize into maladaptive setpoints.

## 3. Prostaglandin Regulatory Model

The prostaglandin regulatory model is used as the biochemical control layer for inflammatory amplification and resolution timing.

### 3.1 Core Variables

- Prostaglandin synthesis pressure
- Receptor sensitivity state
- Local tissue oxygenation
- Cytokine activation burden

### 3.2 Regulatory Assumption

The net mediator load is represented as a bounded state variable that drives downstream nociceptive threshold adaptation.

## 4. Control Systems Model

The control systems model links peripheral inputs to central modulation using nested controllers and error-correction loops.

### 4.1 Controller Layers

1. Peripheral inflammatory controller
2. Vascular-microcirculatory controller
3. Central modulation controller

### 4.2 State Transition Rule

A transition from acute to chronic behavior occurs when compensatory corrections increase long-term gain instead of reducing error.

## 5. Viscero-Cutaneous Reflex and Microcirculation

The viscero-cutaneous reflex is treated as a coupling pathway between internal organ stress and cutaneous/muscular pain zones. Microcirculation is modeled as a constrained transport network sensitive to mediator concentration.

```text
[Inflammatory mediators] --> [Microcirculation shift] --> [Tissue stress]
          ^                                               |
          |------------------- [feedback loop] -----------|
```

## 6. Physiological Readout Layer

Physiological readout integrates measurable indicators used for model calibration.

- Skin temperature gradient
- Local perfusion variation
- Pressure pain threshold
- Resting autonomic balance

## 7. Pain Perception Layer

Pain perception is represented as the output of weighted nociceptive input, contextual modulation, and adaptation history.

```text
Pain perception = f(nociceptive input, contextual modulation, adaptation history)
```

## 8. References

1. Basbaum AI, Bautista DM, Scherrer G, Julius D. Cellular and Molecular Mechanisms of Pain. https://www.cell.com/cell/fulltext/S0092-8674(09)01488-3 (2009)
2. Tracey I, Bushnell MC. How Neuroimaging Studies Have Challenged Us to Rethink: Is Chronic Pain a Disease? https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4058737/ (2009)
3. Woolf CJ. Central sensitization: Implications for the diagnosis and treatment of pain. https://pubmed.ncbi.nlm.nih.gov/15262125/ (2011)
