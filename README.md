# Grey Newell

I build eval infrastructure. MS CS (ML) at Georgia Tech. Ex-AWS, 12x certified.

## MIST stack

**M**atchSpec · **I**nferMux · **S**chemaFlux · **T**okenTrace

Go. Zero external deps. All six repos are pinned below.

| Repo | Purpose |
|------|---------|
| [`matchspec`](https://github.com/greynewell/matchspec) | Benchmark suites. Runs evals against any backend, produces structured reports. |
| [`infermux`](https://github.com/greynewell/infermux) | Inference routing. Abstracts providers, tracks tokens and cost per request. |
| [`schemaflux`](https://github.com/greynewell/schemaflux) | Data compiler. Pass pipeline, pluggable backends, no runtime allocs in hot path. |
| [`tokentrace`](https://github.com/greynewell/tokentrace) | Observability. Collects spans, computes latency percentiles, fires threshold alerts. |
| [`mist-go`](https://github.com/greynewell/mist-go) | Shared core. Protocol, transport, metrics, circuit breakers, checkpointing. |

Methodology: [eval-driven development](https://evaldriven.org).

## Research

[![ORCID](https://img.shields.io/badge/ORCID-0009--0001--0714--3800-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0001-0714-3800)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18627369.svg)](https://doi.org/10.5281/zenodo.18627369)
