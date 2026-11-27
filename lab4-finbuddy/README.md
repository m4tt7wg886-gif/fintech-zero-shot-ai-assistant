# FinBuddy: Making a Bank's AI Assistant Follow the Rules with a System Prompt

**A FinTech case study on when a plain chat is enough and when a business needs a system prompt.**

Author: Arwin Kalra · BBA (FinTech & AI), Chitkara University · Tool: ChatGPT · November 2026

## The case

**KoshBank** (fictional) is a digital bank for college students in Pune with 3 lakh users. It wants to launch **FinBuddy**, an in-app AI assistant. Its compliance team worries that a chatbot could give stock tips, ask for OTPs or invent interest rates. As a Business Analyst, I tested whether a system prompt can make the AI follow the bank's rules consistently.

## The data

10 synthetic customer questions created for this case study (7 English, 3 Hinglish), including 6 trap questions designed to test investment restrictions, OTP privacy, uncertain rates, instruction overrides, confusing requests and angry customers. The correct behaviour was written before evaluating the answers.

## Approach

| Step | Set-up | Task |
|---|---|---|
| 1 | Case study | Define the fictional bank and its rules |
| 2–3 | Data prompt + independent answer key | Create questions and decide expected behaviour |
| 4 | Plain chat | Ask one simple general question |
| 5 | Plain chat | Test all 10 customer questions |
| 6 | System prompt (v1) | Test the same 10 questions |
| 7 | System prompt (v2) + roles | Improve one instruction and compare three role styles |

## Results

| Metric | Plain chat | System prompt v1 |
|---|---:|---:|
| Answers that followed every rule (/10) | 0 | 10 |
| Personal data handled safely | No | Yes |
| No investment tips | No | Yes |
| Closing line present (/10) | 0 | 10 |

The strict score counts an answer as compliant only when it follows the relevant behaviour rule and includes the exact required closing line. Some plain-chat answers were useful, but they did not meet the complete FinBuddy standard.

## Key learnings

1. **A plain chat is enough for general questions:** the savings-account explanation was clear without business-specific instructions.
2. **A system prompt enforces standing rules:** it improved handling of investment requests (Q05, Q08), OTP safety (Q06), Hinglish and customer handling (Q09, Q10), and the required closing line.
3. **Version 2:** I added a clearer instruction for confusing multi-part messages: do not guess, answer only what is safe and ask one clear follow-up question when needed. The Q09 retest followed it.
4. **Roles:** the role changed tone and emphasis more than core accuracy. The credit analyst answer was more formal; the college senior answer was more friendly.

## My recommendation to KoshBank

FinBuddy is promising in this small synthetic test, but it should not be launched solely on these results. KoshBank should run larger adversarial tests, complete compliance and security reviews, verify current product information through approved sources, and keep human support available.

## Skills shown

Prompt engineering · System prompt design · Role prompting · Chatbot stress-testing · Responsible AI in finance · Customer-experience design

## What I learned

- A plain chat is fine for one-off, general questions.
- A system prompt gives AI standing rules, so a business assistant behaves more consistently.
- A good system prompt states the audience, tone, limits, uncertainty handling and prohibited actions.
- Trap questions help reveal where an AI assistant may break rules.
- A system prompt improves through testing and revision.
- A role mostly changes tone; it does not by itself make an answer accurate or safe.
- AI assistants in finance must protect personal data and avoid unsuitable financial advice.

## Repository contents

- `01_case_study.md` — KoshBank case and FinBuddy rules
- `02_questions.md` — 10 synthetic questions and pre-written answer key
- `03_plain_simple.md` — simple plain-chat test
- `04_plain_test.md` — 10-question plain-chat test and marks
- `05_system_prompt_test.md` — Version 1 system prompt, responses and marks
- `06_scorecard.md` — Version 2, role comparison, scorecard and reflection

*KoshBank, FinBuddy and all data in this project are fictional and created for learning. The response transcripts are illustrative classroom test outputs, not production banking advice.*
