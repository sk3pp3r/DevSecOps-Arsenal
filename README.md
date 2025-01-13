# 🌟 DevSecOps Arsenal 🌟

Welcome to the **DevSecOps Arsenal** — a comprehensive, curated collection of tools, methodologies, and resources to seamlessly integrate security into every stage of your SDLC and DevOps workflows.

---

## 📜 Table of Contents
1. [What is DevSecOps? 🤔](#what-is-devsecops)
2. [Tooling 🛠️](#tooling)
   - [Pre-Commit Time Tools ⚡](#pre-commit-time-tools)
   - [Secrets Management 🔒](#secrets-management)
   - [OSS and Dependency Management 📦](#oss-and-dependency-management)
   - [Supply Chain Security 🔗](#supply-chain-security)
   - [SAST (Static Application Security Testing) 🛡️](#sast-static-application-security-testing)
   - [DAST (Dynamic Application Security Testing) 🌐](#dast-dynamic-application-security-testing)
   - [Continuous Deployment Security 🚀](#continuous-deployment-security)
   - [Kubernetes Security 🌀](#kubernetes-security)
   - [Infrastructure as Code Security 🏗️](#infrastructure-as-code-security)
3. [Methodologies, Whitepapers, and Architecture 📚](#methodologies-whitepapers-and-architecture)
4. [Contribution Rules 🤝](#contribution-rules)

---

## 🤔 What is DevSecOps?

**DevSecOps** ensures security is integrated at every phase of the DevOps lifecycle—planning, coding, building, testing, releasing, deploying, operating, and monitoring. It emphasizes automation, collaboration, and enforcement to bridge development, security, and operations. Learn more:
- [RedHat DevSecOps](https://www.redhat.com/en/topics/devops/what-is-devsecops)
- [IBM DevSecOps](https://www.ibm.com/cloud/learn/devsecops)

---

## 🛠️ Tooling

### ⚡ Pre-Commit Time Tools
These tools streamline development by addressing issues before they reach your repository:
- **[Git-Secrets](https://github.com/awslabs/git-secrets)**: Detects secrets in commits. 🔑
- **[SonarLint](https://github.com/SonarSource/sonarlint-core)**: IDE-based code quality scanner. 🕵️‍♂️
- **[ThreatSpec](https://github.com/threatspec/threatspec)**: Threat modeling as code. ⚔️

### 🔒 Secrets Management
Ensure sensitive information like API keys are secure:
- **[TruffleHog](https://github.com/trufflesecurity/truffleHog)**: Detects secrets in source code. 🐷
- **[HashiCorp Vault](https://github.com/hashicorp/vault)**: Centralized secrets storage. 🗄️
- **[Mozilla SOPS](https://github.com/mozilla/sops)**: Secrets management for YAML and JSON. 📜

### 📦 OSS and Dependency Management
Monitor vulnerabilities in open-source dependencies:
- **[Snyk](https://github.com/snyk/snyk)**: Scan projects for vulnerabilities. 🛡️
- **[CycloneDX](https://github.com/CycloneDX)**: Generate software BOMs (Bill of Materials). 📄

### 🔗 Supply Chain Security
Protect the integrity of your CI/CD pipelines:
- **[Tekton Chains](https://github.com/tektoncd/chains)**: Kubernetes-native supply chain security. ⚙️
- **[SLSA Framework](https://github.com/slsa-framework/slsa)**: Supply-chain security standards. 🛠️

### 🛡️ SAST (Static Application Security Testing)
Scan source code for vulnerabilities:
- **[Semgrep](https://github.com/returntocorp/semgrep)**: High-quality static analysis. 🧰
- **[Bandit](https://github.com/PyCQA/bandit)**: Python security linter. 🐍

### 🌐 DAST (Dynamic Application Security Testing)
Test live applications for vulnerabilities:
- **[OWASP ZAP](https://github.com/zaproxy/zaproxy)**: Comprehensive web app scanner. 🌐
- **[Nuclei](https://github.com/projectdiscovery/nuclei)**: Template-based scanning. 🔎

### 🚀 Continuous Deployment Security
Ensure secure deployment practices:
- **[Trivy](https://github.com/aquasecurity/trivy)**: Vulnerability scanning for containers. 🐳
- **[Terrascan](https://github.com/accurics/terrascan)**: Static analysis for IaC. 📏

### 🌀 Kubernetes Security
Secure Kubernetes clusters and workloads:
- **[Kubescape](https://github.com/armosec/kubescape)**: NSA and MITRE ATT&CK compliance. 🎯
- **[Kube-Bench](https://github.com/aquasecurity/kube-bench)**: CIS benchmarking for Kubernetes. 📊

### 🏗️ Infrastructure as Code Security
Shift security left by scanning IaC templates:
- **[Checkov](https://github.com/bridgecrewio/checkov)**: Detect misconfigurations in Terraform, CloudFormation, and more. 🔍
- **[KICS](https://github.com/Checkmarx/kics)**: Scans infrastructure-as-code for vulnerabilities. 📂

---

## 📚 Methodologies, Whitepapers, and Architecture
Enhance your understanding of DevSecOps with these resources:
- [Principles of Chaos Engineering](https://principlesofchaos.org/)
- [OWASP DevSecOps Guidelines](https://owasp.org/)

---

## 🤝 Contribution Rules

Contributions are welcome! Follow these rules:
- Add **only active and open-source** tools. ✅
- Ensure your submission aligns with the **DevSecOps methodology**. 🛠️
- Provide a clear description, including the tool's **maturity** and relevance. ✍️
- Avoid duplicates! Check if the tool is already listed. 🔍

### How to Contribute:
1. **Fork** the repository. 🍴
2. Create a new **branch**. 🌿
3. Submit a **Pull Request (PR)** with details. 📨

---

🌟 *Let's build a safer DevSecOps ecosystem together!* 🌟
