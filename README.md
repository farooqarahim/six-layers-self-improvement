# Six Layers of Self-Improvement

**A framework for decomposing and governing recursive AI enhancement.**

**Farooq Abdul Rahim, Nithish Mohan, Ajomon Jose**

> Version 1.2.3 — Theoretical framework. Implementation pending. Real data outcomes expected soon.

---

## What This Is

A six-layer framework that decomposes recursive self-improvement in AI into a depth-ordered stack:

| Layer | Name | Substrate Modified | Governance |
|-------|------|--------------------|------------|
| L1 | Self-Evaluation & Diagnostics | Performance model | Autonomous |
| L2 | Strategy Evolution | Decision heuristics | Autonomous |
| L3 | Tool & Integration Optimization | External tool interface | Autonomous / escalation |
| L4 | Knowledge Synthesis & Compression | Distilled knowledge | Human review |
| L5 | Architecture Adaptation | Computational structure | Board approval |
| L6 | Meta-Learning | Improvement process itself | Human-in-the-loop + rate limits |

Each layer targets a distinct substrate, exhibits qualitatively different risk dynamics, and demands calibrated governance.

## Key Results (Theoretical)

**Phase diagram.** Two parameters — β (meta-improvement rate) and γ (ceiling-lift rate) — separate four improvement regimes. Regimes A–C are bounded. Regime D produces a superlinear transient toward physical limits. Governance constraining either β or γ prevents Regime D.

**Triple bounding.** Improvement velocity is independently constrained by physical bounds (K_max), economic bounds (EV > 0), and governance bounds (constitution + rate limits + behavioral comparator). The intelligence explosion requires all three to fail simultaneously.

**Falsifiable predictions.** Seven predictions with sensitivity analysis — including inner-loop saturation curves, governance rejection concentration, and drift detection efficacy — enable empirical testing.

## Status

| Component | Status |
|-----------|--------|
| Theoretical framework | ✅ Complete (v1.2.3) |
| Formal model (10 propositions, 12 definitions) | ✅ Complete |
| Governance architecture | ✅ Complete |
| Experimental validation protocol (10 experiments) | ✅ Specified |
| Simulation (Appendix E) | ⏳ Pending implementation |
| Implementation (SIE codebase) | ⏳ Pending |
| Empirical results | ⏳ Pending — real data outcomes expected soon |

## Repository Structure

```
├── paper/
│   └── Six_Layers_Paper_v1.2.3.pdf      # Full paper (Markdown)
├── figures/                             # ⏳ Pending
│   ├── figure_1_six_layer_stack.svg
│   ├── figure_2_inner_loop_bounded.svg
│   ├── figure_3_outer_loop_phase_diagram.svg
│   ├── figure_4_improvement_frontier_migration.svg
│   └── figure_5_governance_gate_flowchart.svg
├── simulation/                           # ⏳ Pending
├── src/                                  # ⏳ Pending — SIE implementation
├── experiments/                          # ⏳ Pending — experiment protocols and results
├── LICENSE
└── README.md
```

## Experimental Roadmap

Ten experiments specified in the paper (Section 7). Simulation first, then inner-loop validation, then governance testing, then full deployment. Details in the paper.

## How to Cite

```bibtex
@article{abdulrahim2026sixlayers,
  title={Six Layers of Self-Improvement: A Framework for Decomposing and Governing Recursive AI Enhancement},
  author={Abdul Rahim, Farooq and Mohan, Nithish and Jose, Ajomon},
  year={2026},
  note={v1.2.3, theoretical framework, implementation pending}
}
```

## Contributing

This is an active research project. Contributions are welcome in:

- **Experiment execution** — running the experiments specified in Section 7
- **Simulation implementation** — implementing the Monte Carlo simulation from Appendix E
- **Retrospective classification** — applying the taxonomy to existing AI system improvement logs
- **Formal review** — identifying gaps or errors in the proofs and definitions

Open an issue before starting work to avoid duplication.

## License

Apache License 2.0 — see [LICENSE](LICENSE).
