# Paper Reading

Paper presentation notes. More reads and write-ups on blog / LinkedIn when time allows.

---


**Paper:** *Conformal Prediction for Uncertainty-Aware Planning with Diffusion Dynamics Model*
Jiankai Sun et al. | Presented by Chia Chien, Liu · Apr 2025


---

## What This Paper Does

PlanCP = diffusion planner + CP as training loss & calibration.

differentiable quantile → enable backprop
---

## My Insights

**No ablation** — can't isolate CP's contribution; alternatives (Bayesian, bootstrap, MC dropout) untested.

**Distributional shift unresolved** — fixed dataset; OOD exposure persists.

**Online RL: CP breaks** — online data violates exchangeability assumption.

**Diffusion Planner unjustified** — RL-guided diffusion can surpass expert quality; this can't.
