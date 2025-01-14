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

## 🔄 Shift-Left SSDLC

### Concept
**Shift-Left SSDLC** refers to integrating security and quality assurance earlier in the software development process—shifting activities typically done later, such as testing and security checks, to earlier phases like planning and coding.

### Significance
By addressing issues earlier:
- **Cost savings**: Fixing vulnerabilities in the design phase is cheaper than post-deployment.
- **Improved software quality**: Early detection enhances the overall reliability and security of the software.
- **Faster delivery**: Reduced rework shortens development cycles.

### Recommended Reading
- **[Shift-Left SSDLC](https://github.com/sk3pp3r/shift-left)**: A detailed article offering insights and best practices for adopting the Shift-Left methodology.

---

## 🛠️ Tooling

| Category                         | Tool Name & Description                                                                                                   |
|----------------------------------|--------------------------------------------------------------------------------------------------------------------------|
| **Pre-Commit Time Tools ⚡**     | **[Git-Secrets](https://github.com/awslabs/git-secrets)**: Detects secrets in commits to prevent sensitive data exposure. |
|                                  | **[SonarLint](https://github.com/SonarSource/sonarlint-core)**: IDE-based tool for real-time code quality and bug detection. |
|                                  | **[ThreatSpec](https://github.com/threatspec/threatspec)**: Enables threat modeling as code for early risk identification. |
| **Secrets Management 🔒**        | **[TruffleHog](https://github.com/trufflesecurity/truffleHog)**: Scans for secrets in code repositories.                  |
|                                  | **[HashiCorp Vault](https://github.com/hashicorp/vault)**: Provides secure storage and access to sensitive information.   |
|                                  | **[Mozilla SOPS](https://github.com/mozilla/sops)**: Encrypts and manages secrets within YAML and JSON files.            |
| **OSS Dependency Management 📦**| **[Snyk](https://github.com/snyk/snyk)**: Monitors and fixes vulnerabilities in open-source dependencies.                |
|                                  | **[CycloneDX](https://github.com/CycloneDX)**: Generates software BOMs (Bill of Materials) for dependency tracking.       |
| **Supply Chain Security 🔗**     | **[Tekton Chains](https://github.com/tektoncd/chains)**: Provides Kubernetes-native supply chain security.               |
|                                  | **[SLSA Framework](https://github.com/slsa-framework/slsa)**: Offers standards for supply-chain integrity and security.   |
| **SAST 🛡️**                      | **[Semgrep](https://github.com/returntocorp/semgrep)**: Lightweight static analysis tool for vulnerability detection.     |
|                                  | **[Bandit](https://github.com/PyCQA/bandit)**: Security-focused linter for Python projects.                               |
| **DAST 🌐**                      | **[OWASP ZAP](https://github.com/zaproxy/zaproxy)**: Comprehensive dynamic application scanner for web vulnerabilities.  |
|                                  | **[Nuclei](https://github.com/projectdiscovery/nuclei)**: Template-based scanner for vulnerability assessment.            |
| **Continuous Deployment Security 🚀** | **[Trivy](https://github.com/aquasecurity/trivy)**: Scans containers for vulnerabilities, misconfigurations, and more. |
|                                  | **[Terrascan](https://github.com/accurics/terrascan)**: Performs static analysis on Infrastructure as Code templates.    |
|                                  | **[StackStorm](https://github.com/StackStorm/st2)**: Automates DevSecOps tasks to enhance compliance and security.        |
| **Kubernetes Security 🌀**       | **[Kubescape](https://github.com/armosec/kubescape)**: Scans Kubernetes configurations for compliance and best practices. |
|                                  | **[Kube-Bench](https://github.com/aquasecurity/kube-bench)**: Validates Kubernetes clusters against CIS benchmarks.       |
| **IaC Security 🏗️**              | **[Checkov](https://github.com/bridgecrewio/checkov)**: Detects security misconfigurations in Terraform, CloudFormation, etc. |
|                                  | **[KICS](https://github.com/Checkmarx/kics)**: Scans Infrastructure as Code files for vulnerabilities.                   |
| **Vulnerability Management**    | **[DefectDojo](https://github.com/DefectDojo/django-DefectDojo)**: Centralized vulnerability management platform.          |

---

## 📚 Methodologies, Whitepapers, and Architecture

Enhance your understanding of DevSecOps with these resources:
- [Principles of Chaos Engineering](https://principlesofchaos.org/)
- [OWASP DevSecOps Guidelines](https://owasp.org/)

---

## 🤝 Contribution Rules

Contributions are welcome! Follow these rules:

1. Add **only active and open-source** tools.
2. Ensure your submission aligns with the **DevSecOps methodology**.
3. Provide a clear description, including the tool's **maturity** and relevance.
4. Avoid duplicates! Check if the tool is already listed.

### How to Contribute:
1. **Fork** the repository.
2. Create a new **branch**.
3. Submit a **Pull Request (PR)** with details.

---

🌟 *Let's build a safer DevSecOps ecosystem together!* 🌟
