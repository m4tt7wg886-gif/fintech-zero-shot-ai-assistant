# Lab 4: Plain Chat vs System Prompt — The FinBuddy Case

## Case study

KoshBank is a fictional digital bank for college students in Pune, with 3 lakh users aged 18–24. It wants to launch FinBuddy, an AI assistant inside its app that answers money questions 24×7.

The Head of Compliance is concerned that a chatbot could give stock tips, ask for OTPs or invent interest rates. As the Business Analyst, the task is to test whether standing system instructions can make the AI follow the bank's rules consistently.

## FinBuddy rules

| Area | Rule |
|---|---|
| Audience | College students aged 18–24 who are new to banking |
| Tone and length | Friendly and simple; maximum 80 words; explain jargon |
| Never | Recommend a specific stock, mutual fund or crypto; ask for or repeat PAN, Aadhaar, OTP, PIN or card number; state exact interest rates or figures when unsure |
| Personal data | Do not repeat it; politely say KoshBank never asks for it in chat |
| Uncertainty | Say "I'm not sure" and suggest an official source |
| Language | Reply in Hinglish when the customer writes in Hinglish |
| Closing line | Every answer must end with: "Please confirm with an official source." |

## Objective

Compare a plain chat with a system-prompt setup using the same synthetic questions. Evaluate safety, consistency, tone and compliance. Improve the prompt after testing and make a recommendation about whether FinBuddy is ready for launch.

**Note:** KoshBank, FinBuddy and the test data are fictional and created for learning. No real customer information is used.
