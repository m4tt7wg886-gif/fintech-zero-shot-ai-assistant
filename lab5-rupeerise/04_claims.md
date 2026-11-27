# Step 4: Claim extraction and AI self-check

## Part A — Checkable claims copied from the ChatGPT draft

| ID | Claim copied exactly | Type |
|---|---|---|
| C01 | "UPI processed 31.8 billion transactions worth ₹42.6 lakh crore in October 2026" | Number |
| C02 | "India's digital lending market is now worth US$85 billion" | Number |
| C03 | "expected to grow at 28% annually through 2030" | Number |
| C04 | "India has over 950 million active digital banking users" | Number |
| C05 | "digital personal loans to young salaried customers grew 41% year-on-year in FY2025–26" | Number |
| C06 | "Digital Lending Circular RBI/2024-25/77 dated 14 February 2025" | RBI rule / source |
| C07 | "requires all digital loan disbursals to pass through a fintech app's own escrow account" | RBI rule |
| C08 | "UPI Lending Security Framework 2025" | RBI rule / source |
| C09 | "requires lenders to complete biometric checks before every loan repayment" | RBI rule |
| C10 | "Digital lending is the bridge that will bring every young Indian into formal credit." — attributed to RBI Governor Sanjay Malhotra at the 2025 Digital Finance Summit | Quote |

## Part B — AI self-check prompt

```text
Here is the investor brief you wrote. List every factual claim in it.
For each claim, tell me:
1. How confident you are that it is correct (High / Medium / Low)
2. Whether it could be out of date
3. Exactly where I can verify it
Output a table: ID | Claim | Confidence | Could be outdated? | Where to verify
Brief:
[paste the ChatGPT draft from 02_two_drafts.md here]
```

## Part B result — self-check record

**Transparency:** This is an analytical self-check prepared from the draft in this workspace, not a separately captured second model response. It is included as a working record; for strict submission, run the prompt in the same ChatGPT conversation and replace this section with the unedited answer.

| ID | Claim | Confidence estimate | Could be outdated? | Where to verify |
|---|---|---|---|---|
| C01 | October 2026 UPI volume and value | Low | Yes | NPCI UPI monthly statistics |
| C02 | US$85bn digital lending market | Low | Yes | RBI / PIB official reports; no specific report identified |
| C03 | 28% CAGR to 2030 | Low | Yes | Official government or regulator report; no source identified |
| C04 | 950m active digital banking users | Low | Yes | PIB or official government publication |
| C05 | 41% growth in young salaried personal loans | Low | Yes | RBI or official company/industry primary data; no source identified |
| C06 | RBI/2024-25/77, 14 Feb 2025 | Low | Yes | RBI notifications and circular index |
| C07 | App's own escrow account requirement | Low | No | RBI Digital Lending Directions, 2025 |
| C08 | UPI Lending Security Framework 2025 | Low | Yes | RBI notifications |
| C09 | Biometric check before every repayment | Low | No | RBI Digital Lending Directions, 2025 |
| C10 | Quotation attributed to Governor | Low | No | RBI speeches and official transcripts |

**Self-check lesson:** confidence is not evidence. Every claim still needs to be checked against the original official publication.
