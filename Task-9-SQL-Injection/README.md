# 🛡️ Task 9: SQL Injection Exploit in Web Application

## 🎯 Objective
To identify and exploit an SQL Injection vulnerability in a vulnerable web application (DVWA) and understand how it can be mitigated.

---

## 🧰 Tools Used
- Damn Vulnerable Web Application (DVWA)
- Web Browser (Manual Testing)
- Kali Linux

---

## 🌐 Target
- DVWA Local Web Application  
- URL: http://127.0.0.1/dvwa

---

## 🔍 Steps Performed

1. Installed and configured DVWA on local system
2. Set security level to **Low**
3. Navigated to **SQL Injection Module**
4. Entered malicious SQL payloads in input fields
5. Observed database response manipulation and authentication bypass

---

## 💉 Example Payloads

- `' OR '1'='1`
- `' OR 1=1--`
- `admin' OR '1'='1`
- `' OR '1'='1' -- -`

---

## ⚠️ Impact of Vulnerability

SQL Injection can lead to:
- Authentication bypass
- Unauthorized database access
- Data leakage
- Full database compromise

---

## 🛡️ Mitigation / Fix

To prevent SQL Injection:
- Use Prepared Statements (Parameterized Queries)
- Validate and sanitize all user inputs
- Use ORM frameworks
- Apply least privilege to database users
- Use Web Application Firewall (WAF)

---

## 📌 Conclusion

This task demonstrates how SQL Injection works in vulnerable web applications like DVWA. It highlights the importance of secure coding practices to protect against database attacks.

---

## 📁 Repository Structure
