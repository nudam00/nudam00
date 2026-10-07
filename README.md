# Hi, I'm Patryk

I'm a software engineer building backend services, data platforms, and cloud
infrastructure with Python and Go.

## Specula Sol

Specula Sol is my private R&D project: an end-to-end data, ML, and automated
trading system for Solana markets. Its goal is to turn market and on-chain
events into reproducible research datasets and, eventually, use selected
prediction artifacts in a trading application.

The architecture spans four components:

- **Infrastructure:** Google Cloud infrastructure managed with Terraform and
  delivered through automated CI/CD workflows.
- **Data platform:** Prefect pipelines process raw events through Bronze,
  Silver, and Gold Delta Lake layers using Polars and Pandera, with explicit
  data contracts, quality checks, and immutable release manifests.
- **ML pipeline:** consumes immutable Gold releases and currently produces
  auditable labeling artifacts. Point-in-time-correct feature preparation,
  training, evaluation, and versioned prediction artifacts are under active
  development.
- **Trading application:** a prototype for collecting live observations,
  evaluating signals, and executing configured decisions.

The repositories remain private because the project contains ongoing research
and operational details.

## Background

At GSK, I develop internal APIs and data-oriented applications on Google Cloud,
build migration and automation tooling, and help modernize legacy systems. My
work has included Python and Go services, CI/CD,
observability, and reusable engineering tooling shared across repositories.
