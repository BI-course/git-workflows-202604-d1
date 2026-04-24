**Data Governance:**

Data governance is the structured, organization-wide practice of managing data availability, usability, integrity, and security through established policies, processes, and roles. It acts as a "traffic control" system for an organization's data, ensuring that verified, high-quality data flows securely to trusted users.

Data governance has some key components:

- **Data quality management:** Defines accuracy, consistency, and reliability through validation rules and monitoring.
- **Data stewardship:** Assigns accountability for data assets to specific individuals(stewards) who ensure policies are followed.
- **Data Security and Privacy:** Implements controls (encryption, role-based access) to protect sensitive data and comply with regulations like GDPR and HIPAA.
- **Metadata management:** Manages information about data (data lineage, definitions, and origins) to make it understandable and traceable.
- **Data cataloguing:** Creates a centralized, searchable inventory of data assets, facilitating discovery.

Data governance has 4 pillars that guide the framework, a framework is the blueprint turning principles into practice, resulting in four interdependent pillars:

- **People:** Governance committees, data owners (accountable), data stewards (executors), and IT custodians.
- **Policies:** Rules defining how data is created, stored, used, and protected.
- **Processes:** repeatable workflows for data quality improvement, audit, and issue resolution.
- **Technology:** Software for data cataloging, lineage tracking, quality monitoring, and access enforcement.

There are certain benefits that come from data governance:

- **The quality of data improves:** Higher accuracy in data, consistency, and integrity/data being trustworthy.
- **There's stronger regulatory compliance:** Adheres to strict regulations (GDPR, CCPA, EU AI Act), avoiding heavy fines.
- **Enhanced Decision-Making:** Provides a "single source of truth," allowing leadership to make data-driven decisions with confidence.
- **Increased Operational Efficiency:** Reduces data silos and duplication.
- **AI readiness:** Provides the clean, reliable data necessary for training trustworthy AI models.

There are roles and responsibilities that come with data governance, they include:

- **Chief Data Officer(CDO):** High-level executive responsible for data strategy and security funding.
- **Governance Committee (Council):** Sets policies, priorities, and resolves disputes.
- **Data Owners:** Senior business leaders accountable for specific data domains (e.g., Finance, Customer).
- **Data Stewards:** Subject matter experts who execute day-to-day management and quality control.
- **Data Custodians:** IT professionals handling technical implementation (security, storage, backups).

To ensure data governance is thoroughly done, the following practices are better suited for implementation:

- **Start small, think big:** Begin by governing one or two critical data domains (e.g., customer data) rather than attempting to "boil the ocean".
- **Automation:** Use tools to automate data lineage, data discovery, and quality checks.
- **Align with Business Goals:** Ensure governance directly supports business needs, such as increased revenue or reduced risk, rather than being solely an IT task.
- **Establish Data literacy:** Train employees on how to understand and use data correctly.
- **Iterate and improve:** Treat governance as a continuous process rather than a one-time project, updating policies as technology evolves.

Data governance faces certain challenges, and could be affected by future trends in the IT world, they are as follows:

- **Challenges:** Resistance to change, limited resources, and balancing data accessibility with strict security.
- **Future Trends:** AI-driven automation for anomaly detection, increasing focus on "active" data governance(real-time), and "data mesh" architectures(decentralized stewardship).

**Access to PII:**

Personally Identifiable Information (PII) refers to the authorized ability to view, modify, or use data that can distinguish or trace an individual's identity (name, social security number, biometric records).

Managing access is a critical component of data privacy, improperly secured PII is a prime target for identity theft, fraud, and ransomware.

This is a comprehensive overview of accessing and controlling PII:

- **Types of PII and sensitivity:**

- **Sensitive PII:** Information that, if disclosed, could result in substantial harm such as SSN, driver's license, financial accounts, medical records. This requires strict access controls and encryption.
- **Non-sensitive PII:** Publicly available information such as phone book listings, business addresses. While lower risk, it can be combined to identify an individual.
- **Quasi-identifiers:** Data points that are not unique alone but can be combined to identify a person.

- **Who has access to PII?**

- **Internal personnel:** Employees, HR staff, IT administrators, and contractors who need the data to perform their job duties.
- **Third-party vendors:** Cloud service providers, payment processors, and consultants.
- **Unauthorized actors:** Hackers, cybercriminals, and intruders committing fraud.

- **Legal and regulatory requirements:**

Access to PII is strictly regulated based on jurisdiction and the industry, they are as stated below:

- **GDPR (EU):** Grants individuals "right of access" to their own data and requires strict control over who can process personal information.
- **HIPAA (USA):** Protects Protected Health Information (PHI) by regulating physical and electronic access in healthcare settings.
- **CCPA/CPRA (California):** Grants consumers rights over how their PII is collected and shared.
- **Privacy act of 1974 (USA):** Governs how federal agencies collect and disclose PII.
- **PCI DSS:** Defines standards for protecting credit card data access.

- **PII access control best practices:**

Organizations must follow the "need to know" principle, ensuring access is restricted to the minimum required for job functions.

- **Role-based access control (RBAC):** Access is assigned based on job role rather than individual identity.
- **Least Privileged principle:** Users are granted the lowest level of permissions necessary.
- **Multi-factor Authentication (MFA):** Mandated for systems storing PII to prevent unauthorized access from stolen credentials.
- **Data masking/anonymization:** Obscuring PII elements (e.g., showing only the last 4 digits of a credit card).
- **Audit trails:** Maintaining detailed logs of who accessed what data, when, and from where.

- **PII Access threats and risks:**

- **Phishing & social engineering:** Tricking employees into providing access credentials.
- **Insider threats:** Employees with legitimate access abusing it or acting negligently.
- **Unsecured devices/IoT:** Laptops, phones, or IoT devices lacking encryption or password protection.
- **Data sprawl:** PII spreading across multiple, unsecured systems, making it difficult to monitor.

- **Incident response and disposal:**

- **Incident response plan:** A documented procedure for identifying, containing, and reporting PII breaches to authorities and affected individuals.
- **Secure disposal:** Shredding physical documents and using data-wiping software for digital media to ensure PII cannot be recovered.

- **Individual rights (Accessing your own PII):**

Individuals have the right to:

- **Be informed:** Know why their PII is being collected and processed.
- **Access:** Request a copy of their personal data from organizations.
- **Rectify:** Correct inaccurate information.
- **Erasure (Right to be forgotten):** Request deletion of data, with some exceptions.
