# Disaster Recovery Strategy — AWS Hybrid Cloud

Oluwaseyi Michael Falode | Cloud & Cybersecurity | Toronto, ON

Enterprise disaster recovery strategy with RTO/RPO design, hybrid cloud architecture, and a 3-2-1 backup model.

## 📖 Overview
This project presents a **Disaster Recovery (DR) Strategy** designed to ensure business continuity, system resilience, and rapid recovery of critical services in the event of a disruption.

It was developed as part of my CloudOps and Cybersecurity training, focusing on aligning **Business Impact Analysis (BIA)** and **Business Continuity Planning (BCP)** with modern cloud-based recovery approaches.

---

## 🎯 Objectives
- Minimize downtime using defined **RTO (Recovery Time Objective)** and **RPO (Recovery Point Objective)**
- Ensure secure and reliable data recovery
- Implement scalable and resilient recovery architecture
- Align with regulatory and compliance requirements

---

## 🏗️ Architecture Approach
The DR strategy follows a **Hybrid Cloud Model**:

- 🖥️ Primary Site (On-Premises Production)
- ☁️ Warm Standby Disaster Recovery Site (Cloud - AWS/Azure)
- 🧊 Cold Backup Storage (Offsite / Object Storage)

### Key Concepts:
- Replication Layer (15 min – 1 hr RPO)
- Tiered Recovery Model (T1, T2, T3 systems)
- Automated failover and restore procedures

---

## 💾 Backup & Recovery Strategy
Implemented using the **3-2-1 Backup Rule**:
- 3 copies of data
- 2 different storage types
- 1 offsite backup

### Backup Types:
- Full backups (weekly)
- Incremental backups (daily)
- Differential backups (every 6 hours)
- Transaction log backups (15 minutes)
- VM snapshots (every 4 hours)

---

## ⚙️ Key Features
- Defined recovery tiers for critical systems
- Documented **runbooks for incident response**
- Regular DR testing (tabletop + live drills)
- Continuous monitoring and alerting
- Integration with BCP communication protocols

---

## 🔐 Security & Compliance
- Addresses risks such as ransomware, system failure, and insider threats
- Aligns with enterprise compliance standards
- Incorporates secure backup and recovery mechanisms

---

## 📊 Key Metrics (KPIs)
- RTO / RPO adherence
- Recovery success rate
- System availability
- Incident response time

---

## 🧠 What I Learned
- Translating BIA and BCP into actionable DR strategy
- Designing resilient hybrid cloud architectures
- Implementing structured backup and recovery frameworks
- Aligning technical recovery with business priorities

---

## 👤 Author

**Oluwaseyi Michael Falode**  
CloudOps | Cybersecurity | DevSecOps  
