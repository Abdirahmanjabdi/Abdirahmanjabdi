# Abdirahman Jama Abdi

**Platform, DevOps and SRE. London.**

Most learning repos show you the version that worked. Mine show what broke.

My first Terraform deploy failed silently. `terraform apply` succeeded, the instance was healthy,
the site was dead. The cause was one line near the top of a log I had been reading from the bottom.
That write-up is public, root cause and all, because the failure taught me more than the fix did.

Trading systems are the domain I keep coming back to. It's where infrastructure stops being
abstract, because latency, correctness and reliability aren't qualities there. They're the product.

---

## Infrastructure

**[Terraform](https://github.com/Abdirahmanjabdi/Terraform)**
WordPress and NGINX on AWS EC2, solved two ways. An imperative bash `user_data` script that raced
`unattended-upgrades` for the dpkg lock and lost, and a declarative cloud-init file that couldn't.
Both written up in full, including the six cascading errors that came from one root cause.

**[AWS](https://github.com/Abdirahmanjabdi/AWS)**
VPC networking, application load balancing, S3 with CloudFront, and a serverless API. Built from
scratch and documented with architecture diagrams.

**[livestock-ledger](https://github.com/Abdirahmanjabdi/livestock-ledger)**
The most complete build here. Ethereum contract with indexed PostgreSQL read models, Next.js
frontend, Prometheus and Grafana observability, Kubernetes manifests, Terraform, GitHub Actions CI.

**[docker-learning](https://github.com/Abdirahmanjabdi/docker-learning)**
Multi-stage builds, Compose, and an NGINX reverse proxy in front of a Python app.

Fundamentals:
[bash](https://github.com/Abdirahmanjabdi/devops-learning-bash) ·
[linux](https://github.com/Abdirahmanjabdi/devops-learning-linux) ·
[git](https://github.com/Abdirahmanjabdi/Git-labs)

## Trading systems

**[VFund](https://github.com/Abdirahmanjabdi/VFund)**
Open-source crypto quant research platform, built around not fooling yourself. Honest backtesting
through to live paper trading. 70 tests, CI on every push, MIT licensed.

**[AIRO / Sentinel Trading](https://github.com/Abdirahmanjabdi/AIRO)**
A behavioural risk engine for MetaTrader 5. Detects revenge entries, oversized positions and
drawdown pressure. It doesn't predict direction, it protects the trader from themselves.

Also:
[Market-Regime-Classifier](https://github.com/Abdirahmanjabdi/Market-Regime-Classifier) ·
[Risk-Engine](https://github.com/Abdirahmanjabdi/Risk-Engine) ·
[Execution-Simulator](https://github.com/Abdirahmanjabdi/Execution-Simulator) ·
[market-replay-engine](https://github.com/Abdirahmanjabdi/market-replay-engine) ·
[Trade-Ledger-Analytics-Engine](https://github.com/Abdirahmanjabdi/Trade-Ledger-Analytics-Engine)

## Stack

**Infrastructure** Terraform · AWS (EC2, VPC, ALB, S3, CloudFront, Lambda) · Docker · Kubernetes · cloud-init

**Observability and CI** Prometheus · Grafana · GitHub Actions

**Systems** Linux · Bash · NGINX · PostgreSQL

**Languages** Python · TypeScript · HCL · SQL · Java

---

London, UK. Open to Platform, DevOps, SRE and Cloud Engineering roles.

[LinkedIn](https://www.linkedin.com/in/abdirahman-jama-abdi-2a35a7305/)

