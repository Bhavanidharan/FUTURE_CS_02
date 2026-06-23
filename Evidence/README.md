# Evidence — Phishing Email Analysis

This folder contains supporting evidence collected during phishing email analysis.

---

## 📂 Files

### `Email_sample.jpeg`
Screenshot of the phishing email sample analyzed in Task 02.
- **Subject:** ⚠️ Urgent: Your Account Will Be Locked
- **Sender:** security-team@secure-account-verify[.]com (spoofed domain)
- **Red Flags Visible:**
  - Fear-based urgency language
  - Suspicious link embedded in body
  - Generic "Dear User" greeting
  - Sender domain unrelated to the claimed organization

### `Toolbox.jpeg`
Screenshot from **Google Admin Toolbox > Messageheader** showing full email header analysis.
- SPF: **FAIL** — sender IP not authorized by domain
- DKIM: **NONE** — no digital signature present
- DMARC: **FAIL** — policy not aligned
- Originating IP traced to unrelated geographic region

---

## 🔎 Analysis Notes

| Indicator | Status |
|-----------|--------|
| Spoofed sender domain | ✅ Detected |
| Missing SPF/DKIM/DMARC | ✅ Confirmed |
| Malicious URL in body | ✅ Identified |
| Urgency / fear tactics | ✅ Present |
| Generic greeting | ✅ No personalization |

---

> **Note:** All samples used are from public phishing repositories for educational purposes only.
> Sources: [phishing_pot](https://github.com/rf-peixoto/phishing_pot), [phishing-mail-examples](https://github.com/autinerd/phishing-mail-examples)
