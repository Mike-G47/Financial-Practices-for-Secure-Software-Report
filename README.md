# Financial-Practices-for-Secure-Software-Report

### Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
The client, Artemis Financial, is a financial services company that required enhanced protection for its data transmission and storage systems. The company wanted a secure way to handle sensitive user data using encryption, secure communication protocols, and vulnerability checks. The primary issue was ensuring data integrity and privacy using best practices in secure software development.

### What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I successfully identified and mitigated potential vulnerabilities by implementing SHA-256 hashing, enabling HTTPS, and using OWASP Dependency-Check to scan for insecure dependencies. Secure coding is vital because even small mistakes can lead to major data breaches. Secure software protects customer trust, prevents legal issues, and supports long-term operational stability.

### Which part of the vulnerability assessment was challenging or helpful to you?
The most challenging part was ensuring that no insecure dependencies remained after refactoring. Running OWASP Dependency-Check and interpreting the results was especially helpful, as it provided insight into which libraries could pose a risk and how to address them.

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased security by implementing HTTPS, encrypting data with SHA-256, and avoiding hardcoded sensitive values. In future projects, I would continue using tools like OWASP Dependency-Check, Snyk, and static code analysis tools to identify and prioritize vulnerabilities based on severity and impact.

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I verified the application through unit testing and browser-based testing of HTTPS endpoints. After refactoring, I re-ran dependency and functional tests to ensure the code still met security and functionality requirements. No new vulnerabilities were introduced, which I confirmed through repeat scans and successful checksum validations.

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Key tools included Spring Boot, SHA-256 hashing, HTTPS configuration, OWASP Dependency-Check, and structured unit tests. Coding practices like modular design, exception handling, and avoiding hardcoded secrets will continue to be valuable for writing secure and maintainable code.

### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would showcase the secure hashing implementation, HTTPS configuration, and automated vulnerability reports. These demonstrate my ability to write secure APIs, integrate security tools, and follow industry standards—all valuable skills for backend and security-focused development roles.
