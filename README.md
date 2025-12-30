# ContinuityMinimal

A minimal proof-of-concept exploring continuity-aware neural representations.

## Hypothesis

**Brain representation is a continuous stream.** To be robust to sparse sensing (sparse actions, sparse sensory inputs), neural network foundation models should be **continuity-aware**.

## The Argument

If Buzsáki's theory of brain rhythms is correct, then neural representations *must* be:

1. **Continuity-aware** — encode information as continuous functions, not discrete points
2. **Multi-scale aware** — represent information at multiple temporal scales simultaneously

This is not optional—it is a **logical necessity** derived from how the brain solves sparse sensing.

## Core Insight

| Buzsáki's Brain | AI Implication |
|-----------------|----------------|
| Theta oscillations as "online state" | Temporal scaffolding required |
| Phase precession compresses space→time | Continuous trajectory encoding |
| Cross-frequency coupling (theta↔gamma) | Multi-scale hierarchical structure |
| Internal sequences without input | Self-sustaining dynamics |

**The brain's solution**: Represent the world as a continuous field that inherently interpolates across the void.

## Documents

| File | Description |
|------|-------------|
| [HYPOTHESIS.md](./HYPOTHESIS.md) | Core hypothesis and initial background |
| [THEORY.md](./THEORY.md) | **Rigorous argument**: Buzsáki's claims → logical implications → AI requirements |

## Minimal Experiment (TODO)

Demonstrate that continuity-aware models degrade gracefully under sparse input, while discrete models fail catastrophically.

## References

- Buzsáki, G. (2006). *Rhythms of the Brain*. Oxford University Press.
- Buzsáki, G. (2019). *The Brain from Inside Out*. Oxford University Press.
- Buzsáki, G., & Tingley, D. (2018). Space and Time: The Hippocampus as a Sequence Generator. *Trends in Cognitive Sciences*.
