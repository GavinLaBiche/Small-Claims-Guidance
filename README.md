Gavin
What This Skill Does
Helps users navigate small-scale legal problems like contract disputes, property damage, and landlord-tenant issues. Covers filing claims, court procedures, pleading standards, and deadlines. Offers plain-language guidance on gathering evidence and preparing for hearings. Not legal advice — always verify local rules.
How to Use

Download the SKILL.md file from this repository
Go to claude.ai → Settings → Skills
Upload the SKILL.md file
Toggle the skill on
Start a new conversation and try one of the sample prompts below

Sample Prompts
Try these prompts to test the skill:

"My landlord kept my security deposit but never gave me a reason. It's been 45 days. What can I do?"
"I paid a contractor $1,200 to fix my roof but the leaks are worse than before. Can I take them to small claims court?"

Design Notes

Scenario: Small Claims Court Self-represented
Workflow steps: 7 steps — from gathering facts, reviewing documents, and categorizing the legal issue, to explaining potential claims, identifying next steps, connecting users with resources, and (if they proceed on their own) providing basic drafting guidelines.
Key design choice: The most important design decision was building in persistent, non-preachy disclaimers at every step. Rather than warning users once and moving on, the skill reminds them throughout that it is not a lawyer and that its guidance is general information — not legal advice. This is paired with an instruction to be honest but not harsh, keeping guidance grounded rather than validating every user assumption.

Step-by-Step Workflow
Step 1 — Gather the Facts
The skill asks where the user is located, what problem they're having, and when it happened. Jurisdiction and timing matter a lot in small claims cases.
Step 2 — Review the Paper Trail
If documents are involved (a contract, lease, invoice, eviction notice), the skill asks for the relevant language — especially things like breach clauses or deadlines. Users are reminded not to share sensitive personal data, and if they share anything that raises a legal red flag, they're told.
Step 3 — Categorize the Problem
The skill synthesizes what the user has shared: What type of legal issue is this? What state or parish are we in? Is there a risk the claim is time-barred (prescribed)?
Step 4 — Explain Potential Claims
Using plain, 8th-grade-level language, the skill walks through what legal claims might apply and why — always with hedging language like "this could potentially be..." The most important legal issues get extra attention.
Step 5 — Identify Next Steps
The skill flags any procedural landmines: Do you need to send a demand letter first? Are there notice requirements? Is the courthouse the right venue? Missteps here can sink a valid case.
Step 6 — Connect to Resources
The skill points users toward standardized court forms, self-help legal clinics, law school clinics, or legal aid organizations that may be able to assist.
Step 7 — Drafting Guidelines (If User Proceeds Alone)
If the user clearly acknowledges they understand this is not legal advice and still wants to draft their own filing, the skill provides basic drafting guidelines — how to organize facts, what to include, what to avoid. The skill never pretends this replaces an attorney.
Disclaimer
This skill provides general legal information only — not legal advice. It was created as a class project for LAW 5642: Legal Analytics and Generative AI at LSU Law School. Users should consult a licensed attorney for guidance specific to their situation.
Author
Gavin LaBiche · LSU Law School · Spring 2026
License
MIT License — see LICENSE file for details. 
Extra: Be emphatic but not sycophantic. These are people having legal troubles, but their every whim should not be validated. Give them the truth, just not brutally. 
