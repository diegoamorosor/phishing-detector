
<p align="center">
  <img src="https://i.imgur.com/iqRChM1.png" alt="CyberGuard-Phishing-Detector" />
</p>

<h1 align="center"> Phishing URL Detector</h1>

<p align="center">
  <a href="www.phishingdetector.diegoamoroso.com">🔗 Try  Phishing Detector Now</a>
</p>

Phishing Detector is a web tool that analyzes the **risk level of any URL** in real time. Paste a link and instantly receive a full evaluation: security score, detected suspicious patterns, structural metrics, and a detailed explanation of potential phishing indicators.

> 🛡️ **Privacy First** — The URL analysis runs securely and does not store personal browsing data.

---

## 📖 What is Phishing Detection?

Phishing detection is a cybersecurity technique used to identify malicious websites designed to impersonate legitimate services in order to steal credentials, financial information, or personal data.

Phishing Detector uses a multi-factor heuristic engine capable of:

- **Classifying URL risk** on a 0–100 scale.
- **Analyzing domain structure** and suspicious subdomain usage.
- **Detecting obfuscation techniques** used in phishing attacks.
- **Identifying known malicious domains** from curated databases.
- **Evaluating entropy and structural anomalies** in URLs.

---

## 🚀 Features

- Cyberpunk-style interface with animated UI.
- Risk score from 0 to 100 with visual indicator.
- Real-time structural URL analysis.
- Detection of suspicious subdomains and deceptive formatting.
- Domain length and entropy evaluation.
- Identification of special-character obfuscation.
- Database cross-check of known phishing domains.
- Detailed breakdown of risk factors.
- Instant analysis when pressing Enter or clicking analyze.

---

## 📝 How to Use Phishing Detector?

### Step 1 — Paste the URL

Copy any website link and paste it into the input field.

Example:
```

[https://secure-paypal-login.verify-account.com](https://secure-paypal-login.verify-account.com/)

```

### Step 2 — Analyze

Click the **"Analyze URL"** button or press **Enter**.

### Step 3 — Review the Results

Phishing Detector will display structured analysis panels:

```

┌──────────────────────────┬──────────────────────────┐  
│ 🛡️ Risk Score │ 📊 Structural Metrics │  
│ 0–100 Indicator │ Domain · Length · SSL │  
├──────────────────────────┴──────────────────────────┤  
│ 🔍 Detected Threat Indicators │  
│ Suspicious Subdomains · Special Characters │  
│ Known Phishing Match · Entropy Level │  
├─────────────────────────────────────────────────────┤  
│ 🧠 Detailed Risk Explanation │  
│ Clear breakdown of why the score was assigned │  
└─────────────────────────────────────────────────────┘

```

### Step 4 — Take Action

If flagged as risky:
- Avoid entering credentials.
- Do not download files.
- Verify the domain manually.
- Report the link to your security team.

---

## 🖼 Analysis Example

For the URL:

```

[http://paypal.verify-login-account.ru/security-update](http://paypal.verify-login-account.ru/security-update)

````

```text
═══════════════════════════════════════════════════════════════
                       ANALYSIS RESULT
═══════════════════════════════════════════════════════════════

🛡️ Risk Score: 87/100 — HIGH RISK

📊 Structural Analysis:
  • Domain Length:              42 characters
  • Suspicious Subdomain:       YES
  • Known Brand Impersonation:  Detected ("paypal")
  • Special Characters:         Hyphenated deception
  • TLD Risk Level:             High (.ru)
  • Entropy:                    Elevated

⚠️ WARNING:
This URL likely attempts to impersonate a legitimate PayPal domain.
The real PayPal domain is:
   https://paypal.com

🔍 Detected Indicators:
  • Brand name embedded in subdomain
  • Suspicious TLD (.ru)
  • Multi-layer subdomain masking
  • No verified trusted domain match

Recommendation:
Do NOT enter credentials on this site.
````

