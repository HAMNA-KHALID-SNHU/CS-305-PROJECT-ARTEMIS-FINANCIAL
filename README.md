# Artemis Financial Practices for Secure Software

**Course:** CS-305 – Secure Software Development
**Student:** Hamna Khalid
**Instructor:** Dr. Ross Foultz
**Date:** December 16, 2025



## Project Overview

This project demonstrates the secure software development practices implemented for **Artemis Financial**, a financial consulting company that provides customized investment and wealth management services.

The goal of this project was to strengthen the **security posture** of Artemis Financial’s software application by implementing **encryption mechanisms**, conducting **vulnerability assessments**, and applying **best practices for secure code**.

The work reflects principles from the **Secure Software Development Life Cycle (SSDLC)** and emphasizes continuous improvement through automated vulnerability management and secure data handling.



## Project Deliverables

This project includes the following key components:

### Source Code Package (ZIP)

 **`Artemis_Financial_Secure_Practices_Source.zip`**
Contains the Maven-based Java RESTful application with the following features:

* Configured **SSL/TLS** encryption for secure data transmission.
* Implemented **input validation** and **exception handling**.
* Integrated **OWASP Dependency-Check Maven plugin** for vulnerability scanning.
* Verified build integrity using `mvn clean verify`.



### Project Report (DOCX)

**`Artemis_Financial_Practices_for_Secure_Software_Report.docx`**
A detailed documentation report covering:

* Overview of Artemis Financial and project requirements.
* Identified vulnerabilities and their mitigations.
* Security enhancements implemented in the code.
* Results from the **OWASP Dependency Check** scan.
* Discussion of testing, encryption configuration, and final security validation.



### Screenshot Evidence

 **Proof of successful execution and testing steps:**

* **CS-305-M6-F1.png:** OWASP Dependency Check command execution in PowerShell.
* **CS-305-M6-F2.png:** Maven build verification showing *BUILD SUCCESS*.
* **CS-305-M6-F3.png:** OWASP plugin running vulnerability analysis.
* **CS-305-M6-F4.png:** Completed `dependency-check-report.html` proof.

These images demonstrate the successful configuration and execution of the OWASP scan and build verification process.



##  Technical Highlights

| **Area**                | **Description**                                                                              |
| ----------------------- | -------------------------------------------------------------------------------------------- |
| **Encryption**          | Configured HTTPS using a self-signed certificate generated via Java Keytool.                 |
| **Dependency Scanning** | Implemented OWASP Dependency-Check Maven plugin (`v8.4.2`) to identify CVEs in dependencies. |
| **Error Handling**      | Added structured exception management to prevent information leakage.                        |
| **Validation**          | Applied input validation and output encoding to prevent injection attacks.                   |
| **Testing**             | Used Maven’s `clean verify` lifecycle to confirm build stability and re-run security checks. |



## Tools and Technologies

* **Java 11**
* **Apache Maven**
* **OWASP Dependency-Check Maven Plugin (v8.4.2)**
* **Java Keytool (for SSL certificate)**
* **GitHub (Version Control)**
* **Microsoft Word (Documentation)**



## Summary of Results

* All build and verification processes completed with **no critical vulnerabilities** found.
* The application successfully compiled and executed under a secure SSL configuration.
* Dependency scans completed with **BUILD SUCCESS**, confirming proper OWASP integration.
* Demonstrated secure coding principles aligned with **industry best practices** and **OWASP Top 10** standards.



##  Reflection

This project deepened my understanding of implementing **defense-in-depth** in software systems.
Troubleshooting the OWASP dependency check (including resolving **NVD API access restrictions**) taught me patience and real-world configuration management.

It reinforced the mindset that **security is not a feature—it’s a process** that must be built into every stage of development.



##  References

* OWASP Foundation. (2025). [OWASP Dependency Check Maven Plugin Documentation](https://owasp.org/www-project-dependency-check/)
  
* CISA. (2025). [Known Exploited Vulnerabilities Catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)

* Apache Software Foundation. (2025). [Apache Maven Documentation](https://maven.apache.org/)

* NIST. (2025). [National Vulnerability Database (NVD)](https://nvd.nist.gov)

* SNHU CS-305 Course Materials and Module 6–8 Guidelines by Dr. Ross Foultz (2025)



## Repository Contents

| **File Name**                                                 | **Description**                                      |
| ------------------------------------------------------------- | ---------------------------------------------------- |
| `Artemis_Financial_Secure_Practices_Source.zip`               | Source code with implemented security practices.     |
| `Artemis_Financial_Practices_for_Secure_Software_Report.docx` | Formal documentation report.                         |
| `CS-305-M6-F1.png` – `CS-305-M6-F4.png`                       | Proof screenshots for build and OWASP execution.     |
| `README.md`                                                   | This file – overview and explanation of the project. |



### Author

**Hamna Khalid**
Bachelor’s in Computer Science – Software Engineering Concentration
Southern New Hampshire University
hamna.khalid@snhu.edu

