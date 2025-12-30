# Continuity Bias in Neural Representations

## Core Hypothesis

Brain representation is a continuous stream. To be robust to sparse sensing (sparse actions, sparse sensory inputs), foundation models should be **continuity-aware**.

**Continuity Bias**: The philosophical assumption that the world is a *field* rather than a set of points.

**Brain Rhythms**: The biological machinery that enforces this assumption.

---

## 1. Oscillations as the Carrier of Continuity

In AI models (SOLID, Neural Fields), continuity is enforced by mathematical functions (coordinate networks, diffusion priors) that connect sparse points.

In Buzsáki's theory, this function is performed by **rhythm** (e.g., Theta waves).

| Problem | Solution |
|---------|----------|
| Neurons fire discrete spikes—point events with no duration | Oscillations act as continuous carrier waves |
| Reading only spikes → stroboscopic, discontinuous world | Embedding spikes into rhythm phase → smooth trajectory |

The rhythm persists between spikes, "filling the void" and forcing the system to treat distinct events as part of one continuous flow.

---

## 2. Phase Precession: The Algorithm of Continuity

**Phase Precession** (hippocampus) provides the strongest evidence:

- As a rat traverses a place field, neurons fire at systematically *earlier* phases of the theta cycle
- This transforms spatial sequence (A → B → C) into temporal sequence within a single oscillation
- Compresses "future" and "past" into the **continuous present** of the theta wave

### AI Parallel

This is exactly what a **Neural Field** does:
- Learn function f(x) such that f(A) and f(B) yield smoothly changing values
- Interpolate between sparse training points
- Phase precession = brain's real-time interpolation

---

## 3. Multi-Scale Rhythms = Multi-Scale Fields

Brain rhythms organize hierarchically (Delta → Theta → Gamma), creating **multi-scale continuity**:

| Rhythm | Scale | Function | Continuity Role |
|--------|-------|----------|-----------------|
| **Slow (Delta/Theta)** | Seconds | Narrative/Context | Global field—maintains long-term structure even when inputs disappear |
| **Fast (Gamma)** | Milliseconds | Sensory items/Content | Local fluctuations—captures discrete details anchored to slow wave |

### AI Parallel

Like **Deep Reservoir Computing** or **Multi-scale Neural Fields**:
- Different layers handle slow trends vs. fast noise
- Cross-frequency coupling enforces stability
- Slow rhythm prevents fast sensory data from shattering unified experience

---

## 4. Rhythms as Prediction in the Void

Oscillators are self-sustaining. When sensory input stops (the "void"), the rhythm continues via **resonance**.

**Result**: The brain "predicts" continuity.
- Eye blinks, occlusions → oscillation carries state forward
- Place cell sequences continue firing
- Rhythm provides the *prior* that "existence is continuous"

---

## Summary

**Buzsáki's rhythms are the syntax of continuity.**

| Component | Role |
|-----------|------|
| **Discrete Data** | Spikes (sensory samples) |
| **Continuous Prior** | Oscillations (generative model) |
| **Mechanism** | Phase-embedding smooths discrete spikes into continuous flow |

The brain performs **real-time interpolation** to construct a seamless world from sparse neural events.

---

## Implications for AI

Foundation models should incorporate:

1. **Continuous representations** - Not just discrete tokens
2. **Multi-scale temporal structure** - Slow context + fast details
3. **Phase-based binding** - Relate sparse events through continuous carriers
4. **Self-sustaining dynamics** - Predictions that persist through input gaps

This is the minimal hypothesis we aim to prove.
