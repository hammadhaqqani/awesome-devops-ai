# AI DevOps Quick Start Guide

Not sure where to start? This guide maps the landscape and recommends tools by role.

## AI DevOps Landscape at a Glance

| Layer                    | Open Source                       | Commercial                       | CNCF Projects         |
| ------------------------ | --------------------------------- | -------------------------------- | --------------------- |
| **Coding Agents**        | Aider, Cline, Continue            | Claude Code, Cursor, Copilot     | -                     |
| **Kubernetes**           | K8sGPT, kubectl-ai, Headlamp     | Komodor, Robusta                 | K8sGPT, Kagent, KAITO |
| **IaC and Terraform**    | OpenTofu, Infracost, Checkov      | Spacelift, Env0, Firefly         | -                     |
| **Incident Response**    | HolmesGPT, IncidentFox, OpenSRE  | AWS DevOps Agent, PagerDuty SRE Agent, Rootly | HolmesGPT             |
| **Monitoring**           | Grafana, Prometheus               | Datadog, Dynatrace, Splunk       | Prometheus            |
| **Security**             | Trivy, Falco, Checkov, Semgrep    | Snyk, Wiz, Prisma Cloud          | Falco                 |
| **Cost and FinOps**      | OpenCost, Kubecost                | CAST AI, Vantage, CloudZero      | OpenCost              |
| **MCP Servers**          | MCP Reference, Kubernetes MCP     | AWS MCP, GitHub MCP              | -                     |
| **CI/CD**                | ArgoCD, Tekton, Dagger            | GitLab Duo, Harness              | ArgoCD, Tekton        |
| **Platform Engineering** | Backstage, Kratix                 | Port, Humanitec, Cortex          | Backstage             |
| **GitOps**               | Flux, Kustomize, Helm             | Weave GitOps, Codefresh          | Flux, Helm            |
| **Chaos Engineering**    | Chaos Mesh, Litmus                | Gremlin, Steadybit               | Chaos Mesh, Litmus    |

## Quick Start by Role

### DevOps Engineer Starting with AI

1. **Daily IaC work**: Start with [Claude Code](https://code.claude.com/docs) or [GitHub Copilot](https://github.com/features/copilot) for writing Terraform, Kubernetes manifests, and Dockerfiles.
2. **Cluster troubleshooting**: Add [K8sGPT](https://github.com/k8sgpt-ai/k8sgpt) to scan clusters and explain issues in plain English.
3. **Cost visibility**: Use [Infracost](https://github.com/infracost/infracost) for cost estimates in Terraform PRs.

### SRE Focused on Reliability

1. **Incident investigation**: [HolmesGPT](https://github.com/HolmesGPT/holmesgpt) combines observability telemetry with LLM reasoning for root cause analysis.
2. **Observability**: [Grafana Assistant](https://grafana.com/products/cloud/ai-observability/) provides AI-assisted query generation, dashboards, and investigations in Grafana Cloud.
3. **Resilience testing**: [Chaos Mesh](https://github.com/chaos-mesh/chaos-mesh) for fault injection in Kubernetes.
4. **Autonomous operations**: [AWS DevOps Agent](https://aws.amazon.com/devops-agent/) or [Azure SRE Agent](https://azure.microsoft.com/en-us/products/sre-agent) as always-on ops teammates that investigate and remediate with approval gates.

### Platform Engineer Building Self-Service

1. **Developer portal**: [Backstage](https://github.com/backstage/backstage) for service catalogs and templates.
2. **GitOps delivery**: [ArgoCD](https://github.com/argoproj/argo-cd) for continuous deployment to Kubernetes.
3. **Continuous reconciliation**: [Flux](https://github.com/fluxcd/flux2) for automated image updates and Helm releases.

### Security Engineer

1. **Vulnerability scanning**: [Trivy](https://github.com/aquasecurity/trivy) for containers, IaC, and code.
2. **Runtime security**: [Falco](https://github.com/falcosecurity/falco) for threat detection in containers.
3. **Supply chain**: [Docker Scout](https://docs.docker.com/scout/) for image analysis and CVE remediation.

### FinOps and Cost Optimization

1. **Kubernetes costs**: [OpenCost](https://github.com/opencost/opencost) for vendor-neutral cost monitoring.
2. **Terraform costs**: [Infracost](https://github.com/infracost/infracost) for cost estimates in pull requests.
3. **Multi-cloud visibility**: [Vantage](https://www.vantage.sh/) for recommendations across cloud providers.

### Building AI Agents for Infrastructure

1. **Agent framework**: [LangChain](https://github.com/langchain-ai/langchain) or [CrewAI](https://github.com/crewAIInc/crewAI) for building custom DevOps agents, or [Kagent](https://github.com/kagent-dev/kagent) for Kubernetes-native agents.
2. **Tool integrations**: Explore [MCP Servers](https://github.com/modelcontextprotocol/servers) for connecting AI to infrastructure tools.
3. **Orchestration**: [Temporal](https://github.com/temporalio/temporal) for durable execution of long-running workflows.
