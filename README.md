# Task 2: Phishing Email Analysis

## Objective
To analyze a phishing email and identify common red flags like spoofing, social engineering, and email header inconsistencies.

---

## Tools Used
- Manual email inspection
- [MxToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)

---

## Files
- `phishing_sample.txt`: The suspicious phishing email content.
- `email_header.txt`: Simulated raw email header of the phishing email.
- `phishing_analysis.txt`: Detailed report of observations and security indicators.
- `screenshots/`: Visual proof of SPF, DKIM, and DMARC failures.

---

## Header Analysis Highlights
- **SPF: FAIL** → The domain does not allow the sending IP.
- **DKIM: FAIL** → The signature does not match.
- **DMARC: FAIL** → Spoofed message violates domain policy.

All three mechanisms confirm the email was likely spoofed.

---

## Screenshots
- `header-analysis.png`: Screenshot of MxToolbox analysis showing failed authentication checks.
- `dangerous-site-warning.png`: Chrome warning about phishing page
- `virustotal-check.png`: VirusTotal showing suspicious rating from Trustwave

---

## Learnings
- Learned how phishing emails attempt to trick users using urgency and fear.
- Understood how email header fields can be used to detect spoofed messages.
- Practiced analyzing headers using real tools to assess legitimacy.

---

## Conclusion
This task helped solidify practical phishing detection skills using both content analysis and header-level investigation.
