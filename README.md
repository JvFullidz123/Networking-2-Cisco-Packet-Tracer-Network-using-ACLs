# Networking-2: Cisco ACL Configuration Project

## 📌 Project Overview
This repository contains a networking project demonstrating the implementation of Access Control Lists (ACL) using Cisco Packet Tracer.

The project focuses on controlling network traffic between departments by applying standard ACL rules across multiple routers and subnetworks.

## 🎥 Video Demonstration
📺 Watch the full explanation here:  
https://youtu.be/RaKKIkONf-4

## 🛠️ Tools & Technologies
- Cisco Packet Tracer
- Networking Concepts:
  - IP Addressing
  - Subnetting
  - Access Control Lists (ACL)

## 🌐 Network Overview

### 📖 Legend
- **N.A.** – Network Address  
- **D.G.** – Default Gateway  
- **S.M.** – Subnet Mask  

---

## 🧩 Network Structure

### 🔹 Network 1 (192.168.0.0/24)
- **Default Gateway:** 192.168.0.1  
- **Subnet Mask:** 255.255.255.0  

**IT Department**
- PC10 – 192.168.0.2  
- PC11 – 192.168.0.3  

**HR Department**
- PC12 – 192.168.0.4  
- PC13 – 192.168.0.5  

---

### 🔹 Network 2 (192.168.3.0/24)
- **Default Gateway:** 192.168.3.1  

**HR Department**
- PC12(1) – 192.168.3.2  
- PC13(1) – 192.168.3.4  

---

### 🔹 Network 3 (192.168.4.0/24)
- **Default Gateway:** 192.168.4.1  

**IT Department**
- PC12(1)(1) – 192.168.4.2  
- PC13(1)(1) – 192.168.4.3  

---

## ⚙️ Router Configuration & Network Configuration

- Router and Network Configuration are in ACL script file.txt
