# ⚙️ DevSecOps Arsenal ⚙️

Welcome to the **DevSecOps Arsenal** — a comprehensive, curated collection of tools, methodologies, and resources to seamlessly integrate security into every stage of your SDLC and DevOps workflows.

---

## 📜 Table of Contents

| Section                                      | Description                                                                                     |
|----------------------------------------------|-------------------------------------------------------------------------------------------------|
| [What is DevSecOps? 🤔](#what-is-devsecops)  | Understanding the integration of security into the DevOps lifecycle.                           |
| [What is SDLC and SSDLC? 🔍](#what-is-sdlc-and-ssdls) | Overview of SDLC and SSDLC practices.                                                        |
| [Shift-Left SSDLC 🔄](#shift-left-ssdls)     | Moving security and QA earlier in the development lifecycle.                                   |
| [Tooling 🛠️](#tooling)                      | A curated list of DevSecOps tools categorized by use case.                                     |
| [Methodologies, Whitepapers, and Architecture 📚](#methodologies-whitepapers-and-architecture) | Resources to deepen understanding of DevSecOps.                                               |
| [Contribution Rules 🤝](#contribution-rules) | Guidelines for contributing to the DevSecOps Arsenal.                                          |

---

## 🤔 What is DevSecOps?

**DevSecOps** ensures security is integrated at every phase of the DevOps lifecycle—planning, coding, building, testing, releasing, deploying, operating, and monitoring. It emphasizes automation, collaboration, and enforcement to bridge development, security, and operations.

| Learn More |                                                                                          |
|------------|------------------------------------------------------------------------------------------|
| [RedHat DevSecOps](https://www.redhat.com/en/topics/devops/what-is-devsecops)                         |
| [IBM DevSecOps](https://www.ibm.com/cloud/learn/devsecops)                                            |

---

## 🔍 What is SDLC and SSDLC?

| Term                  | Description                                                                                             |
|-----------------------|---------------------------------------------------------------------------------------------------------|
| **SDLC**              | A framework defining software development phases like Planning, Design, Development, Testing, and Deployment. |
| **SSDLC**             | Security-enhanced SDLC embedding practices like Threat Modeling and Static Analysis at every stage.     |
| **How They Work Together** | Align SDLC with SSDLC to embed security as a fundamental part of the development process.            |

---

## 🔄 Shift-Left SSDLC

**Shift-Left SSDLC** refers to integrating security and quality assurance earlier in the software development lifecycle.

### Benefits
- **Cost savings**: Address vulnerabilities early.
- **Improved quality**: Enhance reliability and security.
- **Faster delivery**: Reduce rework and shorten cycles.

| Recommended Reading |                                                                                     |
|---------------------|-------------------------------------------------------------------------------------|
| [Shift-Left SSDLC](https://github.com/sk3pp3r/shift-left): Insights and best practices for adopting the methodology.|

---

## 🛠️ Tooling

| Category                         | Tool Name & Description                                                                                                   |
|----------------------------------|--------------------------------------------------------------------------------------------------------------------------|
| **Pre-Commit Time Tools ⚡**     | **[Git-Secrets](https://github.com/awslabs/git-secrets)**: Detects secrets in commits.                                    |
|                                  | **[SonarLint](https://github.com/SonarSource/sonarlint-core)**: IDE-based tool for real-time code quality checks.        |
|                                  | **[ThreatSpec](https://github.com/threatspec/threatspec)**: Threat modeling as code for early risk identification.        |
| **Secrets Management 🔒**        | **[TruffleHog](https://github.com/trufflesecurity/truffleHog)**: Scans repositories for secrets.                         |
|                                  | **[HashiCorp Vault](https://github.com/hashicorp/vault)**: Provides secure access and storage for secrets.               |
|                                  | **[Mozilla SOPS](https://github.com/mozilla/sops)**: Encrypts secrets in YAML and JSON files.                            |
| **OSS Dependency Management 📦**| **[Snyk](https://github.com/snyk/snyk)**: Identifies and fixes vulnerabilities in dependencies.                          |
|                                  | **[CycloneDX](https://github.com/CycloneDX)**: Creates software BOMs (Bill of Materials) for tracking dependencies.       |
| **Supply Chain Security 🔗**     | **[Tekton Chains](https://github.com/tektoncd/chains)**: Provides Kubernetes-native supply chain security.               |
|                                  | **[SLSA Framework](https://github.com/slsa-framework/slsa)**: Offers standards for supply-chain security.                |
| **SAST 🛡️**                      | **[Semgrep](https://github.com/returntocorp/semgrep)**: High-quality static analysis.                                    |
|                                  | **[Bandit](https://github.com/PyCQA/bandit)**: Python-specific security linter.                                          |
| **DAST 🌐**                      | **[OWASP ZAP](https://github.com/zaproxy/zaproxy)**: Dynamic scanner for web vulnerabilities.                           |
|                                  | **[Nuclei](https://github.com/projectdiscovery/nuclei)**: Template-based vulnerability scanning.                         |
| **Continuous Deployment 🚀**     | **[Trivy](https://github.com/aquasecurity/trivy)**: Scans containers and configurations for vulnerabilities.            |
|                                  | **[Terrascan](https://github.com/accurics/terrascan)**: Static analysis for Infrastructure as Code.                     |
|                                  | **[StackStorm](https://github.com/StackStorm/st2)**: Automation platform for DevSecOps workflows.                        |
| **Kubernetes Security 🌀**       | **[Kubescape](https://github.com/armosec/kubescape)**: Kubernetes compliance and hardening scanner.                      |
|                                  | **[Kube-Bench](https://github.com/aquasecurity/kube-bench)**: Benchmarks Kubernetes clusters against CIS standards.       |
| **IaC Security 🏗️**              | **[Checkov](https://github.com/bridgecrewio/checkov)**: Finds misconfigurations in IaC templates.                        |
|                                  | **[KICS](https://github.com/Checkmarx/kics)**: Scans IaC files for vulnerabilities.                                      |
| **Vulnerability Management**    | **[DefectDojo](https://github.com/DefectDojo/django-DefectDojo)**: Platform for centralized vulnerability management.     |

---

## 📚 Methodologies, Whitepapers, and Architecture

| Resource                         | Description                                                                                  |
|----------------------------------|----------------------------------------------------------------------------------------------|
| [Principles of Chaos Engineering](https://principlesofchaos.org/) | Guidelines to build resilient systems.                                                      |
| [OWASP DevSecOps Guidelines](https://owasp.org/)                 | Comprehensive DevSecOps best practices.                                                     |

---

## 🤝 Contribution Rules

1. **Active, Open Source**: Add tools that are currently active and open-source.
2. **Relevance**: Ensure submissions align with the **DevSecOps methodology**.
3. **Avoid Duplication**: Check existing tools before adding new ones.
4. **Provide Details**: Include clear descriptions and tool relevance.

### How to Contribute
1. **Fork** the repository.
2. Create a new **branch**.
3. Submit a **Pull Request**.

---

🌟 *Let’s build a safer DevSecOps ecosystem together!* 🌟
