## Abstract

PLAUD (Performative Latents and Unsupervised DDSP) is a neural synthesizer and Max for Live instrument for live electronic music, built on NoiseBandNet with a variational latent space, and trained on small personal sound corpora. We present its architecture, combining a VAE-based DDSP synthesis model, reconstruction and adversarial training, and an optional transformer prior, alongside a set of bending operations that intervene directly in the synthesis chain: component limiting, waveshaping, and prior feedback. The Max for Live interface exposes control generation, trajectory sampling, and modulation as primary modes of interaction. Throughout, we thread an affordance analysis arguing that the system's performative character follows from architectural decisions rather than being designed on top of them. The paper contributes both a technical account of the system and a situated affordance analysis of its role in live electronic music performance.

---

## Video demonstration

A demonstration of the PLAUD Max for Live instrument, covering latent space navigation, autoregressive prior generation, trajectory sampling, bending operations, and cross-corpus composition.

<iframe width="560" height="315" src="https://www.youtube.com/embed/IP2gmjAcbwY?si=4ki-TA9h9i3ZTbLI" title="PLAUD demonstration" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
