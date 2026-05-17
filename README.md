# STRIDE Threat Modeling – E-Commerce Order Service

This project demonstrates a secure **E-Commerce Order Service** built with **NestJS** and **PostgreSQL**, focusing on **Threat Modeling**, **OWASP API Security**, and **DevSecOps** practices.

The system architecture consists of:

* Client/Customer Layer
* HTTPS-secured API Layer
* NestJS Order Service
* PostgreSQL Database

The project applies the **STRIDE threat modeling methodology** to identify and mitigate security risks across the application and infrastructure layers.

# Image:

<img width="1112" height="469" alt="image" src="https://github.com/user-attachments/assets/3056d8ea-1845-436f-b38f-57772e890cdc" />


---

# Objectives

* Identify security threats in a modern API-based order service
* Apply STRIDE threat modeling techniques
* Improve API and database security posture
* Demonstrate secure software architecture principles
* Integrate DevSecOps security practices into development workflows

---

# STRIDE Threat Modeling Applied

The following STRIDE categories were analyzed:

| STRIDE Category        | Security Focus                               |
| ---------------------- | -------------------------------------------- |
| Spoofing               | Authentication and identity protection       |
| Tampering              | Data integrity and SQL injection prevention  |
| Repudiation            | Audit logging and traceability               |
| Information Disclosure | Protection of sensitive customer/order data  |
| Denial of Service      | API abuse and resource exhaustion prevention |
| Elevation of Privilege | Authorization and access control enforcement |


# Image:

<img width="900" height="696" alt="image" src="https://github.com/user-attachments/assets/cdd3f3a0-3074-4d92-a6cd-438d00372fae" />

---

# Threats Identified

The threat modeling process identified risks such as:

* JWT token misuse or impersonation
* SQL injection attacks against order APIs
* Missing audit trails for transactions
* Exposure of customer and order information
* API flooding and denial-of-service attacks
* Privilege escalation through broken authorization controls


# Sample Image:

<img width="1429" height="869" alt="image" src="https://github.com/user-attachments/assets/fbccc52c-1dfe-4cef-ae4b-bb0d8c20cf9a" />

---

# Security Areas Addressed

* Authentication & Authorization
* API Security
* Database Security
* Secure Communication (HTTPS/TLS)
* Logging & Monitoring
* Input Validation
* Access Control
* Abuse Prevention
* DevSecOps Security Controls

---

# OWASP Security Considerations

The project aligns with several OWASP API Security principles, including:

* Broken Authentication Prevention
* Broken Object Level Authorization Prevention
* Security Misconfiguration Reduction
* API Resource Protection
* Sensitive Data Protection

---

# DevSecOps Focus

This project also emphasizes DevSecOps practices by integrating security into the software development lifecycle through:

* Threat Modeling
* Security Review Processes
* Dependency & Vulnerability Awareness
* Secure Deployment Considerations
* Continuous Security Validation

---

# Purpose of the Repository

This repository serves as a practical demonstration of how to:

* Perform STRIDE-based threat modeling
* Analyze risks in API-driven applications
* Design security-focused backend architectures
* Apply secure engineering principles in NestJS applications
* Understand common threats against e-commerce services

---

# Author:
Varrun Vashisht

