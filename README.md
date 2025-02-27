# CS-305_Artemis-Financial
SNHU CS-305 Software Security

GitHub README Submission for CS-305 Module Eight Journal
1. Client Overview and Software Requirements

Artemis Financial is a financial services company that required an assessment of its web-based application to ensure compliance with secure software development practices. The company needed improved security for authentication, data integrity, and communication channels to protect sensitive client information from potential threats.

2. Strengths in Identifying Security Vulnerabilities & Importance of Secure Coding
We successfully identified security vulnerabilities by:

    Conducting static security scans with OWASP Dependency Check to find risks in third-party dependencies.
    Implementing SHA-256 hashing for data integrity verification.
    Enforcing HTTPS with SSL/TLS encryption to secure data in transit.

Why Secure Coding Matters:

    Protects confidential financial data from breaches.
    Ensures compliance with industry security standards.
    Builds client trust and system reliability.

3. Challenges & Insights from the Vulnerability Assessment

Challenges:

    Configuring SSL/TLS certificates to enforce HTTPS securely.
    Analyzing dependency vulnerabilities and deciding which updates were critical.

Helpful Insights:

    Spring Security integration provided a structured way to enforce authentication.
    Using OWASP guidelines helped prioritize and mitigate security risks efficiently.

4. Increasing Layers of Security & Future Assessment Strategies

Security Enhancements Implemented:

    Enforced authentication using Spring Security.
    Implemented SHA-256 hashing for data integrity.
    Configured SSL/TLS encryption to enable HTTPS.
    Scanned dependencies for vulnerabilities using OWASP Dependency Check.

Future Strategies:

    Conduct regular vulnerability assessments with automated security tools.
    Implement multi-factor authentication (MFA) for additional security layers.

5. Ensuring Functional & Secure Code After Refactoring

To ensure security and functionality:

    Performed unit testing after refactoring security features.
    Verified HTTPS enforcement by checking secure login page deployment.
    Reviewed application logs to detect any security warnings.

6. Tools, Resources & Best Practices for Future Use

Tools Used:

    OWASP Dependency Check – Identified third-party security risks.
    Java Keytool – Created and installed SSL/TLS certificates.
    Spring Security – Enforced authentication and secure access control.

Best Practices Applied:

    Encrypt data in transit with HTTPS.
    Use secure hashing algorithms for data integrity verification.
    Scan dependencies regularly to mitigate known security flaws.

7. Showcasing Work to Future Employers

For potential employers, I would highlight:

    The security report detailing vulnerability assessment and fixes.
    The refactored code with security improvements.
    Screenshots demonstrating HTTPS, SHA-256 hashing, and security testing results.
