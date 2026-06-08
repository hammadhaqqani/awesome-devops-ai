# Awesome DevOps AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Awesome Lint](https://github.com/hammadhaqqani/awesome-devops-ai/actions/workflows/awesome-lint.yml/badge.svg?branch=main)](https://github.com/hammadhaqqani/awesome-devops-ai/actions/workflows/awesome-lint.yml)
[![Link Check](https://github.com/hammadhaqqani/awesome-devops-ai/actions/workflows/link-check.yml/badge.svg?branch=main)](https://github.com/hammadhaqqani/awesome-devops-ai/actions/workflows/link-check.yml)
[![GitHub Pages](https://github.com/hammadhaqqani/awesome-devops-ai/actions/workflows/pages.yml/badge.svg?branch=main)](https://hammadhaqqani.github.io/awesome-devops-ai/)
[![GitHub stars](https://img.shields.io/github/stars/hammadhaqqani/awesome-devops-ai?style=social)](https://github.com/hammadhaqqani/awesome-devops-ai/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/hammadhaqqani/awesome-devops-ai?style=social)](https://github.com/hammadhaqqani/awesome-devops-ai/network/members)

> A curated list of AI tools, agents, MCP servers, and resources for DevOps, SRE, and Platform Engineering.

The AI revolution is transforming how infrastructure is built, monitored, and operated. This list tracks every meaningful tool at the intersection of AI and DevOps, from coding agents that write Terraform to AI-powered incident response that pages you with a root cause already identified.

**Why this list?** Engineers are adopting AI tooling faster than any technology shift in history, but the landscape is fragmented across hundreds of repos, products, and frameworks. This is one place to find them all.

**459 tools** across **20 categories** — updated April 2026. See the [Quick Start Guide](GUIDE.md) for role-based recommendations.

If this list is useful, please give it a star to help others find it.

## Contents

- [Tool of the Week](#tool-of-the-week)
- [What's New](#whats-new)
- [Most Starred Projects](#most-starred-projects)
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
- [Related Awesome Lists](#related-awesome-lists)
- [Author](#author)
- [Support](#support)

## Tool of the Week

**NVIDIA Grove** — NVIDIA's Kubernetes API for orchestrating complex multi-node AI inference with hierarchical gang scheduling and topology-aware placement. Announced at KubeCon 2026 as part of the Dynamo ecosystem, it fills GPU orchestration gaps that plain Deployments and StatefulSets cannot cover.

> Previous picks: JetBrains Junie (LLM-agnostic coding agent) | Gemini CLI (Google's terminal AI agent) | Goose (Block's Rust-based autonomous agent) | K8sGPT (CNCF Kubernetes diagnostics) | HolmesGPT (agentic troubleshooting)

## What's New

**May 2026** — Deep research update adding 43 new tools across 9 categories. **Kubernetes** (7): NVIDIA Grove, Agent Sandbox, Microsoft Agent Governance Toolkit, KubeCopilot Core, kube-agent, LLMKube, OpenSRE. **IaC** (6): Pulumi Neo, HashiCorp Project Infragraph, HashiCorp Agent Skills, Overmind, Saturnhead AI, Quali Torque. **Incident Response** (3): Datafruit, SRE.ai, AWS Security Incident Response Agent. **Observability** (4): Coralogix Olly, LogicMonitor Edwin AI, New Relic SRE Agent, AgentSight. **Security** (9): Prophet Security, Dropzone AI, 7AI, Conifers CognitiveSOC, Hex Security, Upwind, HexStrike AI, Databricks Lakewatch, Microsoft Security Copilot. **FinOps** (1): Costimizer. **MCP Servers** (7): Hetzner Cloud, Snowflake, MCP Toolbox for Databases, LaunchDarkly, Unleash, Temporal, Istio. **Agent Frameworks** (4): Kubiya, agentgateway, open-multi-agent, Composio Agent Orchestrator. **Platform Engineering** (1): OpenChoreo. **Chaos** (1): ChaosEater. **Total: 502 tools** across 20 categories.

**Late April 2026 (#2)** — Web research update adding 45 new tools across 9 categories and fixing the broken KubeStellar Console MCP link from PR #19. **AI Coding Agents** (3): Kilo Code, Plandex, Mistral Vibe. **Kubernetes** (3): Causely, Parity, Azure SRE Agent. **Incident Response** (5): Cleric, Resolve AI, NeuBird Hawkeye, Edge Delta, Traversal. **Observability** (2): SigNoz, Flip AI. **Security** (7): Aikido, ZeroPath, Pixee, Corgea, Backslash, Ghost Security, Cyera. **FinOps** (3): Antimetal, PointFive, ProsperOps. **IaC** (2): Resourcely, Terrateam. **Agent Frameworks** (5): Letta, Strands Agents, BeeAI, Agno, Mirascope. **MCP Servers** (15): Render, Fly.io, SigNoz, Coralogix, Logz.io, ClickHouse, Turso, Databricks, Harness, Twilio, Stripe, CrowdStrike Falcon, Wiz, Bitwarden, Doppler. **Total: 459 tools** across 20 categories.

**April 2026 (Late)** — Major update adding 31 new entries from deep research. **AI Coding Agents** (7): OpenCode (140k+ stars), Roo Code, OpenHands (77.6% SWEBench), Crush (Charm), Factory AI, Qwen Code (Alibaba), Trae (ByteDance). **AI Agent Frameworks** (3): Microsoft Agent Framework 1.0 (April 3 release), LangChain Deep Agents, Llama Stack (Meta). **AI CI/CD and Testing** (5): Mendral (YC AI DevOps engineer), Stably AI, Momentic, Cursor BugBot, Claude Code Review (Anthropic multi-agent). **MCP Servers** (2): Cloudflare Code Mode, Bitbucket. **Kubernetes** (2): NVIDIA AI Cluster Runtime, Velero (CNCF Sandbox). **Terraform/IaC** (1): Terracotta AI. **Databases** (2): Tembo, Xata. **Security/Governance** (3): Credo AI, Holistic AI, Microsoft Purview. **Observability** (1): OpenLLMetry. **System Prompts** (2): AGENTS.md (OpenAI), Claude Skills (Anthropic). **Community** (1): Agentic AI Foundation (Linux Foundation). **Total: 414 tools** across 20 categories.

**April 2026** — Major update with 69 new entries. Added 18 new tools including JetBrains Junie, aiac, NVIDIA KAI Scheduler, llm-d, Sedai, AccuKnox, Checkmarx One, Coroot, Apache SkyWalking, Dash0, MetaGPT, testRigor, Testsigma, ControlMonkey, and Braintrust. Added 24 new MCP servers from GCP, DigitalOcean, Oracle, New Relic, Splunk, Elastic, Dynatrace, CircleCI, Buildkite, MongoDB, Redis, Neon, Supabase, Vault, Snyk, Trivy, Rootly, FireHydrant, incident.io, and Ansible. Added 8 new books, 16 new certifications (AWS, Azure, GCP, CNCF, HashiCorp, FinOps, Datadog), and the Agentic DevOps podcast. **Total: 383 tools** across 20 categories.

**March 2026** — Added 34 new tools including Gemini CLI, Goose, Kiro, KubeAI, Kubescape, Keep, Sysdig, and Pydantic AI. Added 9 new MCP servers (Azure DevOps, GitLab, JFrog, Jenkins, Prometheus, Pulumi, Argo CD, Slack, Notion). Added 3 new CNCF projects (Kubeflow, Kubescape, KServe) and new agent frameworks (Google ADK, Pydantic AI, smolagents, DSPy, OpenClaw). **Total: 314 tools** across 20 categories.

**February 2026** — Added 23 new tools across 12 categories to reach 280 total. New coverage for database operations, networking, and container security.

## Most Starred Projects

The most popular open-source projects in this list by GitHub stars.

| Project                 | Stars                                                                                    | Category            |
| ----------------------- | ---------------------------------------------------------------------------------------- | ------------------- |
| Gemini CLI              | ![Stars](https://img.shields.io/github/stars/google-gemini/gemini-cli?style=flat)        | AI Coding Agents    |
| OpenClaw                | ![Stars](https://img.shields.io/github/stars/openclaw/openclaw?style=flat)               | AI Agent Frameworks |
| Grafana                 | ![Stars](https://img.shields.io/github/stars/grafana/grafana?style=flat)                 | AI Monitoring       |
| Elasticsearch           | ![Stars](https://img.shields.io/github/stars/elastic/elasticsearch?style=flat)           | AI Log Analysis     |
| n8n                     | ![Stars](https://img.shields.io/github/stars/n8n-io/n8n?style=flat)                      | AI Agent Frameworks |
| LangChain               | ![Stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=flat)          | AI Agent Frameworks |
| Dify                    | ![Stars](https://img.shields.io/github/stars/langgenius/dify?style=flat)                 | AI Agent Frameworks |
| Aider                   | ![Stars](https://img.shields.io/github/stars/aider-ai/aider?style=flat)                  | AI Coding Agents    |
| K8sGPT                  | ![Stars](https://img.shields.io/github/stars/k8sgpt-ai/k8sgpt?style=flat)                | AI Kubernetes       |
| Trivy                   | ![Stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=flat)              | AI Security         |
| ArgoCD                  | ![Stars](https://img.shields.io/github/stars/argoproj/argo-cd?style=flat)                | AI CI/CD            |
| Istio                   | ![Stars](https://img.shields.io/github/stars/istio/istio?style=flat)                     | AI Networking       |
| Helm                    | ![Stars](https://img.shields.io/github/stars/helm/helm?style=flat)                       | AI GitOps           |
| Falco                   | ![Stars](https://img.shields.io/github/stars/falcosecurity/falco?style=flat)             | AI Security         |

## AI Coding Agents for Infrastructure

AI-powered coding agents that help write, review, and maintain infrastructure code including Terraform, Kubernetes manifests, Dockerfiles, and CI/CD pipelines.

- [Aider](https://github.com/aider-ai/aider) - Terminal-based AI pair programming that works with any LLM, great for infrastructure repos with git-commit-per-change workflows.
- [Amazon Q Developer](https://aws.amazon.com/q/developer/) - AWS-native AI assistant with deep CloudFormation, CDK, and AWS service knowledge.
- [Augment Code](https://www.augmentcode.com/) - AI coding platform with deep codebase understanding, multi-repo context, and enterprise-grade infrastructure code generation.
- [Bolt](https://bolt.new/) - StackBlitz AI-powered full-stack development environment that generates and deploys applications directly in the browser.
- [Clanker](https://github.com/bgdnvk/clanker) - Autonomous systems engineering CLI agent for any cloud environment including AWS, GCP, and Cloudflare.
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - Anthropic's agentic coding tool that excels at large-scale Terraform refactoring, multi-file Kubernetes manifest generation, and infrastructure debugging.
- [Cline](https://github.com/cline/cline) - Autonomous AI coding agent for VS Code that runs terminal commands, edits files, and handles complex infrastructure tasks.
- [Codex](https://openai.com/index/openai-codex/) - OpenAI's autonomous coding agent with cloud sandbox execution, strong at generating IaC from natural language descriptions.
- [Continue](https://github.com/continuedev/continue) - Open-source AI code assistant for VS Code and JetBrains that supports custom models and local LLMs for air-gapped infrastructure work.
- [Cursor](https://cursor.com) - AI-first IDE with inline Terraform and YAML completions and multi-file editing capabilities.
- [Devin](https://devin.ai/) - Autonomous AI software engineer by Cognition that can independently handle full infrastructure workflows from planning to deployment.
- [Gemini Code Assist](https://cloud.google.com/gemini/docs/codeassist/overview) - Google Cloud AI coding assistant with Gemini models, deep GCP integration, and infrastructure code generation.
- [GitHub Copilot](https://github.com/features/copilot) - AI pair programmer integrated into VS Code, JetBrains, and CLI, with Copilot Workspace for multi-file infrastructure changes.
- [JetBrains AI](https://www.jetbrains.com/ai/) - AI assistant built into IntelliJ-based IDEs with context-aware infrastructure code completions and explanations.
- [Lovable](https://lovable.dev/) - AI-powered full-stack app builder that generates production-ready applications from natural language descriptions with one-click deploy.
- [Crush](https://github.com/charmbracelet/crush) - Glamourous terminal AI coding agent by Charm supporting OpenAI, Anthropic, Groq, Gemini, Bedrock, Azure, and any compatible endpoint without losing session context.
- [Factory AI](https://factory.ai/) - Enterprise AI coding platform with advanced agents that generate complex apps, work on large codebases, and run code locally with web search and MCP access.
- [OpenCode](https://github.com/opencode-ai/opencode) - Go-based terminal AI coding agent with 140k+ GitHub stars supporting 75+ models from Claude, OpenAI, Gemini, and local providers with Build and Plan modes.
- [OpenHands](https://github.com/OpenHands/OpenHands) - Open-source AI software engineering platform (MIT) with 77.6% SWEBench success rate, autonomous shell commands, file navigation, and debugging capabilities.
- [Qwen Code](https://github.com/QwenLM/Qwen3-Coder) - Alibaba Qwen's official CLI coding agent with 20k+ stars supporting Qwen3-Coder models for infrastructure code generation and refactoring.
- [Replit Agent](https://replit.com/ai) - AI agent that builds and deploys full-stack applications from natural language, useful for rapid prototyping of infrastructure dashboards.
- [Roo Code](https://github.com/RooCodeInc/Roo-Code) - Open-source VS Code AI coding agent with Custom Modes, agentic multi-file editing, and enterprise SOC 2 compliance forked from Cline.
- [Trae](https://www.trae.ai/) - ByteDance's free AI-first IDE with vibe coding that generates production-ready code from natural language prompts with built-in MCP support.
- [Sourcegraph Cody](https://sourcegraph.com/cody) - AI coding assistant with full codebase context, ideal for navigating large monorepos with shared infrastructure modules.
- [Tabnine](https://www.tabnine.com/) - AI code completion that runs locally or in the cloud with enterprise-grade privacy for sensitive infrastructure code.
- [Windsurf](https://codeium.com/windsurf) - AI IDE by Codeium with agentic Cascade mode for multi-step infrastructure tasks.
- [Void](https://voideditor.com/) - Open-source AI code editor forked from VS Code that supports local and remote LLMs for privacy-first infrastructure development.
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) - Google's open-source AI agent for the terminal with built-in tools, MCP server support, and a free tier of 1,000 requests per day using Gemini models.
- [Goose](https://github.com/block/goose) - Open-source autonomous AI agent by Block written in Rust that installs, executes, edits, and tests with any LLM via MCP under Apache 2.0.
- [Kiro](https://kiro.dev/) - AWS spec-driven agentic IDE that uses structured requirements, design docs, and agent hooks to produce reproducible infrastructure code.
- [Zed AI](https://zed.dev/) - High-performance editor with built-in AI assistant, inline generation, and terminal integration for infrastructure workflows.
- [toprank](https://github.com/nowork-studio/toprank) - Open-source Claude Code plugin (MIT) providing 9 SEO and Google Ads skills — connects Google Search Console, PageSpeed Insights, and Google Ads API for automated audits, keyword research, and content optimization directly from Claude Code.
- [aiac](https://github.com/gofireflyio/aiac) - AI Infrastructure-as-Code generator CLI by Firefly that creates Terraform, Pulumi, Helm, CloudFormation, Dockerfiles, and CI/CD configs from natural language via OpenAI, Bedrock, or Ollama.
- [JetBrains Junie](https://www.jetbrains.com/junie/) - JetBrains' LLM-agnostic standalone coding agent for the terminal, IDE, and CI/CD pipelines supporting models from OpenAI, Anthropic, Google, and Grok.
- [Kilo Code](https://github.com/Kilo-Org/kilocode) - MIT-licensed agentic engineering platform across VS Code, JetBrains, and CLI with 500+ models at zero markup, parallel subagents, and persistent Memory Bank for long-running infrastructure projects.
- [Plandex](https://github.com/plandex-ai/plandex) - Terminal plan-first coding agent with 2M-token context and a cumulative-diff sandbox that auto-debugs builds, linters, tests, and deployments — built for large multi-file IaC changes.
- [Mistral Vibe](https://github.com/mistralai/mistral-vibe) - Apache-2.0 CLI agent from Mistral with file, search, VCS, and exec tools, MCP support, and explicit on-prem and VPC deployment for regulated DevOps teams.


## AI-Powered Kubernetes

AI tools specifically designed for Kubernetes cluster management, troubleshooting, and operations.

- [Glasskube](https://github.com/glasskube/glasskube) - Open-source Kubernetes package manager with AI-assisted package discovery and dependency resolution.
- [Headlamp](https://github.com/headlamp-k8s/headlamp) - Extensible Kubernetes web UI with plugin architecture that supports AI-powered cluster visualization and management.
- [K8sGPT](https://github.com/k8sgpt-ai/k8sgpt) - AI-powered Kubernetes troubleshooting and diagnostics, a CNCF Sandbox project that scans clusters for issues and explains them in plain English.
- [Kagent](https://github.com/kagent-dev/kagent) - CNCF Sandbox AI agent framework for DevOps and platform engineers to run agents inside Kubernetes clusters.
- [KAITO](https://github.com/kaito-project/kaito) - Kubernetes AI Toolchain Operator that simplifies LLM inference and fine-tuning workloads on clusters, a CNCF Sandbox project.
- [Karpenter](https://github.com/kubernetes-sigs/karpenter) - Kubernetes node autoscaler that uses intelligent bin-packing and just-in-time provisioning to optimize cluster resources and costs.
- [KServe](https://github.com/kserve/kserve) - Standardized distributed AI inference platform for Kubernetes supporting multi-framework model serving with autoscaling and canary rollouts.
- [KubeStellar Console](https://github.com/kubestellar/console) - Multi-cluster Kubernetes dashboard with AI-powered operations, MCP server for natural-language cluster management, and real-time observability across edge and cloud clusters. CNCF Sandbox project.
- [Komodor](https://komodor.com/) - Kubernetes troubleshooting platform with AI-driven root cause analysis, change tracking, and automated remediation workflows.
- [kubectl-ai](https://github.com/GoogleCloudPlatform/kubectl-ai) - Google Cloud kubectl plugin that uses LLMs to generate and apply Kubernetes manifests from natural language.
- [Kubernetes ChatGPT Bot](https://github.com/robusta-dev/kubernetes-chatgpt-bot) - ChatGPT integration for Kubernetes troubleshooting via Slack notifications.
- [Kubeflow](https://github.com/kubeflow/kubeflow) - CNCF incubating ML platform for Kubernetes with distributed training, model serving, pipelines, and notebook environments for AI workloads.
- [Kubescape](https://github.com/kubescape/kubescape) - CNCF incubating Kubernetes security platform with runtime threat detection, SBOM generation, eBPF-based monitoring, and AI agent integration.
- [Kubeshark](https://github.com/kubeshark/kubeshark) - API traffic analyzer for Kubernetes providing real-time visibility into cluster network traffic for AI-powered anomaly detection.
- [Robusta](https://github.com/robusta-dev/robusta) - Kubernetes monitoring and troubleshooting platform with AI root cause analysis and Holmes AI integration for automated diagnostics.
- [ValidKube](https://github.com/komodorio/validkube) - Open-source tool that validates, cleans, and secures Kubernetes manifests in one interface.
- [k8m](https://github.com/weibaohui/k8m) - Lightweight Kubernetes AI dashboard with multi-cluster management, intelligent agents, and MCP support in a single-binary deployment.
- [KubeAI](https://github.com/kubeai-project/kubeai) - Kubernetes AI inference operator for serving LLMs, embeddings, and speech-to-text models with intelligent scaling and zero external dependencies.
- [Kubewall](https://github.com/kubewall/kubewall) - Single-binary Kubernetes dashboard with multi-cluster management and AI integration supporting OpenAI, Claude, Gemini, and local models.
- [vCluster](https://github.com/loft-sh/vcluster) - Virtual Kubernetes clusters for development and testing that enable isolated AI workload experimentation.
- [KAI Scheduler](https://github.com/NVIDIA/KAI-Scheduler) - CNCF Sandbox Kubernetes-native GPU scheduler by NVIDIA for AI workloads with topology-aware scheduling, gang scheduling, GPU sharing, and dynamic resource allocation.
- [llm-d](https://github.com/llm-d/llm-d) - CNCF Sandbox distributed LLM inference framework for Kubernetes by Red Hat, IBM, and Google with disaggregated serving, intelligent scheduling, and vendor-neutral accelerator support.
- [NVIDIA AI Cluster Runtime](https://github.com/NVIDIA/aicr) - NVIDIA's alpha release AI cluster runtime with aicr CLI, API server, cluster agent, and validated recipes for training and inference on H100 and Blackwell accelerators.
- [Sedai](https://sedai.io/) - Autonomous Kubernetes optimization platform using reinforcement learning to continuously tune scaling, compact clusters, and remediate issues in copilot or full autopilot mode.
- [Velero](https://github.com/vmware-tanzu/velero) - CNCF Sandbox Kubernetes backup, disaster recovery, and migration tool donated by Broadcom with AI-assisted scheduling and restore workflows.
- [Causely](https://www.causely.ai/) - Causal AI platform with MCP server for diagnosing Kubernetes issues, cutting agent token use 60% and raising root-cause accuracy versus Claude Code, Codex, and HolmesGPT.
- [Parity](https://www.tryparity.com/) - YC-backed AI SRE purpose-built for on-call Kubernetes engineers, conducting root-cause investigation, runbook execution, and cluster dialog before the engineer is paged.
- [Azure SRE Agent](https://azure.microsoft.com/en-us/products/sre-agent) - Microsoft's GA AI ops teammate for AKS that investigates and, with governance approval, executes remediation through Azure Monitor, Resource Graph, and AKS diagnostics.
- [NVIDIA Grove](https://github.com/ai-dynamo/grove) - Kubernetes API for orchestrating complex multi-node AI inference with hierarchical gang scheduling, topology-aware placement, and PodCliqueScalingGroups, part of the NVIDIA Dynamo ecosystem.
- [Agent Sandbox](https://github.com/kubernetes-sigs/agent-sandbox) - Kubernetes SIG Apps subproject providing a Sandbox CRD for isolated, stateful AI-agent workloads using gVisor or Kata at up to 300 sandboxes per second, the emerging K8s primitive for running untrusted LLM-generated code.
- [Microsoft Agent Governance Toolkit](https://github.com/microsoft/agent-governance-toolkit) - Sidecar-deployable runtime policy engine that enforces all 10 OWASP agentic-AI risks with sub-millisecond decisions on AKS, the first open-source agent guardrail toolkit built for Kubernetes deployment.
- [KubeCopilot Core](https://github.com/kubecopilot/kubecopilot-core) - Kubernetes operator that deploys an in-cluster Copilot AI agent controlled via CRDs, engine-agnostic across OpenAI, Claude, and Gemini for natural-language cluster operations.
- [kube-agent](https://github.com/feiskyer/kube-agent) - Autonomous AI agent for Kubernetes that plans and executes multi-step cluster operations from the kube-copilot author, one of the few openly autonomous K8s agents beyond chat-only assistants.
- [LLMKube](https://github.com/defilantech/llmkube) - Operator for local LLM inference on Kubernetes with llama.cpp, vLLM, and TGI backends, targeting air-gapped and sovereign AI workloads with multi-GPU autoscaling.
- [OpenSRE](https://github.com/Tracer-Cloud/opensre) - Open-source toolkit and training/eval environment for building AI SRE agents that resolve incidents across Kubernetes, EC2, Lambda, ECS, and Flink with 60+ tool connectors and scored synthetic RCA evals.

## AI-Powered Terraform and IaC

Tools that bring AI capabilities to Infrastructure as Code workflows.

- [Atmos](https://github.com/cloudposse/atmos) - Universal tool for DevOps workflows that provides a framework for managing Terraform configurations at scale with AI-assisted component discovery.
- [AWS Terraform MCP Server](https://pypi.org/project/awslabs.terraform-mcp-server/) - AWS Labs MCP server with Terraform best practices, Checkov security scanning, and AWS provider documentation search.
- [Brainboard](https://www.brainboard.co/) - Visual Terraform designer with AI-powered architecture generation from cloud diagrams.
- [Env0](https://www.env0.com/) - Self-service infrastructure platform with AI-assisted policy enforcement, cost estimation, and drift detection for Terraform.
- [Firefly](https://www.firefly.ai/) - Cloud asset management that uses AI to detect drift, generate Terraform from existing resources, and manage IaC coverage gaps.
- [Infracost](https://github.com/infracost/infracost) - Cloud cost estimates for Terraform in pull requests, supporting 1,100+ AWS, Azure, and GCP resources.
- [OpenTofu](https://github.com/opentofu/opentofu) - Open-source Terraform fork maintained by the Linux Foundation, the community-driven foundation for AI-enhanced IaC workflows.
- [Pulumi AI](https://www.pulumi.com/ai/) - Generates Pulumi IaC programs from natural language using AI, supporting AWS, Azure, GCP, and Kubernetes.
- [Spacelift AI](https://spacelift.io/) - AI-enhanced IaC management platform with drift detection, policy-as-code, and automated remediation.
- [Terraform Copilot Prompts](https://github.com/zloeber/terraform-copilot-prompts) - GitHub Copilot prompts for creating and converting Terraform configurations across cloud providers.
- [Terrascan](https://github.com/tenable/terrascan) - Static code analyzer for IaC that detects compliance and security violations across Terraform, Kubernetes, and Helm.
- [Terramate](https://github.com/terramate-io/terramate) - Orchestration and code generation tool for Terraform that simplifies managing complex multi-stack infrastructure.
- [tfswitch](https://github.com/warrensbox/terraform-switcher) - Command-line tool to switch between different versions of Terraform essential for managing multi-version IaC pipelines.
- [ControlMonkey](https://controlmonkey.io/) - Infrastructure governance and resilience platform for Terraform and OpenTofu with AI-powered drift remediation, automatic IaC generation from cloud resources, and compliance guardrails.
- [Terracotta AI](https://tryterracotta.com/) - AI-powered IaC PR reviewer (YC) for Terraform, OpenTofu, and CDK-TF code providing plan analysis, drift detection, IAM security, cost impact, and architecture diagrams on every pull request.
- [Resourcely](https://www.resourcely.io/) - Terraform and OpenTofu guardrails platform with reusable blueprints and the Really policy language enforced at PR time, reducing manual review overhead in regulated infrastructure.
- [Terrateam](https://github.com/terrateamio/terrateam) - Open-source MPL-2.0 GitOps IaC orchestration for Terraform, OpenTofu, Terragrunt, CDKTF, and Pulumi via GitHub or GitLab pull requests with an OPA and Rego policy engine.
- [Pulumi Neo](https://www.pulumi.com/product/neo/) - Agentic AI platform engineer that provisions, governs, and optimizes multi-cloud Infrastructure as Code end-to-end with delegation through the Pulumi MCP server.
- [HashiCorp Project Infragraph](https://developer.hashicorp.com/hcp/docs/infragraph) - Real-time infrastructure knowledge graph powering agentic AI reasoning over Terraform state, cloud APIs, and Kubernetes resources for HashiCorp's IBM-era platform vision.
- [HashiCorp Agent Skills](https://www.hashicorp.com/en/blog/introducing-hashicorp-agent-skills) - Official Claude Code plugin pack with Skills for generating, refactoring, and testing Terraform and Packer configurations using HashiCorp best practices.
- [Overmind](https://github.com/overmindtech) - AI-powered Terraform blast-radius risk analysis and assistant that discovers unmanaged AWS resources and converts them to Terraform, with PR-level impact visualization.
- [Saturnhead AI](https://spacelift.io/blog/introducing-saturnhead-ai) - Spacelift's generative AI engine that auto-explains failed Terraform run logs across init, plan, and apply phases in natural language for faster troubleshooting.
- [Quali Torque](https://www.quali.com/agentic-ai/) - Agentic control-plane platform with modular AI agents for blueprint creation, cost modeling, drift remediation, and FinOps guardrails across IaC and GPU infrastructure.

## AI Incident Response and Troubleshooting

AI systems that detect, investigate, and remediate production incidents.

- [BigPanda](https://www.bigpanda.io/) - AIOps platform for event correlation, automated root cause analysis, and intelligent incident management across hybrid environments.
- [Blameless](https://www.blameless.com/) - SRE platform with AI-powered incident management, automated retrospectives, and reliability insights across distributed systems.
- [FireHydrant](https://firehydrant.com/) - Incident management platform with AI-powered retrospective generation, automated status pages, and runbook execution.
- [GitHub Agentic Workflows](https://github.github.io/gh-aw/) - Run AI agents in GitHub Actions for automated issue triage, CI failure analysis, and PR review.
- [HolmesGPT](https://github.com/HolmesGPT/holmesgpt) - Agentic AI troubleshooting for Kubernetes and cloud-native environments, a CNCF Sandbox project combining observability telemetry with LLM reasoning.
- [incident.io](https://incident.io/) - Incident management platform with AI-powered summaries, automated workflows, and native Slack integration for end-to-end response.
- [IncidentFox](https://github.com/incidentfox/incidentfox) - Open-source AI SRE platform for automated incident investigation, hypothesis formation, and fix suggestions with Slack and PagerDuty integration.
- [Moogsoft](https://www.moogsoft.com/) - AIOps platform with AI-driven noise reduction, correlation, and situation awareness for reducing alert fatigue.
- [Opsgenie](https://www.atlassian.com/software/opsgenie) - Incident management with AI-powered alert routing, on-call scheduling, and intelligent escalation by Atlassian.
- [PagerDuty AIOps](https://www.pagerduty.com/platform/aiops/) - AI event correlation, noise reduction, and intelligent routing that reduces alert fatigue with ML-based grouping.
- [Keep](https://github.com/keephq/keep) - Open-source AIOps platform that correlates, deduplicates, and routes alerts from any monitoring tool with AI-powered noise reduction and workflow automation.
- [Rootly](https://rootly.com/) - AI-powered incident management with automated timelines, AI-generated postmortems, and Slack-native workflows.
- [Shoreline](https://shoreline.io/) - AI-powered incident automation that converts runbooks into automated remediation executing across fleets.
- [Tracecat](https://github.com/TracecatHQ/tracecat) - Open-source AI automation for security and reliability operations with 100+ integrations and sandboxed execution.
- [Cleric](https://cleric.ai/) - Autonomous AI SRE that maps architecture, tests hypotheses across logs and metrics, and delivers root-cause diagnoses with confidence scores in Slack, named a Gartner Cool Vendor 2025.
- [Resolve AI](https://resolve.ai/) - Agentic AI production engineer for Kubernetes, AWS, and GitHub targeting 80% autonomous alert resolution, founded by ex-Splunk OpenTelemetry creators with $1B unicorn valuation.
- [NeuBird Hawkeye](https://neubird.ai/) - Agentic AI SRE for hybrid and multi-cloud incident resolution with Datadog, Splunk, PagerDuty, and ServiceNow integrations, available SaaS or VPC with SOC-2 compliance.
- [Edge Delta](https://edgedelta.com/) - Telemetry pipelines combined with AI Teammates, a role-aware multi-agent team covering SRE, DevOps, security, and cloud that autonomously investigates anomalies.
- [Traversal](https://www.traversal.com/) - AI SRE using causal ML and reinforcement learning on a Production World Model to surface ranked root causes with confidence scores, backed by Amex Ventures.
- [Datafruit](https://datafruit.dev/) - Agentic DevOps engineer (YC S25) that learns infra and deploy standards and handles ops requests like preview environments, secret rotation, and cost spikes via Slack.
- [SRE.ai](https://www.sre.ai/) - YC-backed AI DevOps platform delivering autonomous agents for enterprise CI, test, and incident workflow automation, raised $7.2M seed in August 2025.
- [AWS Security Incident Response Agent](https://aws.amazon.com/blogs/security/aws-launches-ai-enhanced-security-innovations-at-reinvent-2025/) - AWS-native agentic AI for autonomous on-call incident response launched at re:Invent 2025 alongside the Security Agent and DevOps Agent trio.

## AI Monitoring and Observability

AI-enhanced monitoring, alerting, and observability platforms.

- [Arize Phoenix](https://github.com/Arize-ai/phoenix) - Open-source AI observability platform with OpenTelemetry-based tracing, model drift detection, and RAG debugging for production AI systems.
- [Chronosphere](https://chronosphere.io/) - Cloud-native observability platform with AI-driven data optimization that reduces telemetry costs while preserving critical signals.
- [Coralogix](https://coralogix.com/) - Full-stack observability with AI-powered log analysis, anomaly detection, and cost-effective data management.
- [Datadog Bits AI](https://www.datadoghq.com/product/platform/bits-ai/) - AI assistant for natural language metric queries, root cause analysis, and automated investigation across infrastructure.
- [Dynatrace Davis AI](https://docs.dynatrace.com/docs/platform/davis-ai) - Causal AI engine for automated root cause analysis, impact assessment, and predictive problem detection.
- [Grafana](https://github.com/grafana/grafana) - Open-source monitoring and observability platform that serves as the foundation for AI-powered monitoring workflows.
- [Grafana AI](https://grafana.com/products/cloud/ai-tools-for-observability/) - Built-in AI agents for observability including SRE agent for root cause analysis, adaptive telemetry for cost reduction, and AI-assisted query generation.
- [Groundcover](https://www.groundcover.com/) - eBPF-based observability platform with AI-powered root cause analysis that requires zero instrumentation.
- [Honeycomb](https://www.honeycomb.io/) - Observability platform with AI-powered query assistant that translates natural language into complex queries for debugging distributed systems.
- [Metoro Guardian](https://metoro.io/) - AI observability copilot combining telemetry and code analysis for accurate root cause identification and auto-generated fix PRs.
- [New Relic AI](https://newrelic.com/platform/new-relic-ai) - AI monitoring assistant with natural language querying, anomaly explanation, and intelligent alert correlation.
- [Prometheus Operator](https://github.com/prometheus-operator/prometheus-operator) - Cloud-native monitoring foundation essential for AI-powered alerting pipelines, a CNCF project.
- [Splunk AI](https://www.splunk.com/en_us/products.html) - AI-powered analytics platform for natural language search, anomaly detection, and predictive insights across IT infrastructure.
- [Sumo Logic](https://www.sumologic.com/) - Cloud-native machine data analytics with AI-driven log analysis, threat detection, and infrastructure intelligence.
- [Thanos](https://github.com/thanos-io/thanos) - CNCF incubating highly available Prometheus setup with long-term storage and global query view for large-scale monitoring.
- [OpenObserve](https://github.com/openobserve/openobserve) - Open-source observability platform built in Rust covering logs, metrics, and traces with 140x lower storage costs and SQL query interface.
- [Opswald](https://www.opswald.com/ai-agent-debugging/) - AI agent debugging and observability platform that captures prompts, retrieved context, tool calls, retries, outputs, and side effects so engineers can replay failures and trace the first unsupported decision in production runs.
- [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - Fast, cost-effective monitoring solution and time series database compatible with Prometheus and Grafana.
- [Coroot](https://github.com/coroot/coroot) - Open-source observability and APM tool with AI-powered root cause analysis, eBPF-based zero-instrumentation telemetry, deployment tracking, and SLO-based alerting.
- [Apache SkyWalking](https://github.com/apache/skywalking) - Full-stack open-source APM with distributed tracing, service topology, and eBPF-powered Kubernetes monitoring for microservices and cloud-native architectures.
- [Dash0](https://dash0.com/) - OpenTelemetry-native observability platform with Agent0, specialized AI agents for SRE, cost optimization, migration, and security that transform telemetry into autonomous action.
- [SigNoz](https://github.com/SigNoz/signoz) - Open-source OpenTelemetry-native APM unifying logs, metrics, and traces with native LLM and AI-app observability for frameworks like CrewAI and Vercel AI SDK.
- [Flip AI](https://www.flip.ai/) - DevOps-specific LLM that predicts incidents and generates root-cause analyses in seconds across Datadog, Splunk, and AppDynamics with on-prem, hybrid, and multi-cloud deployment.
- [Coralogix Olly](https://ollyhq.com/) - Autonomous AI observability agent that correlates logs, metrics, and traces with natural-language queries and code-aware root cause analysis, launched with Coralogix's $115M unicorn round.
- [LogicMonitor Edwin AI](https://www.logicmonitor.com/edwin-ai) - AIOps agent that connects 3,000+ tools, correlates alerts, performs root cause analysis, and executes remediation autonomously across hybrid infrastructure.
- [New Relic SRE Agent](https://newrelic.com/platform/sre-agent) - AI-powered SRE agent for autonomous incident diagnosis across application and infrastructure layers with Intelligent Root Cause Analysis (iRCA) across the New Relic platform.
- [AgentSight](https://github.com/eunomia-bpf/agentsight) - eBPF-based boundary tracing for AI agent observability without instrumentation, validated against Claude Code, Cursor, and Gemini CLI with under 3% overhead for runtime agent monitoring.

## AI Security Scanning

AI-powered security tools for infrastructure, containers, and supply chain.

- [Aqua Security](https://www.aquasec.com/) - Cloud-native security platform with AI-powered runtime protection, image scanning, and compliance enforcement for containers.
- [Checkov](https://github.com/bridgecrewio/checkov) - Static analysis for IaC security that scans Terraform, CloudFormation, Kubernetes, Helm, and Dockerfile for misconfigurations.
- [Falco](https://github.com/falcosecurity/falco) - CNCF graduated cloud-native runtime security project for threat detection in containers and Kubernetes.
- [GitGuardian](https://www.gitguardian.com/) - AI-powered secrets detection that scans Git repositories, CI/CD pipelines, and Docker images for exposed credentials.
- [Endor Labs](https://www.endorlabs.com/) - AI-powered dependency management that identifies reachable vulnerabilities and reduces false positives in software supply chains.
- [Lacework](https://www.lacework.com/) - Cloud security platform with behavioral AI that detects anomalies and threats across cloud workloads without rules.
- [MCP-Scan](https://labs.snyk.io/) - Open-source tool for analyzing Model Context Protocol security issues and auditing MCP servers for vulnerabilities.
- [Orca Security](https://orca.security/) - Agentless cloud security with AI-powered risk prioritization across workloads, configurations, and identities.
- [Prisma Cloud](https://www.paloaltonetworks.com/prisma/cloud) - Comprehensive cloud-native application protection platform with AI-driven vulnerability prioritization and compliance.
- [Semgrep](https://github.com/semgrep/semgrep) - Fast open-source static analysis for finding bugs and enforcing code standards across 30+ languages including HCL and YAML.
- [Snyk](https://snyk.io/product/) - AI-powered security platform with DeepCode AI engine that scans code, containers, IaC, and AI-generated code in real-time.
- [Socket](https://socket.dev/) - Supply chain security platform with AI-powered detection of malicious and compromised open-source packages before they reach production.
- [SonarQube](https://www.sonarsource.com/products/sonarqube/) - Code quality and security analysis platform with AI-powered code smell detection and vulnerability identification.
- [Terraform Sentinel](https://www.hashicorp.com/sentinel) - Policy-as-code framework by HashiCorp that enforces fine-grained, logic-based policies on Terraform infrastructure changes.
- [tfsec](https://github.com/aquasecurity/tfsec) - Security scanner for Terraform code that checks for security misconfigurations and compliance violations.
- [Trivy](https://github.com/aquasecurity/trivy) - Comprehensive open-source vulnerability scanner for containers, IaC, Kubernetes, and code that is fast, accurate, and widely adopted.
- [Wiz](https://www.wiz.io/) - Cloud security platform that unifies vulnerability findings with cloud context to prioritize exploitable risks.
- [Kyverno](https://github.com/kyverno/kyverno) - CNCF incubating Kubernetes-native policy engine for validating, mutating, and generating configurations.
- [OPA Gatekeeper](https://github.com/open-policy-agent/gatekeeper) - Policy controller for Kubernetes based on Open Policy Agent for admission control and audit.
- [Sysdig](https://www.sysdig.com/) - Cloud-native security platform with Sysdig Sage AI analyst for automated threat investigation, runtime protection, and AI coding agent security monitoring.
- [AccuKnox](https://accuknox.com/) - Cloud-native zero-trust security platform with AI CoPilot for Kubernetes using eBPF-based runtime visibility, GenAI policy generation, and compliance tracking.
- [Checkmarx One](https://checkmarx.com/) - Unified application security platform combining SAST, SCA, DAST, IaC, API, container, and supply chain security with AI-powered autonomous vulnerability remediation.
- [Credo AI](https://www.credo.ai/) - AI governance and compliance platform for enforcing EU AI Act, NIST AI RMF, and other frameworks across enterprise AI systems and LLM deployments.
- [Holistic AI](https://www.holisticai.com/) - AI governance and risk management platform providing continuous audit, bias detection, and compliance tracking for AI systems in production infrastructure.
- [Microsoft Purview](https://www.microsoft.com/en-us/security/business/microsoft-purview) - Unified data governance and AI security platform with data loss prevention, insider risk management, and AI compliance controls across Microsoft 365 and Azure.
- [Aikido Security](https://www.aikido.dev/) - Unified AppSec platform combining SAST, DAST, SCA, IaC, secrets, and runtime scanning with AI AutoTriage that cuts noise 95% and AutoFix that drops false positives 85%.
- [ZeroPath](https://zeropath.com/) - AI-native SAST combining LLMs with AST analysis that found 170 verified bugs in curl and finds twice as many vulnerabilities with 75% fewer false positives.
- [Pixee](https://www.pixee.ai/) - Agentic AppSec platform that auto-triages findings and writes context-aware fix PRs with a 76% merge rate across 100,000+ PRs and up to 98% false positive removal.
- [Corgea](https://corgea.com/) - YC-backed AI security agent that finds and fixes insecure code, packages, IaC, and containers with over 90% fix accuracy, including a BLAST product targeting AI-generated code.
- [Backslash Security](https://www.backslash.security/) - Vibe coding security platform with a digital-twin approach for AI-native development covering IDEs, agents, MCPs, and AI-generated code.
- [Ghost Security](https://ghostsecurity.ai/) - Agent-native AppSec platform with the Exorcist autonomous engine, the open-source Reaper framework, and a Claude Code plugin for in-IDE vulnerability find and fix.
- [Cyera](https://www.cyera.com/) - AI-native data security posture management platform with an agentless classifier scanning hundreds of petabytes to secure the data fueling AI applications.
- [Prophet Security](https://www.prophetsecurity.ai/) - Agentic AI SOC platform with autonomous agents for Tier 1-3 alert triage, investigation, response, and threat hunting, raised $30M Series A led by Accel.
- [Dropzone AI](https://www.dropzone.ai/) - Pre-trained AI agents acting as Tier-1 SOC analysts that autonomously investigate alerts end-to-end, raised $37M Series B in 2025.
- [7AI](https://7ai.com/) - Agentic security platform from the Cybereason founders that has processed 2.5M+ alerts and raised $130M Series A — the largest Series A round in cybersecurity history.
- [Conifers CognitiveSOC](https://www.conifers.ai/) - Multi-tier AI SOC agents named a Gartner "Company to Beat" in the December 2025 AI SOC Vendor Race for enterprise-scale autonomous triage and response.
- [Hex Security](https://www.ycombinator.com/companies/hex-security) - YC W26 AI agents that run continuous autonomous penetration tests 24/7, finding vulnerabilities before attackers do.
- [Upwind](https://www.upwind.io/) - Runtime-first CNAPP with eBPF-based threat detection, AI workload security, and $250M Series B at a $1.5B valuation in January 2026.
- [HexStrike AI](https://github.com/0x4m4/hexstrike-ai) - Open-source MCP server bridging LLMs to 150+ offensive security tools for AI-driven penetration testing and red-team automation.
- [Databricks Lakewatch](https://www.databricks.com/product/lakewatch) - Open agentic SIEM on the lakehouse with Agent Bricks and Genie for automated triage, detection authoring, and natural-language-to-SQL queries, launched March 2026.
- [Microsoft Security Copilot](https://learn.microsoft.com/en-us/copilot/security/agents-overview) - Microsoft's agentic AI SOC platform extending Defender with autonomous investigation agents for alert triage, phishing analysis, and vulnerability management.

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
- [Komiser](https://github.com/tailwarden/komiser) - Open-source cloud cost management dashboard that analyzes spending across multi-cloud environments.
- [Antimetal](https://www.antimetal.com/) - AI autopilot for AWS that autonomously purchases Reserved Instances and Savings Plans based on real-time usage analysis and commitment optimization.
- [PointFive](https://www.pointfive.co/) - Multi-cloud cost optimization platform with DeepWaste detection covering 400+ checks and the Claude-powered Pointer AI assistant for actionable savings recommendations.
- [ProsperOps](https://www.prosperops.com/) - Autonomous Discount Management for AWS, Azure, and GCP commitments that manages over $6B in annual cloud spend with a no-touch optimization model.
- [Costimizer](https://costimizer.ai/) - Agentic FinOps autopilot that rightsizes workloads, auto-parks idle resources, and enforces budgets without manual intervention across AWS, Azure, and GCP.

## MCP Servers for DevOps

Model Context Protocol servers that give AI assistants like Claude, ChatGPT, and Cursor access to DevOps tools and infrastructure.

- [Atlassian MCP Server](https://www.npmjs.com/package/@anthropic/mcp-atlassian) - MCP server for Jira and Confluence integration enabling AI agents to query issues, create tickets, and search documentation.
- [AWS MCP Servers](https://awslabs.github.io/mcp/) - Official AWS MCP server suite covering Terraform, CDK, CloudFormation, Lambda, S3, CloudWatch, ECS, and more.
- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) - Comprehensive curated list of all MCP servers across every category.
- [Cloudflare MCP Server](https://github.com/cloudflare/mcp-server-cloudflare) - Official Cloudflare MCP server for managing Workers, KV, R2, and DNS from AI agents.
- [Datadog MCP Server](https://github.com/datadog-labs/mcp-server) - MCP server for querying Datadog metrics, monitors, dashboards, and logs from AI agents.
- [Docker MCP Gateway](https://github.com/docker/mcp-gateway) - Docker-maintained MCP server for container management, image operations, and Docker Compose workflows.
- [GitHub MCP Server](https://github.com/github/github-mcp-server) - Official GitHub MCP server for repos, issues, PRs, Actions, and code search from AI agents.
- [Grafana MCP Server](https://github.com/grafana/mcp-grafana) - Official Grafana MCP server for querying dashboards, datasources, and alerts from AI agents.
- [Kubernetes MCP Server](https://github.com/Flux159/mcp-server-kubernetes) - MCP server for kubectl operations, pod management, and cluster introspection.
- [KubeStellar Console MCP](https://github.com/kubestellar/console/tree/main/cmd/kc-agent) - Go-based MCP server (kc-agent) bridging kubeconfig contexts to LLMs for AI-assisted multi-cluster Kubernetes operations across edge and cloud.
- [Linear MCP Server](https://github.com/jerhadf/linear-mcp-server) - MCP server for Linear project management enabling AI agents to manage issues, projects, and cycles.
- [MCP Reference Servers](https://github.com/modelcontextprotocol/servers) - Official MCP reference implementations including filesystem, Git, GitHub, PostgreSQL, Puppeteer, and more.
- [PagerDuty MCP Server](https://github.com/PagerDuty/pagerduty-mcp-server) - MCP server for PagerDuty incident management, on-call schedules, and alert routing from AI agents.
- [Sentry MCP Server](https://github.com/getsentry/sentry-mcp) - Official Sentry MCP server for error tracking, issue search, and event analysis from AI agents.
- [Terraform MCP Server](https://github.com/hashicorp/terraform-mcp-server) - Official HashiCorp MCP server for Terraform module search, provider documentation, and policy enforcement.
- [Argo CD MCP Server](https://github.com/argoproj-labs/mcp-for-argocd) - Official Argo Project MCP server enabling AI assistants to list, inspect, sync, and manage Argo CD applications via natural language.
- [Azure DevOps MCP Server](https://github.com/microsoft/azure-devops-mcp) - Official Microsoft MCP server for Azure DevOps work items, pull requests, pipelines, repos, and wikis with Entra authentication.
- [GitLab MCP Server](https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/) - Official GitLab MCP server for secure AI access to projects, issues, merge requests, and CI/CD pipelines with OAuth 2.0 support.
- [Jenkins MCP Server](https://github.com/jenkinsci/mcp-server-plugin) - Official Jenkins plugin implementing an MCP server that exposes jobs, builds, and pipelines to AI assistants via SSE and streamable HTTP.
- [JFrog MCP Server](https://github.com/jfrog/jfrog-mcp-server) - Official JFrog MCP server for Artifactory repository management, artifact search, security scanning, and supply chain management via AI agents.
- [Notion MCP Server](https://developers.notion.com/docs/mcp) - Official Notion MCP server providing AI tools with semantic search across workspaces and connected sources plus page creation capabilities.
- [Prometheus MCP Server](https://github.com/pab1it0/prometheus-mcp-server) - MCP server for querying Prometheus metrics via PromQL from AI agents, compatible with Claude Desktop, VS Code, and Cursor.
- [Slack MCP Server](https://docs.slack.dev/ai/slack-mcp-server/) - Official Slack MCP server enabling AI assistants to search messages, read channel histories, send messages, and manage canvases securely.
- [Pulumi MCP Server](https://www.pulumi.com/docs/ai/mcp-server/) - Official Pulumi MCP server for infrastructure previews, resource lookups, and delegating complex IaC tasks to Pulumi Neo from AI assistants.
- [Vercel MCP Server](https://github.com/vercel/mcp-adapter) - MCP adapter by Vercel for integrating AI agents with serverless deployment and edge function management.
- [Lens MCP Server](https://lenshq.io/) - Built-in MCP server in Lens Kubernetes IDE connecting AI coding assistants directly to Kubernetes clusters with native EKS and AKS integration.
- [StackGen MCP Server](https://docs.stackgen.com/docs/stackbuilder/mcp-integration) - MCP server for AI-powered infrastructure lifecycle management that generates policy-compliant Terraform, Kubernetes manifests, and Helm charts from natural language.
- [GCP gcloud MCP Server](https://github.com/googleapis/gcloud-mcp) - Official Google Cloud MCP server enabling AI assistants to interact with GCP resources via the gcloud CLI using natural language.
- [Google Cloud Run MCP Server](https://github.com/GoogleCloudPlatform/cloud-run-mcp) - Official MCP server for deploying and managing applications on Google Cloud Run from AI agents.
- [DigitalOcean MCP Server](https://github.com/digitalocean/digitalocean-mcp) - Official DigitalOcean MCP server for managing Droplets, App Platform, databases, DOKS, networking, and Spaces via AI assistants.
- [Oracle Cloud MCP Server](https://github.com/oracle/mcp) - Official Oracle MCP server with reference implementations for managing and interacting with Oracle Cloud products.
- [New Relic MCP Server](https://github.com/newrelic/mcp-server) - Official New Relic MCP server for querying telemetry data, investigating alerts, and analyzing application performance through AI assistants.
- [Splunk MCP Server](https://github.com/CiscoDevNet/Splunk-MCP-Server-official) - Official Splunk and Cisco MCP server for running searches, querying Splunk data, and outputting results for agentic LLM workflows.
- [Elasticsearch MCP Server](https://github.com/elastic/mcp-server-elasticsearch) - Official Elastic MCP server connecting AI agents to Elasticsearch for natural language querying, analysis, and data retrieval.
- [Dynatrace MCP Server](https://github.com/dynatrace-oss/dynatrace-mcp) - Official Dynatrace MCP server bringing real-time observability data including metrics, traces, and logs into AI development workflows.
- [CircleCI MCP Server](https://github.com/CircleCI-Public/mcp-server-circleci) - Official CircleCI MCP server for interacting with pipelines, builds, and workflows through natural language in any MCP-compatible client.
- [Buildkite MCP Server](https://github.com/buildkite/buildkite-mcp-server) - Official Buildkite MCP server exposing pipelines, builds, jobs, and test data for AI tools and agents.
- [MongoDB MCP Server](https://github.com/mongodb-js/mongodb-mcp-server) - Official MongoDB MCP server for connecting Atlas, Community, or Enterprise deployments to AI assistants for natural language database management.
- [Redis MCP Server](https://github.com/redis/mcp-redis) - Official Redis MCP server providing a natural language interface for managing and searching data in Redis.
- [Neon MCP Server](https://github.com/neondatabase/mcp-server-neon) - Official Neon MCP server for managing serverless PostgreSQL projects, branches, and running SQL queries through AI assistants.
- [Supabase MCP Server](https://github.com/supabase-community/supabase-mcp) - Community Supabase MCP server for managing tables, querying data, fetching config, and database operations via AI agents.
- [HashiCorp Vault MCP Server](https://github.com/hashicorp/vault-mcp-server) - Official HashiCorp MCP server for managing secrets and mounts in Vault through AI assistants.
- [Snyk MCP Server](https://github.com/snyk/studio-mcp) - Official Snyk MCP server integrating security scanning for code, dependencies, and configurations into AI-powered development tools.
- [Trivy MCP Server](https://github.com/aquasecurity/trivy-mcp) - Official Aqua Security MCP server providing vulnerability scanning, misconfiguration detection, and secret scanning through Trivy.
- [Rootly MCP Server](https://docs.rootly.com/integrations/mcp-server) - MCP server enabling incident management within IDE environments for resolving production incidents without leaving the editor.
- [FireHydrant MCP Server](https://github.com/firehydrant/firehydrant-mcp) - Official FireHydrant MCP server for interacting with incident management API through AI assistants.
- [Incident.io MCP Server](https://github.com/incident-io/incidentio-mcp-golang) - Official incident.io MCP server connecting AI assistants to incident.io for incident management and response.
- [Ansible MCP Server](https://github.com/sibilleb/AAP-Enterprise-MCP-Server) - MCP server for Ansible Automation Platform and Event-Driven Ansible enabling AI-driven playbook execution and infrastructure automation.
- [Bitbucket MCP Server](https://github.com/MatanYemini/bitbucket-mcp) - MCP server for integrating with Bitbucket Cloud and Server APIs enabling AI agents to manage repositories, pull requests, and code reviews.
- [Cloudflare Code Mode MCP Server](https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/) - Cloudflare MCP server with Code Mode that exposes only search and execute tools backed by a type-aware SDK, reducing context footprint across 2,500+ API endpoints.
- [Render MCP Server](https://github.com/render-oss/render-mcp-server) - Official Render MCP server enabling LLMs to manage services, deploys, environments, and resources via natural language.
- [Fly.io MCP Server](https://github.com/superfly/flymcp) - Official Fly.io MCP server wrapping the flyctl CLI to provision and manage Fly machines, apps, and infrastructure from MCP clients.
- [SigNoz MCP Server](https://github.com/SigNoz/signoz-mcp-server) - Official SigNoz MCP server exposing metrics, traces, logs, alerts, dashboards, services, and ClickHouse SQL queries via natural language.
- [Coralogix MCP Server](https://coralogix.com/docs/user-guides/mcp-server/overview/) - Official Coralogix MCP server exposing logs, metrics, traces, and RUM data via remote streamable HTTP for AI-driven investigation.
- [Logz.io MCP Server](https://docs.logz.io/docs/open360/logzio-mcp/) - Official Logz.io public-API MCP server exposing logs, metrics, dashboards, and alerts to Claude, Cursor, ChatGPT, and other MCP clients.
- [ClickHouse MCP Server](https://github.com/ClickHouse/mcp-clickhouse) - Official ClickHouse MCP server for SQL queries, schema exploration, and chDB embedded engine access with read-only defaults and explicit write opt-in.
- [Turso MCP Server](https://turso.tech/blog/introducing-the-turso-database-mcp-server) - Official Turso MCP built into the Turso CLI providing nine tools for AI assistants to query and manage Turso and LibSQL databases.
- [Databricks MCP Servers](https://docs.databricks.com/aws/en/generative-ai/mcp/) - Official managed Genie Space, Vector Search, and Unity Catalog Function MCP servers giving agents governed access to structured and unstructured data.
- [Harness MCP Server](https://github.com/harness/mcp-server) - Official Harness MCP server with 10 consolidated tools across 139+ resource types covering CI/CD, GitOps, feature flags, FinOps, STO, and chaos.
- [Twilio MCP Server](https://github.com/twilio-labs/mcp) - Official Twilio Labs MCP monorepo exposing all Twilio public APIs as MCP tools, plus an OpenAPI-to-MCP generator for custom integrations.
- [Stripe MCP Server](https://github.com/stripe/agent-toolkit) - Official Stripe Agent Toolkit and remote MCP exposing payments, customers, invoices, and product APIs via local npx server or hosted OAuth-secured remote endpoint.
- [CrowdStrike Falcon MCP Server](https://github.com/CrowdStrike/falcon-mcp) - Official CrowdStrike-maintained MCP server connecting AI agents to Falcon for detections, incidents, and behaviors enabling automated threat hunting workflows.
- [Wiz MCP Server](https://www.wiz.io/blog/introducing-mcp-server-for-wiz) - Official Wiz MCP server translating natural-language queries into Wiz operations across cloud inventory, misconfigurations, and security risk posture.
- [Bitwarden MCP Server](https://github.com/bitwarden/mcp-server) - Official local-only Bitwarden MCP server giving AI assistants secure CLI-backed access to vault items and organization administration.
- [Doppler MCP Server](https://github.com/DopplerHQ/mcp-server) - Official Doppler MCP server providing AI assistants with access to the Doppler API for secrets and configuration management.
- [Hetzner Cloud MCP Server](https://github.com/dkruyt/mcp-hetzner) - MCP server for managing Hetzner Cloud resources including servers, networks, and volumes via natural language with AI assistants.
- [Snowflake MCP Server](https://github.com/Snowflake-Labs/mcp) - Official Snowflake Labs MCP server with Cortex AI integration, object management, and SQL orchestration for AI-driven data warehouse operations.
- [MCP Toolbox for Databases](https://github.com/googleapis/mcp-toolbox) - Google's open-source MCP server covering BigQuery, Spanner, AlloyDB, Cloud SQL, and 15+ databases for unified AI database access.
- [LaunchDarkly MCP Server](https://github.com/launchdarkly/mcp-server) - Official LaunchDarkly MCP server for managing feature flags, targeting rules, segments, and AI configs through natural language.
- [Unleash MCP Server](https://github.com/cuongtl1992/unleash-mcp) - MCP server for the Unleash open-source feature toggle system enabling AI agents to read and toggle flags.
- [Temporal MCP Server](https://github.com/alisaitteke/temporal-mcp) - MCP server for running, querying, and signaling Temporal workflows from AI assistants for durable execution use cases.
- [Istio MCP Server](https://github.com/krutsko/istio-mcp-server) - MCP server providing read-only access to Istio Virtual Services, Destination Rules, Gateways, and Envoy configs for AI-driven service mesh diagnosis.

- [TWZRD Agent Intel](https://intel.twzrd.xyz) - Trust scoring and preflight checks for AI agents on Solana before executing paid runbooks or remediation API calls via x402 micropayments. Free MCP: `{"mcpServers":{"twzrd-agent-intel":{"url":"https://intel.twzrd.xyz/mcp"}}}`
## AI-Powered CI/CD

AI tools that enhance continuous integration and delivery pipelines.

- [ArgoCD](https://github.com/argoproj/argo-cd) - CNCF GitOps continuous delivery for Kubernetes that serves as the foundation for AI-driven deployment workflows.
- [Buildkite](https://buildkite.com/) - CI/CD platform with AI-powered test analytics, flaky test detection, and intelligent pipeline optimization for infrastructure builds.
- [CircleCI](https://circleci.com/) - Cloud CI/CD platform with AI-powered test splitting, flaky test detection, and pipeline optimization insights.
- [Codefresh](https://codefresh.io/) - GitOps CI/CD platform built on Argo with AI-assisted pipeline creation and deployment analytics.
- [Dagger](https://github.com/dagger/dagger) - Programmable CI/CD engine that runs pipelines in containers, enabling AI agents to compose and execute build workflows.
- [Depot](https://depot.dev/) - Managed CI build infrastructure with up to 40x faster Docker builds through intelligent layer caching and remote execution.
- [GitLab Duo](https://about.gitlab.com/gitlab-duo/) - AI across the GitLab DevSecOps platform with code suggestions, root cause analysis, vulnerability resolution, and CI/CD pipeline generation.
- [Harness AIDA](https://www.harness.io/products/aida) - AI Development Assistant for intelligent pipeline creation, failure analysis, and deployment optimization.
- [Mergify](https://mergify.com/) - AI-powered merge queue and PR automation with intelligent batch merging and conflict resolution.
- [PR-Agent](https://github.com/qodo-ai/pr-agent) - AI-powered pull request analysis that auto-describes, reviews, improves, and generates tests for GitHub, GitLab, and Bitbucket.
- [Tekton](https://github.com/tektoncd/pipeline) - Cloud-native CI/CD building blocks for Kubernetes providing the foundation for AI-orchestrated build and deploy pipelines.
- [Trunk](https://trunk.io/) - Developer experience platform with AI-powered code quality checks, merge queues, and flaky test management.
- [Devtron](https://github.com/devtron-labs/devtron) - Kubernetes-native DevOps platform with AI-driven cost optimization, multi-cluster management, and integrated CI/CD with canary deployments and automated rollbacks.
- [Woodpecker CI](https://github.com/woodpecker-ci/woodpecker) - Community fork of Drone CI with a simple pipeline engine, container-native execution, and multi-platform support.
- [Claude Code Review](https://github.com/anthropics/claude-code-security-review) - Anthropic's multi-agent GitHub Action that analyzes pull requests for logic errors, race conditions, data handling mistakes, API misuse, and security vulnerabilities in parallel.
- [Cursor BugBot](https://cursor.com/bugbot) - AI code review bot from Cursor that reviews 2 million+ PRs monthly using 8 parallel review passes with randomized diff order to catch bugs single-pass reviewers miss.
- [Mendral](https://www.mendral.com/) - Always-on AI DevOps engineer (YC W26) that autonomously diagnoses CI failures, fixes flaky tests, and opens fix PRs with a 75% acceptance rate.
- [Momentic](https://momentic.ai/) - AI-native automated testing platform (YC) that writes, runs, and maintains end-to-end tests for CI/CD pipelines with self-healing capabilities.
- [Stably AI](https://www.stably.ai/) - AI testing platform (YC, Vercel Ventures) that auto-writes, runs, and maintains diff-aware end-to-end tests directly in CI with automatic selector healing.
- [testRigor](https://testrigor.com/) - AI-driven codeless testing platform that integrates into CI/CD pipelines with natural language test creation and intelligent test maintenance.
- [Testsigma](https://github.com/testsigmahq/testsigma) - Open-source agentic AI test automation platform with self-healing tests, natural language test creation, and CI/CD integration.

## AI Log Analysis and Debugging

AI tools for log analysis, pattern detection, and debugging production systems.

- [agenttrace](https://github.com/luoyuctl/agenttrace) - Local TUI for inspecting AI coding agent logs across cost, token usage, latency, failures, and reports.
- [Axiom](https://axiom.co/) - Cloud-native log management with AI-powered query generation, anomaly detection, and unlimited data retention.
- [Elasticsearch](https://github.com/elastic/elasticsearch) - Foundation for AI-powered log analysis with ES|QL, vector search, and ML anomaly detection.
- [Grafana Loki](https://github.com/grafana/loki) - Log aggregation system designed for cloud-native environments that pairs with Grafana AI for intelligent log querying.
- [LogAI](https://github.com/salesforce/logai) - Salesforce's open-source toolkit for AI-powered log analysis with ML algorithms for anomaly detection, clustering, and summarization.
- [OpenTelemetry Collector](https://github.com/open-telemetry/opentelemetry-collector) - Vendor-agnostic telemetry collection that serves as the essential pipeline for feeding logs, metrics, and traces to AI analysis tools.
- [Parseable](https://github.com/parseablehq/parseable) - Cloud-native log storage and observability platform built in Rust with AI-powered log analysis and alerting.
- [Vector](https://github.com/vectordotdev/vector) - High-performance observability data pipeline for collecting, transforming, and routing logs, metrics, and traces to AI analysis backends.
- [Zebrium](https://www.zebrium.com/) - ML-powered root cause analysis from logs that automatically identifies incident root cause without manual queries.
- [Fluentd](https://github.com/fluent/fluentd) - CNCF graduated unified logging layer for collecting, filtering, and routing logs from any source to any destination.
- [Fluent Bit](https://github.com/fluent/fluent-bit) - Fast and lightweight log processor and forwarder for Linux, macOS, and embedded systems built for cloud-native environments.
- [Langfuse](https://github.com/langfuse/langfuse) - Open-source LLM observability platform with tracing, prompt management, and evaluations for monitoring AI agents in DevOps pipelines.
- [OpenLLMetry](https://github.com/traceloop/openllmetry) - OpenTelemetry-compatible observability project for AI agents providing standardized instrumentation for OpenAI, Anthropic, and other LLM providers.
- [Braintrust](https://braintrust.dev/) - AI observability and evaluation platform for monitoring LLM applications and AI agents in production with trace capture, automated scoring, and real-time feedback loops.

## AI Agent Frameworks for Infrastructure

General-purpose AI agent frameworks with strong infrastructure and DevOps use cases.

- [AutoGen](https://github.com/microsoft/autogen) - Microsoft's multi-agent framework supporting infrastructure workflows with tool use, code execution, and human-in-the-loop approvals.
- [Claude Agent SDK](https://docs.anthropic.com/en/docs/agents) - Anthropic's framework for building agentic applications with tool use, orchestration, and guardrails for infrastructure automation.
- [CrewAI](https://github.com/crewAIInc/crewAI) - Multi-agent orchestration framework for building teams of AI agents that handle complex infrastructure tasks like migration planning.
- [Dify](https://github.com/langgenius/dify) - LLM application development platform with agent workflows, RAG, and model management for building custom DevOps chatbots.
- [Haystack](https://github.com/deepset-ai/haystack) - Open-source LLM framework by deepset for building RAG pipelines and AI agents with infrastructure knowledge bases.
- [LangChain](https://github.com/langchain-ai/langchain) - Framework for building LLM-powered applications, widely used for building custom DevOps agents with tool integrations.
- [LangChain Deep Agents](https://github.com/langchain-ai/deepagents) - Reference agent harness from LangChain with built-in planning tools, filesystem backend, and subagent spawning for complex infrastructure tasks.
- [LangGraph](https://github.com/langchain-ai/langgraph) - Library for building stateful, multi-actor applications with LLMs, ideal for complex infrastructure orchestration workflows.
- [Llama Stack](https://github.com/meta-llama/llama-stack) - Meta's unified deployment stack with inference, agents, safety, and evaluation APIs for running open-source LLMs in production AI workloads.
- [LlamaIndex](https://github.com/run-llama/llama_index) - Data framework for LLM applications with indexing, retrieval, and agent capabilities for infrastructure documentation and knowledge bases.
- [Mastra](https://github.com/mastra-ai/mastra) - TypeScript AI agent framework with built-in tool integrations, workflows, and RAG for building DevOps automation agents.
- [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) - Microsoft's unified .NET and Python SDK that merges Semantic Kernel and AutoGen with MCP, A2A, graph workflows, and multi-agent orchestration.
- [n8n](https://github.com/n8n-io/n8n) - Workflow automation platform with 400+ integrations and AI agent capabilities for low-code DevOps automation.
- [Google ADK](https://github.com/google/adk-python) - Google's open-source code-first framework for building multi-agent systems with workflow agents, MCP tool integration, and Cloud Run deployment.
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) - OpenAI's framework for building multi-agent systems with handoffs, guardrails, and tracing for infrastructure automation.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) - Type-safe AI agent framework with native MCP support, 25+ model providers, and OpenTelemetry-based observability for DevOps automation.
- [smolagents](https://github.com/huggingface/smolagents) - Minimalist open-source AI agent library from Hugging Face where agents write and execute Python code directly with sandboxed execution.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - Microsoft's SDK for integrating LLMs into applications with plugin architecture ideal for building infrastructure automation agents.
- [Temporal](https://github.com/temporalio/temporal) - Durable execution platform for orchestrating long-running infrastructure workflows with built-in retry and failure handling.
- [DSPy](https://github.com/stanfordnlp/dspy) - Stanford framework for programming language models with automatic prompt optimization and weight tuning, ideal for building reliable DevOps AI pipelines.
- [OpenClaw](https://github.com/openclaw/openclaw) - Open-source personal AI assistant with 50+ integrations across messaging platforms, self-extending agent skills, and fully local execution for privacy.
- [Wren AI](https://github.com/Canner/WrenAI) - Open-source text-to-SQL AI agent that generates SQL queries from natural language for infrastructure analytics and reporting.
- [MetaGPT](https://github.com/geekan/MetaGPT) - Multi-agent software development framework that simulates an AI software company with product managers, architects, engineers, and QA agents collaborating on requirements-to-code pipelines.
- [Letta](https://github.com/letta-ai/letta) - Open-source platform for stateful agents with self-editing memory evolved from MemGPT, including Letta Code, Letta Evals, and Context Repositories for long-running infrastructure agents.
- [Strands Agents](https://github.com/strands-agents) - AWS open-source model-driven SDK for Python and TypeScript with Graph, Swarm, and Workflow patterns plus native MCP and A2A protocol support.
- [BeeAI Framework](https://github.com/i-am-bee/beeai-framework) - IBM and Linux Foundation open-source multi-agent toolkit for Python and TypeScript with Agent Communication Protocol for cross-framework interoperability.
- [Agno](https://github.com/agno-agi/agno) - Lightweight pure-Python multi-modal agent framework with built-in FastAPI runtime, 100+ integrations, and agentic RAG for DevOps automation.
- [Mirascope](https://github.com/Mirascope/mirascope) - Pythonic LLM toolkit positioned as an anti-framework with a unified provider interface across OpenAI, Anthropic, Mistral, and Gemini plus structured outputs via Pydantic.
- [Kubiya](https://www.kubiya.ai/) - Agentic engineering platform with deterministic execution, MCP-based tool integration, and Slack and Teams natural-language interface for Terraform and CI/CD automation.
- [agentgateway](https://github.com/agentgateway/agentgateway) - AI-native Rust-built proxy with deep MCP and A2A protocol awareness, inference gateway support, and unified LLM routing for agentic systems contributed by Solo.io.
- [open-multi-agent](https://github.com/JackChen-me/open-multi-agent) - TypeScript-native multi-agent orchestrator that decomposes a goal into a task DAG with MCP integration and live tracing for transparent execution.
- [Composio Agent Orchestrator](https://github.com/ComposioHQ/agent-orchestrator) - Parallel coding-agent fleet manager with per-agent git worktrees, autonomous CI fix-up, and merge-conflict handling for large-scale agent workflows.

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
- [Roadie](https://roadie.io/) - Managed Backstage platform with AI-powered scaffolding, TechDocs hosting, and developer productivity insights.
- [Upbound](https://www.upbound.io/) - Universal cloud platform built on Crossplane for building internal platforms with declarative infrastructure APIs.
- [Score](https://github.com/score-spec/spec) - Open-source workload specification that eliminates configuration drift between local and remote environments.
- [StackGen](https://stackgen.com/) - Autonomous infrastructure platform with AI agents that generate validated, policy-compliant Terraform from natural language descriptions.
- [OpenChoreo](https://github.com/openchoreo/openchoreo) - CNCF Sandbox Internal Developer Platform (Jan 2026) exposing MCP servers so AI agents deploy components and reason about platform state, with a built-in SRE LLM agent.

## AI for Database Operations

AI tools for database management, query optimization, and data operations.

- [Aiven AI](https://aiven.io/) - Managed database platform with AI-powered query optimization, anomaly detection, and automated performance tuning.
- [Bytebase](https://github.com/bytebase/bytebase) - Database DevOps and CI/CD platform with AI-assisted schema review, migration management, and SQL linting.
- [CloudNativePG](https://github.com/cloudnative-pg/cloudnative-pg) - Kubernetes operator for PostgreSQL that manages the full lifecycle of PostgreSQL clusters with automated failover.
- [Drizzle](https://github.com/drizzle-team/drizzle-orm) - TypeScript ORM with declarative schema migrations and AI-friendly type-safe query building for infrastructure databases.
- [Metabase](https://github.com/metabase/metabase) - Open-source BI platform with natural language querying that enables non-technical users to explore infrastructure databases.
- [Neon](https://github.com/neondatabase/neon) - Serverless PostgreSQL with database branching, autoscaling, and AI-powered query optimization for modern infrastructure.
- [OtterTune](https://ottertune.com/) - AI-powered database optimization that automatically tunes PostgreSQL, MySQL, and MariaDB configurations for performance.
- [pganalyze](https://pganalyze.com/) - PostgreSQL performance monitoring with AI-powered query optimization recommendations and index advisor.
- [PlanetScale](https://planetscale.com/) - Serverless MySQL platform with AI-powered schema change management, query insights, and non-blocking deploys.
- [SchemaHero](https://github.com/schemahero/schemahero) - Kubernetes-native database schema management tool that applies declarative schema definitions as migrations.
- [Tembo](https://tembo.io/) - Open-source serverless PostgreSQL platform with AI-driven database optimization, error resolution, and integration with AWS RDS, Supabase, Linear, and GitHub.
- [Vitess](https://github.com/vitessio/vitess) - CNCF graduated database clustering system for horizontal scaling of MySQL, essential for AI workloads needing distributed data.
- [Xata](https://xata.io/) - Serverless database platform combining PostgreSQL with OpenSearch for AI applications with full-text search, vector search, and database branching in a single managed service.

## AI for Networking and Service Mesh

AI tools for network management, service mesh, and traffic engineering.

- [Calico](https://github.com/projectcalico/calico) - Cloud-native networking and security with AI-enhanced network policy management and threat detection for Kubernetes.
- [Cilium](https://github.com/cilium/cilium) - eBPF-based networking, security, and observability for Kubernetes with Hubble UI for AI-powered network flow analysis.
- [Consul](https://github.com/hashicorp/consul) - Service mesh and service discovery by HashiCorp with intentions-based security and automated traffic management.
- [Istio](https://github.com/istio/istio) - CNCF graduated service mesh providing traffic management, security, and observability for microservices architectures.
- [Linkerd](https://github.com/linkerd/linkerd2) - CNCF graduated ultralight service mesh for Kubernetes with automated mTLS, traffic splitting, and golden metrics.
- [Ngrok](https://ngrok.com/) - Unified ingress platform with AI-powered traffic inspection, policy enforcement, and API gateway capabilities.
- [Traefik](https://github.com/traefik/traefik) - Cloud-native application proxy with automatic service discovery, Let's Encrypt integration, and observability features.
- [Envoy](https://github.com/envoyproxy/envoy) - CNCF graduated high-performance edge and service proxy powering the data plane for Istio and other service meshes.

## AI for Container Security and Supply Chain

AI tools for container image security, software supply chain, and build verification.

- [Chainguard](https://www.chainguard.dev/) - Secure container images and supply chain tools with zero known CVEs, built for reducing vulnerability remediation.
- [Cosign](https://github.com/sigstore/cosign) - Container signing and verification tool from the Sigstore project for supply chain security.
- [Docker Scout](https://docs.docker.com/scout/) - Docker's AI-powered supply chain security for image analysis, CVE remediation guidance, and base image recommendations.
- [Grype](https://github.com/anchore/grype) - Fast open-source vulnerability scanner for container images and filesystems with SBOM-based analysis.
- [Harbor](https://github.com/goharbor/harbor) - CNCF graduated cloud-native registry with vulnerability scanning, image signing, and policy-based image replication.
- [Slim.AI](https://www.slim.ai/) - Container optimization platform with AI-powered image analysis, vulnerability reduction through minification.
- [Copa](https://github.com/project-copacetic/copacetic) - Directly patches container image vulnerabilities without rebuilding, reducing the time to remediate CVEs in production images.
- [Syft](https://github.com/anchore/syft) - Open-source SBOM generator for container images and filesystems supporting multiple output formats.
- [Wolfi](https://github.com/wolfi-dev/os) - Community Linux distribution designed for building minimal container images with automated CVE patching.

## AI for Chaos Engineering and Reliability

AI tools for chaos engineering, resilience testing, and reliability validation.

- [Chaos Mesh](https://github.com/chaos-mesh/chaos-mesh) - CNCF incubating cloud-native chaos engineering platform for Kubernetes with fault injection and workflow orchestration.
- [Gremlin](https://www.gremlin.com/) - Enterprise chaos engineering platform with AI-powered reliability recommendations and targeted failure testing.
- [k6](https://github.com/grafana/k6) - Modern load testing tool by Grafana with scriptable scenarios and AI-assisted test generation for infrastructure endpoints.
- [Litmus](https://github.com/litmuschaos/litmus) - CNCF incubating chaos engineering framework for Kubernetes with a hub of prebuilt experiments and GitOps integration.
- [Steadybit](https://www.steadybit.com/) - Chaos engineering platform with AI-assisted experiment design and automated reliability validation.
- [Testkube](https://github.com/kubeshop/testkube) - Kubernetes-native test orchestration framework for running any testing tool inside clusters with CI/CD integration.
- [Toxiproxy](https://github.com/Shopify/toxiproxy) - TCP proxy by Shopify for simulating network conditions and testing system resilience to network failures.
- [ChaosEater](https://github.com/ntt-dkiku/chaos-eater) - NTT's open-source LLM-based system that automates the entire chaos engineering cycle (hypothesis, experiment, analysis, improvement) supporting GPT, Claude, Gemini, and Ollama backends.

## AI for Cloud Migration and Modernization

AI tools that assist with cloud migration planning, execution, and application modernization.

- [AWS Application Discovery Service](https://aws.amazon.com/application-discovery/) - Automated discovery and planning for cloud migration with dependency mapping and utilization analysis.
- [AWS Migration Hub](https://aws.amazon.com/migration-hub/) - Central hub for tracking migrations across multiple AWS and partner tools with AI-powered progress tracking.
- [Azure Migrate](https://azure.microsoft.com/en-us/products/azure-migrate/) - Unified migration platform with AI-powered assessment, server migration, and database modernization tools.
- [Google Cloud Migrate](https://cloud.google.com/solutions/migration-center) - Comprehensive migration platform with AI-driven assessment, workload discovery, and total cost of ownership analysis.
- [Konveyor](https://github.com/konveyor/tackle2-hub) - Open-source migration toolkit for modernizing applications to Kubernetes with AI-assisted code transformation.
- [Zerto](https://www.zerto.com/) - Disaster recovery and workload migration platform with AI-powered resilience and continuous data protection.

## AI for GitOps

AI tools for GitOps workflows, declarative infrastructure, and continuous reconciliation.

- [Argo Rollouts](https://github.com/argoproj/argo-rollouts) - Progressive delivery controller for Kubernetes with canary deployments, blue-green releases, and automated rollback analysis.
- [Flux](https://github.com/fluxcd/flux2) - CNCF graduated GitOps toolkit for Kubernetes with automated image updates, Helm releases, and Kustomize reconciliation.
- [Helm](https://github.com/helm/helm) - CNCF graduated Kubernetes package manager essential for templating and deploying AI workloads and infrastructure components.
- [Kargo](https://github.com/akuity/kargo) - Continuous promotion and lifecycle orchestrator for Kubernetes applications across environments with GitOps principles.
- [Kustomize](https://github.com/kubernetes-sigs/kustomize) - Kubernetes configuration customization tool that enables declarative management of manifests without template engines.
- [Weave GitOps](https://github.com/weaveworks/weave-gitops) - Enterprise GitOps platform with progressive delivery, policy enforcement, and multi-cluster management.
- [Crossplane](https://github.com/crossplane/crossplane) - CNCF incubating project for building cloud-native control planes with declarative infrastructure APIs and GitOps workflows.

## System Prompt and Config Templates

Ready-to-use AI agent configurations for infrastructure repositories.

- [AGENTS.md](https://agents.md/) - Universal open standard from OpenAI for providing project-specific guidance to AI coding agents, supported across Cursor, Claude Code, Codex, and Gemini CLI.
- [Awesome CursorRules](https://github.com/PatrickJS/awesome-cursorrules) - Community-curated .cursorrules files for various project types including infrastructure and DevOps.
- [ChatGPT Prompts for DevOps](https://github.com/f/awesome-chatgpt-prompts) - Community-curated prompt library that includes DevOps and system administration automation prompts.
- [Claude Code DevOps Toolkit](https://github.com/hammadhaqqani/claude-code-devops-toolkit) - Production-tested CLAUDE.md files, curated DevOps prompts, automation scripts, and project configs for infrastructure workflows.
- [Claude Skills](https://github.com/anthropics/skills) - Anthropic's official repository of agent skills — folders of instructions, scripts, and resources that Claude loads dynamically for specialized DevOps workflows.
- [Free AI and DevOps Tools](https://hammadhaqqani.com/tools) - Collection of 41 free browser-based AI and DevOps tools including prompt builder, system prompt generator, and token counter.
- [GitHub Copilot Custom Instructions](https://docs.github.com/en/copilot/customizing-copilot/adding-custom-instructions-for-github-copilot) - Official guide for creating copilot-instructions.md to customize AI behavior per repository.
- [Awesome Claude Code](https://github.com/anthropics/claude-code) - Anthropic's official Claude Code repository with documentation, examples, and tips for infrastructure workflows.
- [DevOps GPT Prompts](https://github.com/dair-ai/Prompt-Engineering-Guide) - Comprehensive prompt engineering guide with patterns applicable to DevOps automation.

## Learning Resources

Courses, certifications, articles, and guides on AI for DevOps.

### Articles and Guides

- [FinOps for AI Overview](https://www.finops.org/wg/finops-for-ai-overview/) - FinOps Foundation guide on managing AI workload costs in the cloud.
- [HolmesGPT: Agentic Troubleshooting for Cloud Native](https://www.cncf.io/blog/2026/01/07/holmesgpt-agentic-troubleshooting-built-for-the-cloud-native-era/) - CNCF deep dive into AI-powered Kubernetes troubleshooting.
- [I Built 41 Free AI and DevOps Tools](https://hammadhaqqani.com/blog/41-free-ai-devops-tools-no-signup) - Deep dive into building client-side AI and DevOps tools that run entirely in the browser.
- [The AI Singularity Is Closer Than You Think](https://hammadhaqqani.com/blog/the-ai-singularity-is-closer-than-you-think) - First-hand account of how AI agents are replacing engineering workflows from a DevOps veteran with 10+ years of experience.
- [Top 15 AI Prompts Every DevOps Engineer Should Master](https://kubezilla.io/top-15-ai-prompts-every-devops-engineer-should-master-in-2026) - Essential prompt patterns for infrastructure automation.

### Books

- [AI Engineering](https://www.oreilly.com/library/view/ai-engineering/9781098166298/) - End-to-end guide by Chip Huyen to building applications with foundation models covering RAG, fine-tuning, agents, and evaluation in production.
- [AI Agents in Action](https://www.manning.com/books/ai-agents-in-action) - Practical guide to building trustworthy multi-agent systems with prompt engineering, personas, and collaboration patterns for high-stakes environments.
- [Designing Machine Learning Systems](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/) - Comprehensive guide to production ML systems covering infrastructure, monitoring, and deployment patterns.
- [Engineering AI Systems](https://www.pearson.com/en-us/subject-catalog/p/engineering-ai-systems-devops-and-architecture-approaches/P200000011757/9780138261450) - Combines software architecture with DevOps practices for AI systems covering reliability, security, monitoring, and observability in enterprise deployments.
- [Learning OpenTelemetry](https://www.oreilly.com/library/view/learning-opentelemetry/9781098147174/) - Practical guide to setting up and operating OpenTelemetry for modern cloud-native observability systems.
- [LLMOps](https://www.oreilly.com/library/view/llmops/9781098154196/) - Guide by Abi Aryan to running LLM systems at scale covering monitoring, evaluation, governance, security audits, and infrastructure cost management.
- [MLOps Engineering at Scale](https://www.manning.com/books/mlops-engineering-at-scale) - Shows how to put ML into production efficiently using pre-built cloud services covering the full lifecycle from training to deployment.
- [Observability Engineering](https://www.oreilly.com/library/view/observability-engineering-2nd/9781098179915/) - Second edition with expanded coverage of OpenTelemetry, trace-first telemetry, and using AI agents to instrument code.
- [Platform Engineering on Kubernetes](https://www.manning.com/books/platform-engineering-on-kubernetes) - Practical guide to building internal platforms with Kubernetes, GitOps, and developer self-service.
- [Prompt Engineering for LLMs](https://www.oreilly.com/library/view/prompt-engineering-for/9781098156145/) - Covers building LLM-based applications from few-shot learning to chain-of-thought prompting and RAG strategies.
- [Site Reliability Engineering](https://sre.google/books/) - Google's definitive SRE book covering the principles that AI tools are now automating.

### Certifications

- [AWS AI Practitioner](https://aws.amazon.com/certification/certified-ai-practitioner/) - Foundational AI and ML certification with cloud infrastructure context.
- [AWS Certified DevOps Engineer Professional](https://aws.amazon.com/certification/certified-devops-engineer-professional/) - Validates CI/CD automation, monitoring, and operations at scale on AWS.
- [AWS Certified Machine Learning Engineer Associate](https://aws.amazon.com/certification/certified-machine-learning-engineer-associate/) - Focuses on getting ML models into production using SageMaker and AWS ML services.
- [AWS Certified Generative AI Developer Professional](https://aws.amazon.com/certification/certified-generative-ai-developer-professional/) - Validates building and deploying production-ready generative AI solutions using AWS Bedrock and related services.
- [Azure DevOps Engineer Expert](https://learn.microsoft.com/en-us/credentials/certifications/exams/az-400/) - Covers designing and implementing DevOps processes including CI/CD, infrastructure as code, and compliance on Azure.
- [Azure AI Engineer Associate](https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-engineer/) - Validates building AI solutions using Azure Cognitive Services including RAG patterns and autonomous agents.
- [Certified Argo Project Associate](https://www.cncf.io/training/certification/capa/) - CNCF certification demonstrating expertise in Argo CD, Rollouts, and Workflows used for GitOps-driven ML pipeline deployments.
- [Certified Kubernetes Application Developer](https://www.cncf.io/training/certification/ckad/) - CNCF hands-on exam validating ability to design, build, and manage cloud-native applications on Kubernetes.
- [Certified Kubernetes Security Specialist](https://www.cncf.io/training/certification/cks/) - CNCF performance-based exam covering security best practices for container-based applications and Kubernetes platforms.
- [Cilium Certified Associate](https://www.cncf.io/training/certification/cca/) - CNCF certification validating eBPF-based networking, security, and observability for Kubernetes clusters.
- [CKA and KCNA](https://www.cncf.io/certification/) - CNCF Kubernetes certifications that provide essential foundation before adding AI-powered Kubernetes tools.
- [Datadog Fundamentals](https://www.datadoghq.com/certification/overview/) - Validates expertise with the Datadog observability platform for monitoring cloud infrastructure, APM, and AI system health.
- [FinOps Certified Engineer](https://learn.finops.org/path/finops-certified-engineer) - Advanced FinOps certification for engineers managing cloud infrastructure cost optimization and value delivery.
- [FinOps Certified Practitioner](https://learn.finops.org/page/finops-certified-practitioner) - Linux Foundation and FinOps Foundation certification for cloud cost management covering multi-cloud, SaaS, and data center spend.
- [GitHub Actions Certification](https://docs.github.com/en/get-started/showcase-your-expertise-with-github-certifications/about-github-certifications) - Certifies proficiency in automating CI/CD workflows with GitHub Actions, a foundational skill for AI-enhanced DevOps pipelines.
- [GitHub Copilot Certification](https://learn.github.com/certification/COPILOT) - Validates proficiency in AI-driven code completion across programming languages, development workflow optimization, and responsible AI practices.
- [Google Cloud Professional Cloud DevOps Engineer](https://cloud.google.com/learn/certification/cloud-devops-engineer) - Certifies SRE and DevOps skills on GCP covering service reliability, CI/CD pipelines, and monitoring.
- [Google Cloud Professional ML Engineer](https://cloud.google.com/learn/certification/machine-learning-engineer) - ML engineering certification focused on GCP infrastructure.
- [HashiCorp Certified Vault Associate](https://www.hashicorp.com/certification/vault-associate) - Covers secrets management, encryption, and identity-based access critical for securing AI and ML pipeline credentials.
- [Istio Certified Associate](https://www.cncf.io/training/certification/ica/) - CNCF certification covering service mesh fundamentals with Istio for securing and managing traffic between microservices.
- [Microsoft MLOps Engineer Associate](https://learn.microsoft.com/en-us/credentials/certifications/operationalizing-machine-learning-and-generative-ai-solutions/) - Azure certification validating MLOps and GenAIOps infrastructure skills covering model training, deployment, and monitoring.
- [OpenTelemetry Certified Associate](https://www.cncf.io/training/certification/otca/) - CNCF certification validating skills in distributed tracing, metrics, and log collection with OpenTelemetry.
- [Prometheus Certified Associate](https://www.cncf.io/training/certification/pca/) - CNCF certification in observability and monitoring using Prometheus, a core tool in AI and ML infrastructure monitoring.
- [Terraform Associate](https://www.hashicorp.com/certification/terraform-associate) - HashiCorp IaC certification providing prerequisite knowledge for AI-assisted Terraform workflows.

### Podcasts

- [Agentic DevOps](https://agenticdevops.fm/) - Dedicated podcast by Bret Fisher exploring how LLMs, AI agents, and MCP tools are used for real-world DevOps automation and platform engineering.
- [Kubernetes Podcast from Google](https://kubernetespodcast.com/) - Weekly podcast covering Kubernetes ecosystem news, interviews, and AI tooling developments.
- [Ship It!](https://changelog.com/shipit) - Podcast about building and shipping software with coverage of AI-enhanced DevOps workflows.
- [The CloudCast](https://www.thecloudcast.net/) - Weekly cloud technology podcast covering AI, DevOps, and infrastructure trends.

## Community and Newsletters

Communities, forums, and newsletters covering AI and DevOps.

- [Agentic AI Foundation](https://aaif.io/) - Linux Foundation community anchored by MCP, Goose, and AGENTS.md for open standards in agentic AI infrastructure and DevOps workflows.
- [CNCF Slack](https://communityinviter.com/apps/cloud-native/cncf) - Cloud Native Computing Foundation community with channels for K8sGPT, HolmesGPT, and AI-native projects.
- [DevOps Weekly](https://www.devopsweekly.com/) - Weekly newsletter covering DevOps tooling and practices including AI adoption.
- [KubeWeekly](https://www.cncf.io/kubeweekly/) - Official CNCF newsletter covering Kubernetes ecosystem updates and AI-powered tooling announcements.
- [Platformers Community](https://platformengineering.org/) - Platform engineering community with discussions on AI-powered developer experience and internal platforms.
- [r/devops](https://reddit.com/r/devops) - Reddit community with 780k+ members actively discussing AI tool adoption in DevOps workflows.
- [r/Kubernetes](https://reddit.com/r/kubernetes) - Reddit community with 260k+ members discussing K8sGPT, KAITO, and AI-powered cluster management.
- [r/Terraform](https://reddit.com/r/Terraform) - Active Reddit community discussing AI-assisted IaC and Terraform automation.
- [The New Stack](https://thenewstack.io/) - Publication covering cloud-native, Kubernetes, and AI infrastructure developments.
- [TLDR DevOps](https://tldr.tech/devops) - Daily DevOps newsletter with AI and automation coverage.

## Related Awesome Lists

- [Awesome](https://github.com/sindresorhus/awesome) - The original awesome list of awesome lists.
- [Awesome Kubernetes](https://github.com/ramitsurana/awesome-kubernetes) - Curated list of Kubernetes resources.
- [Awesome Terraform](https://github.com/shuaibiyy/awesome-terraform) - Curated list of Terraform resources and modules.
- [Awesome SRE](https://github.com/dastergon/awesome-sre) - Curated list of Site Reliability Engineering resources.
- [Awesome Cloud Native](https://github.com/rootsongjc/awesome-cloud-native) - Curated list of cloud native tools and resources.
- [Awesome Docker](https://github.com/veggiemonk/awesome-docker) - Curated list of Docker resources and projects.
- [Awesome CI/CD](https://github.com/cicdops/awesome-ciandcd) - Curated list of CI/CD tools and resources.
- [Awesome LLMOps](https://github.com/tensorchord/Awesome-LLMOps) - Curated list of tools for deploying and operating LLMs in production.
- [Awesome Platform Engineering](https://github.com/toptechevangelist/awesome-platform-engineering) - Curated list of platform engineering resources.
- [Awesome Self-Hosted](https://github.com/awesome-selfhosted/awesome-selfhosted) - Curated list of self-hosted software for infrastructure and DevOps teams.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first. We especially welcome:

- New AI tools for DevOps workflows.
- Corrections to descriptions or broken links.
- New categories as the ecosystem evolves.

Join the [discussion](https://github.com/hammadhaqqani/awesome-devops-ai/discussions) to suggest tools or ask questions.

## Author

**Hammad Haqqani** - DevOps Architect and Cloud Engineer

- Website: [hammadhaqqani.com](https://hammadhaqqani.com)
- LinkedIn: [linkedin.com/in/haqqani](https://www.linkedin.com/in/haqqani)
- GitHub: [github.com/hammadhaqqani](https://github.com/hammadhaqqani?tab=repositories)

---

## Support

If you find this useful, consider buying me a coffee!

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/hammadhaqqani)

- [OpenClaw Monitor](https://github.com/flik2002/openclaw-monitor) - Real-time monitoring dashboard for OpenClaw AI agents. Track token usage, session status, and message trends.
