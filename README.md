# FollowUp SaaS

FollowUp is not a CRM. It's the missing last step — the follow-up that never happens.

Built for and validated with a real salon client in Noida (Hair Court Salon). The goal was one outcome: get lost customers to come back. Everything else was cut.

Simplicity was a deliberate choice. The owner needed zero training. If it required explanation, it was too complex.

## How it works

1. **Customer scans QR** on salon counter → fills name + WhatsApp number
2. **Data auto-saves** to Google Sheets — owner touches nothing
3. **Owner dashboard** flags customers who haven't returned in 30+ days
4. **One-click WhatsApp** opens with pre-written message — owner just hits Send

## Live URLs

- Customer Registration: https://hair-court-salon-register.netlify.app
- Owner Dashboard: https://hairsaloonownertool.netlify.app/

## Stack

- Pure HTML/CSS/JS — no framework, no backend
- Google Apps Script (webhook) → Google Sheets
- Netlify (deployment)
- WhatsApp Click-to-Chat API

## Why this stack

Small business owners in India don't need complex tools. They need something that works in a browser, requires zero training, and integrates with WhatsApp — where they already operate.
