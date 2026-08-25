# University Campus Secure Network (HCIA Security)

By : Ahmed Ehab Ahmed

---

## 1. Project Scenario. 

We are building a secure network for a university campus[cite: 3]. The goal is to separate the different departments and control their access.

### Main Goals:
* **IT Full Control:** The IT department can access all servers to manage the network.
* **Department Isolation:** Every faculty (like Medical or Engineering) has its own safe network[cite: 3]. They can only open their own specific server.
* **Time Rules:** Engineering and Research students can only use their servers during lab time (from 08:00 AM to 06:00 PM).
* **Internet Filter:** Students cannot open social media or games.Medical staff can only open medical websites.
* **Guest Internet:** Guest Wi-Fi has a speed limit to keep the network fast for others.

* <img width="637" height="831" alt="image" src="https://github.com/user-attachments/assets/66d74ae9-b269-4980-ac15-29ad5d18c816" />


---

## 2. Network Topology .

<img width="1145" height="621" alt="image" src="https://github.com/user-attachments/assets/373e789c-2786-4183-bf57-b74bf45bef1e" />



---

## 3. Firewall Network Interfaces (GUI).
This section shows the firewall interfaces. Every department has a specific VLAN and sub-interface[cite: 3].

<img width="1200" height="2089" alt="11111111" src="https://github.com/user-attachments/assets/a660b0a0-79c5-441a-be24-9c6811d1fb12" />

---
## . Firewall Network Interfaces.

<img width="1182" height="577" alt="image" src="https://github.com/user-attachments/assets/a595192d-1d18-4b86-88d2-cf353d50fd8c" />


---

## 4. Firewall Security Policies (GUI)
Here are the security rules. They control who can open the servers and the internet, with time limits and URL filters.

<img width="1160" height="450" alt="image" src="https://github.com/user-attachments/assets/1341e187-36b8-41e9-b8d1-c04d1d7d9c01" />



---

## 5. NAT Policy
We used Source NAT (Easy-IP) to allow internal users to go to the Internet.

<img width="1718" height="672" alt="image" src="https://github.com/user-attachments/assets/e9559c57-05e3-4f84-a5ce-f0fa6c0ed827" />



---

## 6. CLI Configuration — Core Switch.
This is the configuration for the Core Switch to create VLANs and the Trunk port.

<img width="453" height="717" alt="image" src="https://github.com/user-attachments/assets/d17e964e-ba12-412c-9ccf-2f2373c50d37" />

---

## 7. Firewall CLI — Interfaces & Security Zones.

<img width="646" height="688" alt="image" src="https://github.com/user-attachments/assets/751de0a2-f633-4178-ba81-d6db5d259091" />

---

## 8. UTM Profiles & Time-Range.

<img width="818" height="353" alt="image" src="https://github.com/user-attachments/assets/f6142826-28e7-4a79-9637-6d362c6fcc02" />


---

## 9. Security Policies — DMZ Access Rules.

<img width="476" height="560" alt="image" src="https://github.com/user-attachments/assets/7a1016ec-4ee5-4ee1-9dca-7ea1ed26e592" />


---

## 10. Security Policies — DMZ Access Rules.

<img width="470" height="326" alt="image" src="https://github.com/user-attachments/assets/9c62f3f7-44bc-49ac-8938-a4a6d1bddb30" />

