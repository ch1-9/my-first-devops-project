# Automated Website Deployment Pipeline (CI/CD)

## Project Overview
This project implements a fully automated Continuous Integration and Continuous Deployment (CI/CD) pipeline. Instead of manually uploading web files to a cloud server every time an update is made, pushing code changes to GitHub automatically builds, delivers, and serves the updated website live on the internet.

---

## Why We Are Doing This (The Problem & Solution)
* **The Manual Problem:** In traditional workflows, developers manually copy files to servers using FTP or SSH. This manual process is slow, prone to human error, and difficult to track.
* **The DevOps Solution:** Automating deployments ensures that code delivery is fast, repeatable, consistent, and secure. Every commit triggers a standardized pipeline execution.

---

## Real-World Use Case
* **Company Scenario:** A startup marketing team needs to update their company landing page instantly when a new promotion goes live. 
* **Business Value:** By automating deployment through CI/CD, updates go live within seconds of a developer saving the code, minimizing downtime and eliminating manual server access risks.

---

## What We Can Learn From This Project
Building this project hands-on teaches the foundational pillars of DevOps engineering:
1. **Version Control:** Managing source code history using **Git and GitHub**.
2. **Cloud Infrastructure:** Provisioning and configuring virtual servers using **AWS EC2 (Free Tier)**.
3. **Web Server Management:** Installing and managing **Nginx** to handle HTTP web traffic requests.
4. **Pipeline Automation:** Writing automation workflows using **GitHub Actions** to connect cloud and code repositories securely.

---

## Architecture & Tools Flow
```text
[ GitHub Repository ] 
       │ (Push Code)
       ▼
[ GitHub Actions CI/CD Pipeline ] 
       │ (Secure SSH Connection)
       ▼
[ AWS EC2 Linux Instance running Nginx ] 
       │ (Serves content)
       ▼
[ Live Website on the Internet ]

Author
Name: Channayya Hiremath

Background: Transitioning into DevOps / Cloud Engineering
