# 🔍 Web Application Breach Forensic Investigation

This repository contains a forensic investigation of an unauthorized admin login on the OWASP Juice Shop web application deployed on Kali Linux via Docker. The attacker gained access without exploiting a technical vulnerability, instead leveraging default administrative credentials—an example of **OWASP Top 10 A05: Security Misconfiguration**.

---

## 🚀 Project Overview

| Category | Details |
|---------|---------|
| Target Application | OWASP Juice Shop |
| Host OS | Kali Linux |
| Deployment | Docker Container |
| Attack Type | Unauthorized Admin Access |
| Root Cause | Default admin credentials enabled |
| OWASP Category | **A05 – Security Misconfiguration** |

---

## 🕵️‍♂️ Investigation Objectives

- Collect and analyze application logs  
- Identify evidence of unauthorized access  
- Determine the attack vector used to gain admin privileges  
- Map event sequences into a forensic timeline  
- Recommend security measures to prevent similar breaches  

---

## 🧰 Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Kali Linux | Forensic investigation environment |
| Docker | OWASP Juice Shop deployment |
| OWASP Juice Shop | Vulnerable web application |
| Bash CLI | Log extraction and event tracing |
| grep | Pattern search within logs |

---

## ⚠️ Impact Assessment

- Full administrative access was obtained by an unauthorized user  
- High risk of data exposure, privilege abuse, or system manipulation  
- Authentication bypassed without any technical exploit

---

## 🛡️ Recommendations

| Recommendation | Benefit |
|---------------|---------|
| Change default admin password | Prevent unauthorized reuse |
| Disable unused accounts | Reduce attack surface |
| Apply account lockout thresholds | Prevent brute-force attacks |
| Implement MFA for admin access | Strengthen authentication |
| Perform periodic configuration audits | Detect risky defaults early |

---

## 🎯 Skills Demonstrated

- Digital Forensics & Log Analysis  
- Web Application Security  
- Incident Response Investigation  
- Root Cause Analysis  
- OWASP Top 10 Mapping  
- Technical Reporting & Documentation

---

## 📌 Conclusion

The incident occurred due to a preventable configuration oversight rather than a sophisticated exploit. Securing authentication mechanisms and removing default credentials would have completely mitigated this breach.

---



