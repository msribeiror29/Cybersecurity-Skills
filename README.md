
# Cybersecurity-Skills

# Conducting a security audit:

# Controls and compliance checklist

**Controls assessment checklist**

|   Yes |     No | Control | *Explanation* |
| ----- | ----- | :---- | :---- |
|  |  | Least Privilege  | *Currently, all employees have access to customer data; privileges need to be limited to reduce the risk of a breach.* |
|  |  | Disaster recovery plans | *There are no disaster recovery plans in place. These need to be implemented to ensure business continuity.* |
|  |  | Password policies | *Employee password requirements are minimal, which could allow a threat actor to more easily access secure data/other assets via employee work equipment/the internal network.* |
|  |  | Separation of duties | *Needs to be implemented to reduce the possibility of fraud/access to critical data, since the company CEO currently runs day-to-day operations and manages the payroll.* |
|  |  | Firewall | *The existing firewall blocks traffic based on an appropriately defined set of security rules.* |
|  |  |  |  |
|  |  | Intrusion detection system (IDS) | *The IT department needs an IDS in place to help identify possible intrusions by threat actors.* |
|  |  | Backups | *The IT department needs to have backups of critical data, in the case of a breach, to ensure business continuity.* |
|  |  | Antivirus software | *Antivirus software is installed and monitored regularly by the IT department.* |
|  |  | Manual monitoring, maintenance, and intervention for legacy systems | *The list of assets notes the use of legacy systems. The risk assessment indicates that these systems are monitored and maintained, but there is not a regular schedule in place for this task and procedures/ policies related to intervention are unclear, which could place these systems at risk of a breach.*  |
|  |  | Encryption | *Encryption is not currently used; implementing it would provide greater confidentiality of sensitive information.* |
|  |  | Password management system | *There is no password management system currently in place; implementing this control would improve IT department/other employee productivity in the case of password issues.* |
|  |  | Locks (offices, storefront, warehouse) | *The store’s physical location, which includes the company’s main offices, store front, and warehouse of products, has sufficient locks.* |
|  |  | Closed-circuit television (CCTV) surveillance | *CCTV is installed/functioning at the store’s physical location.* |
|  |  | Fire detection/prevention (fire alarm, sprinkler system, etc.) | *Botium Toys’ physical location has a functioning fire detection and prevention system.* |

---

**Compliance checklist**

Payment Card Industry Data Security Standard (PCI DSS)

| Yes |     No | Best practice | *Explanation* |
| ----- | ----- | :---- | :---- |
|  |  | Only authorized users have access to customers’ credit card information.  | *Currently, all employees have access to the company’s internal data.* |
|  |  | Credit card information is accepted, processed, transmitted, and stored internally, in a secure environment. | *Credit card information is not encrypted and all employees currently have access to internal data, including customers’ credit card information.* |
|  |  | Implement data encryption procedures to better secure credit card transaction touchpoints and data.  | *The company does not currently use encryption to better ensure the confidentiality of customers’ financial information.* |
|  |  | Adopt secure password management policies. | *Password policies are nominal and no password management system is currently in place.* |

General Data Protection Regulation (GDPR)

| Yes |     No | Best practice | *Explanation* |
| ----- | ----- | :---- | :---- |
|  |  | E.U. customers’ data is kept private/secured. | *The company does not currently use encryption to better ensure the confidentiality of customers’ financial information.* |
|  |  | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. | *There is a plan to notify E.U. customers within 72 hours of a data breach.* |
|  |  | Ensure data is properly classified and inventoried. | *Current assets have been inventoried/listed, but not classified.* |
|  |  | Enforce privacy policies, procedures, and processes to properly document and maintain data. | *Privacy policies, procedures, and processes have been developed and enforced among IT team members and other employees, as needed.* |

System and Organizations Controls (SOC type 1, SOC type 2\) 

| Yes |     No | Best practice | *Explanation* |
| ----- | ----- | :---- | :---- |
|  |  | User access policies are established. | *Controls of Least Privilege and separation of duties are not currently in place; all employees have access to internally stored data.* |
|  |  | Sensitive data (PII/SPII) is confidential/private. | *Encryption is not currently used to better ensure the confidentiality of PII/SPII.* |
|  |  | Data integrity ensures the data is consistent, complete, accurate, and has been validated. | *Data integrity is in place.* |
|  |  | Data is available to individuals authorized to access it. | *While data is available to all employees, authorization needs to be limited to only the individuals who need access to it to do their jobs.* |

---

## 

## ***Security Audit Recommendations: Botium Toys***

*Based on the internal audit conducted, critical gaps were identified that expose Botium Toys to operational, financial (fines), and reputational risks. The recommendations below aim to align the company with the **NIST CSF** framework and ensure compliance with **PCI DSS**, **GDPR**, and **SOC** standards.*

### ***1\. Implementation of Access Controls and Identity Management***

* ***Principle of Least Privilege:** Currently, all employees have access to customer data. It is urgent to restrict access to only the information necessary for each specific job function.*

* ***Separation of Duties:** Management of payroll and daily operations should be separated from the CEO’s exclusive control to reduce the risk of fraud and errors.*

* ***Password Management:** Implement a **Password Management System** and robust password policies (complexity and rotation) to replace the current minimal requirements.*

### ***2\. Data Protection and Business Continuity***

* ***Data Encryption:** Implement encryption for data at rest and in transit. Currently, credit card information and PII/SPII (Personally Identifiable Information) are not encrypted, violating PCI DSS and GDPR standards.*  
  *\+4*  
* ***Disaster Recovery Plan (DRP) and Backups:** Establish a formal recovery plan and regular backup routines for critical data to ensure business continuity in the event of an incident.*

* ***Legacy Systems:** Define a regular schedule for monitoring, maintenance, and intervention policies for the older systems identified in the risk assessment.*

### ***3\. Network Security and Monitoring***

* ***Intrusion Detection System (IDS):** Install and configure an IDS to assist the IT department in proactively identifying potential intrusions by threat actors.*

### ***4\. Regulatory Compliance and Governance***

* ***Asset Classification:** Perform a detailed classification and inventory of all data and assets. Currently, assets are inventoried but not classified by sensitivity level.*

* ***GDPR Compliance (E.U.):** Although a 72-hour breach notification plan exists, the lack of encryption and data classification compromises the privacy of European Union customers.*

* ***PCI DSS Compliance:** To continue processing online payments, it is mandatory to restrict access to cardholder data and implement encryption across all transaction touchpoints.*

