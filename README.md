# Abdirahman Jama Abdi

London. Working toward Platform, DevOps and SRE roles.

I build infrastructure, break it, and write down exactly what broke. Most of the repos here are
learning projects, and the documentation is the point as much as the code is. If something failed,
the write-up says so and explains the root cause.

Trading systems are the domain I keep coming back to. It's where infrastructure gets interesting,
because latency, correctness and reliability stop being abstract qualities and start being the
product.

## Infrastructure and platform

| Project | What it is |
|---------|------------|
| [Terraform](https://github.com/Abdirahmanjabdi/Terraform) | WordPress and NGINX on AWS EC2. Two approaches to the same problem: an imperative bash `user_data` script that hit an apt lock race and broke, and a declarative cloud-init file that didn't. Full write-ups of both. |
| [AWS](https://github.com/Abdirahmanjabdi/AWS) | VPC networking, application load balancing, S3 with CloudFront, and a serverless API. Built from scratch, documented with architecture diagrams. |
| [livestock-ledger](https://github.com/Abdirahmanjabdi/livestock-ledger) | Livestock traceability platform. Ethereum contract with indexed PostgreSQL read models, Next.js frontend, Prometheus and Grafana, Kubernetes manifests, Terraform, GitHub Actions CI. |
| [docker-learning](https://github.com/Abdirahmanjabdi/docker-learning) | Multi-stage builds, Compose, and an NGINX reverse proxy in front of a Python app. |
| [devops-learning-bash](https://github.com/Abdirahmanjabdi/devops-learning-bash) · [devops-learning-linux](https://github.com/Abdirahmanjabdi/devops-learning-linux) · [Git-labs](https://github.com/Abdirahmanjabdi/Git-labs) | Fundamentals. Scripting, filesystem and process internals, and git workflows. |

## Trading systems and fintech

| Project | What it is |
|---------|------------|
| [AIRO / Sentinel Trading](https://github.com/Abdirahmanjabdi/AIRO) | A behavioural risk engine for MetaTrader 5. Detects revenge entries, oversized positions and drawdown pressure. It doesn't predict direction, it protects the trader from themselves. |
| [Market-Regime-Classifier](https://github.com/Abdirahmanjabdi/Market-Regime-Classifier) | Classifying market conditions into regimes. |
| [Risk-Engine](https://github.com/Abdirahmanjabdi/Risk-Engine) | Position and portfolio risk evaluation. |
| [Execution-Simulator](https://github.com/Abdirahmanjabdi/Execution-Simulator) | Order execution modelling. |
| [market-replay-engine](https://github.com/Abdirahmanjabdi/market-replay-engine) | Replaying historical market data for testing. |
| [Trade-Ledger-Analytics-Engine](https://github.com/Abdirahmanjabdi/Trade-Ledger-Analytics-Engine) | Analytics over trade history. |

## Tools

**Infrastructure:** Terraform, AWS (EC2, VPC, ALB, S3, CloudFront, Lambda), Docker, Kubernetes,
cloud-init

**Observability and CI:** Prometheus, Grafana, GitHub Actions

**Systems:** Linux, Bash, NGINX, PostgreSQL

**Languages:** Python, TypeScript, Java, HCL, SQL

## Contact

London, UK. Open to Platform, DevOps, SRE and Cloud Engineering roles.

<!-- profile -->
