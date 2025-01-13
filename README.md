# DevSecOps Arsenal

⚙️ A curated hub of DevSecOps tools to secure CI/CD workflows and more.

## Table of Contents
1. [Planning & Design](#planning--design)
2. [Development](#development)
3. [Build & Integration](#build--integration)
4. [Testing & Validation](#testing--validation)
5. [Deployment](#deployment)
6. [Monitoring & Feedback](#monitoring--feedback)
7. [Contribution Rules](#contribution-rules)

---

## Planning & Design

- **[Mindmap](https://github.com/Ignitetechnologies/Mindmap)**: A tool to visualize cloud infrastructure and design architectures, supporting the planning phase of SSDLC.

## Development

- **[sonarlint-core](https://github.com/SonarSource/sonarlint-core)**: An IDE plugin for real-time code analysis to identify bugs, vulnerabilities, and code quality issues during development.
- **[bandit](https://github.com/PyCQA/bandit)**: A security linter for Python to detect common security issues early in the development process.
- **[gitleaks](https://github.com/gitleaks/gitleaks)**: A tool for detecting and preventing hardcoded secrets in source code repositories, ensuring secure code practices during development.
- **[awesome-security](https://github.com/sbilly/awesome-security)**: A curated list of security resources and tools for developers to incorporate into their workflow.
- **[awesome-tunneling](https://github.com/anderspitman/awesome-tunneling)**: A collection of tunneling tools to facilitate secure development in isolated environments.

## Build & Integration

- **[checkov](https://github.com/bridgecrewio/checkov)**: A static code analysis tool for Infrastructure-as-Code, ensuring compliance and security during the build phase.
- **[tfsec](https://github.com/aquasecurity/tfsec)**: A security scanner for Terraform code that helps identify vulnerabilities in cloud infrastructure code during the build process.
- **[infracost](https://github.com/infracost/infracost)**: A tool for tracking cloud infrastructure costs during the CI/CD pipeline, ensuring cost-effective builds and integrations.
- **[terrascan](https://github.com/accurics/terrascan)**: A static code analyzer for Infrastructure-as-Code to detect security and compliance risks before deployment.

## Testing & Validation

- **[lynis](https://github.com/CISOfy/lynis)**: A security auditing tool for Unix-based systems to validate security best practices and configurations.
- **[fail2ban](https://github.com/fail2ban/fail2ban)**: A tool to protect systems from brute-force attacks, important for validating security settings during testing.
- **[zaproxy](https://github.com/zaproxy/zaproxy)**: An open-source web application security scanner, useful for validating web applications during testing.
- **[gophish](https://github.com/gophish/gophish)**: A phishing framework to test social engineering resilience and awareness in the testing phase.
- **[semgrep](https://github.com/semgrep/semgrep)**: A static analysis tool for detecting bugs, vulnerabilities, and code quality issues in source code during testing.

## Deployment

- **[clair](https://github.com/quay/clair)**: A vulnerability scanner for container images, ensuring secure images before deployment.
- **[grype](https://github.com/anchore/grype)**: A container and file system vulnerability scanner that can be integrated into deployment pipelines to ensure security.
- **[nginx-proxy-manager](https://github.com/NginxProxyManager/nginx-proxy-manager)**: A tool to manage NGINX proxies in a secure manner, critical during deployment and reverse proxy management.
- **[cloudgoat](https://github.com/RhinoSecurityLabs/cloudgoat)**: A tool for simulating cloud security challenges during deployment to identify potential risks.

## Monitoring & Feedback

- **[DetectionLab](https://github.com/clong/DetectionLab)**: A framework to build and test detection capabilities, providing feedback on security and incident response during and after deployment.
- **[prowler](https://github.com/prowler-cloud/prowler)**: A security tool for AWS environments to ensure that security best practices are followed post-deployment.
- **[gitleaks](https://github.com/gitleaks/gitleaks)**: Continuously monitor and scan code repositories for hardcoded secrets after deployment.
- **[checkov](https://github.com/bridgecrewio/checkov)**: Provides continuous scanning of infrastructure-as-code to prevent security misconfigurations in deployed infrastructure.
- **[sonarlint-core](https://github.com/SonarSource/sonarlint-core)**: Ensures that post-deployment, the application code remains free from security vulnerabilities and performance issues.

---

## Contribution Rules

- Fork the repository and create a branch for your changes.
- Submit a pull request with a clear description of the changes and the category of tools.
- Please ensure the tools you add are open-source and relevant to the DevSecOps SSDLC methodology.

