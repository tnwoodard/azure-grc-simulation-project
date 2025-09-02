# Azure GRC Simulation Project – Risk and Compliance Assessment

## 📌 Executive Summary
GetsIt2U is a global shipping platform contracted by the United States government (US-GOV). GetsIt2U is migrating its core departments (Marketing, Accounting, and IT) to Microsoft Azure’s IaaS platform to improve scalability. The initial migration revealed three compliance gaps:  

1. Unauthorized user access beyond job/departmental scope  
2. Unverified mission-critical backups  
3. Outdated vulnerability scanning  

Addressing these findings is essential for compliance with FISMA, NIST SP 800-53, and PCI DSS. Recommended actions are to implement role-based access controls (RBAC), enforce backup verifications and scheduling, and define and maintain a vulnerability management program.  

> **Note:** Colored tables, charts, and full formatting are included in the PDF version:  
[Download full report PDF](docs/report.pdf)

---

## 🎯 Objectives
- Identify and evaluate risks in a simulated Azure environment  
- Map risks to compliance frameworks (PCI DSS, FISMA, NIST)  
- Provide remediation strategies to strengthen cloud governance

---

## 🛠️ Methodology
The project followed a structured approach:  
1. Risk identification in the simulated Azure environment  
2. Likelihood and impact scoring  
3. Mapping risks to compliance frameworks  
4. Recommendations for mitigation  

> **For full-color tables and snapshots of the methodology, see the PDF snapshot:**  
[View project snapshot](docs/snapshot.pdf)

---

## 🔎 Key Findings
- **Access Controls:** Users can access resources beyond their job roles or department boundaries.  
- **Disaster Recovery:** No verifiable backups or defined recovery plan for mission-critical data.  
- **Vulnerability Scanning:** No defined scanning scope or schedule exists.  

> Detailed risk tables with colors are available in the PDF snapshot.

---

## 📑 Compliance Mapping

Risks were mapped against:

- **PCI DSS** – Limited access to cardholder data via Azure RBAC, regular backups, and scheduled vulnerability scanning align with PCI DSS requirements 7.1-7.2, 11.2.x, and 12.5.1/12.10.1.  
- **FISMA** – Implementing RBAC, regular backup tests, and a vulnerability management schedule supports FISMA’s security controls and continuous monitoring mandates.  
- **NIST CSF** – Mapping identified risks to access controls (AC-6), backup processes (CP-9), and vulnerability scanning (RA-5) aligns with NIST CSF functions: Identify, Protect, Detect, and Respond.  

> Colored compliance tables are available in the PDF snapshot.

---

## 🛡️ Remediation Recommendations
1. **Implement RBAC** within segmented Azure Resource Groups (RGs) to enforce least privilege.  
   - NIST SP 800-53 AC-6(1)-(10)  
   - PCI DSS 7.1-7.2  

2. **Implement backups of files and systems and develop a backup schedule**.  
   - NIST SP 800-53 CP-9  
   - PCI DSS 12.5.1 & 12.10.1  

3. **Implement vulnerability scanning; develop a vulnerability management schedule**.  
   - NIST SP 800-53 RA-5(a) & (b)  
   - PCI DSS 11.2.x  

> Full visual summaries with colored tables and diagrams are included in the PDF.

---

## 🔌 Secure Network Topology
A secure network topology was designed by incorporating least privilege principles, network segmentation, and RBAC enforcement.  

> See the PDF snapshot for a visual diagram.

---

## 📝 Conclusion
By implementing RBAC, defining and testing a backup strategy, and establishing a vulnerability management program, GetsIt2U can significantly strengthen its Azure cloud security posture. These measures directly align with NIST SP 800-53 and PCI DSS requirements, reducing compliance risk while improving operational resilience. Addressing these gaps now safeguards sensitive cardholder and government data and positions GetsIt2U for sustained compliance and trust with its partners.

---

## 📂 Supporting Files
- [Download full report PDF](docs/report.pdf) – complete report with colors and tables  
- [View project snapshot](docs/snapshot.pdf) – 4-page case study snapshot with tables

---

## 👩‍💻 Author
**Tempestt Woodard**  
- Navy veteran & cybersecurity professional  
- M.S. Cybersecurity and Information Assurance (WGU, in progress)  
- Focus: GRC, SOC, and cloud security  
- [LinkedIn](https://www.linkedin.com/in/tempesttwoodard) | [GitHub](https://github.com/tnwoodard)
