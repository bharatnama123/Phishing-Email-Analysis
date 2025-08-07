# Phishing-Email-Analysis
# Task 2 - Email Header Analysis & IP Investigation

This repository contains the analysis of a spoofed phishing email for my cybersecurity internship at **Elevate Labs**.

## 🔍 Objective

To identify signs of email spoofing and analyze the originating IP address using various tools.

## 🛠️ Tools Used

- [MXToolbox - Analyze Headers](https://mxtoolbox.com/EmailHeaders.aspx)
- [VirusTotal](https://www.virustotal.com/)
- WHOIS Lookup
- Online Blacklist Checkers

## 📊 Observations

- **DMARC**: ❌ No DMARC Record Found  
- **SPF Alignment**: ❌ Failed  
- **IP Address**: `137.184.34.0` flagged as malicious by VirusTotal  
- **Relay Delays**: Unusual delays and unknown server used  
- **Originating Server**: DigitalOcean VPS

## 📸 Screenshots

- Email Header Analysis (MXToolbox)
- IP Reputation Check (VirusTotal)
- Relay Path & Delay Chart

## ✅ Conclusion

The analyzed email was **spoofed** and originated from an unverified mail server. The IP address used is listed as **malicious**, confirming phishing activity.

---

🔐 This task helped me understand how to:
- Spot spoofed emails  
- Use header analysis tools  
- Verify IP reputation  
- Track email relay paths

