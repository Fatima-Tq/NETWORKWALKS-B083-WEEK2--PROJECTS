# Footprinting & Reconnaissance with GHDB

## Cybersecurity & Ethical Hacking – Project Task

This project is based on **Footprinting and Reconnaissance using the Google Hacking Database (GHDB)**.

The purpose of this project is to understand how publicly indexed information can be discovered using search-engine operators and GHDB dorks. The activity is performed for educational and cybersecurity awareness purposes.

---

## 📌 About GHDB

**Google Hacking Database (GHDB)** is a collection of search queries, commonly called **Google Dorks**, that can be used to identify information indexed by search engines.

Security researchers and penetration testers can use these queries to identify information that may have been unintentionally exposed online.

Examples of information that may be discovered include:

* Open directories
* Public documents
* Login pages
* Exposed services
* Camera interfaces
* Configuration files
* Publicly accessible PDF files

GHDB is maintained by **Exploit Database (Exploit-DB)**.

---

# 🎯 Project Objectives

The main objectives of this project are:

1. Understand the concept of footprinting and reconnaissance.
2. Learn how GHDB and Google Dorks work.
3. Practice identifying publicly indexed information.
4. Understand the risks of accidentally exposed resources.
5. Learn how security researchers can use search engines for reconnaissance.
6. Understand the importance of securing publicly accessible resources.

---

# 📝 Task 1 – Security Camera Reconnaissance

## Objective

Find publicly indexed security-camera/webcam resources using relevant GHDB/Google Dorks and document the findings.

## Methodology

The following general process was followed:

1. Open the Exploit Database GHDB section.
2. Search for camera/webcam-related GHDB entries.
3. Select relevant search queries.
4. Use the queries in a search engine for reconnaissance.
5. Review the search results without attempting unauthorized access.
6. Record the relevant finding and the dork used.
7. Document the results for educational analysis.

## Finding Table

For privacy and responsible disclosure, live third-party camera URLs are not reproduced in this public repository.

| No. | Finding Type                            | Relevant Dork            | Authentication       |
| --- | --------------------------------------- | ------------------------ | -------------------- |
| 1   | Publicly indexed webcam/camera resource | Camera-related GHDB dork | Not tested           |
| 2   | Publicly indexed camera resource        | Camera-related GHDB dork | Not tested           |
| 3   | Public directory related to webcam      | Directory-index dork     | Not tested           |
| 4   | Public webcam directory                 | Directory-index dork     | Not tested           |
| 5   | IP camera interface                     | IP-camera dork           | Credentials required |
| 6   | IP camera interface                     | IP-camera dork           | Credentials required |
| 7   | Public camera image directory           | DCIM/camera dork         | Not tested           |
| 8   | Webcam service                          | WebcamXP-related dork    | Not tested           |
| 9   | Public webcam directory                 | Webcam directory dork    | Not tested           |
| 10  | Webcam interface                        | Webcam-related dork      | Not tested           |

> **Note:** No attempt was made to bypass authentication, guess passwords, access private areas, or interact with third-party devices beyond publicly indexed information.

---

# 📚 Task 2 – Mathematics PDF Reconnaissance

## Objective

Identify publicly accessible directory listings containing mathematics-related PDF resources using search-engine operators.

## Methodology

The following process was used:

1. Search for relevant GHDB/Google Dorks.
2. Use search operators such as `intitle`, `filetype`, and `ext`.
3. Review publicly indexed results.
4. Identify listings containing mathematics-related PDF resources.
5. Record the source and relevant search query.
6. Do not bypass access controls or authentication.

## Finding Table

| No. | Resource Type             | Relevant Search Query                                      | Authentication |
| --- | ------------------------- | ---------------------------------------------------------- | -------------- |
| 1   | Mathematics PDF directory | `intitle:index.of "parent directory" mathematics pdf`      | None observed  |
| 2   | Mathematics PDF directory | `intitle:index.of "parent directory" mathematics pdf`      | None observed  |
| 3   | Mathematics PDF directory | `intitle:index.of "parent directory" mathematics pdf`      | None observed  |
| 4   | Mathematics PDF resources | `intitle:"index of" ext:pdf "advanced mathematics"`        | None observed  |
| 5   | Calculus PDF resources    | `intitle:"index of /" mathematics calculus pdf`            | None observed  |
| 6   | Mathematics PDF directory | `intitle:"index of /" mathematics calculus pdf`            | None observed  |
| 7   | Mathematics textbook PDFs | `filetype:pdf "mathematics textbook" intitle:"index of /"` | None observed  |
| 8   | Mathematics PDF resource  | `filetype:pdf "mathematics textbook" intitle:"index of /"` | None observed  |
| 9   | Mathematics PDF resources | `intitle:"index of" mathematics filetype:pdf`              | None observed  |
| 10  | Mathematics PDF resources | `intitle:"index of" mathematics filetype:pdf`              | None observed  |

---

# 🔎 Google Dork Examples

Some examples of search operators used during the exercise include:

```text
intitle:
inurl:
filetype:
ext:
intitle:"index of"
```

Examples:

```text
intitle:"Index of" mathematics filetype:pdf

intitle:"webcam"

intitle:"Device(IP CAMERA)"

filetype:pdf "mathematics textbook"
```

These operators help narrow search results to specific types of publicly indexed content.

---

# 🛡️ Security & Ethical Considerations

This project is strictly for **educational and authorized security research**.

The techniques demonstrated here should only be used:

* On systems owned by the researcher
* In an authorized laboratory environment
* With explicit written permission from the system owner
* As part of an approved penetration-testing or security assessment

Unauthorized access to cameras, networks, accounts, files, or other systems may violate laws and organizational policies.

## Important Rules

* Do not bypass authentication.
* Do not guess or brute-force passwords.
* Do not access private information.
* Do not download sensitive personal data.
* Do not modify or damage any system.
* Do not share sensitive live targets publicly.
* Use virtual labs or systems that you own for practical testing.

---

# 💡 Key Learning Outcomes

Through this project, I learned:

* The difference between footprinting and reconnaissance.
* What GHDB is and how it is used.
* How Google Dorks use search operators.
* How accidentally exposed resources can become searchable.
* How open directories can expose files.
* Why publicly accessible services should be properly secured.
* How the same reconnaissance techniques can be used defensively to identify an organization's own exposure.

---

# 🔐 Defensive Recommendations

Organizations can reduce exposure by:

1. Protecting cameras with strong authentication.
2. Changing default usernames and passwords.
3. Avoiding direct Internet exposure of IP cameras.
4. Using firewalls and VPNs for administrative interfaces.
5. Disabling unnecessary directory listing.
6. Removing sensitive files from publicly accessible directories.
7. Reviewing search-engine indexing regularly.
8. Monitoring publicly exposed services.
9. Applying security updates to network devices.
10. Performing authorized security assessments regularly.

---

# ⚠️ Disclaimer

This repository is created for **educational and cybersecurity learning purposes only**.

The techniques discussed in this project are intended to help students understand how information can become publicly exposed and how defenders can identify and secure such exposure.

No unauthorized access, authentication bypass, password cracking, exploitation, or modification of third-party systems is intended.

The author is not responsible for misuse of the information contained in this repository.

---

## 👩‍💻 Author

**Fatima Tariq**

Cybersecurity Student

**Project:** Footprinting & Reconnaissance with GHDB

---

## 📖 Reference

* Google Hacking Database (GHDB)
* Exploit Database
* Networkwalks – Cybersecurity & Ethical Hacking Training Material
