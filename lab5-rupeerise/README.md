# RupeeRise: Fact-Checking an AI-Written Investor Brief

**A FinTech case study on catching AI hallucinations before they reach investors.**

Author: Arwin Kalra · BBA (FinTech & AI), Chitkara University · Tools: ChatGPT; Claude and Perplexity runs pending · November 2026

## The case

**RupeeRise** (fictional) is a digital lending app in Bengaluru. Its founder asked AI to write an investor brief on India's digital lending and UPI market and wanted to send it as it was. As a Business Analyst, I checked the claims against official sources before they could reach investors.

## What I did

| Step | Task | Tool |
|---|---|---|
| 1 | Read the case | Manual |
| 2 | Draft investor brief and record second-tool requirement | ChatGPT; Claude run pending |
| 3 | Score both tools fairly | Manual; Claude comparison pending |
| 4 | List 10 claims and assess confidence | Manual + ChatGPT-based working self-check |
| 5 | Verify claims against RBI and NPCI | Official websites |
| 6 | Open every Perplexity citation | Perplexity run pending |
| 7 | Write corrected brief and safety guide | Manual + official sources |

## Results — current working log

| Metric | Result |
|---|---:|
| Claims checked | 10 |
| Correct | 0 |
| Outdated / Distorted / Fabricated / Unsupported | 0 / 2 / 4 / 4 |
| Rated "High confidence" by AI but wrong | 0 in the working self-check; replace after actual same-chat run |
| Perplexity citations that fully supported the claim | Pending real Perplexity run |
| Tool comparison score (Claude vs ChatGPT, /10) | Pending vs 6 |

## Worst error I found

The draft claimed an October 2026 UPI volume of 31.8 billion transactions and value of ₹42.6 lakh crore. NPCI's monthly statistics instead show 25,466.70 million transactions and ₹31,52,929.46 crore for that month. This is a material numerical distortion that could mislead an investor about payment-system scale.

## My top 3 "What not to do" rules

1. Never forward AI-generated market numbers without checking the official table (evidence: C01).
2. Verify the exact circular number, date and title on the regulator's website (evidence: C06).
3. Never publish an attributed quotation without opening the original speech (evidence: C10).

## My answer to the founder

The original brief should not go to investors. Several claims are wrong, unsupported or fabricated. Replace them with verified RBI/NPCI facts, add RupeeRise's own substantiated metrics, and obtain compliance review first.

## Skills shown

AI output evaluation · Fact-checking with official sources · Hallucination detection · Citation analysis · Responsible AI in finance · FinTech domain knowledge

## What I learned

- AI writes confident, fluent text even when facts are wrong, outdated or made up.
- Exact numbers, circular numbers, quotes and sources need direct verification.
- AI's confidence rating is not proof; only an official source is.
- A cited link is not proof either: it must be opened and must actually support the claim.
- Different AI tools may give different answers; fair comparison requires the same prompt.
- For Indian finance, official sources include RBI, NPCI, PIB and company reports.
- Nothing AI-written should reach investors or customers without a human check.

## Repository contents

- `01_case_study.md` — case and acceptable sources
- `02_two_drafts.md` — prompt and ChatGPT draft; Claude output field pending
- `03_tool_comparison.md` — scorecard and Claude run placeholder
- `04_claims.md` — 10 claims and working self-check
- `05_hallucination_log.md` — official-source verification
- `06_citation_check.md` — Perplexity citation-audit template and NPCI cross-check
- `07_what_not_to_do.md` — corrected brief and 10-rule guide

## Before final academic submission

Run the exact prompt in Claude and paste its complete, unedited answer into `02_two_drafts.md`; update `03_tool_comparison.md` with a fair score. Run the self-check prompt in the same ChatGPT chat and replace the working confidence table with the actual answer. Run the Perplexity prompt, open every citation and complete `06_citation_check.md`. Recalculate README metrics after those real runs. These outputs are deliberately marked pending rather than fabricated.

*RupeeRise and the test case are fictional. The ChatGPT draft is a classroom test artifact, not financial advice. Official facts are dated 27 November 2026.*
