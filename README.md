# CS-305_Artemis-Financial
SNHU CS-305 Software Security

# CS-305: Practices for Secure Software  
## Artemis Financial Security Assessment Report  
**Author:** Emmalie Cole  
**Course:** CS-305 Software Security  
**Date:** February 2025  

---

## Project Overview  

### Client: Artemis Financial  
Artemis Financial is a financial services company that required a security assessment and refactoring of its web application to enhance security and ensure compliance with industry best practices.  

### Objective  
The goal of this project was to:  
- Assess and identify software security vulnerabilities  
- Implement strong authentication and encryption mechanisms  
- Strengthen data integrity and secure communications  
- Ensure compliance with secure software development best practices  

---

## Security Enhancements Implemented  

| Security Measure | Description |
|----------------------|----------------|
| Secure Authentication | Configured authentication using Spring Security to restrict unauthorized access |
| Cryptographic Hashing | Implemented SHA-256 hashing to ensure data integrity |
| SSL/TLS Encryption | Enforced HTTPS communication for secure data transmission |
| Vulnerability Scanning | Used OWASP Dependency Check to detect and mitigate risks in third-party libraries |

These enhancements improve the confidentiality, integrity, and availability of Artemis Financial's application.

---

## Key Insights and Challenges  

### Strengths in Identifying Vulnerabilities  
- Conducted static and dynamic security analysis  
- Identified authentication flaws, weak encryption, and dependency risks  
- Enforced secure data handling and communication practices  

### Challenges Faced and Solutions  
- **SSL/TLS Configuration:** Implemented self-signed certificates for HTTPS in a local environment  
- **Dependency Security:** Resolved known vulnerabilities identified by OWASP Dependency Check  
- **Refactoring Security Code:** Ensured minimal impact on application functionality  

---

## Testing and Validation  

To verify the effectiveness of security enhancements, the following tests were conducted:  

| Test Type | Purpose |
|--------------|------------|
| Unit Testing | Verified that security improvements did not break functionality |
| Security Scanning | Performed vulnerability analysis using OWASP Dependency Check |
| SSL/TLS Validation | Ensured secure HTTPS communication and certificate validity |
| Authentication Testing | Confirmed Spring Security successfully restricts unauthorized access |

All security enhancements were successfully tested, validated, and documented.

---

## Tools and Technologies Used  

| Tool | Purpose |
|----------|------------|
| OWASP Dependency Check | Identified and mitigated security vulnerabilities in third-party dependencies |
| Java Keytool | Generated self-signed SSL/TLS certificates for HTTPS configuration |
| Spring Security | Enforced authentication and access control |
| Postman | Tested secure API authentication and HTTPS enforcement |

These tools ensured a thorough security assessment and implementation.

---

## Portfolio and Employer Showcase  

This project demonstrates:  
- Real-world secure software development skills  
- Ability to assess, identify, and mitigate security vulnerabilities  
- Proficiency in cryptographic hashing, authentication, and secure communication  

### Artifacts for Portfolio Submission  
- Practices for Secure Software Report (Project Two)  
- Screenshots of HTTPS security, SHA-256 hashing, and vulnerability scans  

These documents provide concrete examples of secure coding practices for future employers.
