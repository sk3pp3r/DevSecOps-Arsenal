# ⚙️ DevSecOps Arsenal ⚙️

## Welcome to the **DevSecOps Arsenal** — a comprehensive, curated collection of tools, methodologies, and resources to seamlessly integrate security into every stage of your SDLC and DevOps workflows.
![DevSecOps_HaimCohen](https://github.com/user-attachments/assets/874410e3-d3a1-435b-a26d-33196a23577a)

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
|                                 | **[ArcherySec](https://github.com/archerysec/archerysec)**: ASOC, ASPM, DevSecOps, Vulnerability Management Using ArcherySec.|

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
