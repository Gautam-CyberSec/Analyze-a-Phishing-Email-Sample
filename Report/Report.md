# Analyze a Phishing Email Sample

## OBJECTIVE  
Identify phishing characteristics in a suspicious email and summarize the indicators found through analysis.

---

<img width="669" height="472" alt="Image" src="https://github.com/Gautam-CyberSec/Analyze-a-Phishing-Email-Sample/blob/main/Screenshots/Screenshot%202025-09-24%20163549.png" />

---

## EMAIL SAMPLE OVERVIEW  
- **Subject Line:** There's issue with your American Express account  
- **Sender:** administraciones@pentagon-seguridad.cl  
- **Date:** Fri, 11/8/2019  
- **Recipient:** hashedout@thesslstore.com  
- **Claim:** Account temporarily suspended due to suspicious activity  
- **Call-to-Action:** “Click here to review your account now”

## PHISHING INDICATORS IDENTIFIED

### 1. Suspicious Sender Address
- The sender uses the domain `pentagon-seguridad.cl`, which is **not affiliated** with American Express.
- This is a clear case of **email spoofing**.

### 2. Urgent Language & Threat
- The email warns of **temporary suspension** unless the user verifies the account immediately.
- Creating a sense of urgency is a common phishing tactic to pressure the recipient into clicking malicious links.

### 3. Suspicious Link/Button
- CTA Button: “Click here to review your account now”
- The actual URL behind this button (not visible in the screenshot) is likely a **phishing site** designed to steal credentials.

### 4. Spelling and Grammar Issues
- “...we placed a temporary suspension **untill** you verify your account.”
- Such errors are typical in phishing emails and lower the credibility of the sender.

### 5. Generic Salutation
- No name or personalized greeting is used.
- Legitimate services usually address the user by their name or username.

### 6. Inconsistent Branding
- The American Express logo appears distorted or improperly formatted.
- Could be hosted on an external or suspicious source.

### 7. Header Mismatch (Potential - To Be Verified)
- The “From” domain does not match the brand name.
- Full header analysis could confirm additional discrepancies like SPF/DKIM failures.

## CONCLUSION  
This email is a **clear example of a phishing attempt**, using social engineering tactics to trick the user into revealing sensitive information. It demonstrates several classic indicators including spoofed sender addresses, urgency, poor grammar, mismatched branding, and suspicious links. Users should be trained to spot such signs and avoid interacting with such messages.
