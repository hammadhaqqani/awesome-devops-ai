# Awesome DevOps AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI tools, agents, MCP servers, and resources for DevOps, SRE, and Platform Engineering.

The AI revolution is transforming how infrastructure is built, monitored, and operated. This list tracks every meaningful tool at the intersection of AI and DevOps, from coding agents that write Terraform to AI-powered incident response that pages you with a root cause already identified.

**Why this list?** Engineers are adopting AI tooling faster than any technology shift in history, but the landscape is fragmented across hundreds of repos, products, and frameworks. This is one place to find them all.

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
- [AI Agent Frameworks for Infrastructure](#ai-agent-frameworks-for-infrastructure)
- [System Prompt and Config Templates](#system-prompt-and-config-templates)
- [Learning Resources](#learning-resources)
- [Community and Newsletters](#community-and-newsletters)
- [Author](#author)

## AI Coding Agents for Infrastructure

AI-powered coding agents that help write, review, and maintain infrastructure code including Terraform, Kubernetes manifests, Dockerfiles, and CI/CD pipelines.

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - Anthropic's agentic coding tool that excels at large-scale Terraform refactoring, multi-file Kubernetes manifest generation, and infrastructure debugging.
- [Codex](https://openai.com/index/openai-codex/) - OpenAI's autonomous coding agent with cloud sandbox execution, strong at generating IaC from natural language descriptions.
- [Cursor](https://cursor.com) - AI-first IDE with inline Terraform and YAML completions and multi-file editing capabilities.
- [GitHub Copilot](https://github.com/features/copilot) - AI pair programmer integrated into VS Code, JetBrains, and CLI, with Copilot Workspace for multi-file infrastructure changes.
- [Cline](https://github.com/cline/cline) - Autonomous AI coding agent for VS Code that runs terminal commands, edits files, and handles complex infrastructure tasks.
- [Aider](https://github.com/aider-ai/aider) - Terminal-based AI pair programming that works with any LLM, great for infrastructure repos with git-commit-per-change workflows.
- [Continue](https://github.com/continuedev/continue) - Open-source AI code assistant for VS Code and JetBrains that supports custom models and local LLMs for air-gapped infrastructure work.
- [Amazon Q Developer](https://aws.amazon.com/q/developer/) - AWS-native AI assistant with deep CloudFormation, CDK, and AWS service knowledge.
- [Windsurf](https://codeium.com/windsurf) - AI IDE by Codeium with agentic Cascade mode for multi-step infrastructure tasks.

## AI-Powered Kubernetes

AI tools specifically designed for Kubernetes cluster management, troubleshooting, and operations.

- [K8sGPT](https://github.com/k8sgpt-ai/k8sgpt) - AI-powered Kubernetes troubleshooting and diagnostics, a CNCF Sandbox project that scans clusters for issues and explains them in plain English.
- [Kagent](https://github.com/kagent-dev/kagent) - CNCF Sandbox AI agent framework for DevOps and platform engineers to run agents inside Kubernetes clusters.
- [KAITO](https://github.com/kaito-project/kaito) - Kubernetes AI Toolchain Operator that simplifies LLM inference and fine-tuning workloads on clusters, a CNCF Sandbox project.
- [Robusta](https://github.com/robusta-dev/robusta) - Kubernetes monitoring and troubleshooting platform with AI root cause analysis and Holmes AI integration for automated diagnostics.
- [kubectl-ai](https://github.com/GoogleCloudPlatform/kubectl-ai) - Google Cloud kubectl plugin that uses LLMs to generate and apply Kubernetes manifests from natural language.
- [Kubernetes ChatGPT Bot](https://github.com/robusta-dev/kubernetes-chatgpt-bot) - ChatGPT integration for Kubernetes troubleshooting via Slack notifications.

## AI-Powered Terraform and IaC

Tools that bring AI capabilities to Infrastructure as Code workflows.

- [AWS Terraform MCP Server](https://awslabs.github.io/mcp/servers/terraform-mcp-server) - AWS MCP server with Terraform best practices, Checkov security scanning, and AWS provider documentation search.
- [Terraform Copilot Prompts](https://github.com/zloeber/terraform-copilot-prompts) - GitHub Copilot prompts for creating and converting Terraform configurations across cloud providers.
- [Pulumi AI](https://www.pulumi.com/ai/) - Generates Pulumi IaC programs from natural language using AI, supporting AWS, Azure, GCP, and Kubernetes.
- [Spacelift AI](https://spacelift.io/) - AI-enhanced IaC management platform with drift detection, policy-as-code, and automated remediation.
- [Infracost](https://github.com/infracost/infracost) - Cloud cost estimates for Terraform in pull requests, supporting 1,100+ AWS, Azure, and GCP resources.
- [Brainboard](https://www.brainboard.co/) - Visual Terraform designer with AI-powered architecture generation from cloud diagrams.

## AI Incident Response and Troubleshooting

AI systems that detect, investigate, and remediate production incidents.

- [HolmesGPT](https://github.com/HolmesGPT/holmesgpt) - Agentic AI troubleshooting for Kubernetes and cloud-native environments, a CNCF Sandbox project combining observability telemetry with LLM reasoning.
- [IncidentFox](https://github.com/incidentfox/incidentfox) - Open-source AI SRE platform for automated incident investigation, hypothesis formation, and fix suggestions with Slack and PagerDuty integration.
- [Tracecat](https://github.com/TracecatHQ/tracecat) - Open-source AI automation for security and reliability operations with 100+ integrations and sandboxed execution.
- [Rootly](https://rootly.com/) - AI-powered incident management with automated timelines, AI-generated postmortems, and Slack-native workflows.
- [Shoreline](https://shoreline.io/) - AI-powered incident automation that converts runbooks into automated remediation executing across fleets.
- [PagerDuty AIOps](https://www.pagerduty.com/platform/aiops/) - AI event correlation, noise reduction, and intelligent routing that reduces alert fatigue with ML-based grouping.
- [GitHub Agentic Workflows](https://github.github.io/gh-aw/) - Run AI agents in GitHub Actions for automated issue triage, CI failure analysis, and PR review.

## AI Monitoring and Observability

AI-enhanced monitoring, alerting, and observability platforms.

- [Grafana AI](https://grafana.com/products/cloud/ai-tools-for-observability/) - Built-in AI agents for observability including SRE agent for root cause analysis, adaptive telemetry for cost reduction, and AI-assisted query generation.
- [Grafana](https://github.com/grafana/grafana) - Open-source monitoring and observability platform that serves as the foundation for AI-powered monitoring workflows.
- [Metoro Guardian](https://metoro.io/) - AI observability copilot combining telemetry and code analysis for accurate root cause identification and auto-generated fix PRs.
- [Datadog Bits AI](https://www.datadoghq.com/product/platform/bits-ai/) - AI assistant for natural language metric queries, root cause analysis, and automated investigation across infrastructure.
- [New Relic AI](https://newrelic.com/platform/new-relic-ai) - AI monitoring assistant with natural language querying, anomaly explanation, and intelligent alert correlation.
- [Dynatrace Davis AI](https://www.dynatrace.com/platform/davis-ai/) - Causal AI engine for automated root cause analysis, impact assessment, and predictive problem detection.
- [Prometheus Operator](https://github.com/prometheus-operator/prometheus-operator) - Cloud-native monitoring foundation essential for AI-powered alerting pipelines, a CNCF project.

## AI Security Scanning

AI-powered security tools for infrastructure, containers, and supply chain.

- [Trivy](https://github.com/aquasecurity/trivy) - Comprehensive open-source vulnerability scanner for containers, IaC, Kubernetes, and code that is fast, accurate, and widely adopted.
- [Snyk](https://snyk.io/product/) - AI-powered security platform with DeepCode AI engine that scans code, containers, IaC, and AI-generated code in real-time.
- [MCP-Scan](https://labs.snyk.io/) - Open-source tool for analyzing Model Context Protocol security issues and auditing MCP servers for vulnerabilities.
- [Checkov](https://github.com/bridgecrewio/checkov) - Static analysis for IaC security that scans Terraform, CloudFormation, Kubernetes, Helm, and Dockerfile for misconfigurations.
- [tfsec](https://github.com/aquasecurity/tfsec) - Security scanner for Terraform code that checks for security misconfigurations and compliance violations.
- [Wiz](https://www.wiz.io/) - Cloud security platform that unifies vulnerability findings with cloud context to prioritize exploitable risks.
- [Falco](https://github.com/falcosecurity/falco) - CNCF graduated cloud-native runtime security project for threat detection in containers and Kubernetes.

## AI Cost Optimization

AI and automation tools for cloud cost management, FinOps, and resource optimization.

- [Kubecost](https://github.com/kubecost/kubecost) - Real-time Kubernetes cost monitoring by service, deployment, namespace, and container with cloud billing integration.
- [OpenCost](https://github.com/opencost/opencost) - CNCF Sandbox project for vendor-neutral, real-time Kubernetes cost monitoring and allocation.
- [CAST AI](https://cast.ai/) - AI-powered Kubernetes cost optimization with automated rightsizing, spot instance management, and cluster autoscaling.
- [Spot by NetApp](https://spot.io/) - AI-driven cloud infrastructure optimization using spot instances, autoscaling, and intelligent workload placement.
- [Vantage](https://www.vantage.sh/) - Cloud cost transparency platform with AI-powered recommendations across AWS, Azure, GCP, Kubernetes, and Datadog.

## MCP Servers for DevOps

Model Context Protocol servers that give AI assistants like Claude, ChatGPT, and Cursor access to DevOps tools and infrastructure.

- [MCP Reference Servers](https://github.com/modelcontextprotocol/servers) - Official MCP reference implementations including filesystem, Git, GitHub, PostgreSQL, Puppeteer, and more.
- [GitHub MCP Server](https://github.com/github/github-mcp-server) - Official GitHub MCP server for repos, issues, PRs, Actions, and code search from AI agents.
- [AWS MCP Servers](https://awslabs.github.io/mcp/) - Official AWS MCP server suite covering Terraform, CDK, CloudFormation, Lambda, S3, CloudWatch, ECS, and more.
- [Docker MCP Gateway](https://github.com/docker/mcp-gateway) - Docker-maintained MCP server for container management, image operations, and Docker Compose workflows.
- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) - Comprehensive curated list of all MCP servers across every category.
- [Kubernetes MCP Server](https://github.com/stevelacy/mcp-k8s) - MCP server for kubectl operations, pod management, and cluster introspection.

## AI-Powered CI/CD

AI tools that enhance continuous integration and delivery pipelines.

- [PR-Agent](https://github.com/qodo-ai/pr-agent) - AI-powered pull request analysis that auto-describes, reviews, improves, and generates tests for GitHub, GitLab, and Bitbucket.
- [GitLab Duo](https://about.gitlab.com/gitlab-duo/) - AI across the GitLab DevSecOps platform with code suggestions, root cause analysis, vulnerability resolution, and CI/CD pipeline generation.
- [Harness AIDA](https://www.harness.io/products/aida) - AI Development Assistant for intelligent pipeline creation, failure analysis, and deployment optimization.
- [ArgoCD](https://github.com/argoproj/argo-cd) - CNCF GitOps continuous delivery for Kubernetes that serves as the foundation for AI-driven deployment workflows.
- [Mergify](https://mergify.com/) - AI-powered merge queue and PR automation with intelligent batch merging and conflict resolution.

## AI Log Analysis and Debugging

AI tools for log analysis, pattern detection, and debugging production systems.

- [Elasticsearch](https://github.com/elastic/elasticsearch) - Foundation for AI-powered log analysis with ES|QL, vector search, and ML anomaly detection.
- [Grafana Loki](https://github.com/grafana/loki) - Log aggregation system designed for cloud-native environments that pairs with Grafana AI for intelligent log querying.
- [OpenTelemetry Collector](https://github.com/open-telemetry/opentelemetry-collector) - Vendor-agnostic telemetry collection that serves as the essential pipeline for feeding logs, metrics, and traces to AI analysis tools.
- [LogAI](https://github.com/salesforce/logai) - Salesforce's open-source toolkit for AI-powered log analysis with ML algorithms for anomaly detection, clustering, and summarization.
- [Zebrium](https://www.zebrium.com/) - ML-powered root cause analysis from logs that automatically identifies incident root cause without manual queries.

## AI Agent Frameworks for Infrastructure

General-purpose AI agent frameworks with strong infrastructure and DevOps use cases.

- [LangChain](https://github.com/langchain-ai/langchain) - Framework for building LLM-powered applications, widely used for building custom DevOps agents with tool integrations.
- [CrewAI](https://github.com/crewAIInc/crewAI) - Multi-agent orchestration framework for building teams of AI agents that handle complex infrastructure tasks like migration planning.
- [AutoGen](https://github.com/microsoft/autogen) - Microsoft's multi-agent framework supporting infrastructure workflows with tool use, code execution, and human-in-the-loop approvals.
- [n8n](https://github.com/n8n-io/n8n) - Workflow automation platform with 400+ integrations and AI agent capabilities for low-code DevOps automation.
- [Dify](https://github.com/langgenius/dify) - LLM application development platform with agent workflows, RAG, and model management for building custom DevOps chatbots.

## System Prompt and Config Templates

Ready-to-use AI agent configurations for infrastructure repositories.

- [Claude Code DevOps Toolkit](https://github.com/hammadhaqqani/claude-code-devops-toolkit) - Production-tested CLAUDE.md files, curated DevOps prompts, automation scripts, and project configs for infrastructure workflows.
- [Awesome CursorRules](https://github.com/PatrickJS/awesome-cursorrules) - Community-curated .cursorrules files for various project types including infrastructure and DevOps.
- [GitHub Copilot Custom Instructions](https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions) - Official guide for creating copilot-instructions.md to customize AI behavior per repository.
- [ChatGPT Prompts for DevOps](https://www.yourdevopsguy.com/chatgpt-prompts-for-devops/) - Community-curated prompt library for common DevOps automation tasks.
- [Free AI and DevOps Tools](https://hammadhaqqani.com/tools) - Collection of 41 free browser-based AI and DevOps tools including prompt builder, system prompt generator, and token counter.

## Learning Resources

Courses, certifications, articles, and guides on AI for DevOps.

### Articles and Guides

- [The AI Singularity Is Closer Than You Think](https://hammadhaqqani.com/blog/the-ai-singularity-is-closer-than-you-think) - First-hand account of how AI agents are replacing engineering workflows from a DevOps veteran with 10+ years of experience.
- [I Built 41 Free AI and DevOps Tools](https://hammadhaqqani.com/blog/41-free-ai-devops-tools-no-signup) - Deep dive into building client-side AI and DevOps tools that run entirely in the browser.
- [Top 15 AI Prompts Every DevOps Engineer Should Master](https://kubezilla.io/top-15-ai-prompts-every-devops-engineer-should-master-in-2026) - Essential prompt patterns for infrastructure automation.
- [HolmesGPT: Agentic Troubleshooting for Cloud Native](https://www.cncf.io/blog/2026/01/07/holmesgpt-agentic-troubleshooting-built-for-the-cloud-native-era/) - CNCF deep dive into AI-powered Kubernetes troubleshooting.
- [FinOps for AI Overview](https://www.finops.org/wg/finops-for-ai-overview/) - FinOps Foundation guide on managing AI workload costs in the cloud.

### Certifications

- [AWS AI Practitioner](https://aws.amazon.com/certification/certified-ai-practitioner/) - Foundational AI and ML certification with cloud infrastructure context.
- [Google Cloud Professional ML Engineer](https://cloud.google.com/learn/certification/machine-learning-engineer) - ML engineering certification focused on GCP infrastructure.
- [CKA and KCNA](https://www.cncf.io/certification/) - CNCF Kubernetes certifications that provide essential foundation before adding AI-powered Kubernetes tools.
- [Terraform Associate](https://www.hashicorp.com/certification/terraform-associate) - HashiCorp IaC certification providing prerequisite knowledge for AI-assisted Terraform workflows.

## Community and Newsletters

Communities, forums, and newsletters covering AI and DevOps.

- [r/devops](https://reddit.com/r/devops) - Reddit community with 780k+ members actively discussing AI tool adoption in DevOps workflows.
- [r/Kubernetes](https://reddit.com/r/kubernetes) - Reddit community with 260k+ members discussing K8sGPT, KAITO, and AI-powered cluster management.
- [r/Terraform](https://reddit.com/r/Terraform) - Active Reddit community discussing AI-assisted IaC and Terraform automation.
- [CNCF Slack](https://communityinviter.com/apps/cloud-native/cncf) - Cloud Native Computing Foundation community with channels for K8sGPT, HolmesGPT, and AI-native projects.
- [DevOps Weekly](https://www.devopsweekly.com/) - Weekly newsletter covering DevOps tooling and practices including AI adoption.
- [TLDR DevOps](https://tldr.tech/devops) - Daily DevOps newsletter with AI and automation coverage.
- [The New Stack](https://thenewstack.io/) - Publication covering cloud-native, Kubernetes, and AI infrastructure developments.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first. We especially welcome:

- New AI tools for DevOps workflows.
- Star count updates for listed tools.
- Corrections to descriptions or broken links.
- New categories as the ecosystem evolves.

## Author

**Hammad Haqqani** - DevOps Architect and Cloud Engineer

- Website: [hammadhaqqani.com](https://hammadhaqqani.com)
- LinkedIn: [linkedin.com/in/haqqani](https://www.linkedin.com/in/haqqani)
- GitHub: [github.com/hammadhaqqani](https://github.com/hammadhaqqani?tab=repositories)

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/hammadhaqqani)
