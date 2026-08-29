## Alexander Bering

Founder and principal investigator at **[ZenSation AI](https://github.com/zensation-ai)**, an
independent research lab in Kiel, Germany, working on cognitive architectures for AI, agent
memory and AI safety. Self-funded, without external grants or investors — income from pilots
and consulting goes back into the research.

I have been putting software into production since 2009, across three domains: financial
trading systems, enterprise CRM, and now AI research infrastructure.

### What I build here

**[zenbrain](https://github.com/zensation-ai/zenbrain)** — a seven-layer, neuroscience-derived
memory architecture for LLM agents. Zero-dependency TypeScript, Apache-2.0. On LongMemEval-500
it wins all nine head-to-head answer-quality comparisons against Letta, Mem0 and A-Mem (three
competitors × three LLM judges, Bonferroni-corrected), reaching 91.3% of a full-context
oracle's binary-judge accuracy at 1/106th of the per-query token cost.

**[zenai](https://github.com/zensation-ai/zenai)** — the self-hosted AI platform ZenBrain was
extracted from, published as a frozen, readable snapshot.

### The research trail

| | |
|---|---|
| Preprint | [arXiv:2604.23878](https://arxiv.org/abs/2604.23878) |
| Author ID | [ORCID 0009-0001-1793-012X](https://orcid.org/0009-0001-1793-012X) |
| Open records | [Zenodo](https://zensation.ai/en/publikationen) — CC BY 4.0, each with its own version and concept DOI |
| Reproduction | [Mechanism ablation package](https://doi.org/10.5281/zenodo.22162064) — Apache-2.0; reproduces Tables 7–9 from a clean clone |
| Lab | [zensation.ai](https://zensation.ai) · research@zensation.ai |

Every number I publish is meant to be re-derived, not believed. Benchmarks ship with the
protocol, the effect sizes, and the cases where the system loses. Replications and
counter-results are welcome — open an issue or write.
