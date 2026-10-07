# Hi, I'm Patryk

I'm a software engineer building backend services, data platforms, and cloud
infrastructure with Python and Go.

## Specula Sol

Specula Sol is my private R&D project: an end-to-end data, ML, and automated
trading system for Solana markets. Its goal is to turn market and on-chain
events into reproducible research datasets and, eventually, use selected
prediction artifacts in a trading application.

The system is split into four independently developed parts:

- **Infrastructure:** a Terraform-managed development environment on Google
  Cloud, including workload identities, secrets, storage, compute, and
  container delivery.
- **Data platform:** Prefect pipelines process raw events through Bronze,
  Silver, and Gold Delta Lake layers using Polars and Pandera, with explicit
  data contracts, quality checks, and immutable release manifests.
- **ML pipeline:** consumes immutable Gold releases and currently produces
  auditable labeling artifacts. Point-in-time-correct feature preparation,
  training, evaluation, and versioned prediction artifacts are under active
  development.
- **Trading application:** an earlier application prototype for collecting live
  observations, evaluating signals, and executing configured decisions.

The source remains private while the research is active, but the project is
where I apply most of my current work in data engineering, ML systems, cloud
infrastructure, testing, and delivery automation.

## Background

At GSK, I develop internal APIs and data-oriented applications on Google Cloud,
build migration and automation tooling, and help modernize legacy systems. My
work has included Python and Go services, WebSocket ingestion, CI/CD,
observability, and reusable engineering tooling shared across repositories.

## Contact

- [LinkedIn](https://www.linkedin.com/in/patryk-dratwa/)
- [Email](mailto:dratwap@gmail.com)
