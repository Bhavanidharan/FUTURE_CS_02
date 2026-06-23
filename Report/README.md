# Task 2 — Phishing Email Detection & Awareness System

**Internship:** Future Interns — Cyber Security Track (2026)
**Task:** Phishing Email Detection & Awareness System

---

## 📁 Project Structure

```
Task_2_Phishing_Detection/
├── Evidence/
│   ├── Email_sample.jpeg        # Screenshot of analyzed phishing email
│   ├── Toolbox.jpeg             # Google Toolbox / MX Toolbox header analysis screenshot
│   └── README.md                # Evidence documentation
├── Report/
│   ├── Task 02.pdf              # Full Phishing Detection & Awareness Report
│   └── README.md                # Report summary
└── README.md                    # This file
```

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Google Admin Toolbox | Email header analysis |
| MXToolbox | Sender domain & SPF/DKIM verification |
| Browser DevTools | Safe URL inspection |
| Python (ReportLab) | PDF report generation |
| GitHub | Version control & submission |

---

## 🔍 Analysis Approach

1. **Collected** phishing email samples from public datasets (phishing_pot, autinerd/phishing-mail-examples)
2. **Analyzed** email headers using Google Toolbox to inspect sender IP, SPF, DKIM, DMARC
3. **Inspected** sender domains and embedded links for spoofing indicators
4. **Identified** phishing indicators: urgency language, mismatched domains, generic greetings
5. **Classified** risk level for each sample (Safe / Suspicious / Phishing)
6. **Documented** findings and produced a professional awareness report

---

## 📄 Deliverables

- ✅ Phishing Detection & Awareness Report (PDF)
- ✅ Analyzed email samples with evidence screenshots
- ✅ Prevention guidelines for employees

---

## 👤 Author

**Future Interns Cyber Security Intern — 2026**
