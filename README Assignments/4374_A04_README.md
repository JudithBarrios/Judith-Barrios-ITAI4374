# Assignment 04 — LIF Neuron Experiments in Wolfram Language

**Course:** ITAI 4374  
**Tool:** Wolfram Language (Mathematica)

---

## What This Was

This assignment used Wolfram Language to simulate a Leaky Integrate-and-Fire neuron and run a series of experiments changing different parameters to see how neuron behavior changed.

---

## The Model

The LIF neuron was set up with these base parameters:
- Resting potential: –70 mV
- Firing threshold: –55 mV
- Reset potential: –75 mV
- Membrane time constant: 20 ms
- Input current: 18 nA, active from t = 0.05s to t = 0.4s

With these settings the neuron fired **8 spikes**.

---

## Experiments

**Experiment 1 — Threshold Sweep**

Changed threshold from –65 mV to –45 mV in steps of 5 mV.

| Threshold (mV) | Spike Count |
|----------------|------------|
| –65 | 31 |
| –60 | 16 |
| –55 | 8 |
| –50 | 0 |
| –45 | 0 |

Lower threshold = easier to fire = more spikes. Above –50 mV the membrane potential can no longer reach the threshold before current turns off.

**Experiment 2 — Time Constant Comparison**

Compared tau = 0.010, 0.020, and 0.050 seconds.

| Tau | Spike Count |
|-----|------------|
| 0.010s | 17 |
| 0.020s | 8 |
| 0.050s | 3 |

Smaller tau = faster membrane response = more spikes. Larger tau = slower, smoother voltage curve.

**Experiment 3 — Noisy Input**

Replaced constant 18 nA current with noisy current (18 + random value between –8 and +8 nA). Each run produced a different spike pattern — sometimes 0 spikes, sometimes 23. The randomness in the input directly creates randomness in spike timing.

**Experiment 4 — Refractory Period**

Added a 3ms refractory window after each spike. Result: still 8 spikes, same as without it. The reason — at 18 nA the natural interval between spikes is already longer than 3ms, so the refractory period never became a limiting factor. It would only matter with a stronger input current.

---

## Interactive Dashboard (Manipulate)

Used Wolfram's `Manipulate[]` function to build an interactive dashboard with sliders for threshold, time constant, and input current. Key findings:
- **Rheobase** (minimum current to fire at least one spike): ~16–18 nA
- Neuron stops firing at threshold of ~–48 to –50 mV with current = 25 nA
- tau = 0.010 produces more spikes; tau = 0.050 produces a smoother curve

---

## What I Learned

The interactive dashboard made this feel real in a way that just reading about neurons doesn't. Moving a slider and watching the spike count drop to zero showed how close the system always is to silence. The most surprising thing was how a 3ms refractory period had zero effect at normal input levels — the constraint only matters when you push the system to its limits.

---

## Files

| File | Description |
|------|-------------|
| `A04_Judith_Barrios_ITAI4374.pdf` | Full simulation report with code and outputs |
