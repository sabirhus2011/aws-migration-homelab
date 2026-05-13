# AWS Migration Home Lab

A hands-on lab project simulating an on-premises to AWS cloud migration using industry-standard tools. Built to demonstrate practical experience with AWS migration services, virtualization, and cloud infrastructure.

## 🎯 Project Goal

Simulate a real-world enterprise migration scenario by moving a two-tier application (database + application server) from a local virtualized environment to AWS, using the same tools and patterns used in production migrations.

## 🛠️ Tools & Technologies

- **Virtualization:** VMware Workstation
- **Cloud Platform:** AWS (Free Tier)
- **Migration Services:** AWS Application Migration Service (MGN), AWS Database Migration Service (DMS)
- **Target Services:** Amazon EC2, Amazon RDS, Amazon VPC, IAM
- **Operating Systems:** Linux (Ubuntu Server), Windows Server

## 🏗️ Architecture

**Source Environment (On-Premises Simulation):**
- VM 1: Application Server (Ubuntu)
- VM 2: Database Server (MySQL/PostgreSQL)

**Target Environment (AWS):**
- Application Server → Amazon EC2 (via AWS MGN lift-and-shift)
- Database → Amazon RDS (via AWS DMS)
- Networking: Custom VPC with public/private subnets

*Architecture diagram to be added.*

## 📋 Project Phases

- [ ] Phase 1: Set up local VM environment (app + database server)
- [ ] Phase 2: Configure AWS Free Tier account, VPC, IAM roles
- [ ] Phase 3: Install AWS MGN replication agent on source app server
- [ ] Phase 4: Replicate and cut over app server to EC2
- [ ] Phase 5: Configure AWS DMS for database migration to RDS
- [ ] Phase 6: Validate migrated environment and document lessons learned

## 🎓 Skills Demonstrated

- AWS cloud migration patterns (lift-and-shift, replatform)
- Virtualization and hypervisor management
- Network design (VPC, subnets, security groups)
- Database migration and replication
- IAM and cloud security fundamentals
- Infrastructure documentation

## 📚 Background

This project supports my transition back into IT infrastructure roles, building on my prior experience as an IT Infrastructure Program Manager at Thomson Reuters where I managed data center operations across on-premises and AWS environments. It complements my AWS Certified Cloud Practitioner certification with hands-on technical depth.

## 📫 Connect

- **LinkedIn:** https://www.linkedin.com/in/sabirmhussain/
- **Certifications:** PMP, CSM, PRINCE2 Practitioner, CCNA, AWS Cloud Practitioner, ITIL v3

---

*This is a living document — updated as the project progresses.*
