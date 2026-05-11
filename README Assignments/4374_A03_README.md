# Assignment 03 — Bridging Neuroscience and Artificial Intelligence

**Course:** ITAI 4374  
**Date:** February 2, 2026  
**Group:** Magnolia  
**Submitter:** Oscar Cortez

---

## What This Was

This assignment compared biological neural networks to artificial ones — mapping the physical components of a neuron to their AI equivalents, then scaling up to look at how brain architecture inspired specific AI designs like CNNs, LSTMs, and Transformers.

---

## Neuron Component Mapping

| Biological component | Role | AI equivalent |
|---------------------|------|---------------|
| Cell body (soma) | Integrates inputs, triggers firing | Processing unit (weighted sum + activation) |
| Dendrites | Receive signals from other neurons | Input connections / incoming features |
| Axon | Transmits output to other cells | Output connection to next layer |
| Synapses | Connection strength, changes with learning | Weights (learnable parameters) |

---

## Brain Systems and Their AI Counterparts

- **Visual cortex → CNNs** — The visual system processes information in stages, from simple edges to complex objects. CNNs mirror this with early filters capturing edges and later layers capturing semantics.
- **Hippocampus → LSTMs / memory** — The hippocampus supports memory formation and consolidation. LSTMs provide gated state to maintain information over time.
- **Frontoparietal attention → Transformers** — Biological attention uses top-down control to prioritize relevant signals. Transformer attention does the same computationally by weighting which parts of the input matter most.
- **Amygdala → Risk detection** — The amygdala flags threat and emotional importance. AI could use a similar module to slow down and respond more carefully in high-stakes prompts.

---

## Key Insight

Biology offers more than just inspiration — it offers solutions to problems AI still struggles with. Brains learn continuously without catastrophic forgetting, generalize from few examples, and run on 20 watts. Most AI systems can't do any of those things yet. That gap is where the most interesting future research lives.

---

## Files

| File | Description |
|------|-------------|
| `A03_OscarCortez_Group_Magnolia_ITAI4374.pdf` | Full written analysis |
