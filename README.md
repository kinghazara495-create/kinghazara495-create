# Abdulsamad

**Cyber security student | Self-taught pentesting | Building OSINT and security tools in Python**

Karachi, Pakistan · HUmdard University · First semester, CGPA 3.25

Self-taught through free YouTube and practice rather than paid courses. Currently
working on Kali Linux, Burp Suite, Hydra and penetration testing fundamentals,
with HackTheBox as the practice ground.

---

## Projects

### [osint-tool](https://github.com/kinghazara495-create/osint-tool)
Public-data OSINT toolkit in Python. No API keys required.

- Email assessment: MX records including Null MX (RFC 7505), SPF and DMARC analysis, breach exposure via HIBP k-anonymity so the full email hash never leaves the machine
- Domain assessment: WHOIS over raw port 43 with IANA TLD referral, full DNS dump, subdomain dictionary enumeration, PTR reverse lookup, scored posture summary

Every lookup returns why it failed, so a DNS timeout can never be reported as
"no record exists". That distinction matters more than the lookups themselves: a
tool that reports GitHub as spoofable when it is not is worse than no tool.

### [tcp-port-scanner](https://github.com/kinghazara495-create/tcp-port-scanner)
TCP port scanner in pure standard library. Published as written, with the
limitations documented rather than hidden — including that `connect_ex()` errno
values for closed, filtered and unreachable all collapse into one message.

### [password-strength](https://github.com/kinghazara495-create/password-strength)
Password strength estimator reporting time-to-crack under four attacker models
instead of invented tiers. 33 unit tests, CI matrix on Python 3.9 to 3.12.

A rewrite of a character-class scorer that rated `P@ssw0rd!` as "Very
Excellent". Reports effective entropy in bits, reads input with `getpass`, and
never logs or prints the password.

### [Quiz-Game-Project-For-C-Programer](https://github.com/kinghazara495-create/Quiz-Game-Project-For-C-Programer)
Console quiz game in C++, written while learning the language.

---

## Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Kali](https://img.shields.io/badge/Kali_Linux-367BF2?style=flat-square&logo=kali-linux&logoColor=white)
![Burp](https://img.shields.io/badge/Burp_Suite-FC5A2A?style=flat-square)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Practising:** Kali Linux, Burp Suite, Hydra, Nmap, HackTheBox
**Languages:** Python, C++, Bash
**Infrastructure:** Docker, Linux, PostgreSQL, Redis, Nginx, self-hosting

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdulsamad)
[![Gmail](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sammadkhan2356789@gmail.com)

Open to junior security roles, SOC positions, and security internships.