---

## 🔍 What Phishing Techniques Does It Detect?

|Technique|Example|Why It's Dangerous|
|---|---|---|
|**Subdomain impersonation**|`paypal.verify-account.com`|The real domain is verify-account.com, not PayPal.|
|**Brand embedding**|`secure-amazon-login.net`|Attackers embed trusted names to trick users.|
|**Suspicious TLDs**|`.ru`, `.xyz`, `.top`|Frequently used in short-lived phishing campaigns.|
|**Hyphen deception**|`bank-security-update.com`|Mimics official naming patterns.|
|**Excessive length**|Very long URLs|Often hide malicious intent deep in structure.|
|**High entropy strings**|`login-8fj3k2j-secure.com`|Randomized segments used to evade filters.|
|**Known malicious domains**|Listed phishing URLs|Confirmed in threat databases.|

---

## 📊 Risk Classification Scale

|Score|Risk Level|Color|Meaning|
|---|---|---|---|
|0 – 20|**Safe**|🟢 Green|No suspicious indicators detected|
|21 – 40|**Low Risk**|🟡 Yellow|Minor anomalies present|
|41 – 70|**Moderate Risk**|🟠 Orange|Multiple suspicious indicators|
|71 – 85|**High Risk**|🔴 Red|Likely phishing attempt|
|86 – 100|**Critical**|💀 Dark Red|Confirmed or extremely suspicious|

---

## 📐 Detection Dimensions

Phishing Detector evaluates each URL across multiple dimensions:

|Dimension|What It Measures|Why It Matters|
|---|---|---|
|**Domain Authenticity**|Exact match vs impersonation|Prevents brand spoofing|
|**Subdomain Structure**|Nested misleading prefixes|Detects masking techniques|
|**Length & Complexity**|Total URL length|Long URLs hide malicious paths|
|**Entropy**|Randomness of segments|Detects obfuscation attempts|
|**TLD Risk**|Top-level domain analysis|Some TLDs are higher risk|
|**Database Match**|Known phishing entries|Immediate confirmation of threat|

---

## ⚙️ Scoring Model

The risk score is calculated based on weighted heuristics:

- +30 points → Known malicious domain match
    
- +20 points → Brand impersonation detected
    
- +15 points → Suspicious TLD
    
- +10 points → Abnormal URL length
    
- +10 points → High entropy segment
    
- +5–15 points → Structural anomalies
    

Maximum score: 100

---

## 🛡️ Why Phishing Detection Matters

Phishing remains one of the most common cyberattack vectors:

- 90%+ of data breaches begin with phishing emails.
    
- Attackers increasingly use AI-generated phishing pages.
    
- Fake login portals are visually indistinguishable from real ones.
    

Real-time URL inspection adds a preventive security layer before credentials are compromised.

---

## 💡 Tips to Avoid Phishing

- Always verify the root domain (e.g., `paypal.com`).
    
- Avoid clicking login links from emails.
    
- Check for HTTPS — but remember HTTPS alone does not guarantee legitimacy.
    
- Use a password manager (it won't autofill on fake domains).
    
- Enable multi-factor authentication (MFA).
    
- When in doubt, access websites manually via browser bookmarks.
    

---

## 🔒 Privacy & Security

Phishing Detector analyzes URLs without collecting personal browsing data.

- No credential collection.
    
- No tracking scripts.
    
- No storage of submitted URLs beyond analysis context.
    
- Secure processing architecture.
    

---

## 📚 Useful Resources

- [Google Safe Browsing Transparency Report](https://transparencyreport.google.com/safe-browsing)
    
- [PhishTank](https://www.phishtank.com/)
    
- [OWASP Phishing Prevention Guide](https://owasp.org/)
    
- [VirusTotal](https://www.virustotal.com/)
    
- [NIST Digital Identity Guidelines](https://pages.nist.gov/800-63-3/)
    
