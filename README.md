# ⚙️ DevSecOps Arsenal ⚙️

## Welcome to the **DevSecOps Arsenal** — a comprehensive, curated collection of tools, methodologies, and resources to seamlessly integrate security into every stage of your SDLC and DevOps workflows.
![DevSecOps_HaimCohen](https://github.com/user-attachments/assets/874410e3-d3a1-435b-a26d-33196a23577a)
For interactive interface [click here](https://www.mymap.ai/share/security-practices-mind-map-vqn0O11g9UdTu)

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

**DevSecOps** ensures security is integrated at every phase of the DevOps lifecycle—planning, coding, building, testing, releasing, deploying, operating, and monitoring. It emphasizes automation, collaboration, and enforcement to bridge development, security, and operations. Learn more:
- [RedHat DevSecOps](https://www.redhat.com/en/topics/devops/what-is-devsecops)
- [IBM DevSecOps](https://www.ibm.com/cloud/learn/devsecops)
- [Standard DevSecOps Platform Framework](https://tech.gsa.gov/guides/dev_sec_ops_guide/)

---

## 🔍 What is SDLC and SSDLC?

### Software Development Life Cycle (SDLC)
The **SDLC** is a framework that defines the processes and phases involved in software development, including:
1. Planning 📝
2. Analysis 📊
3. Design 🎨
4. Implementation 💻
5. Testing 🧪
6. Deployment 🚀
7. Maintenance 🔄

### Secure Software Development Life Cycle (SSDLC)
**SSDLC** integrates security practices into each phase of the SDLC. It ensures vulnerabilities are addressed early, reducing risks and costs. Key practices include:
- **Threat Modeling** during planning and design.
- **Static Analysis** during development.
- **Dynamic Testing** before deployment.

### How They Work Together
The SSDLC augments the SDLC by embedding security checks at every stage. This alignment ensures that security becomes a fundamental part of the development process rather than an afterthought, fostering secure and high-quality software.

---

## 🔄 Shift-Left SSDLC

### Concept
**Shift-Left SSDLC** refers to integrating security and quality assurance (QA) earlier in the software development process—shifting activities typically done later, such as testing and security checks, to earlier phases like planning and coding. 

### Significance
By addressing issues earlier:
- **Cost savings**: Fixing vulnerabilities in the design phase is cheaper than post-deployment.
- **Improved software quality**: Early detection enhances the overall reliability and security of the software.
- **Faster delivery**: Reduced rework shortens development cycles.

### Methodologies and Best Practices
1. **Early Threat Modeling**: Incorporate tools like **[ThreatSpec](https://github.com/threatspec/threatspec)** to identify potential risks during planning.
2. **Pre-Commit Hooks**: Use tools like **[Git-Secrets](https://github.com/awslabs/git-secrets)** to prevent sensitive data from being committed.
3. **Static Code Analysis**: Implement tools like **[Semgrep](https://github.com/returntocorp/semgrep)** during development.
4. **Collaborative Development**: Foster teamwork between developers, QA, and security teams.
5. **Continuous Feedback Loops**: Use CI/CD pipelines to automate testing and provide feedback.

### Recommended Reading 📖: **[Shift-Left SSDLC](https://github.com/sk3pp3r/shift-left)**
This article focuses on enabling organizations to implement Shift-Left principles effectively by providing integrations and best practices for embedding security and QA into the earliest stages of development. 🌟

---

## 🛠️ Tooling

| Category                         | Tool Name & Description                                                                                                   | GitHub Stars |
|----------------------------------|--------------------------------------------------------------------------------------------------------------------------|--------------|
| **Pre-Commit Time Tools ⚡**     | **[Git-Secrets](https://github.com/awslabs/git-secrets)**: Detects secrets in commits.                                    | ![GitHub stars](https://img.shields.io/github/stars/awslabs/git-secrets?style=social) |
|                                  | **[SonarLint](https://github.com/SonarSource/sonarlint-core)**: IDE-based tool for real-time code quality checks.        | ![GitHub stars](https://img.shields.io/github/stars/SonarSource/sonarlint-core?style=social) |
|                                  | **[ThreatSpec](https://github.com/threatspec/threatspec)**: Threat modeling as code for early risk identification.        | ![GitHub stars](https://img.shields.io/github/stars/threatspec/threatspec?style=social) |
|                                  | **[Gitleaks](https://github.com/gitleaks/gitleaks)**: Detect and prevent hardcoded secrets like passwords, api keys, and tokens in git repos. | ![GitHub stars](https://img.shields.io/github/stars/gitleaks/gitleaks?style=social) |
|                                  | **[pre-commit](https://github.com/pre-commit/pre-commit)**: Framework for managing and maintaining git pre-commit hooks. | ![GitHub stars](https://img.shields.io/github/stars/pre-commit/pre-commit?style=social) |
| **Secrets Management 🔒**        | **[TruffleHog](https://github.com/trufflesecurity/truffleHog)**: Scans repositories for secrets.                         | ![GitHub stars](https://img.shields.io/github/stars/trufflesecurity/truffleHog?style=social) |
|                                  | **[HashiCorp Vault](https://github.com/hashicorp/vault)**: Provides secure access and storage for secrets.               | ![GitHub stars](https://img.shields.io/github/stars/hashicorp/vault?style=social) |
|                                  | **[Mozilla SOPS](https://github.com/mozilla/sops)**: Encrypts secrets in YAML and JSON files.                            | ![GitHub stars](https://img.shields.io/github/stars/mozilla/sops?style=social) |
|                                  | **[AWS Secrets Manager](https://github.com/aws/aws-secrets-manager)**: Securely store and manage secrets in AWS.         | ![GitHub stars](https://img.shields.io/github/stars/aws/aws-secrets-manager?style=social) |
|                                  | **[Sealed Secrets](https://github.com/bitnami-labs/sealed-secrets)**: Kubernetes controller for one-way encrypted secrets. | ![GitHub stars](https://img.shields.io/github/stars/bitnami-labs/sealed-secrets?style=social) |
| **OSS Dependency Management 📦**| **[Snyk](https://github.com/snyk/snyk)**: Identifies and fixes vulnerabilities in dependencies.                          | ![GitHub stars](https://img.shields.io/github/stars/snyk/snyk?style=social) |
|                                  | **[CycloneDX](https://github.com/CycloneDX)**: Creates software BOMs (Bill of Materials) for tracking dependencies.       | ![GitHub stars](https://img.shields.io/github/stars/CycloneDX/cyclonedx-core-java?style=social) |
|                                  | **[Dependabot](https://github.com/dependabot/dependabot-core)**: Automated dependency updates and security alerts.       | ![GitHub stars](https://img.shields.io/github/stars/dependabot/dependabot-core?style=social) |
|                                  | **[Renovate](https://github.com/renovatebot/renovate)**: Automated dependency updates with flexible configuration.       | ![GitHub stars](https://img.shields.io/github/stars/renovatebot/renovate?style=social) |
| **Supply Chain Security 🔗**     | **[Tekton Chains](https://github.com/tektoncd/chains)**: Provides Kubernetes-native supply chain security.               | ![GitHub stars](https://img.shields.io/github/stars/tektoncd/chains?style=social) |
|                                  | **[SLSA Framework](https://github.com/slsa-framework/slsa)**: Offers standards for supply-chain security.                | ![GitHub stars](https://img.shields.io/github/stars/slsa-framework/slsa?style=social) |
|                                  | **[Sigstore](https://github.com/sigstore/sigstore)**: Tools for signing, verifying and protecting software.             | ![GitHub stars](https://img.shields.io/github/stars/sigstore/sigstore?style=social) |
|                                  | **[in-toto](https://github.com/in-toto/in-toto)**: Framework to secure the integrity of software supply chains.         | ![GitHub stars](https://img.shields.io/github/stars/in-toto/in-toto?style=social) |
| **SAST 🛡️**                      | **[Semgrep](https://github.com/returntocorp/semgrep)**: High-quality static analysis.                                    | ![GitHub stars](https://img.shields.io/github/stars/returntocorp/semgrep?style=social) |
|                                  | **[Bandit](https://github.com/PyCQA/bandit)**: Python-specific security linter.                                          | ![GitHub stars](https://img.shields.io/github/stars/PyCQA/bandit?style=social) |
|                                  | **[SonarQube](https://github.com/SonarSource/sonarqube)**: Continuous code quality and security analysis.               | ![GitHub stars](https://img.shields.io/github/stars/SonarSource/sonarqube?style=social) |
|                                  | **[CodeQL](https://github.com/github/codeql)**: Semantic code analysis engine for security vulnerabilities.              | ![GitHub stars](https://img.shields.io/github/stars/github/codeql?style=social) |
| **DAST 🌐**                      | **[OWASP ZAP](https://github.com/zaproxy/zaproxy)**: Dynamic scanner for web vulnerabilities.                           | ![GitHub stars](https://img.shields.io/github/stars/zaproxy/zaproxy?style=social) |
|                                  | **[Nuclei](https://github.com/projectdiscovery/nuclei)**: Template-based vulnerability scanning.                         | ![GitHub stars](https://img.shields.io/github/stars/projectdiscovery/nuclei?style=social) |
|                                  | **[Burp Suite](https://portswigger.net/burp)**: Web application security testing platform.                              | - |
|                                  | **[Acunetix](https://www.acunetix.com/)**: Automated web vulnerability scanner.                                         | - |
| **Continuous Deployment 🚀**     | **[Trivy](https://github.com/aquasecurity/trivy)**: Scans containers and configurations for vulnerabilities.            | ![GitHub stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=social) |
|                                  | **[Terrascan](https://github.com/accurics/terrascan)**: Static analysis for Infrastructure as Code.                     | ![GitHub stars](https://img.shields.io/github/stars/accurics/terrascan?style=social) |
|                                  | **[StackStorm](https://github.com/StackStorm/st2)**: Automation platform for DevSecOps workflows.                        | ![GitHub stars](https://img.shields.io/github/stars/StackStorm/st2?style=social) |
|                                  | **[Anchore](https://github.com/anchore/anchore-engine)**: Container image scanning and policy enforcement.              | ![GitHub stars](https://img.shields.io/github/stars/anchore/anchore-engine?style=social) |
|                                  | **[Clair](https://github.com/quay/clair)**: Vulnerability static analysis for containers.                               | ![GitHub stars](https://img.shields.io/github/stars/quay/clair?style=social) |
| **Kubernetes Security 🌀**       | **[Kubescape](https://github.com/armosec/kubescape)**: Kubernetes compliance and hardening scanner.                      | ![GitHub stars](https://img.shields.io/github/stars/armosec/kubescape?style=social) |
|                                  | **[Kube-Bench](https://github.com/aquasecurity/kube-bench)**: Benchmarks Kubernetes clusters against CIS standards.       | ![GitHub stars](https://img.shields.io/github/stars/aquasecurity/kube-bench?style=social) |
|                                  | **[Falco](https://github.com/falcosecurity/falco)**: Cloud-native runtime security project.                             | ![GitHub stars](https://img.shields.io/github/stars/falcosecurity/falco?style=social) |
|                                  | **[Kyverno](https://github.com/kyverno/kyverno)**: Kubernetes native policy management.                                 | ![GitHub stars](https://img.shields.io/github/stars/kyverno/kyverno?style=social) |
| **IaC Security 🏗️**              | **[Checkov](https://github.com/bridgecrewio/checkov)**: Finds misconfigurations in IaC templates.                        | ![GitHub stars](https://img.shields.io/github/stars/bridgecrewio/checkov?style=social) |
|                                  | **[KICS](https://github.com/Checkmarx/kics)**: Scans IaC files for vulnerabilities.                                      | ![GitHub stars](https://img.shields.io/github/stars/Checkmarx/kics?style=social) |
|                                  | **[tfsec](https://github.com/aquasecurity/tfsec)**: Security scanner for Terraform code.                                | ![GitHub stars](https://img.shields.io/github/stars/aquasecurity/tfsec?style=social) |
|                                  | **[Snyk IaC](https://github.com/snyk/snyk)**: Infrastructure as Code security scanning.                                 | ![GitHub stars](https://img.shields.io/github/stars/snyk/snyk?style=social) |
| **Vulnerability Management**    | **[DefectDojo](https://github.com/DefectDojo/django-DefectDojo)**: Platform for centralized vulnerability management.     | ![GitHub stars](https://img.shields.io/github/stars/DefectDojo/django-DefectDojo?style=social) |
|                                 | **[ArcherySec](https://github.com/archerysec/archerysec)**: ASOC, ASPM, DevSecOps, Vulnerability Management Using ArcherySec.| ![GitHub stars](https://img.shields.io/github/stars/archerysec/archerysec?style=social) |
|                                 | **[VulnWhisperer](https://github.com/HASecuritySolutions/VulnWhisperer)**: Vulnerability management dashboard.           | ![GitHub stars](https://img.shields.io/github/stars/HASecuritySolutions/VulnWhisperer?style=social) |
|                                 | **[VulnIQ](https://github.com/vulniq/vulniq)**: Vulnerability intelligence and management platform.                      | ![GitHub stars](https://img.shields.io/github/stars/vulniq/vulniq?style=social) |

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

🌟 *Let's build a safer DevSecOps ecosystem together!* 🌟
