# 🖧 Enterprise Network Design Project

> Design of a complete enterprise network system for a company with two branches: the headquarters in Thu Duc City and a branch office in District 3, ensuring performance, security, and scalability.

---

## 📌 Project Objectives

- Build a full **logical and physical network model** for the enterprise

- Implement VLAN segmentation by department: CEO, HR, Developer, Tester, etc.

- Establish **VPN Site-to-Site** connection between the two branches

- Integrate **Data Center** and **Cloud-based architecture**

- Ensure data security, internal network isolation, and public Wi-Fi access

---

## 🧱 Network Architecture Model

<p align="">
  <strong>📌 Overall Network Topology:</strong><br>

  
  ![TSC](https://github.com/MHabc/design-enterprise-network-project/blob/main/Picture1.png)


  <strong>🏢 Headquarters – Thu Duc City:</strong><br>


  ![TSC](https://github.com/MHabc/design-enterprise-network-project/blob/main/Picture2.png)


  <strong>🏬 Branch Office – District 3:</strong><br>


  ![CN](https://github.com/MHabc/design-enterprise-network-project/blob/main/Picture3.png)


</p>

---

## 🛠 Technical Components

| Component     | Description |
|-------------------|------|
Deployment Sites | Thu Duc Headquarters & District 3 Branch |
| Technologies Used | VPN IPsec, VLAN, DHCP, NAT, Wi-Fi |
| Design Tools | Cisco Packet Tracer, MS Visio |
| Core Devices    | Router, Switch Layer 2/3, Access Point |
| Deployment Model| Hybrid: On-Premise + Cloud |

---

## 📊 Bảng phân tích thiết bị

| Devices          | Quantity | Notes|
|--------------------|----------|---------|
| Router Layer 3     | 2        | One at each site |
| Switch Layer 2     | 4        | Divided by floors and departments |
| Access Point Wi-Fi | 2        | Public & Internal Wi-Fi |
| Firewall / NAT     | 1        | Internal NAT setup |

---

## 📁 Results & Evaluation

- Clear and intuitive network model, deployable in real-world environments

- Scalable design for future branch expansions

- Applied routing, segmentation, and security techniques

- Completed network diagrams, IP addressing table, and equipment cost estimation

---


## 📝 Attached Documents

- Detailed Report: `report-design-network-system.docx`
- Network Topology (Cisco Packet Tracer): `design-network-system.pkt` 

