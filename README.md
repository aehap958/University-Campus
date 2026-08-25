# 🎓 University Campus Secure Network (HCIA Security)

👤 **By:** Ahmed Ehab Ahmed

---

## 1. 🎯 Project Scenario
We are building a secure network for a university campus. The goal is to separate the different departments and control their access.

### ✨ Main Goals:
* 👨‍💻 **IT Full Control:** The IT department can access all servers to manage the network.
* 🛡️ **Department Isolation:** Every faculty (like Medical or Engineering) has its own safe network. They can only open their own specific server.
* ⏱️ **Time Rules:** Engineering and Research students can only use their servers during lab time (from 08:00 AM to 06:00 PM).
* 🛑 **Internet Filter:** Students cannot open social media or games. Medical staff can only open medical websites.
* 📶 **Guest Internet:** Guest Wi-Fi has a speed limit to keep the network fast for others.

<img width="637" height="831" alt="Project Team & Scenario" src="https://github.com/user-attachments/assets/66d74ae9-b269-4980-ac15-29ad5d18c816" />

---

## 2. 🗺️ Network Topology

<img width="1145" height="621" alt="Network Topology" src="https://github.com/user-attachments/assets/373e789c-2786-4183-bf57-b74bf45bef1e" />

---

## 3. 🌐 Firewall Network Interfaces (GUI)
This section shows the firewall interfaces. Every department has a specific VLAN and sub-interface.

<img width="1297" height="522" alt="Firewall Interfaces 1" src="https://github.com/user-attachments/assets/54a94109-6bb5-4259-bfe1-2d038e2ebb0e" />
<br>
<img width="1182" height="577" alt="Firewall Interfaces 2" src="https://github.com/user-attachments/assets/a595192d-1d18-4b86-88d2-cf353d50fd8c" />

---

## 4. 🔒 Firewall Security Policies (GUI)
Here are the security rules. They control who can open the servers and the internet, with time limits and URL filters.

<img width="1160" height="450" alt="Security Policies GUI" src="https://github.com/user-attachments/assets/1341e187-36b8-41e9-b8d1-c04d1d7d9c01" />

---

## 5. 🌍 NAT Policy
We used Source NAT (Easy-IP) to allow internal users to go to the Internet.

<img width="1718" height="672" alt="NAT Policy" src="https://github.com/user-attachments/assets/e9559c57-05e3-4f84-a5ce-f0fa6c0ed827" />

---

## 6. ⚙️ CLI Configuration — Core Switch
This is the configuration for the Core Switch to create VLANs and the Trunk port.

<img width="1200" height="2089" alt="Core Switch Config" src="https://github.com/user-attachments/assets/6c0559a0-fabb-4d6d-8983-af51ef148a73" />

---

## 7. 💻 Firewall CLI — Interfaces & Security Zones

<img width="1200" height="1400" alt="Firewall Interfaces CLI" src="https://github.com/user-attachments/assets/60ab0ce5-83e7-48ef-bf11-f79840b375e3" />

---

## 8. ⏳ UTM Profiles & Time-Range

<img width="2000" height="1127" alt="UTM Profiles" src="https://github.com/user-attachments/assets/237fec9a-5b31-4db9-85a3-aa6052584549" />

---

## 9. 🛡️ Security Policies — DMZ Access Rules

<img width="1200" height="1544" alt="DMZ Access Rules" src="https://github.com/user-attachments/assets/e599fc83-a165-4549-a203-16bf03a23478" />

---

## 10. 🌐 Security Policies — Internet Access Rules

<img width="947" height="707" alt="Internet Access Rules" src="https://github.com/user-attachments/assets/9f5558ff-d887-4c00-87a6-77b949de0e44" />

---

## 🏁 Conclusion & Contact

Thank you for reading my project! 

**Let's Connect:**
* 💼 **LinkedIn:** [Ahmed Ehab](www.linkedin.com/in/ahmedehab-engineer)
* 📧 **Email:** [Contact Me](eng.ahmed.ehap@gmail.com)
