# Multi-Honeypot Platform on Azure using T-Pot

This project demonstrates how to deploy a **cloud-based honeypot platform** using **T-Pot** on **Microsoft Azure**. It provides real-time attack telemetry, automated threat intelligence collection, and a centralized web interface for monitoring multiple honeypot services.

---

## Table of Contents

- [Multi-Honeypot Platform on Azure using T-Pot](#multi-honeypot-platform-on-azure-using-t-pot)
  - [Table of Contents](#table-of-contents)
  - [Project Structure](#project-structure)
  - [Overview](#overview)
  - [Tools \& Environment](#tools--environment)
  - [Medium Article](#medium-article)

---

## Project Structure

* `screenshots/` — Screenshots of the setup and configuration process

---

## Overview

**T-Pot** is an all-in-one honeypot platform that integrates multiple honeypot services into a single, easy-to-deploy system. This project focuses on:

* Deploying T-Pot on a Linux-based Azure virtual machine
* Collecting and visualizing real-time attack telemetry through the web interface
* Logging and analyzing network intrusion attempts using multiple honeypot types
* Configuring network security rules to safely expose services to the internet
* Gaining insights into attacker behavior through dashboards and log analysis

---


## Tools & Environment

- **[Microsoft Azure](https://azure.microsoft.com)** — Cloud platform used to host the honeypot virtual machine.  
- **[T-Pot](https://github.com/telekom-security/tpotce)** — All-in-one honeypot solution integrating multiple sensors for attack detection and monitoring.  
- **Windows** — Local operating system used for deployment, access, and server management.  
- **[PuTTY](https://www.putty.org)** — SSH client used to securely connect to the Azure VM.  


---

## Medium Article

A complete step-by-step deployment and analysis guide for this project is available here:
https://medium.com/@wazeen.tech/multi-honeypot-platform-on-azure-using-t-pot-10fca1142bfe

---
