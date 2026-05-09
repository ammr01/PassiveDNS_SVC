# PassiveDNS_SVC

**Install and Deploy PassiveDNS with Best Practices**

> *“Logging DNS Become Easy on Linux.”*
> — Author: Amr Alasmer

---

## What is this?

`PassiveDNS_SVC` is a Bash script that installs PassiveDNS on the system, 
and create service user and service to run PassiveDNS in that service.
---




## Installation

To install and run PassiveDNS on your system use 
```bash
git clone https://github.com/ammr01/PassiveDNS_SVC.git
cd PassiveDNS_SVC
chmod +x ./pdns.sh
./pdns.sh 'eth0'
```
NOTE: replace eth0 in the command above ./pdns.sh 'eth0' with the network interface you want to monitor.

---

## Article

I wrote an article about PassiveDNS, and how to investigate PassiveDNS logs,
happy reading: https://medium.com/@amrasmer/linux-log-enhancement-part-3-4f793ca01fca
---

## Best Security Practices Series

This project is part of Best Security Practices.

Best Security Practices is a series I started to share my security knowledege with the community.
---


## License

This project is licensed under the **GNU General Public License v3 or later**.

---

## Author

**Amr Alasmer**
This tool was developed to solve a real-world problem I saw on reddit and is shared with the hope it will help others too.

