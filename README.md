# CS 305 – Software Security Portfolio  

## Artifact Submitted  
For this course, I chose to include my **Artemis Financial Practices for Secure Software Report** as the artifact for my portfolio. This project shows how I applied secure coding practices, implemented encryption, set up secure communications, and tested the application for vulnerabilities.  

---

## Reflection  

**Client and Requirements**  
Artemis Financial is a financial services company that builds personalized plans for clients covering savings, investments, insurance, and retirement. As part of their modernization, they needed stronger security in their web application to protect sensitive financial data. My role was to implement secure software practices, verify functionality, and document the results.  

**What I Did Well**  
I implemented a SHA-256 hashing algorithm, configured SSL/TLS certificates, and enforced secure HTTPS communication. I also ran the OWASP Dependency-Check tool to identify vulnerable third-party libraries. Secure coding matters because it prevents data breaches, protects client trust, and reduces business risk.  

**Challenges and Helpful Aspects**  
One of the harder parts was configuring the TLS certificate correctly and making sure the application served traffic securely. This was also one of the most helpful learning opportunities because I gained hands-on experience with encryption and certificates.  

**Increasing Layers of Security**  
Security was strengthened through multiple layers, including strong cryptography, encrypted communication, dependency scanning, and careful filtering of false positives in vulnerability reports. In the future, I would also use automated security testing tools and penetration testing to expand coverage.  

**Ensuring Functionality and Security**  
After refactoring, I tested the application to confirm that everything worked as expected. The `/hash` endpoint produced the correct checksum, the HTTPS connection worked with the new certificate, and the dependency scans confirmed that vulnerabilities had been addressed.  

**Resources and Tools**  
- SHA-256 for secure hashing  
- Java keytool for SSL/TLS certificate generation  
- OWASP Dependency-Check Maven plugin  
- Oracle Java Secure Coding Guidelines and OWASP best practices  

**What to Show Employers**  
This artifact highlights my ability to:  
- Implement secure coding techniques  
- Configure and deploy TLS for secure client-server communication  
- Run vulnerability scans on external dependencies  
- Document the process and results in a professional format  

It demonstrates both my technical skills and my understanding of industry best practices for secure software development.  

---

## Repository Contents  
- `Project2-Artemis-Secure-Software-Report.pdf`  
- `README.md`  

---

## Author  
Liam Farrell  
Computer Science, SNHU  

