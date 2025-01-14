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

**Shift-Left SSDLC** integrates security and QA into earlier stages of development, fostering cost savings, improved quality, and faster delivery.

| Methodology                 | Description                                                                                   |
|-----------------------------|-----------------------------------------------------------------------------------------------|
| **Early Threat Modeling**   | Use tools like [ThreatSpec](https://github.com/threatspec/threatspec).                        |
| **Pre-Commit Hooks**        | Implement tools like [Git-Secrets](https://github.com/awslabs/git-secrets).                  |
| **Static Code Analysis**    | Adopt tools like [Semgrep](https://github.com/returntocorp/semgrep).                         |
| **Continuous Feedback**     | Automate testing with CI/CD pipelines for iterative improvements.                            |

---

## 🛠️ Tooling

| Category                         | Tools                                                                                       |
|----------------------------------|---------------------------------------------------------------------------------------------|
| **Pre-Commit Time Tools ⚡**     | [Git-Secrets](https://github.com/awslabs/git-secrets), [SonarLint](https://github.com/SonarSource/sonarlint-core), [ThreatSpec](https://github.com/threatspec/threatspec) |
| **Secrets Management 🔒**        | [TruffleHog](https://github.com/trufflesecurity/truffleHog), [HashiCorp Vault](https://github.com/hashicorp/vault), [Mozilla SOPS](https://github.com/mozilla/sops) |
| **OSS Dependency Management 📦**| [Snyk](https://github.com/snyk/snyk), [CycloneDX](https://github.com/CycloneDX)                                               |
| **Supply Chain Security 🔗**     | [Tekton Chains](https://github.com/tektoncd/chains), [SLSA Framework](https://github.com/slsa-framework/slsa)                   |
| **SAST 🛡️**                      | [Semgrep](https://github.com/returntocorp/semgrep), [Bandit](https://github.com/PyCQA/bandit)                                   |
| **DAST 🌐**                      | [OWASP ZAP](https://github.com/zaproxy/zaproxy), [Nuclei](https://github.com/projectdiscovery/nuclei)                          |
| **Continuous Deployment 🚀**     | [Trivy](https://github.com/aquasecurity/trivy), [Terrascan](https://github.com/accurics/terrascan), [StackStorm](https://github.com/StackStorm/st2) |
| **Kubernetes Security 🌀**       | [Kubescape](https://github.com/armosec/kubescape), [Kube-Bench](https://github.com/aquasecurity/kube-bench)                    |
| **IaC Security 🏗️**              | [Checkov](https://github.com/bridgecrewio/checkov), [KICS](https://github.com/Checkmarx/kics)                                  |
| **Vulnerability Management**    | [DefectDojo](https://github.com/DefectDojo/django-DefectDojo)                                                                   |

---

## 📚 Methodologies, Whitepapers, and Architecture

| Resource                         | Description                                                                                  |
|----------------------------------|----------------------------------------------------------------------------------------------|
| [Principles of Chaos Engineering](https://principlesofchaos.org/) | Guidelines to build resilient systems.                                                      |
| [OWASP DevSecOps Guidelines](https://owasp.org/)                 | DevSecOps best practices from OWASP.                                                        |

---

## 🤝 Contribution Rules

| Rule                                   | Description                                                                                 |
|---------------------------------------|---------------------------------------------------------------------------------------------|
| **Active and Open Source Only**       | Add tools that are active and open-source.                                                  |
| **Relevance**                         | Ensure submissions align with the **DevSecOps methodology**.                                |
| **Unique**                            | Avoid duplicates; check existing tools.                                                    |
| **Clear Description**                 | Provide clear details about the tool's use case and relevance.                             |

🌟 *Let's build a safer DevSecOps ecosystem together!* 🌟
