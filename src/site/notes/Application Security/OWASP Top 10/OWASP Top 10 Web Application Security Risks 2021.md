---
{"dg-publish":true,"permalink":"/application-security/owasp-top-10/owasp-top-10-web-application-security-risks-2021/","created":"2023-04-05T17:04:48.784-05:00","updated":"2023-04-05T17:49:15.344-05:00"}
---


# OWASP Top 10 Web Application Security Risks - 2021

_[[Epistemic status\|Epistemic status]]_:  Confident that these are the attacks that OWASP lists. Reasonably confident in their methodology to identify the attacks though I haven't done more than read their [Methodology Overview](https://owasp.org/Top10/#methodology)
_[[Epistemic effort\|Epistemic effort]]_: Multiple rounds of awareness training, thinking about each attack and how it might apply to software I work on. Currently working on gathering language-specific resources for each issue.

The OWASP Top 10 are a set of attacks believed to be the most common across a wide range of software. Addressing and preventing these attacks are now broadly considered table stakes for an [[Application Security/Application Security\|Application Security]] program. 

Every few years, OWASP surveys their community to ask about applications and the [[Common Weakness Enumeration\|CWEs]] found in testing those applications. In the most recent 2021 process, the group looked at almost 400 different CWEs. In analyzing these CWEs, they grouped them and focused on the root causes of the issues wherever they could.  Each issue category in the 2021 Top 10 averaged 19.6 CWEs grouped to it, with the real range going from 1 (for [[A10:2021 - Server Side Request Forgery\|A10:2021 - Server Side Request Forgery]]) to 40 (for [[A04:2021 - Insecure Design\|A04:2021 - Insecure Design]]).

After grouping the CWEs, the OWASP team extracted [[CVSS\|CVSS]] scores for both exploitability and impact for [[Common Vulnerability Enumeration\|CVEs]] that mapped to a [[Common Weakness Enumeration\|CWE]].  They had approximately 125000 [[Common Vulnerability Enumeration\|CVE]] records they extracted.  They then averaged these values for each category and used that to determine the ordering. 

The field of [[Application Security/Application Security\|Application Security]] is evolving rapidly, however, and because it takes time to analyze results, [[Common Vulnerability Enumeration\|CVE]] data can be a trailing indicator. To account for more up-to-the-minute results, the statistical data described above was used only to pick 8 of the 10 top categories. The other 2 are from a community survey of active practitioners who were asked to give the highest risks they perceived at the time of the survey. 

## Top 10 Issues
- [[A01:2021 - Broken Access Control\|A01:2021 - Broken Access Control]]
- [[A02:2021 - Cryptographic Failures\|A02:2021 - Cryptographic Failures]]
- [[A03:2021 - Injection\|A03:2021 - Injection]]
- [[A04:2021 - Insecure Design\|A04:2021 - Insecure Design]]
- [[A05:2021 - Security Misconfiguration\|A05:2021 - Security Misconfiguration]]
- [[A06:2021 - Vulnerable and Outdated Components\|A06:2021 - Vulnerable and Outdated Components]]
- [[A07:2021 - Identification and Authentication Failures\|A07:2021 - Identification and Authentication Failures]]
- [[A08:2021 - Software and Data Integrity Failures\|A08:2021 - Software and Data Integrity Failures]]
- [[A09:2021 - Security Logging and Monitoring Failures\|A09:2021 - Security Logging and Monitoring Failures]]
- [[A10:2021 - Server Side Request Forgery\|A10:2021 - Server Side Request Forgery]]

## Sources

- [OWASP Top 10:2021](https://owasp.org/Top10/)


