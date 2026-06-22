# Sophos Firewall Policy Configuration (Basics)

## 🎯 Objective
To define secure firewall rules for enterprise network traffic control and protection.

---

## 🔐 Common Policy Rules

### 1. Allow LAN to Internet
- Source: Internal Network
- Destination: WAN
- Services: HTTP, HTTPS, DNS
- Action: ALLOW

---

### 2. Block Unauthorized Traffic
- Source: Any Unknown IP
- Destination: Internal Network
- Services: All
- Action: DENY

---

### 3. VPN Access Rule
- Source: VPN Users
- Destination: Internal Servers
- Services: Required Application Ports
- Action: ALLOW

---

## 🛡 Security Features Enabled

- Intrusion Prevention System (IPS)
- Web Filtering
- Application Control
- Geo-IP Filtering
- NAT Policies

---

## 📊 Monitoring

- Real-time traffic monitoring enabled
- Log analysis through SIEM integration
- Alert generation for abnormal traffic patterns

---

## 🎯 Outcome

Improved network security posture by enforcing strict access control and monitoring traffic flow across enterprise infrastructure.
