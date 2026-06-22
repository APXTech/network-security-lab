# NAT & Port Forwarding

## 🎯 Objective
To enable secure communication between internal private networks and external public networks using NAT.

---

## 🌐 What is NAT?

Network Address Translation (NAT) is a method used to map private IP addresses to a public IP address for internet communication.

---

## 🔄 Types of NAT

### 1. Static NAT
- One-to-one mapping
- Used for servers

### 2. Dynamic NAT
- Pool of public IPs
- Assigned dynamically

### 3. PAT (Port Address Translation)
- Many-to-one mapping
- Most commonly used in enterprises

---

## 🔐 Port Forwarding

- Redirect external traffic to internal systems
- Used for services like web servers, VPN access

Example:
- External IP: 203.x.x.x:443
- Internal Server: 192.168.1.10:443

---

## 🛡 Security Considerations

- Only required ports should be open
- Restrict unauthorized external access
- Monitor NAT logs in SIEM
