# 💰 Fake Invoice/Billing Scam (Microsoft-style)

## Scenario
This phishing email pretends to be a billing notice from Microsoft, claiming a large unauthorized charge to scare the victim into clicking a malicious link.

## Sample Email
From: Microsoft Billing <billing@microsoft-support.com>
Subject: Invoice #MS-2026-4471 — Payment Required

Dear User,

Your account has been charged R499.99 for Microsoft Office 365 Enterprise.
If you did not authorize this payment, please cancel immediately:

👉 Cancel & Refund: https://microsoft.com.billing.verify-payment.info

Invoice details:

Product: Office 365 Enterprise

Amount: $499.99

Date: July 17, 2026

Thank you for your prompt attention.
Microsoft Billing Department

## 🔎 Annotations
- **Fake charge:** Claims a large unauthorized payment to trigger panic.  
- **Link mismatch:** Text shows "microsoft.com" but actual link is `billing.verify-payment.info`.  
- **Spoofed sender:** `billing@microsoft-support.com` looks official but is not a real Microsoft domain.  
- **Emotional manipulation:** Fear of losing money pushes the victim to click.  

## ✅ Key Takeaway
Always verify billing notices directly in your account portal — never trust links in suspicious emails.
