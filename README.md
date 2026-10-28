# Energy storage systems in power systems: technologies, modeling, applications, and market participation

A reading and citation companion to **Qixin Liu (2026), “Energy storage systems in power systems: A review of technologies, modeling, applications, and market participation,” Future Batteries, 12, 100216.**

**[Read the published paper](https://doi.org/10.1016/j.fub.2026.100216)** · [中文介绍](README.zh-CN.md) · [Reading guide](reading-guide.md) · [BibTeX](references.bib)

## What does this review cover?

Energy storage systems (ESS) connect renewable generation, power-system flexibility, operational decisions, and electricity markets. This review examines five linked dimensions: storage technologies, modeling approaches, operational roles, application scenarios, and ownership/market participation.

Its central message is that storage suitability depends on the task. Device performance alone does not determine system value: service timescales, model assumptions, deployment location, ownership incentives, and market rules all matter.

| Dimension | Topics covered in the paper | Questions for readers |
| --- | --- | --- |
| Technologies | Electrochemical, electromagnetic, mechanical, chemical, and thermal storage | Which technology characteristics fit the intended service? |
| Modeling | Energy-balance/bucket, equivalent-circuit, and electrochemical models | How much physical detail does the decision require? |
| Operational roles | Renewable integration, arbitrage, peak shaving, reserves, frequency and voltage support, reliability | Which services can the asset credibly provide? |
| Applications | Grid-connected storage, microgrids, behind-the-meter resources, distributed aggregation, virtual power plants | How do location and coordination change constraints and objectives? |
| Markets and ownership | Generation, grid, customer, merchant, aggregator, and hybrid arrangements | How are technical capabilities converted into operational and economic value? |

## When is this paper a relevant reference?

Consider it as a background or synthesis reference when writing about:

- Energy storage technology classification and application suitability in power systems.
- The trade-off between model fidelity and computational tractability in storage planning and operation.
- Connections between storage services, application settings, ownership structures, and electricity markets.
- Research directions in degradation-aware operation, multi-service coordination, long-duration storage, and distributed storage integration.

For a specific numerical performance claim, experiment, algorithm, or jurisdiction-specific market rule, consult the relevant primary source and current official rules. This is an integrative review, rather than a new experimental benchmark or an implementation of an optimization algorithm.

## Key takeaways

1. There is no universally optimal storage technology; suitability depends on service duration, cycling, location, and operational objectives.
2. Model complexity should match the question. Energy-balance models support tractable system optimization; more detailed device models address different accuracy and control needs.
3. Multiple services create coordination challenges as well as opportunities, including constraints associated with aging and competing uses of capacity.
4. Ownership and market access influence dispatch incentives and realized value, even for the same physical asset.

These points are paraphrased from the paper. This repository adds explanatory material; it does not report additional experimental findings.

## Cite the published article

Liu, Q. (2026). Energy storage systems in power systems: A review of technologies, modeling, applications, and market participation. *Future Batteries, 12*, 100216. https://doi.org/10.1016/j.fub.2026.100216

```bibtex
@article{liu2026energystorage,
  author = {Liu, Qixin},
  title = {Energy storage systems in power systems: A review of technologies, modeling, applications, and market participation},
  journal = {Future Batteries},
  volume = {12},
  pages = {100216},
  year = {2026},
  doi = {10.1016/j.fub.2026.100216},
  url = {https://doi.org/10.1016/j.fub.2026.100216}
}
```

Please cite the published article when using its synthesis. GitHub's citation file points to that article.

## Materials and provenance

- [English reading guide and FAQ](reading-guide.md)
- [中文论文介绍](README.zh-CN.md)
- [Citation metadata](CITATION.cff) and [BibTeX](references.bib)

Prepared from the published paper supplied by the author. The paper states that data will be made available on request; no research dataset or research code is included here. Original article: © 2026 The Author, published by Elsevier, CC BY-NC 4.0. The publisher's version and its license remain authoritative. This repository links to the original article rather than redistributing the PDF.

Keywords: energy storage systems; ESS; battery energy storage systems; BESS; power systems; renewable energy integration; energy storage modeling; ancillary services; electricity markets; virtual power plants; storage ownership.
