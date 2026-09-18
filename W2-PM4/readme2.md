# Footprinting & Reconnaissance with theHarvester

## Cybersecurity & Ethical Hacking – Project Task

This project focuses on **Footprinting and Reconnaissance using theHarvester** in Kali Linux.

The purpose of this project is to understand how publicly available information can be collected from different online sources during the reconnaissance phase of cybersecurity.

---

## 📌 About theHarvester

**theHarvester** is an open-source reconnaissance tool written in Python.

It is used to gather publicly available information related to a domain, such as:

* Email addresses
* Sub-domains
* Hostnames
* IP addresses
* Employee names
* Publicly available information from different sources

theHarvester can use multiple public data sources and search engines to collect information during the reconnaissance phase.

---

# 🎯 Project Objectives

The main objectives of this project are:

1. Understand the concept of passive reconnaissance.
2. Learn how theHarvester works.
3. Learn how to use theHarvester in Kali Linux.
4. Understand different data sources supported by the tool.
5. Gather publicly available domain information.
6. Understand how emails and sub-domains can increase an organization's attack surface.
7. Learn how defenders can use reconnaissance techniques to identify their own publicly exposed information.

---

# 📝 Task 1 – Reconnaissance Using Baidu

## Objective

Use theHarvester with the **Baidu** data source to gather publicly available email IDs and sub-domains related to a target domain.

## Command Used

```bash
theHarvester -d microsoft.com -l 1000 -b baidu
```

## Command Explanation

| Option | Meaning                            |
| ------ | ---------------------------------- |
| `-d`   | Specifies the target domain        |
| `-l`   | Sets the maximum number of results |
| `-b`   | Specifies the data source          |

In this task:

* **Target domain:** `microsoft.com`
* **Result limit:** `1000`
* **Data source:** `baidu`

The output was reviewed to understand the type of information that can be discovered from a public source.

---

# 📝 Task 2 – Reconnaissance Using Multiple Sources

## Objective

Use theHarvester with multiple available sources and set the result limit to 50.

## Command Used

```bash
theHarvester -d microsoft.com -l 50 -b all
```

## Command Explanation

| Option | Meaning                      |
| ------ | ---------------------------- |
| `-d`   | Specifies the target domain  |
| `-l`   | Limits the number of results |
| `-b`   | Selects the data source      |

In this task:

* **Target domain:** `microsoft.com`
* **Result limit:** `50`
* **Data sources:** `all`

Different sources may produce different results because their databases and search methods change over time.

---

# 🔍 Data Sources

theHarvester supports multiple public information sources.

Examples include:

```text
baidu
brave
duckduckgo
github-code
crtsh
hunter
rapiddns
robtex
urlscan
virustotal
waybackarchive
yahoo
zoomeye
```

The available sources can change with different versions of theHarvester.

---

# 🛠️ Tools & Technologies

* **Kali Linux**
* **theHarvester**
* **Baidu**
* **Public Search Sources**
* **Command Line / Terminal**

---

# 📊 Information Collected

During the reconnaissance process, theHarvester can identify information such as:

### Email Addresses

Publicly indexed email addresses associated with a domain.

### Sub-domains

Additional domains or sub-domains that may belong to an organization.

### Hosts

Publicly identified hosts related to the target domain.

### Other Public Information

Depending on the selected source, additional publicly available information may be returned.

---

# 🧪 Methodology

The general workflow used in this project was:

1. Start Kali Linux.
2. Open the terminal.
3. Run theHarvester.
4. Specify the target domain.
5. Select a data source.
6. Set the result limit.
7. Review the output.
8. Record the results for the assignment.
9. Save screenshots and command output as evidence.

---

# 📸 Evidence

Screenshots and command outputs were captured during the practical exercise.

The evidence demonstrates:

* theHarvester command execution
* Selected data source
* Result limit
* Generated reconnaissance output

Sensitive or unnecessary information is not included in this public repository.

---

# 🛡️ Security Importance

Reconnaissance is an important phase of cybersecurity.

Information such as publicly available email addresses and sub-domains can provide useful information about an organization's external presence.

From a defensive perspective, organizations can use tools such as theHarvester to understand what information is publicly discoverable about their own domains.

This can help security teams:

* Identify unnecessary public information
* Review exposed sub-domains
* Reduce information leakage
* Improve security awareness
* Monitor their external attack surface

---

# 💡 Key Learning Outcomes

Through this project, I learned:

* What footprinting and reconnaissance mean.
* The difference between active and passive reconnaissance.
* How theHarvester is used for information gathering.
* How data sources can affect reconnaissance results.
* How to use command-line options with theHarvester.
* Why publicly available information is important in cybersecurity.
* How defenders can perform reconnaissance on their own organization.

---

# ⚠️ Ethical & Legal Disclaimer

This project was completed for **educational and cybersecurity learning purposes**.

The techniques demonstrated should only be used on:

* Systems and domains that you own
* Authorized security-testing environments
* Cybersecurity labs
* Targets where written permission has been provided

Do not use reconnaissance information for unauthorized access, phishing, credential attacks, or other malicious activities.

The purpose of this project is to understand how publicly available information can be discovered and how organizations can reduce unnecessary information exposure.

---

# 📚 References

* theHarvester
* Kali Linux
* Google Hacking / Reconnaissance concepts
* Publicly available OSINT resources

---

## 👩‍💻 Author

**Fatima Tariq**

Cybersecurity Student

**Project:** Footprinting & Reconnaissance with theHarvester

---

## 🔐 Project Focus

**Reconnaissance → Information Gathering → Attack Surface Awareness → Defensive Security**
