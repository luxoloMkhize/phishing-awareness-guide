Phishing & Social Engineering Awareness Guide

Overview

This project analyzes real phishing emails collected from my own spam/junk folder. Each sample is broken down and annotated to identify common social engineering tactics, technical red flags, and the appropriate response — building practical threat-recognition skills that go beyond textbook theory.

Why This Project

This project builds on my Cisco Introduction to Cybersecurity certification, which covers phishing and social engineering as core threat vectors. I wanted to apply that theory to real-world examples rather than just studying definitions, since phishing remains one of the most common initial attack vectors used against individuals and organizations.

Methodology


Collected 3–5 real phishing emails from my personal spam folder.
Redacted personal/sensitive information (my email address, account numbers, etc.) before publishing.
Annotated each email across five categories:

Sender analysis — spoofed, misspelled, or mismatched domains
Subject line tactics — urgency, fear, curiosity, reward-based hooks
Link inspection — comparing displayed text vs. actual destination URL
Content red flags — grammar/spelling errors, generic greetings, mismatched branding
Recommended response — report, delete, verify via a separate trusted channel





Sample Analysis Format

Each email in /samples includes:


A redacted screenshot or text copy of the original email
A red-flag breakdown table
A short verdict explaining why it's phishing and what a user should do


Example structure:

Red Flag CategoryObservationRisk LevelSender domainpaypa1-support.com (note the "1" instead of "l")HighUrgency tactic"Your account will be suspended in 24 hours"HighLink mismatchDisplayed text says paypal.com, actual link goes elsewhereCriticalGrammarInconsistent capitalization, awkward phrasingMedium

Repository Structure

phishing-awareness-guide/
├── README.md
├── samples/
│   ├── sample-1-analysis.md
│   ├── sample-2-analysis.md
│   └── ...
└── images/
    └── redacted screenshots

Key Takeaways


Most phishing emails rely on urgency and fear to bypass critical thinking.
Sender domain spoofing is often subtle (character substitution, extra subdomains) and easy to miss at a glance.
Hovering over links before clicking is one of the simplest and most effective defenses.
Legitimate organizations rarely request sensitive info or immediate action via email.


Skills Demonstrated


Threat identification and social engineering analysis
Email header / URL inspection
Security awareness documentation
Practical application of Cisco Introduction to Cybersecurity coursework


Author

Luxolo Nduduzo Mkhize
Final-year BSc Computer Science & Mathematics student, University of Zululand
Cisco Networking Academy certified — Junior Cybersecurity Analyst Career Path
LinkedIn(www.linkedin.com/in/luxolo-mkhize-008807370)
