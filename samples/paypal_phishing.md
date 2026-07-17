# 🚨 Fake Account Suspension (PayPal-style)

## Scenario
This phishing email pretends to be from PayPal, using a typosquatted domain and urgency to trick users into revealing their login credentials.

## Sample Email
From: PayPal Security <support@paypai-secure.com>
Subject: URGENT: Your Account Has Been Suspended!

Dear Customer,

We detected unusual activity in your PayPal account. For your safety, we have temporarily suspended access.
To restore service, please verify your credentials immediately:

👉 Click here to verify: http://paypai-secure.com/login

Failure to act within 24 hours will result in permanent account closure.

Thank you,
PayPal Security Team

## 🔎 Annotations
- **Typosquatting domain:** `paypai-secure.com` looks like PayPal but is misspelled.  
- **Urgency tactic:** "Failure to act within 24 hours" pressures the victim.  
- **Credential harvesting:** Fake login page collects usernames and passwords.  
- **Generic greeting:** "Dear Customer" instead of personalized name.  

## ✅ Key Takeaway
Phishing emails often combine urgency with fake domains to trick users into revealing credentials.
