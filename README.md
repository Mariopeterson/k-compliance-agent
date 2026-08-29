# K-Compliance Agent

Catches U.S. FDA compliance risks in Korean beauty product labels before a brand ships. Works in Korean or English.

## Why this exists

The U.S. is now the largest market for Korean beauty, passing China for the first time. Korean cosmetics exports to the U.S. reached about $2.2B last year, up 15 percent, and much of that growth is small indie brands selling direct to consumers online. Those brands rarely have a regulatory team.

One label detail can stop a shipment:

- A claim that makes the FDA treat a cosmetic like a drug, such as "treats acne"
- A sunscreen ingredient that is routine in Korea and not approved in the U.S.
- Wording that is fine in Korean and becomes a drug claim in English

## What it does

Paste in a product label or ingredient list. About twelve seconds later you get back:

- The U.S. compliance risks in that label, flagged
- The actual FDA rule behind each finding, cited
- A specific fix for each one

It works in Korean or English, so the same report is usable by a U.S. regulatory reviewer and by a Korean product team.

## How it is built

| Layer | Stack |
| --- | --- |
| Orchestration | n8n |
| Models | Claude and OpenAI |
| Front end | Next.js on Vercel |

The models were the easy part. Getting the FDA rules right was the work.

## Status

Portfolio project. Validated against three real products. No users, not commercially launched.

## Repo contents

Being added. The n8n workflow export and the Next.js front end land here next.
