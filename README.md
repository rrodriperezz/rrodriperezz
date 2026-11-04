# Rodrigo Pérez · DevOps & Cloud Engineer

**I make AWS infrastructure safe, cheap and boring to run in production.** CI/CD, Kubernetes and security scanning for a national bank; AWS and infrastructure as code for 10+ companies.

AWS Certified Solutions Architect – Associate · Montevideo, Uruguay (UTC-3, overlaps US business hours)

## Track record

- **Leading DevOps adoption from scratch at Banco República (BROU),** Uruguay's largest bank: CI/CD, monitoring, security scanning and AI-assisted operations, in an environment where a bad deploy is not an option.
- **Cut static analysis findings from 565 to 167** by wiring code scanning into every commit and fixing real issues instead of muting alerts.
- **Took a critical deployment from 2-9 minutes down to about 1 minute,** measured against production logs.
- **3 years running AWS in production for 10+ clients at once** (EC2, S3, IAM, VPC, ELB, Auto Scaling, CloudWatch), on-call shifts included.

## Featured projects

- **[terraform-localstack-pipeline](https://github.com/rrodriperezz/terraform-localstack-pipeline):** serverless AWS event pipeline (EventBridge, SQS, Lambda, DynamoDB) in Terraform, with a dead-letter queue, alarms, least-privilege IAM and end-to-end tests against LocalStack. CI runs checkov, trivy and gitleaks.
- **[kubelab](https://github.com/rrodriperezz/kubelab):** production-style Kubernetes platform rebuilt from zero with one command: ingress-nginx, cert-manager, metrics-server and a hardened app, verified by a seven-check smoke test on every push.
- **[challenge-fullstack](https://github.com/rrodriperezz/challenge-fullstack):** React app deployed to AWS ECS Fargate behind an ALB, with VPC, ECR and per-environment Terraform.
- **[Deploy_K8s_Dockerfile_GithubActions](https://github.com/rrodriperezz/Deploy_K8s_Dockerfile_GithubActions):** FastAPI service tested inside its own Docker image and deployed to Kubernetes by GitHub Actions.
- **[stems-app](https://github.com/rrodriperezz/stems-app):** local GPU app that splits songs into stems with PyTorch models, with a FastAPI backend and a browser multitrack player.

## Stack

**Cloud & IaC:** AWS · Terraform · Ansible · LocalStack
**Containers:** Kubernetes · OpenShift · Docker · Helm · k3d
**CI/CD:** GitHub Actions · GitLab CI · Jenkins
**Security:** IAM least privilege · checkov · trivy · gitleaks · static code analysis
**Observability:** Prometheus · Grafana · CloudWatch
**Code:** Python · Bash · PowerShell
