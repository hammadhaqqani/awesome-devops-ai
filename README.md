# Awesome DevOps AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Awesome Lint](https://github.com/hammadhaqqani/awesome-devops-ai/actions/workflows/awesome-lint.yml/badge.svg?branch=main)](https://github.com/hammadhaqqani/awesome-devops-ai/actions/workflows/awesome-lint.yml)
[![Link Check](https://github.com/hammadhaqqani/awesome-devops-ai/actions/workflows/link-check.yml/badge.svg?branch=main)](https://github.com/hammadhaqqani/awesome-devops-ai/actions/workflows/link-check.yml)
[![GitHub Pages](https://github.com/hammadhaqqani/awesome-devops-ai/actions/workflows/pages.yml/badge.svg?branch=main)](https://hammadhaqqani.github.io/awesome-devops-ai/)
[![GitHub stars](https://img.shields.io/github/stars/hammadhaqqani/awesome-devops-ai?style=social)](https://github.com/hammadhaqqani/awesome-devops-ai/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/hammadhaqqani/awesome-devops-ai?style=social)](https://github.com/hammadhaqqani/awesome-devops-ai/network/members)

> A curated list of AI tools, agents, MCP servers, and resources for DevOps, SRE, and Platform Engineering.

The AI revolution is transforming how infrastructure is built, monitored, and operated. This list tracks every meaningful tool at the intersection of AI and DevOps, from coding agents that write Terraform to AI-powered incident response that pages you with a root cause already identified.

**Why this list?** Engineers are adopting AI tooling faster than any technology shift in history, but the landscape is fragmented across hundreds of repos, products, and frameworks. This is one place to find them all.

**218 tools** across **20 categories** — updated March 2026.

If this list is useful, please give it a star to help others find it.

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
- [AI for Platform Engineering](#ai-for-platform-engineering)
- [AI for Database Operations](#ai-for-database-operations)
- [AI for Networking and Service Mesh](#ai-for-networking-and-service-mesh)
- [AI for Container Security and Supply Chain](#ai-for-container-security-and-supply-chain)
- [AI for Chaos Engineering and Reliability](#ai-for-chaos-engineering-and-reliability)
- [AI for Cloud Migration and Modernization](#ai-for-cloud-migration-and-modernization)
- [AI for GitOps](#ai-for-gitops)
- [System Prompt and Config Templates](#system-prompt-and-config-templates)
- [Learning Resources](#learning-resources)
- [Community and Newsletters](#community-and-newsletters)
- [Author](#author)
- [Support](#support)

## AI Coding Agents for Infrastructure

AI-powered coding agents that help write, review, and maintain infrastructure code including Terraform, Kubernetes manifests, Dockerfiles, and CI/CD pipelines.

- [Aider](https://github.com/aider-ai/aider) - Terminal-based AI pair programming that works with any LLM, great for infrastructure repos with git-commit-per-change workflows.
- [Amazon Q Developer](https://aws.amazon.com/q/developer/) - AWS-native AI assistant with deep CloudFormation, CDK, and AWS service knowledge.
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - Anthropic's agentic coding tool that excels at large-scale Terraform refactoring, multi-file Kubernetes manifest generation, and infrastructure debugging.
- [Cline](https://github.com/cline/cline) - Autonomous AI coding agent for VS Code that runs terminal commands, edits files, and handles complex infrastructure tasks.
- [Codex](https://openai.com/index/openai-codex/) - OpenAI's autonomous coding agent with cloud sandbox execution, strong at generating IaC from natural language descriptions.
- [Continue](https://github.com/continuedev/continue) - Open-source AI code assistant for VS Code and JetBrains that supports custom models and local LLMs for air-gapped infrastructure work.
- [Cursor](https://cursor.com) - AI-first IDE with inline Terraform and YAML completions and multi-file editing capabilities.
- [Devin](https://devin.ai/) - Autonomous AI software engineer by Cognition that can independently handle full infrastructure workflows from planning to deployment.
- [GitHub Copilot](https://github.com/features/copilot) - AI pair programmer integrated into VS Code, JetBrains, and CLI, with Copilot Workspace for multi-file infrastructure changes.
- [JetBrains AI](https://www.jetbrains.com/ai/) - AI assistant built into IntelliJ-based IDEs with context-aware infrastructure code completions and explanations.
- [Replit Agent](https://replit.com/ai) - AI agent that builds and deploys full-stack applications from natural language, useful for rapid prototyping of infrastructure dashboards.
- [Sourcegraph Cody](https://sourcegraph.com/cody) - AI coding assistant with full codebase context, ideal for navigating large monorepos with shared infrastructure modules.
- [Tabnine](https://www.tabnine.com/) - AI code completion that runs locally or in the cloud with enterprise-grade privacy for sensitive infrastructure code.
- [Windsurf](https://codeium.com/windsurf) - AI IDE by Codeium with agentic Cascade mode for multi-step infrastructure tasks.
- [Zed AI](https://zed.dev/) - High-performance editor with built-in AI assistant, inline generation, and terminal integration for infrastructure workflows.

## AI-Powered Kubernetes

AI tools specifically designed for Kubernetes cluster management, troubleshooting, and operations.

- [Glasskube](https://github.com/glasskube/glasskube) - Open-source Kubernetes package manager with AI-assisted package discovery and dependency resolution.
- [Headlamp](https://github.com/headlamp-k8s/headlamp) - Extensible Kubernetes web UI with plugin architecture that supports AI-powered cluster visualization and management.
- [K8sGPT](https://github.com/k8sgpt-ai/k8sgpt) - AI-powered Kubernetes troubleshooting and diagnostics, a CNCF Sandbox project that scans clusters for issues and explains them in plain English.
- [Kagent](https://github.com/kagent-dev/kagent) - CNCF Sandbox AI agent framework for DevOps and platform engineers to run agents inside Kubernetes clusters.
- [KAITO](https://github.com/kaito-project/kaito) - Kubernetes AI Toolchain Operator that simplifies LLM inference and fine-tuning workloads on clusters, a CNCF Sandbox project.
- [Komodor](https://komodor.com/) - Kubernetes troubleshooting platform with AI-driven root cause analysis, change tracking, and automated remediation workflows.
- [kubectl-ai](https://github.com/GoogleCloudPlatform/kubectl-ai) - Google Cloud kubectl plugin that uses LLMs to generate and apply Kubernetes manifests from natural language.
- [Kubernetes ChatGPT Bot](https://github.com/robusta-dev/kubernetes-chatgpt-bot) - ChatGPT integration for Kubernetes troubleshooting via Slack notifications.
- [Kubeshark](https://github.com/kubeshark/kubeshark) - API traffic analyzer for Kubernetes providing real-time visibility into cluster network traffic for AI-powered anomaly detection.
- [Robusta](https://github.com/robusta-dev/robusta) - Kubernetes monitoring and troubleshooting platform with AI root cause analysis and Holmes AI integration for automated diagnostics.
- [vCluster](https://github.com/loft-sh/vcluster) - Virtual Kubernetes clusters for development and testing that enable isolated AI workload experimentation.

## AI-Powered Terraform and IaC

Tools that bring AI capabilities to Infrastructure as Code workflows.

- [Atmos](https://github.com/cloudposse/atmos) - Universal tool for DevOps workflows that provides a framework for managing Terraform configurations at scale with AI-assisted component discovery.
- [AWS Terraform MCP Server](https://awslabs.github.io/mcp/servers/terraform-mcp-server) - AWS MCP server with Terraform best practices, Checkov security scanning, and AWS provider documentation search.
- [Brainboard](https://www.brainboard.co/) - Visual Terraform designer with AI-powered architecture generation from cloud diagrams.
- [Env0](https://www.env0.com/) - Self-service infrastructure platform with AI-assisted policy enforcement, cost estimation, and drift detection for Terraform.
- [Firefly](https://www.firefly.ai/) - Cloud asset management that uses AI to detect drift, generate Terraform from existing resources, and manage IaC coverage gaps.
- [Infracost](https://github.com/infracost/infracost) - Cloud cost estimates for Terraform in pull requests, supporting 1,100+ AWS, Azure, and GCP resources.
- [OpenTofu](https://github.com/opentofu/opentofu) - Open-source Terraform fork maintained by the Linux Foundation, the community-driven foundation for AI-enhanced IaC workflows.
- [Pulumi AI](https://www.pulumi.com/ai/) - Generates Pulumi IaC programs from natural language using AI, supporting AWS, Azure, GCP, and Kubernetes.
- [Spacelift AI](https://spacelift.io/) - AI-enhanced IaC management platform with drift detection, policy-as-code, and automated remediation.
- [Terraform Copilot Prompts](https://github.com/zloeber/terraform-copilot-prompts) - GitHub Copilot prompts for creating and converting Terraform configurations across cloud providers.
- [Terramate](https://github.com/terramate-io/terramate) - Orchestration and code generation tool for Terraform that simplifies managing complex multi-stack infrastructure.

## AI Incident Response and Troubleshooting

AI systems that detect, investigate, and remediate production incidents.

- [BigPanda](https://www.bigpanda.io/) - AIOps platform for event correlation, automated root cause analysis, and intelligent incident management across hybrid environments.
- [FireHydrant](https://firehydrant.com/) - Incident management platform with AI-powered retrospective generation, automated status pages, and runbook execution.
- [GitHub Agentic Workflows](https://github.github.io/gh-aw/) - Run AI agents in GitHub Actions for automated issue triage, CI failure analysis, and PR review.
- [HolmesGPT](https://github.com/HolmesGPT/holmesgpt) - Agentic AI troubleshooting for Kubernetes and cloud-native environments, a CNCF Sandbox project combining observability telemetry with LLM reasoning.
- [IncidentFox](https://github.com/incidentfox/incidentfox) - Open-source AI SRE platform for automated incident investigation, hypothesis formation, and fix suggestions with Slack and PagerDuty integration.
- [Moogsoft](https://www.moogsoft.com/) - AIOps platform with AI-driven noise reduction, correlation, and situation awareness for reducing alert fatigue.
- [Opsgenie](https://www.atlassian.com/software/opsgenie) - Incident management with AI-powered alert routing, on-call scheduling, and intelligent escalation by Atlassian.
- [PagerDuty AIOps](https://www.pagerduty.com/platform/aiops/) - AI event correlation, noise reduction, and intelligent routing that reduces alert fatigue with ML-based grouping.
- [Rootly](https://rootly.com/) - AI-powered incident management with automated timelines, AI-generated postmortems, and Slack-native workflows.
- [Shoreline](https://shoreline.io/) - AI-powered incident automation that converts runbooks into automated remediation executing across fleets.
- [Tracecat](https://github.com/TracecatHQ/tracecat) - Open-source AI automation for security and reliability operations with 100+ integrations and sandboxed execution.

## AI Monitoring and Observability

AI-enhanced monitoring, alerting, and observability platforms.

- [Chronosphere](https://chronosphere.io/) - Cloud-native observability platform with AI-driven data optimization that reduces telemetry costs while preserving critical signals.
- [Coralogix](https://coralogix.com/) - Full-stack observability with AI-powered log analysis, anomaly detection, and cost-effective data management.
- [Datadog Bits AI](https://www.datadoghq.com/product/platform/bits-ai/) - AI assistant for natural language metric queries, root cause analysis, and automated investigation across infrastructure.
- [Dynatrace Davis AI](https://docs.dynatrace.com/docs/platform/davis-ai) - Causal AI engine for automated root cause analysis, impact assessment, and predictive problem detection.
- [Grafana](https://github.com/grafana/grafana) - Open-source monitoring and observability platform that serves as the foundation for AI-powered monitoring workflows.
- [Grafana AI](https://grafana.com/products/cloud/ai-tools-for-observability/) - Built-in AI agents for observability including SRE agent for root cause analysis, adaptive telemetry for cost reduction, and AI-assisted query generation.
- [Groundcover](https://www.groundcover.com/) - eBPF-based observability platform with AI-powered root cause analysis that requires zero instrumentation.
- [Metoro Guardian](https://metoro.io/) - AI observability copilot combining telemetry and code analysis for accurate root cause identification and auto-generated fix PRs.
- [New Relic AI](https://newrelic.com/platform/new-relic-ai) - AI monitoring assistant with natural language querying, anomaly explanation, and intelligent alert correlation.
- [Prometheus Operator](https://github.com/prometheus-operator/prometheus-operator) - Cloud-native monitoring foundation essential for AI-powered alerting pipelines, a CNCF project.
- [Splunk AI](https://www.splunk.com/en_us/products/ai-assistant.html) - AI assistant for natural language search, anomaly detection, and predictive analytics across IT infrastructure.
- [Sumo Logic](https://www.sumologic.com/) - Cloud-native machine data analytics with AI-driven log analysis, threat detection, and infrastructure intelligence.

## AI Security Scanning

AI-powered security tools for infrastructure, containers, and supply chain.

- [Aqua Security](https://www.aquasec.com/) - Cloud-native security platform with AI-powered runtime protection, image scanning, and compliance enforcement for containers.
- [Checkov](https://github.com/bridgecrewio/checkov) - Static analysis for IaC security that scans Terraform, CloudFormation, Kubernetes, Helm, and Dockerfile for misconfigurations.
- [Falco](https://github.com/falcosecurity/falco) - CNCF graduated cloud-native runtime security project for threat detection in containers and Kubernetes.
- [GitGuardian](https://www.gitguardian.com/) - AI-powered secrets detection that scans Git repositories, CI/CD pipelines, and Docker images for exposed credentials.
- [Lacework](https://www.lacework.com/) - Cloud security platform with behavioral AI that detects anomalies and threats across cloud workloads without rules.
- [MCP-Scan](https://labs.snyk.io/) - Open-source tool for analyzing Model Context Protocol security issues and auditing MCP servers for vulnerabilities.
- [Orca Security](https://orca.security/) - Agentless cloud security with AI-powered risk prioritization across workloads, configurations, and identities.
- [Prisma Cloud](https://www.paloaltonetworks.com/prisma/cloud) - Comprehensive cloud-native application protection platform with AI-driven vulnerability prioritization and compliance.
- [Semgrep](https://github.com/semgrep/semgrep) - Fast open-source static analysis for finding bugs and enforcing code standards across 30+ languages including HCL and YAML.
- [Snyk](https://snyk.io/product/) - AI-powered security platform with DeepCode AI engine that scans code, containers, IaC, and AI-generated code in real-time.
- [SonarQube](https://www.sonarsource.com/products/sonarqube/) - Code quality and security analysis platform with AI-powered code smell detection and vulnerability identification.
- [Terraform Sentinel](https://www.hashicorp.com/sentinel) - Policy-as-code framework by HashiCorp that enforces fine-grained, logic-based policies on Terraform infrastructure changes.
- [tfsec](https://github.com/aquasecurity/tfsec) - Security scanner for Terraform code that checks for security misconfigurations and compliance violations.
- [Trivy](https://github.com/aquasecurity/trivy) - Comprehensive open-source vulnerability scanner for containers, IaC, Kubernetes, and code that is fast, accurate, and widely adopted.
- [Wiz](https://www.wiz.io/) - Cloud security platform that unifies vulnerability findings with cloud context to prioritize exploitable risks.

## AI Cost Optimization

AI and automation tools for cloud cost management, FinOps, and resource optimization.

- [Anodot](https://www.anodot.com/) - AI-powered cloud cost management with autonomous anomaly detection, optimization recommendations, and commitment management.
- [CAST AI](https://cast.ai/) - AI-powered Kubernetes cost optimization with automated rightsizing, spot instance management, and cluster autoscaling.
- [CloudZero](https://www.cloudzero.com/) - Cloud cost intelligence platform with AI-driven cost allocation, anomaly detection, and unit economics tracking.
- [Finout](https://www.finout.io/) - FinOps platform with AI-powered cost allocation across cloud, Kubernetes, and SaaS that combines billing data with observability.
- [Kubecost](https://github.com/kubecost/kubecost) - Real-time Kubernetes cost monitoring by service, deployment, namespace, and container with cloud billing integration.
- [nOps](https://www.nops.io/) - AWS cost optimization platform with AI-driven rightsizing, commitment management, and automated savings execution.
- [OpenCost](https://github.com/opencost/opencost) - CNCF Sandbox project for vendor-neutral, real-time Kubernetes cost monitoring and allocation.
- [Spot by NetApp](https://spot.io/) - AI-driven cloud infrastructure optimization using spot instances, autoscaling, and intelligent workload placement.
- [Turbonomic](https://www.ibm.com/products/turbonomic) - IBM AI-powered application resource management that continuously optimizes compute, storage, and network allocation.
- [Vantage](https://www.vantage.sh/) - Cloud cost transparency platform with AI-powered recommendations across AWS, Azure, GCP, Kubernetes, and Datadog.

## MCP Servers for DevOps

Model Context Protocol servers that give AI assistants like Claude, ChatGPT, and Cursor access to DevOps tools and infrastructure.

- [Atlassian MCP Server](https://www.npmjs.com/package/@anthropic/mcp-atlassian) - MCP server for Jira and Confluence integration enabling AI agents to query issues, create tickets, and search documentation.
- [AWS MCP Servers](https://awslabs.github.io/mcp/) - Official AWS MCP server suite covering Terraform, CDK, CloudFormation, Lambda, S3, CloudWatch, ECS, and more.
- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) - Comprehensive curated list of all MCP servers across every category.
- [Cloudflare MCP Server](https://github.com/cloudflare/mcp-server-cloudflare) - Official Cloudflare MCP server for managing Workers, KV, R2, and DNS from AI agents.
- [Docker MCP Gateway](https://github.com/docker/mcp-gateway) - Docker-maintained MCP server for container management, image operations, and Docker Compose workflows.
- [GitHub MCP Server](https://github.com/github/github-mcp-server) - Official GitHub MCP server for repos, issues, PRs, Actions, and code search from AI agents.
- [Kubernetes MCP Server](https://github.com/Flux159/mcp-server-kubernetes) - MCP server for kubectl operations, pod management, and cluster introspection.
- [Linear MCP Server](https://github.com/jerhadf/linear-mcp-server) - MCP server for Linear project management enabling AI agents to manage issues, projects, and cycles.
- [MCP Reference Servers](https://github.com/modelcontextprotocol/servers) - Official MCP reference implementations including filesystem, Git, GitHub, PostgreSQL, Puppeteer, and more.
- [Sentry MCP Server](https://github.com/getsentry/sentry-mcp) - Official Sentry MCP server for error tracking, issue search, and event analysis from AI agents.
- [Slack MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) - MCP server for Slack workspace interaction enabling AI agents to read channels, post messages, and search conversations.
- [Terraform MCP Server](https://github.com/hashicorp/terraform-mcp-server) - Official HashiCorp MCP server for Terraform module search, provider documentation, and policy enforcement.

## AI-Powered CI/CD

AI tools that enhance continuous integration and delivery pipelines.

- [ArgoCD](https://github.com/argoproj/argo-cd) - CNCF GitOps continuous delivery for Kubernetes that serves as the foundation for AI-driven deployment workflows.
- [CircleCI](https://circleci.com/) - Cloud CI/CD platform with AI-powered test splitting, flaky test detection, and pipeline optimization insights.
- [Codefresh](https://codefresh.io/) - GitOps CI/CD platform built on Argo with AI-assisted pipeline creation and deployment analytics.
- [Dagger](https://github.com/dagger/dagger) - Programmable CI/CD engine that runs pipelines in containers, enabling AI agents to compose and execute build workflows.
- [GitLab Duo](https://about.gitlab.com/gitlab-duo/) - AI across the GitLab DevSecOps platform with code suggestions, root cause analysis, vulnerability resolution, and CI/CD pipeline generation.
- [Harness AIDA](https://www.harness.io/products/aida) - AI Development Assistant for intelligent pipeline creation, failure analysis, and deployment optimization.
- [Mergify](https://mergify.com/) - AI-powered merge queue and PR automation with intelligent batch merging and conflict resolution.
- [PR-Agent](https://github.com/qodo-ai/pr-agent) - AI-powered pull request analysis that auto-describes, reviews, improves, and generates tests for GitHub, GitLab, and Bitbucket.
- [Tekton](https://github.com/tektoncd/pipeline) - Cloud-native CI/CD building blocks for Kubernetes providing the foundation for AI-orchestrated build and deploy pipelines.
- [Trunk](https://trunk.io/) - Developer experience platform with AI-powered code quality checks, merge queues, and flaky test management.

## AI Log Analysis and Debugging

AI tools for log analysis, pattern detection, and debugging production systems.

- [Axiom](https://axiom.co/) - Cloud-native log management with AI-powered query generation, anomaly detection, and unlimited data retention.
- [Elasticsearch](https://github.com/elastic/elasticsearch) - Foundation for AI-powered log analysis with ES|QL, vector search, and ML anomaly detection.
- [Grafana Loki](https://github.com/grafana/loki) - Log aggregation system designed for cloud-native environments that pairs with Grafana AI for intelligent log querying.
- [LogAI](https://github.com/salesforce/logai) - Salesforce's open-source toolkit for AI-powered log analysis with ML algorithms for anomaly detection, clustering, and summarization.
- [OpenTelemetry Collector](https://github.com/open-telemetry/opentelemetry-collector) - Vendor-agnostic telemetry collection that serves as the essential pipeline for feeding logs, metrics, and traces to AI analysis tools.
- [Parseable](https://github.com/parseablehq/parseable) - Cloud-native log storage and observability platform built in Rust with AI-powered log analysis and alerting.
- [Vector](https://github.com/vectordotdev/vector) - High-performance observability data pipeline for collecting, transforming, and routing logs, metrics, and traces to AI analysis backends.
- [Zebrium](https://www.zebrium.com/) - ML-powered root cause analysis from logs that automatically identifies incident root cause without manual queries.

## AI Agent Frameworks for Infrastructure

General-purpose AI agent frameworks with strong infrastructure and DevOps use cases.

- [AutoGen](https://github.com/microsoft/autogen) - Microsoft's multi-agent framework supporting infrastructure workflows with tool use, code execution, and human-in-the-loop approvals.
- [Claude Agent SDK](https://docs.anthropic.com/en/docs/agents) - Anthropic's framework for building agentic applications with tool use, orchestration, and guardrails for infrastructure automation.
- [CrewAI](https://github.com/crewAIInc/crewAI) - Multi-agent orchestration framework for building teams of AI agents that handle complex infrastructure tasks like migration planning.
- [Dify](https://github.com/langgenius/dify) - LLM application development platform with agent workflows, RAG, and model management for building custom DevOps chatbots.
- [LangChain](https://github.com/langchain-ai/langchain) - Framework for building LLM-powered applications, widely used for building custom DevOps agents with tool integrations.
- [LangGraph](https://github.com/langchain-ai/langgraph) - Library for building stateful, multi-actor applications with LLMs, ideal for complex infrastructure orchestration workflows.
- [n8n](https://github.com/n8n-io/n8n) - Workflow automation platform with 400+ integrations and AI agent capabilities for low-code DevOps automation.
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) - OpenAI's framework for building multi-agent systems with handoffs, guardrails, and tracing for infrastructure automation.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - Microsoft's SDK for integrating LLMs into applications with plugin architecture ideal for building infrastructure automation agents.
- [Temporal](https://github.com/temporalio/temporal) - Durable execution platform for orchestrating long-running infrastructure workflows with built-in retry and failure handling.

## AI for Platform Engineering

AI tools for building internal developer platforms, service catalogs, and self-service infrastructure.

- [Backstage](https://github.com/backstage/backstage) - CNCF incubating project by Spotify for building developer portals with service catalogs, templates, and plugin-based extensibility.
- [Cortex](https://www.cortex.io/) - Internal developer portal with AI-driven service maturity scorecards, ownership tracking, and reliability standards enforcement.
- [Cycloid](https://www.cycloid.io/) - Platform engineering solution with AI-powered infrastructure self-service, cost governance, and green IT scoring.
- [Humanitec](https://humanitec.com/) - Platform orchestrator that powers enterprise internal developer platforms with dynamic configuration management.
- [Kratix](https://github.com/syntasso/kratix) - Open-source framework for building platforms-as-a-product on Kubernetes with composable promise-based abstractions.
- [Mia-Platform](https://mia-platform.eu/) - Internal developer platform with AI-powered microservice orchestration, API management, and developer self-service.
- [OpsLevel](https://www.opslevel.com/) - Service ownership platform with AI-powered maturity tracking, dependency mapping, and developer self-service.
- [Port](https://www.getport.io/) - Open internal developer portal with AI-powered software catalog, self-service actions, and scorecards for engineering standards.
- [Qovery](https://www.qovery.com/) - Platform that provides production-like environments for developers with AI-assisted deployment and environment management.

## AI for Database Operations

AI tools for database management, query optimization, and data operations.

- [Aiven AI](https://aiven.io/) - Managed database platform with AI-powered query optimization, anomaly detection, and automated performance tuning.
- [Bytebase](https://github.com/bytebase/bytebase) - Database DevOps and CI/CD platform with AI-assisted schema review, migration management, and SQL linting.
- [CloudNativePG](https://github.com/cloudnative-pg/cloudnative-pg) - Kubernetes operator for PostgreSQL that manages the full lifecycle of PostgreSQL clusters with automated failover.
- [Metabase](https://github.com/metabase/metabase) - Open-source BI platform with natural language querying that enables non-technical users to explore infrastructure databases.
- [OtterTune](https://ottertune.com/) - AI-powered database optimization that automatically tunes PostgreSQL, MySQL, and MariaDB configurations for performance.
- [pganalyze](https://pganalyze.com/) - PostgreSQL performance monitoring with AI-powered query optimization recommendations and index advisor.
- [PlanetScale](https://planetscale.com/) - Serverless MySQL platform with AI-powered schema change management, query insights, and non-blocking deploys.
- [Vitess](https://github.com/vitessio/vitess) - CNCF graduated database clustering system for horizontal scaling of MySQL, essential for AI workloads needing distributed data.

## AI for Networking and Service Mesh

AI tools for network management, service mesh, and traffic engineering.

- [Calico](https://github.com/projectcalico/calico) - Cloud-native networking and security with AI-enhanced network policy management and threat detection for Kubernetes.
- [Cilium](https://github.com/cilium/cilium) - eBPF-based networking, security, and observability for Kubernetes with Hubble UI for AI-powered network flow analysis.
- [Consul](https://github.com/hashicorp/consul) - Service mesh and service discovery by HashiCorp with intentions-based security and automated traffic management.
- [Istio](https://github.com/istio/istio) - CNCF graduated service mesh providing traffic management, security, and observability for microservices architectures.
- [Linkerd](https://github.com/linkerd/linkerd2) - CNCF graduated ultralight service mesh for Kubernetes with automated mTLS, traffic splitting, and golden metrics.
- [Ngrok](https://ngrok.com/) - Unified ingress platform with AI-powered traffic inspection, policy enforcement, and API gateway capabilities.
- [Traefik](https://github.com/traefik/traefik) - Cloud-native application proxy with automatic service discovery, Let's Encrypt integration, and observability features.

## AI for Container Security and Supply Chain

AI tools for container image security, software supply chain, and build verification.

- [Chainguard](https://www.chainguard.dev/) - Secure container images and supply chain tools with zero known CVEs, built for reducing vulnerability remediation.
- [Cosign](https://github.com/sigstore/cosign) - Container signing and verification tool from the Sigstore project for supply chain security.
- [Docker Scout](https://docs.docker.com/scout/) - Docker's AI-powered supply chain security for image analysis, CVE remediation guidance, and base image recommendations.
- [Grype](https://github.com/anchore/grype) - Fast open-source vulnerability scanner for container images and filesystems with SBOM-based analysis.
- [Harbor](https://github.com/goharbor/harbor) - CNCF graduated cloud-native registry with vulnerability scanning, image signing, and policy-based image replication.
- [Slim.AI](https://www.slim.ai/) - Container optimization platform with AI-powered image analysis, vulnerability reduction through minification.
- [Syft](https://github.com/anchore/syft) - Open-source SBOM generator for container images and filesystems supporting multiple output formats.

## AI for Chaos Engineering and Reliability

AI tools for chaos engineering, resilience testing, and reliability validation.

- [Chaos Mesh](https://github.com/chaos-mesh/chaos-mesh) - CNCF incubating cloud-native chaos engineering platform for Kubernetes with fault injection and workflow orchestration.
- [Gremlin](https://www.gremlin.com/) - Enterprise chaos engineering platform with AI-powered reliability recommendations and targeted failure testing.
- [k6](https://github.com/grafana/k6) - Modern load testing tool by Grafana with scriptable scenarios and AI-assisted test generation for infrastructure endpoints.
- [Litmus](https://github.com/litmuschaos/litmus) - CNCF incubating chaos engineering framework for Kubernetes with a hub of prebuilt experiments and GitOps integration.
- [Steadybit](https://www.steadybit.com/) - Chaos engineering platform with AI-assisted experiment design and automated reliability validation.
- [Testkube](https://github.com/kubeshop/testkube) - Kubernetes-native test orchestration framework for running any testing tool inside clusters with CI/CD integration.

## AI for Cloud Migration and Modernization

AI tools that assist with cloud migration planning, execution, and application modernization.

- [AWS Application Discovery Service](https://aws.amazon.com/application-discovery/) - Automated discovery and planning for cloud migration with dependency mapping and utilization analysis.
- [AWS Migration Hub](https://aws.amazon.com/migration-hub/) - Central hub for tracking migrations across multiple AWS and partner tools with AI-powered progress tracking.
- [Azure Migrate](https://azure.microsoft.com/en-us/products/azure-migrate/) - Unified migration platform with AI-powered assessment, server migration, and database modernization tools.
- [Google Cloud Migrate](https://cloud.google.com/solutions/migration-center) - Comprehensive migration platform with AI-driven assessment, workload discovery, and total cost of ownership analysis.
- [Konveyor](https://github.com/konveyor/konveyor) - Open-source migration toolkit for modernizing applications to Kubernetes with AI-assisted code transformation.

## AI for GitOps

AI tools for GitOps workflows, declarative infrastructure, and continuous reconciliation.

- [Flux](https://github.com/fluxcd/flux2) - CNCF graduated GitOps toolkit for Kubernetes with automated image updates, Helm releases, and Kustomize reconciliation.
- [Helm](https://github.com/helm/helm) - CNCF graduated Kubernetes package manager essential for templating and deploying AI workloads and infrastructure components.
- [Kargo](https://github.com/akuity/kargo) - Continuous promotion and lifecycle orchestrator for Kubernetes applications across environments with GitOps principles.
- [Kustomize](https://github.com/kubernetes-sigs/kustomize) - Kubernetes configuration customization tool that enables declarative management of manifests without template engines.
- [Weave GitOps](https://github.com/weaveworks/weave-gitops) - Enterprise GitOps platform with progressive delivery, policy enforcement, and multi-cluster management.

## System Prompt and Config Templates

Ready-to-use AI agent configurations for infrastructure repositories.

- [Awesome CursorRules](https://github.com/PatrickJS/awesome-cursorrules) - Community-curated .cursorrules files for various project types including infrastructure and DevOps.
- [ChatGPT Prompts for DevOps](https://github.com/f/awesome-chatgpt-prompts) - Community-curated prompt library that includes DevOps and system administration automation prompts.
- [Claude Code DevOps Toolkit](https://github.com/hammadhaqqani/claude-code-devops-toolkit) - Production-tested CLAUDE.md files, curated DevOps prompts, automation scripts, and project configs for infrastructure workflows.
- [Free AI and DevOps Tools](https://hammadhaqqani.com/tools) - Collection of 41 free browser-based AI and DevOps tools including prompt builder, system prompt generator, and token counter.
- [GitHub Copilot Custom Instructions](https://docs.github.com/en/copilot/customizing-copilot/adding-custom-instructions-for-github-copilot) - Official guide for creating copilot-instructions.md to customize AI behavior per repository.

## Learning Resources

Courses, certifications, articles, and guides on AI for DevOps.

### Articles and Guides

- [FinOps for AI Overview](https://www.finops.org/wg/finops-for-ai-overview/) - FinOps Foundation guide on managing AI workload costs in the cloud.
- [HolmesGPT: Agentic Troubleshooting for Cloud Native](https://www.cncf.io/blog/2026/01/07/holmesgpt-agentic-troubleshooting-built-for-the-cloud-native-era/) - CNCF deep dive into AI-powered Kubernetes troubleshooting.
- [I Built 41 Free AI and DevOps Tools](https://hammadhaqqani.com/blog/41-free-ai-devops-tools-no-signup) - Deep dive into building client-side AI and DevOps tools that run entirely in the browser.
- [The AI Singularity Is Closer Than You Think](https://hammadhaqqani.com/blog/the-ai-singularity-is-closer-than-you-think) - First-hand account of how AI agents are replacing engineering workflows from a DevOps veteran with 10+ years of experience.
- [Top 15 AI Prompts Every DevOps Engineer Should Master](https://kubezilla.io/top-15-ai-prompts-every-devops-engineer-should-master-in-2026) - Essential prompt patterns for infrastructure automation.

### Certifications

- [AWS AI Practitioner](https://aws.amazon.com/certification/certified-ai-practitioner/) - Foundational AI and ML certification with cloud infrastructure context.
- [CKA and KCNA](https://www.cncf.io/certification/) - CNCF Kubernetes certifications that provide essential foundation before adding AI-powered Kubernetes tools.
- [Google Cloud Professional ML Engineer](https://cloud.google.com/learn/certification/machine-learning-engineer) - ML engineering certification focused on GCP infrastructure.
- [Terraform Associate](https://www.hashicorp.com/certification/terraform-associate) - HashiCorp IaC certification providing prerequisite knowledge for AI-assisted Terraform workflows.

## Community and Newsletters

Communities, forums, and newsletters covering AI and DevOps.

- [CNCF Slack](https://communityinviter.com/apps/cloud-native/cncf) - Cloud Native Computing Foundation community with channels for K8sGPT, HolmesGPT, and AI-native projects.
- [DevOps Weekly](https://www.devopsweekly.com/) - Weekly newsletter covering DevOps tooling and practices including AI adoption.
- [KubeWeekly](https://www.cncf.io/kubeweekly/) - Official CNCF newsletter covering Kubernetes ecosystem updates and AI-powered tooling announcements.
- [Platformers Community](https://platformengineering.org/) - Platform engineering community with discussions on AI-powered developer experience and internal platforms.
- [r/devops](https://reddit.com/r/devops) - Reddit community with 780k+ members actively discussing AI tool adoption in DevOps workflows.
- [r/Kubernetes](https://reddit.com/r/kubernetes) - Reddit community with 260k+ members discussing K8sGPT, KAITO, and AI-powered cluster management.
- [r/Terraform](https://reddit.com/r/Terraform) - Active Reddit community discussing AI-assisted IaC and Terraform automation.
- [The New Stack](https://thenewstack.io/) - Publication covering cloud-native, Kubernetes, and AI infrastructure developments.
- [TLDR DevOps](https://tldr.tech/devops) - Daily DevOps newsletter with AI and automation coverage.

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

---

## Support

If you find this useful, consider buying me a coffee!

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/hammadhaqqani)
