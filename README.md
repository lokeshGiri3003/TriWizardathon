
**TriWizardathon**

**Overview**

Phishing is one of the most common cyber threats, tricking users into revealing sensitive information through fake websites and malicious links. With 1.2+ billion phishing emails sent daily (Forbes, 2024) and a 175% rise in India (H1 2024), there’s an urgent need for smarter detection systems.

**Our solution?**

A multi-layered phishing detection system that goes beyond traditional blacklist checks. It integrates whitelisting, blacklisting, threat intelligence APIs (VirusTotal), and an ML model (Random Forest) to accurately detect phishing URLs in real-time.

Unlike static tools like Google Safe Browsing or antivirus software, our approach adapts to zero-day phishing URLs and provides real-time protection with minimal resources—perfect for mobile and rural users.

**Problem Statement**

Phishing affects individuals, organizations, and governments, leading to financial loss, data breaches, and cyber espionage.
Existing tools fail against new/zero-day phishing attacks since they rely only on static blacklists.
Non-technical users need an easy-to-use, lightweight solution that works on the web and mobile.

**Why Our Solution is Unique**

✔ Multi-layer Detection: Combines whitelist, blacklist, VirusTotal API, and ML-based verification
✔ Real-time Protection: Works instantly when a suspicious link is clicked
✔ User-Friendly: Minimal UI for non-technical users
✔ Lightweight: Designed for low-resource environments

**How It Works**

1️⃣ Layer 1: Whitelist & Blacklist Check

If in whitelist → Allowed

If in blacklist → Blocked

Otherwise → Forwarded to next layer

2️⃣ Layer 2: Threat Intelligence API (VirusTotal)

Checks URL against global threat intelligence

If phishing → Block & update blacklist

If safe → Forward to ML layer

**3️⃣ Layer 3: ML-Based Detection (Random Forest)**

Extracts features like domain length, HTTPS usage, symbol count, etc.

ML model predicts phishing vs legitimate

Updates whitelist/blacklist dynamically

**Future Scope**

Convert into a Web & Android App for real-time scanning

Integrate more APIs like Google Safe Browsing, AbuseIPDB, WHOIS

Online learning & retraining to adapt to evolving phishing techniques

