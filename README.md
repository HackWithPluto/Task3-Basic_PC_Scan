#  Cybersecurity Internship – Task 3

##  Basic Vulnerability Scan on Personal Computer

###  Date: June 26, 2025  
###  Intern: SHUBHAM MUKUND DONGARE

---

##  Important Note

Due to lack of access to my laptop today, I could not perform the actual vulnerability scan. However, I have documented the steps I would follow, the tool I would use, and the expected outcomes.

I will complete the scan and upload real results (screenshots + report) by **June 27, 2025**.

---

## Objective

Perform a vulnerability scan on my local machine using free tools like **Nessus Essentials** or **OpenVAS**, and document the results for analysis and learning.

---

##  Tool of Choice: Nessus Essentials

- Free version of Nessus for students and learners
- Easy to install and use on Windows or Linux
- Supports CVSS scoring and detailed vulnerability descriptions

---

##  Planned Steps

1. Download and install **Nessus Essentials** from [Tenable](https://www.tenable.com/products/nessus/nessus-essentials)
2. Register for a free activation code
3. Set up a **Full Scan** targeting `localhost` or local IP
4. Start the scan and wait (30–60 minutes)
5. Review the scan report to identify **Critical**, **High**, and **Medium** vulnerabilities
6. Research mitigation steps and understand CVSS scores

---

##  Expected Vulnerabilities (Examples)

| Vulnerability                     | CVSS Score | Severity  | Suggested Fix                         |
|----------------------------------|------------|-----------|----------------------------------------|
| SMBv1 Protocol Enabled           | 9.8        | Critical  | Disable SMBv1 via Windows features     |
| Outdated OpenSSL Version        | 7.5        | High      | Update to latest version               |
| Weak Password Policy             | 6.0        | Medium    | Enforce strong password requirements   |

---

##  Interview Questions & Answers

**1. What is vulnerability scanning?**  
It’s the automated process of identifying known security flaws in systems, applications, or networks.

**2. Difference between vulnerability scanning and penetration testing?**  
Vulnerability scanning is passive and automated; penetration testing is manual, active, and simulates real attacks.

**3. Common vulnerabilities in personal computers?**  
- Outdated OS or software  
- Open ports and services  
- Weak passwords  
- Misconfigured security settings

**4. How do scanners detect vulnerabilities?**  
They compare system/software information with known vulnerability databases like CVE.

**5. What is CVSS?**  
CVSS (Common Vulnerability Scoring System) is a standardized way to rate the severity of vulnerabilities on a scale from 0.0 to 10.0.

**6. How often should vulnerability scans be performed?**  
At least monthly, and after major updates or system changes.

**7. What is a false positive in vulnerability scanning?**  
It’s when a scan reports a vulnerability that doesn’t actually exist or isn’t exploitable in context.

**8. How do you prioritize vulnerabilities?**  
Based on severity (CVSS score), exploitability, impact on systems, and exposure to external networks.

---

##  Repository Contents

- `README.md` (this file)
- `/screenshots/` _(will add real screenshots after completing the scan)_
- `nessus_scan_report.pdf` _(to be uploaded on June 27, 2025)_

---

##  Next Steps

I will update this repository with:
- Real scan screenshots  
- Actual Nessus report  
- Additional insights based on findings  

 _Real scan data will be available by **tomorrow**._

---
