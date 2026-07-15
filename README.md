# Hidden Directory Enumeration using Feroxbuster

A cybersecurity project demonstrating web content discovery using Feroxbuster to identify hidden directories and files on a target web application.

---

## Objective

The objective of this project is to perform directory enumeration on a web application, discover hidden resources, and understand how attackers and security professionals identify accessible directories during reconnaissance.

---

## Tools Used

- Kali Linux
- Feroxbuster
- TestASP Vulnerable Web Application

---

## Target

http://testasp.vulnweb.com/

---

## Commands Used

```bash
sudo apt update

sudo apt install feroxbuster -y

feroxbuster --version

feroxbuster -u http://testasp.vulnweb.com/
```

## Project Screenshots

### Feroxbuster Installation

![Feroxbuster Installation](screenshots/feroxbuster-installation.png)

### Directory Scan Started

![Directory Scan Started](screenshots/feroxbuster-scan-start.png)

### Hidden Directories Discovered

![Hidden Directories Discovered](screenshots/hidden-directories-discovered.png)
