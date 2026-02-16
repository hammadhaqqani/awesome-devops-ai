# Awesome DevOps AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI tools, agents, MCP servers, and resources for DevOps, SRE, and Platform Engineering.

The AI revolution is transforming how infrastructure is built, monitored, and operated. This list tracks every meaningful tool at the intersection of AI and DevOps, from coding agents that write Terraform to AI-powered incident response that pages you with a root cause already identified.

**Why this list?** Engineers are adopting AI tooling faster than any technology shift in history, but the landscape is fragmented across hundreds of repos, products, and frameworks. This is one place to find them all.

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-ffdd00?style=flat&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/hammadhaqqani)

## Contents

- [AI Coding Agents for Infrastructure](#ai-coding-agents-for-infrastructure)
- [AI-Powered Kubernetes](#ai-powered-kubernetes)
- [AI-Powered Terraform and IaC](#ai-powered-terraform-and-iac)
- [AI Incident Response and Troubleshooting](#ai-incident-response-and-troubleshooting)
- [AI Monitoring and Observability](#ai-monitoring-and-observability)
- [AI Security Scanning](#ai-security-scanning)
- [AI Cost Optimization](#ai-cost-optimization)
- [MCP Servers for DevOps](#mcp-servers-for-devops)
- [AI-Powered CI/CD](#ai-powered-cicd)
- [AI Log Analysis and Debugging](#ai-log-analysis-and-debugging)
- [AI Prompt Collections for DevOps](#ai-prompt-collections-for-devops)
- [AI Agent Frameworks for Infrastructure](#ai-agent-frameworks-for-infrastructure)
- [System Prompt and Config Templates](#system-prompt-and-config-templates)
- [Learning Resources](#learning-resources)
- [Community and Newsletters](#community-and-newsletters)

---

## AI Coding Agents for Infrastructure

AI-powered coding agents that help write, review, and maintain infrastructure code including Terraform, Kubernetes manifests, Dockerfiles, and CI/CD pipelines.

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - Anthropic's agentic coding tool. Excels at large-scale Terraform refactoring, multi-file K8s manifest generation, and infrastructure debugging. `commercial` `cli`
- [OpenAI Codex](https://openai.com/index/openai-codex/) - OpenAI's autonomous coding agent with cloud sandbox execution. Strong at generating IaC from natural language descriptions. `commercial` `cli`
- [Cursor](https://cursor.com) - AI-first IDE with inline Terraform/YAML completions and multi-file editing. `commercial` `ide` ![Stars](https://img.shields.io/github/stars/getcursor/cursor?style=flat)
- [GitHub Copilot](https://github.com/features/copilot) - AI pair programmer integrated into VS Code, JetBrains, and CLI. Copilot Workspace handles multi-file infrastructure changes. `commercial` `ide` `cli`
- [Cline](https://github.com/cline/cline) - Autonomous AI coding agent for VS Code. Runs terminal commands, edits files, and handles complex infrastructure tasks autonomously. `open-source` ![Stars](https://img.shields.io/github/stars/cline/cline?style=flat)
- [Aider](https://github.com/aider-ai/aider) - Terminal-based AI pair programming. Works with any LLM. Great for infrastructure repos where you want git-commit-per-change workflows. `open-source` ![Stars](https://img.shields.io/github/stars/aider-ai/aider?style=flat)
- [Continue](https://github.com/continuedev/continue) - Open-source AI code assistant for VS Code and JetBrains. Supports custom models and local LLMs for air-gapped infrastructure work. `open-source` ![Stars](https://img.shields.io/github/stars/continuedev/continue?style=flat)
- [Amazon Q Developer](https://aws.amazon.com/q/developer/) - AWS-native AI assistant with deep CloudFormation, CDK, and AWS service knowledge. `commercial` `aws`
- [Windsurf](https://codeium.com/windsurf) - AI IDE by Codeium with agentic "Cascade" mode for multi-step infrastructure tasks. `commercial` `ide`

## AI-Powered Kubernetes

AI tools specifically designed for Kubernetes cluster management, troubleshooting, and operations.

- [K8sGPT](https://github.com/k8sgpt-ai/k8sgpt) - AI-powered Kubernetes troubleshooting and diagnostics. CNCF Sandbox project. Scans clusters for issues and explains them in plain English. `open-source` `cncf` ![Stars](https://img.shields.io/github/stars/k8sgpt-ai/k8sgpt?style=flat)
- [Kagent](https://github.com/kagent-dev/kagent) - AI agent framework for DevOps and platform engineers to run agents inside Kubernetes. CNCF Sandbox. `open-source` `cncf` ![Stars](https://img.shields.io/github/stars/kagent-dev/kagent?style=flat)
- [KAITO](https://github.com/azure/kaito) - Kubernetes AI Toolchain Operator. Simplifies LLM inference and fine-tuning workloads on K8s. CNCF Sandbox. `open-source` `cncf` ![Stars](https://img.shields.io/github/stars/azure/kaito?style=flat)
- [Robusta](https://github.com/robusta-dev/robusta) - Kubernetes monitoring and troubleshooting platform with AI root cause analysis. Holmes AI integration for automated diagnostics. `open-source` ![Stars](https://img.shields.io/github/stars/robusta-dev/robusta?style=flat)
- [kubectl-ai](https://github.com/GoogleCloudPlatform/kubectl-ai) - kubectl plugin that uses LLMs to generate and apply Kubernetes manifests from natural language. `open-source` `google`
- [Kubernetes ChatGPT Bot](https://github.com/robusta-dev/kubernetes-chatgpt-bot) - ChatGPT integration for Kubernetes troubleshooting via Slack. `open-source`

## AI-Powered Terraform and IaC

Tools that bring AI capabilities to Infrastructure as Code workflows.

- [AWS Terraform MCP Server](https://github.com/awslabs/mcp) - Official AWS MCP servers including Terraform best practices, Checkov security scanning, and AWS provider docs. `open-source` `aws` ![Stars](https://img.shields.io/github/stars/awslabs/mcp?style=flat)
- [Terraform Copilot Prompts](https://github.com/zloeber/terraform-copilot-prompts) - GitHub Copilot prompts for creating and converting Terraform configurations across cloud providers. `open-source`
- [Pulumi AI](https://www.pulumi.com/ai/) - Generate Pulumi IaC programs from natural language using AI. Supports AWS, Azure, GCP, and Kubernetes. `commercial`
- [Spacelift AI](https://spacelift.io/) - AI-enhanced IaC management platform with drift detection, policy-as-code, and automated remediation. `commercial`
- [Infracost](https://github.com/infracost/infracost) - Cloud cost estimates for Terraform. Not AI itself, but essential for AI-generated IaC cost validation. `open-source` ![Stars](https://img.shields.io/github/stars/infracost/infracost?style=flat)
- [Brainboard](https://www.brainboard.co/) - Visual Terraform designer with AI-powered architecture generation from diagrams. `commercial`

## AI Incident Response and Troubleshooting

AI systems that detect, investigate, and remediate production incidents.

- [HolmesGPT](https://github.com/robusta-dev/holmesgpt) - Agentic AI troubleshooting for Kubernetes and cloud-native environments. CNCF Sandbox. Combines observability telemetry with LLM reasoning. `open-source` `cncf` ![Stars](https://img.shields.io/github/stars/robusta-dev/holmesgpt?style=flat)
- [IncidentFox](https://github.com/incidentfox/incidentfox) - Open-source AI SRE platform. Automated incident investigation, hypothesis formation, and fix suggestions. Slack-native with PagerDuty integration. `open-source` ![Stars](https://img.shields.io/github/stars/incidentfox/incidentfox?style=flat)
- [Tracecat](https://github.com/TracecatHQ/tracecat) - Open-source AI automation for security and reliability operations. 100+ integrations, sandboxed execution, AI agents for investigation. `open-source`
- [Rootly](https://rootly.com/) - AI-powered incident management with automated timelines, AI-generated postmortems, and Slack-native workflows. `commercial`
- [Shoreline](https://shoreline.io/) - AI-powered incident automation. Converts runbooks into automated remediation that executes across fleets. `commercial`
- [PagerDuty AIOps](https://www.pagerduty.com/platform/aiops/) - AI event correlation, noise reduction, and intelligent routing. Reduces alert fatigue with ML-based grouping. `commercial`
- [GitHub Agentic Workflows](https://github.github.io/gh-aw/) - Run AI agents (Copilot, Claude, Codex) in GitHub Actions for automated issue triage, CI failure analysis, and PR review. `open-source` `github`

## AI Monitoring and Observability

AI-enhanced monitoring, alerting, and observability platforms.

- [Grafana AI](https://grafana.com/products/cloud/ai-tools-for-observability/) - Built-in AI agents for observability: SRE agent for root cause analysis via knowledge graphs, adaptive telemetry for 35-50% cost reduction, AI-assisted query generation. `commercial` `open-core`
- [Grafana](https://github.com/grafana/grafana) - Open-source monitoring and observability platform. Foundation for AI-powered monitoring workflows. `open-source` ![Stars](https://img.shields.io/github/stars/grafana/grafana?style=flat)
- [Metoro Guardian](https://metoro.io/) - AI observability copilot combining telemetry and code analysis for accurate root cause identification. Auto-generates fix PRs. `commercial`
- [Datadog AI](https://www.datadoghq.com/product/platform/bits-ai/) - Bits AI assistant for natural language metric queries, root cause analysis, and automated investigation across infrastructure. `commercial`
- [New Relic AI](https://newrelic.com/platform/new-relic-ai) - AI monitoring assistant with natural language querying, anomaly explanation, and intelligent alert correlation. `commercial`
- [Dynatrace Davis AI](https://www.dynatrace.com/platform/davis-ai/) - Causal AI engine for automated root cause analysis, impact assessment, and predictive problem detection. `commercial`
- [Prometheus](https://github.com/prometheus-operator/prometheus-operator) - Cloud-native monitoring foundation. Essential for AI-powered alerting pipelines. `open-source` `cncf` ![Stars](https://img.shields.io/github/stars/prometheus-operator/prometheus-operator?style=flat)

## AI Security Scanning

AI-powered security tools for infrastructure, containers, and supply chain.

- [Trivy](https://github.com/aquasecurity/trivy) - Comprehensive open-source vulnerability scanner for containers, IaC, Kubernetes, and code. Fast, accurate, and widely adopted. `open-source` ![Stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=flat)
- [Snyk AI](https://snyk.io/product/) - AI-powered security platform with DeepCode AI engine. Scans code, containers, IaC, and AI-generated code in real-time. `commercial` ![Stars](https://img.shields.io/github/stars/snyk/cli?style=flat)
- [MCP-Scan](https://labs.snyk.io/) - Snyk's open-source tool for analyzing Model Context Protocol security issues. Audits MCP servers for vulnerabilities. `open-source`
- [Checkov](https://github.com/bridgecrewio/checkov) - Static analysis for IaC security. Scans Terraform, CloudFormation, Kubernetes, Helm, and Dockerfile for misconfigurations. `open-source`
- [tfsec](https://github.com/aquasecurity/tfsec) - Security scanner for Terraform code. Checks for security misconfigurations and compliance violations. `open-source`
- [Wiz](https://www.wiz.io/) - Cloud security platform that unifies vulnerability findings with cloud context to prioritize exploitable risks. `commercial`
- [Falco](https://github.com/falcosecurity/falco) - Cloud-native runtime security. CNCF graduated project for threat detection in containers and Kubernetes. `open-source` `cncf`

## AI Cost Optimization

AI and automation tools for cloud cost management, FinOps, and resource optimization.

- [Infracost](https://github.com/infracost/infracost) - Cloud cost estimates for Terraform in pull requests. Supports 1,100+ AWS, Azure, and GCP resources. `open-source` ![Stars](https://img.shields.io/github/stars/infracost/infracost?style=flat)
- [Kubecost](https://github.com/kubecost/cost-analyzer-helm-chart) - Real-time Kubernetes cost monitoring by service, deployment, namespace, and container. `open-source` ![Stars](https://img.shields.io/github/stars/kubecost/cost-analyzer-helm-chart?style=flat)
- [OpenCost](https://github.com/opencost/opencost) - CNCF Sandbox project for Kubernetes cost monitoring. Vendor-neutral, real-time cost allocation. `open-source` `cncf`
- [CAST AI](https://cast.ai/) - AI-powered Kubernetes cost optimization with automated rightsizing, spot instance management, and cluster autoscaling. `commercial`
- [Spot by NetApp](https://spot.io/) - AI-driven cloud infrastructure optimization using spot instances, autoscaling, and intelligent workload placement. `commercial`
- [Vantage](https://www.vantage.sh/) - Cloud cost transparency platform with AI-powered recommendations across AWS, Azure, GCP, Kubernetes, and Datadog. `commercial`

## MCP Servers for DevOps

Model Context Protocol (MCP) servers that give AI assistants (Claude, ChatGPT, Cursor) access to DevOps tools and infrastructure.

- [MCP Reference Servers](https://github.com/modelcontextprotocol/servers) - Official MCP reference implementations including filesystem, Git, GitHub, Postgres, Puppeteer, and more. `open-source` ![Stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=flat)
- [GitHub MCP Server](https://github.com/github/github-mcp-server) - Official GitHub MCP server for repos, issues, PRs, Actions, and code search from AI agents. `open-source` ![Stars](https://img.shields.io/github/stars/github/github-mcp-server?style=flat)
- [AWS MCP Servers](https://github.com/awslabs/mcp) - Official AWS MCP server suite: Terraform, CDK, CloudFormation, Lambda, S3, CloudWatch, ECS, and more. `open-source` `aws` ![Stars](https://img.shields.io/github/stars/awslabs/mcp?style=flat)
- [Docker MCP Server](https://github.com/docker/docker-mcp) - Docker-maintained MCP server for container management, image operations, and Docker Compose. `open-source` ![Stars](https://img.shields.io/github/stars/docker/docker-mcp?style=flat)
- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) - Comprehensive curated list of all MCP servers across every category. `awesome-list` ![Stars](https://img.shields.io/github/stars/punkpeye/awesome-mcp-servers?style=flat)
- [Kubernetes MCP Server](https://github.com/stevelacy/mcp-k8s) - MCP server for kubectl operations, pod management, and cluster introspection. `open-source`

## AI-Powered CI/CD

AI tools that enhance continuous integration and delivery pipelines.

- [GitHub Agentic Workflows](https://github.github.io/gh-aw/) - Run AI agents (Copilot, Claude, Codex) inside GitHub Actions. Automates issue triage, CI failure analysis, docs maintenance. `open-source` `github`
- [PR-Agent](https://github.com/Codium-ai/pr-agent) - AI-powered pull request analysis: auto-describe, review, improve, and generate tests. Works with GitHub, GitLab, and Bitbucket. `open-source` ![Stars](https://img.shields.io/github/stars/Codium-ai/pr-agent?style=flat)
- [GitLab Duo](https://about.gitlab.com/gitlab-duo/) - AI across the GitLab DevSecOps platform: code suggestions, root cause analysis, vulnerability resolution, and CI/CD pipeline generation. `commercial`
- [Harness AI](https://www.harness.io/products/aida) - AIDA (AI Development Assistant) for intelligent pipeline creation, failure analysis, and deployment optimization. `commercial` ![Stars](https://img.shields.io/github/stars/harness/harness?style=flat)
- [ArgoCD](https://github.com/argoproj/argo-cd) - GitOps continuous delivery for Kubernetes. Foundation for AI-driven deployment workflows. `open-source` `cncf` ![Stars](https://img.shields.io/github/stars/argoproj/argo-cd?style=flat)
- [Mergify](https://mergify.com/) - AI-powered merge queue and PR automation. Intelligent batch merging and conflict resolution. `commercial`

## AI Log Analysis and Debugging

AI tools for log analysis, pattern detection, and debugging production systems.

- [Elasticsearch](https://github.com/elastic/elasticsearch) - Foundation for AI-powered log analysis. ES|QL, vector search, and ML anomaly detection. `open-source` ![Stars](https://img.shields.io/github/stars/elastic/elasticsearch?style=flat)
- [Grafana Loki](https://github.com/grafana/loki) - Log aggregation system designed for cloud-native environments. Pairs with Grafana AI for intelligent log querying. `open-source` ![Stars](https://img.shields.io/github/stars/grafana/loki?style=flat)
- [OpenTelemetry Collector](https://github.com/open-telemetry/opentelemetry-collector) - Vendor-agnostic telemetry collection. Essential pipeline for feeding logs, metrics, and traces to AI analysis tools. `open-source` `cncf` ![Stars](https://img.shields.io/github/stars/open-telemetry/opentelemetry-collector?style=flat)
- [LogAI](https://github.com/salesforce/logai) - Salesforce's open-source toolkit for AI-powered log analysis. ML algorithms for anomaly detection, clustering, and summarization. `open-source`
- [Zebrium](https://www.zebrium.com/) - ML-powered root cause analysis from logs. Automatically identifies incident root cause without manual queries. `commercial`

## AI Prompt Collections for DevOps

Curated prompt libraries specifically designed for DevOps and infrastructure workflows.

- [Claude Code DevOps Toolkit](https://github.com/hammadhaqqani/claude-code-devops-toolkit) - CLAUDE.md templates, curated DevOps prompts, automation scripts, and project configs for Claude Code workflows. `open-source`
- [Terraform Copilot Prompts](https://github.com/zloeber/terraform-copilot-prompts) - GitHub Copilot prompts for Terraform configuration generation and cloud provider conversion. `open-source`
- [Free AI & DevOps Tools](https://hammadhaqqani.com/tools) - 41 free browser-based AI and DevOps tools including prompt builder, system prompt generator, token counter, and more. `free` `web`
- [ChatGPT Prompts for DevOps](https://www.yourdevopsguy.com/chatgpt-prompts-for-devops/) - Community-curated prompts for common DevOps tasks. `free`

## AI Agent Frameworks for Infrastructure

General-purpose AI agent frameworks with strong infrastructure and DevOps use cases.

- [LangChain](https://github.com/langchain-ai/langchain) - Framework for building LLM-powered applications. Used for building custom DevOps agents with tool integrations. `open-source` ![Stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=flat)
- [CrewAI](https://github.com/crewAIInc/crewAI) - Multi-agent orchestration framework. Build teams of AI agents for complex infrastructure tasks like migration planning or incident response. `open-source` ![Stars](https://img.shields.io/github/stars/crewAIInc/crewAI?style=flat)
- [AutoGen](https://github.com/microsoft/autogen) - Microsoft's multi-agent framework. Supports infrastructure workflows with tool use, code execution, and human-in-the-loop approvals. `open-source` ![Stars](https://img.shields.io/github/stars/microsoft/autogen?style=flat)
- [n8n](https://github.com/n8n-io/n8n) - Workflow automation with 400+ integrations and AI agent capabilities. Low-code DevOps automation with LLM nodes. `open-source`
- [Dify](https://github.com/langgenius/dify) - LLM application development platform with agent workflows, RAG, and model management. Build custom DevOps chatbots and agents. `open-source`

## System Prompt and Config Templates

Ready-to-use AI agent configurations for infrastructure repositories.

- [CLAUDE.md Templates](https://github.com/hammadhaqqani/claude-code-devops-toolkit) - Production-tested CLAUDE.md files for Terraform repos, Kubernetes projects, CI/CD pipelines, and Python infrastructure tools. `open-source`
- [Awesome CursorRules](https://github.com/PatrickJS/awesome-cursorrules) - Community-curated .cursorrules files for various project types including infrastructure and DevOps. `awesome-list`
- [GitHub Copilot Instructions](https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions) - Official guide for creating .github/copilot-instructions.md to customize AI behavior per repository. `docs`
- [Codex Project Config](https://openai.com/index/openai-codex/) - Configuration guide for Codex autonomous agent, including sandbox permissions, environment setup, and project-specific instructions. `docs`

## Learning Resources

Courses, certifications, articles, and guides on AI for DevOps.

### Articles and Guides

- [The AI Singularity Is Closer Than You Think](https://hammadhaqqani.com/blog/the-ai-singularity-is-closer-than-you-think) - First-hand account of how AI agents are replacing engineering workflows from a 10+ year DevOps veteran.
- [I Built 41 Free AI and DevOps Tools](https://hammadhaqqani.com/blog/41-free-ai-devops-tools-no-signup) - Deep dive into building client-side AI and DevOps tools that run entirely in the browser.
- [Top 15 AI Prompts Every DevOps Engineer Should Master](https://kubezilla.io/top-15-ai-prompts-every-devops-engineer-should-master-in-2026) - Essential prompt patterns for infrastructure automation.
- [HolmesGPT: Agentic Troubleshooting for Cloud Native](https://www.cncf.io/blog/2026/01/07/holmesgpt-agentic-troubleshooting-built-for-the-cloud-native-era/) - CNCF deep dive into AI-powered Kubernetes troubleshooting.
- [FinOps for AI Overview](https://www.finops.org/wg/finops-for-ai-overview/) - FinOps Foundation guide on managing AI workload costs in the cloud.

### Certifications

- [AWS AI Practitioner](https://aws.amazon.com/certification/certified-ai-practitioner/) - Foundational AI/ML certification with cloud infrastructure context.
- [Google Cloud Professional ML Engineer](https://cloud.google.com/learn/certification/machine-learning-engineer) - ML engineering on GCP infrastructure.
- [CKA + KCNA](https://www.cncf.io/certification/) - CNCF Kubernetes certifications. Essential foundation before adding AI-powered K8s tools.
- [Terraform Associate](https://www.hashicorp.com/certification/terraform-associate) - HashiCorp IaC certification. Prerequisite knowledge for AI-assisted Terraform workflows.

## Community and Newsletters

Communities, forums, and newsletters covering AI + DevOps.

- [r/devops](https://reddit.com/r/devops) - 780k+ members. Active discussions on AI tool adoption in DevOps workflows. `reddit`
- [r/kubernetes](https://reddit.com/r/kubernetes) - 260k+ members. K8sGPT, KAITO, and AI-powered cluster management discussions. `reddit`
- [r/Terraform](https://reddit.com/r/Terraform) - Active community discussing AI-assisted IaC and Terraform automation. `reddit`
- [CNCF Slack](https://communityinviter.com/apps/cloud-native/cncf) - Cloud Native Computing Foundation community. Channels for K8sGPT, HolmesGPT, and AI-native projects. `slack`
- [DevOps Weekly](https://www.devopsweekly.com/) - Weekly newsletter covering DevOps tooling and practices including AI adoption. `newsletter`
- [TLDR DevOps](https://tldr.tech/devops) - Daily DevOps newsletter with AI and automation coverage. `newsletter`
- [The New Stack](https://thenewstack.io/) - Publication covering cloud-native, Kubernetes, and AI infrastructure developments. `publication`

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first. We especially welcome:

- New AI tools for DevOps workflows
- Star count updates for listed tools
- Corrections to descriptions or broken links
- New categories as the ecosystem evolves

## Author

**Hammad Haqqani** - DevOps Architect & Cloud Engineer

- Website: [hammadhaqqani.com](https://hammadhaqqani.com)
- Free AI & DevOps Tools: [hammadhaqqani.com/tools](https://hammadhaqqani.com/tools)
- LinkedIn: [linkedin.com/in/haqqani](https://www.linkedin.com/in/haqqani)
- X/Twitter: [@hammadhaqqani](https://x.com/hammadhaqqani)
- GitHub: [github.com/hammadhaqqani](https://github.com/hammadhaqqani?tab=repositories)

---

## Support

If you find this list useful, consider giving it a star and buying me a coffee!

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/hammadhaqqani)
