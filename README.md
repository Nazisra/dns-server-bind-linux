# dns-server-bind-linux


# DNS Server Setup using BIND9

This project demonstrates how to configure a DNS server using **BIND9 on Ubuntu Linux**.  
The system supports both **Forward Lookup (Domain → IP)** and **Reverse Lookup (IP → Domain)** within a local network environment.

---

## Project Features

- Forward DNS Lookup
- Reverse DNS Lookup
- DNS Zone File Configuration
- Local Domain Resolution
- Web Interface for DNS Lookup
- Admin Panel for DNS Management

---

## Technologies Used

- Ubuntu Linux
- BIND9 DNS Server
- Flask
- SQLite
- Bash
- Dig Command

---

## Project Structure

```

dns-server-bind-linux
│
├── bind-config
├── web-interface
├── docs
├── report
├── screenshots
└── README.md

```

---

## Example DNS Commands

Forward Lookup

```

dig example.local

```

Reverse Lookup

```

dig -x 192.168.1.10

```

---

## GitHub Repository

https://github.com/Nazisra/dns-server-bind-linux

---

## Author
Nazmul Rahad

Operating System Lab Project  
Department of Computer Science and Engineering  
Daffodil International University
```

---

