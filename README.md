# Enterprise-Networking-and-Security Project - Trading Floor Support Center
Here's a GitHub README format based on your project details:


**Project Overview:**  
This project focuses on designing and implementing a scalable, secure, and robust network for a Trading Floor Support Center with 600+ users distributed across three floors. It incorporates advanced networking principles and security measures to build a future-ready enterprise network.

---

### **Project Highlights:**

#### 1️⃣ **Enterprise-Grade Network Design** 🖧
- Built a **redundant hierarchical topology** with two routers and two multilayer switches, ensuring **high availability** and minimizing **downtime**.
- Established connections to **two ISPs** for **failover** and uninterrupted internet access.

#### 2️⃣ **Departmental Segmentation & Wireless Access** 📶
- Designed **VLANs** for departmental segmentation, allocating unique subnets using **172.16.1.0/22**, ensuring network isolation and scalability.
- Enabled **seamless wireless connectivity** for all departments, enhancing flexibility and mobility.

#### 3️⃣ **Advanced Security Measures** 🛡️🔑
- Configured **SSH** on routers and switches for **secure remote management**.
- Implemented **port-security** in the Finance & Accounts department to prevent unauthorized access, using **sticky MAC** with a violation mode of **shutdown**.
- Used **Access Control Lists (ACLs)** to control traffic and ensure secure internet access.

#### 4️⃣ **Dynamic IP Management & Static Server Allocation** ⚙️
- Deployed **dedicated DHCP servers** for **dynamic IP allocation** across all devices.
- Assigned **static IPs** to server room devices for consistency and manageability.

#### 5️⃣ **Optimized Routing** 🚦
- Configured **OSPF** as the routing protocol for efficient and scalable route advertisement.

#### 6️⃣ **PAT Configuration** 🌐
- Set up **Port Address Translation (PAT)** for secure internet access using the router’s outbound interface IPv4 address.

---

### **Tools & Technologies Used:**
- **Cisco Packet Tracer**
- **VLANs, Subnetting, OSPF Routing Protocol, DHCP Servers, Port Security**

---

### **Key Takeaways:**
- This project significantly enhanced my skills in **Enterprise Networking, IT Security**, and **Infrastructure Design**.
- Gained hands-on experience in balancing **security** and **scalability**, ensuring seamless communication across departments while meeting enterprise-grade requirements.

---

### **Project Setup:**

To view or contribute to this project, clone the repository:

```bash
git clone https://github.com/yourusername/enterprise-networking-security.git
```


