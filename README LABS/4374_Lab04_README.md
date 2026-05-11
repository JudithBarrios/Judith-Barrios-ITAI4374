# Lab 04 — LIF Neuron Model: Biological Realism

**Course:** ITAI 4374  
**Tool:** Jupyter Notebook

---

## What This Lab Was About

This lab built on the basic LIF neuron model and made it more biologically realistic. The focus was on two key features: afterhyperpolarization and the membrane time constant (tau), and understanding what they actually mean in terms of how real neurons behave.

---

## Key Concepts

**Afterhyperpolarization (V_reset < V_rest)**

After a real neuron fires, potassium channels open and push the membrane voltage briefly below the resting potential — a dip called afterhyperpolarization. In the model, setting V_reset lower than V_rest captures this behavior. It creates a natural refractory period because the neuron has to climb back up from below resting potential before it can fire again, which prevents it from firing immediately after a spike.

**Membrane Time Constant (tau)**

Tau controls how quickly the membrane potential leaks back toward rest when there is no input coming in. A small tau means the neuron forgets input quickly — it needs strong current to fire because weak signals decay before they build up. A larger tau means the neuron integrates input over a longer time window, making it more sensitive to weak but sustained signals. The same input current can produce very different firing behavior depending on tau alone.

---

## What I Learned

The basic LIF model from earlier labs treated the reset and time constant as just numbers. This lab explained what those numbers actually represent biologically. V_reset isn't arbitrary — it models a real electrochemical event that happens after every spike. Tau isn't just a rate — it determines whether a neuron is a fast detector or a slow integrator. Those distinctions matter when thinking about why different types of neurons in the brain serve different functions.

---

## Files

| File | Description |
|------|-------------|
| `L04_Judith_Barrios_ITAI4374.ipynb` | Lab notebook |
