Gavin 🏛️
> Plain-language small claims court guidance — not legal advice.
---
What This Skill Does
Gavin helps users navigate small-scale legal problems like contract disputes, property damage, and landlord-tenant issues. It covers filing claims, court procedures, pleading standards, and deadlines — all in plain English.
Gavin is not a lawyer and does not provide legal advice. It provides general legal information to help you understand your situation and your options. Always verify local rules and consult a licensed attorney for guidance specific to your case.
---
How to Use
Download the `SKILL.md` file from this repository
Go to claude.ai → Settings → Skills
Upload the `SKILL.md` file
Toggle the skill on
Start a new conversation and try one of the sample prompts below
---
Sample Prompts
```
"My landlord kept my security deposit but never gave me a reason. It's been 45 days. What can I do?"
```
```
"I paid a contractor $1,200 to fix my roof but the leaks are worse than before. Can I take them to small claims court?"
```
```
"I hired someone off Facebook Marketplace to paint my house for $800. He did a terrible job and left without finishing. That was about 14 months ago. Do I still have time to sue him?"
```
---
Design Notes
Property	Details
Scenario	Small Claims Court — Self-represented
Workflow steps	7
Reading level	8th grade
Jurisdiction-aware	Yes — location is gathered in Step 1
Key design choice: The most important decision was building in persistent, non-preachy disclaimers at every step. Rather than warning users once and moving on, the skill reminds them throughout that it is not a lawyer. This is paired with a tone instruction: be honest but not harsh — give people the truth, just not brutally.
---
Step-by-Step Workflow
Step 1 — Gather the Facts
The skill asks where the user is located, what problem they're having, and when it happened. Jurisdiction and timing are critical in small claims cases.
Step 2 — Review the Paper Trail
If documents are involved (a contract, lease, invoice, or eviction notice), the skill asks for the relevant language — especially breach clauses or deadlines. Users are reminded not to share sensitive personal data, and if something raises a legal red flag, they're told.
Step 3 — Categorize the Problem
The skill synthesizes what the user has shared: What type of legal issue is this? What state or parish are we in? Is there a risk the claim is time-barred (prescribed)?
Step 4 — Explain Potential Claims
Using plain language, the skill walks through what legal claims might apply and why — always with hedging language like "this could potentially be..." The most important legal issues get extra attention.
Step 5 — Identify Next Steps
The skill flags procedural landmines: Do you need to send a demand letter first? Are there notice requirements? Is the courthouse the right venue? Missteps here can sink a valid case.
Step 6 — Connect to Resources
The skill points users toward standardized court forms, self-help legal clinics, law school clinics, or legal aid organizations that may be able to assist.
Step 7 — Drafting Guidelines (if the user proceeds alone)
If the user clearly acknowledges they understand this is not legal advice and still wants to draft their own filing, the skill provides basic guidelines — how to organize facts, what to include, what to avoid. The skill never pretends this replaces an attorney.
---
Disclaimer
> This skill provides **general legal information only — not legal advice.** It was created as a class project for **LAW 5642: Legal Analytics and Generative AI** at LSU Paul M. Hebert Law Center. Users should consult a licensed attorney for guidance specific to their situation.
---
Author
Gavin LaBiche · LSU Law School · Spring 2026
---
License
MIT License — see LICENSE file for details.
