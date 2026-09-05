# Utkarsh Mehrotra

Backend/distributed systems engineer. I own the architecture behind real-time risk-decisioning platforms — the consistency, exactly-once, and serving infrastructure that ML models sit on top of.

```bash
$ whoami
utkarsh-mehrotra — backend engineer, samsung research bengaluru

$ cat /proc/current-focus
architecting real-time risk-decisioning platforms · exactly-once semantics at scale · ml-serving infra

$ history | grep architecture
samsung research   → owns backend architecture, multi-country lending platform, real-time risk scoring
western union      → architected 100M+ events/day fraud-detection pipeline (kafka, spark streaming, flink)
cisco               → distributed backend systems, core infra, 5y

$ ls ~/systems-designed
consensus/ exactly-once-pipelines/ graph-order-visibility/ feature-serving/ observability/

$ tail -f ~/logs/status.log
[INFO] delinquency-detection pipeline in prod, sub-second p99, multi-country
[INFO] side-project: self-evolving knowledge systems, multi-agent orchestration
```

**Architecture** — Systems designed for correctness under failure first, throughput second: exactly-once semantics on payment and event pipelines, consistency guarantees carried across service boundaries, graph-based state (Neo4j → Neptune) where relational models broke down, full-stack observability (ELK, Prometheus, Grafana) so failure modes are diagnosable, not guessed at.

**Impact** — Backend architecture for a lending platform spanning Southeast Asia and India, with a delinquency-detection pipeline scoring at-risk accounts in real time at sub-second p99. Earlier, architected the 100M+ events/day fraud-detection pipeline at Western Union that the business still runs on.

**AI-inclined** — Applied ML and Advanced NLP grounding used to design the feature and serving infrastructure ML models actually depend on — the pipelines have to be exactly-once and low-latency before a model can be trusted in the decision loop. Currently building self-evolving knowledge systems with multi-agent orchestration as a side project.

**Stack** — Kafka, Flink, Spark Streaming, consensus/replication · Java, Python, TypeScript · Postgres, Redis, Neo4j/Neptune · AWS, Terraform, Docker, Kubernetes

**Contact** — [LinkedIn](https://linkedin.com/in/utkarshmehrotra-/) · [Portfolio](https://utkarsh-mehrotra.github.io/)
