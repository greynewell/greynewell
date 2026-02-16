# Grey Newell

Building evaluation infrastructure for AI systems. Creator of the **MIST stack**.

MS CS (Machine Learning) at Georgia Tech. Ex-AWS (SDE + Solutions Architect, 12x certified).

## MIST Stack

An end-to-end evaluation and inference platform for AI systems, written in Go with zero external dependencies at the core.

**M**atchSpec · **I**nferMux · **S**chemaFlux · **T**okenTrace

| Repo | What it does |
|------|-------------|
| [`matchspec`](https://github.com/greynewell/matchspec) | Define benchmark suites, run evals against any inference backend, report results |
| [`infermux`](https://github.com/greynewell/infermux) | LLM inference router — provider abstraction, model routing, cost observability |
| [`schemaflux`](https://github.com/greynewell/schemaflux) | Structured data compiler with pass pipeline and pluggable backends |
| [`tokentrace`](https://github.com/greynewell/tokentrace) | Real-time inference observability — span collection, latency percentiles, alerts |
| [`mist-go`](https://github.com/greynewell/mist-go) | Shared library — protocol, transport, metrics, circuit breaking, checkpointing |

Every component follows [eval-driven development](https://evaldriven.org): deterministic, automated evaluation as the foundation of AI system reliability.

## Research

[![ORCID](https://img.shields.io/badge/ORCID-0009--0001--0714--3800-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0001-0714-3800)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18627369.svg)](https://doi.org/10.5281/zenodo.18627369)
