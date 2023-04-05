---
{"dg-publish":true,"permalink":"/application-security/owasp-top-10/owasp-kubernetes-top-10-2022/","created":"2023-04-05T17:29:06.991-05:00","updated":"2023-04-05T17:49:00.766-05:00"}
---


# OWASP Kubernetes Top 10 2022

_[[Epistemic status\|Epistemic status]]_: Confident that these are the issues OWASP identified
_[[Epistemic effort\|Epistemic effort]]_: Still a beginner at [[Kubernetes\|Kubernetes]] in general. I've read through the descriptions of these issues and thought about how they might impact [[Conjur\|Conjur]] (the software I work on for pay).

Inspired by the [[Application Security/OWASP Top 10/OWASP Top 10 Web Application Security Risks 2021\|OWASP Top 10 Web Application Security Risks 2021]] and earlier iteration, OWASP has started identifying Top 10 lists in other areas. Historically, the main Top 10 list has focused on [[Web Applications\|Web Applications]]. Making new lists allows more tailoring to the needs of individual technologies.

Kubernetes is a technology that can be misconfigured in ways that introduce new classes of security holes. In 2022, OWASP identified a list of the top 10 security risks around [[Kubernetes\|Kubernetes]].

## Top 10 Kubernetes Risks - 2022
- [[K01:2022 - Insecure Workload Configurations\|K01:2022 - Insecure Workload Configurations]]
- [[K02:2022 - Supply Chain Vulnerabilities\|K02:2022 - Supply Chain Vulnerabilities]]
- [[K03:2022 - Overly Permissive RBAC Configurations\|K03:2022 - Overly Permissive RBAC Configurations]]
- [[K04:2022 - Lack of Centralized Policy Enforcement\|K04:2022 - Lack of Centralized Policy Enforcement]]
- [[K05:2022 - Inadequate Logging and Monitoring\|K05:2022 - Inadequate Logging and Monitoring]]
- [[K06:2022 - Broken Authentication Mechanisms\|K06:2022 - Broken Authentication Mechanisms]]
- [[K07:2022 - Missing Network Segmentation Controls\|K07:2022 - Missing Network Segmentation Controls]]
- [[K08:2022 - Secrets Management Failures\|K08:2022 - Secrets Management Failures]]
- [[K09:2022 - Misconfigured Cluster Components\|K09:2022 - Misconfigured Cluster Components]]
- [[K10:2022 - Outdated and Vulnerable Kubernetes Components\|K10:2022 - Outdated and Vulnerable Kubernetes Components]]

## Sources
- [OWASP Kubernetes Top Ten Project](https://owasp.org/www-project-kubernetes-top-ten/)