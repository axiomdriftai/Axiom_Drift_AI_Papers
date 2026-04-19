# Axiom Drift AI · Papers

Research publications from Axiom Drift AI on the structural dynamics of long-form human–LLM interaction.

All papers are published open access via Zenodo. DOIs are the canonical citation targets. PDFs are mirrored here for browsability.

---

## Beyond Content series

An ongoing series examining long-form human–LLM interaction as a temporal system — not what is said, but how interaction unfolds, stabilizes, and fails over time. Each paper tests a narrower question against the same empirical foundation.

---

### 01 · Temporal Dynamics of Long-Form Human-LLM Interaction
**Baldovino (2026) · January 2026**

An exploratory study of 25 extended human-LLM conversations, examining how interaction unfolds over time when represented as normalized response-magnitude trajectories rather than semantic content. Multiple repeatable interaction regimes emerge with distinct temporal envelopes — robust to stochastic perturbation but degrading under temporal scrambling, indicating sensitivity to sequential order rather than static statistics.

> Descriptive and conditional in scope. Intended as a methodological starting point.

**DOI:** https://doi.org/10.5281/zenodo.18273459  
**Zenodo record:** https://zenodo.org/records/18273459

---

### 02 · Surface Matching, Temporal Divergence, and the Limits of Synthetic Baselines
**Baldovino (2026) · March 2026**

Tests whether a surface-matched, stateless synthetic baseline can reproduce the temporal structure observed across 25 extended human-LLM threads. The synthetic condition approximated assistant-side bulk behavior but failed to recover user-side variability, amplification structure, and recovery dynamics. The result is methodological: surface matching alone is insufficient, and building a strong synthetic null for long-form interaction is itself a nontrivial problem.

> Introduces the amplification ratio and lagged coupling metrics as structural measures of interaction.

**DOI:** https://doi.org/10.5281/zenodo.19143515  
**Zenodo record:** https://zenodo.org/records/19143515

---

### 03 · Shared Temporal Structure and Distinct Coupling Regimes in Two Human-LLM Archives
**Baldovino (2026) · April 2026**

Extends the Beyond Content framework from a single-participant archive to two human-LLM archives. Using three paired threads exceeding 600 turns, the analysis compares structural metrics only — turn lengths, rolling variability, amplification, consecutive-turn correlation, and separated user and assistant rolling means. What generalizes across archives is temporally organized long-form structure; what varies is the coupling profile through which it is expressed.

> Deliberately uses archives with divergent semantic content to provide a more demanding test of the non-semantic claim.

**DOI:** https://doi.org/10.5281/zenodo.19633916  
**Zenodo record:** https://zenodo.org/records/19633916

---

## Methodology

All analyses in this series are non-semantic. Measurements are derived from structural properties of the interaction — response length, variance, amplification, temporal correlation — without reference to content, sentiment, or meaning. This is a deliberate epistemological constraint, not a limitation.

The non-semantic approach is motivated in part by the observer effect in interaction research: when participants know their conversation is being studied, they adjust behavior in ways that contaminate semantic-level data. Structural metrics derived from turn-level properties are below the level of strategic self-presentation and are therefore less susceptible to this confound.

---

## Instruments

Measurement instruments associated with this research are publicly available on Hugging Face:

- **Variance Register** — structural analysis of fixed example archives · [Open instrument](https://huggingface.co/spaces/axiomdriftai/Variance_Register)
- **Open Register** — structural analysis of user-supplied transcripts · [Open instrument](https://huggingface.co/spaces/axiomdriftai/Open_Register)
- **TwinTrack** — human archive vs. synthetic profile comparison · [Open instrument](https://huggingface.co/spaces/axiomdriftai/TwinTrack)

All instruments run entirely in the browser. No data is transmitted or stored.

---

## Citation

If citing work from this series, please use the Zenodo DOI for the specific paper. For the series as a whole:

```
Baldovino, K. (2026). Beyond Content series. Axiom Drift AI. https://axiomdrift.ai
```

---

## License

All papers in this repository are published under  
[Creative Commons Attribution–NonCommercial–NoDerivatives 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)

---

[axiomdrift.ai](https://axiomdrift.ai) · [ORCID 0009-0007-0457-4342](https://orcid.org/0009-0007-0457-4342) · hello@axiomdrift.ai
