# whatsapp chatbot

## Introduction
WhatsApp is a high-trust channel, which makes **opt-in, transactional chatbots** ideal for commerce and customer support—*not* for unsolicited messaging.

<p align="center">
  <a href="https://Appilot.app" target="_blank"><img src="https://github.com/Instagram-Automations/Footer-test/blob/main/appilot-baner.png" alt="Appilot Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/devpilot1" target="_blank"><img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:support@appilot.app" target="_blank"><img src="https://img.shields.io/badge/Email-support@appilot.app-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a href="https://Appilot.app" target="_blank"><img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website"></a>
  <a href="https://discord.gg/3YrZJZ6hA2" target="_blank"><img src="https://img.shields.io/badge/Join-Appilot_Community-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Appilot Discord"></a>
</p>



<p align="center">
Created by Appilot, built to showcase our approach to Automation! <br>
If you are looking for custom <strong> whatsapp chatbot </strong>, you've just found your team — Let’s Chat.&#128070; &#128070;
</p>

**Whatsapp chatbot** is a **policy-aware WhatsApp Business bot** that allows users to request products by name or description and receive **affiliate purchase options** retrieved from AliExpress via API.

The system is designed for:
- explicit user initiation,
- approved WhatsApp Business messaging,
- stable API-based integrations (no scraping or browser automation).

---

## Why This Automation Matters
- Converts chat intent into measurable commerce actions  
- Eliminates manual product lookup and link generation  
- Keeps affiliate workflows compliant and auditable  
- Scales safely with rate limits and observability  
- Maintains WhatsApp account health long-term  

---

## Core Features

| Feature | Description |
|------|-------------|
| User-Initiated Requests | Users send product names or descriptions |
| Product Search | Query AliExpress API for matching items |
| Affiliate Link Builder | Generate tracked affiliate URLs |
| Message Templates | Clean, readable product option cards |
| Rate Limiting | Enforced per WhatsApp Business policies |
| Error Handling | Graceful fallback for empty results |
| Audit Logging | Track queries, responses, and clicks |
| Observability | Logs, metrics, and health checks |

---

## How It Works

| Step | Operation | Safety Control |
|---|---|---|
| 1 | User sends product query | Explicit opt-in |
| 2 | Webhook receives message | Verified WhatsApp signature |
| 3 | AliExpress API search | API quota + retry logic |
| 4 | Affiliate links generated | Deterministic tagging |
| 5 | Results formatted | Template validation |
| 6 | Response sent | Rate-limited delivery |
| 7 | Interaction logged | Immutable audit trail |

> **Design principle:** No scraping, no spam, no unsolicited outreach.

---

## Tech Stack
- Python
- WhatsApp Business Cloud API
- AliExpress API (affiliate-enabled)
- FastAPI (webhooks)
- SQLite / PostgreSQL
- Structured JSON logging

---

## Directory Structure

```
whatsapp-chatbot/
├── app/
│ ├── main.py
│ ├── webhooks/
│ │ └── whatsapp.py
│ ├── integrations/
│ │ ├── aliexpress.py
│ │ └── affiliate_links.py
│ ├── messaging/
│ │ ├── templates.py
│ │ └── sender.py
│ ├── policies/
│ │ ├── rate_limits.py
│ │ └── opt_in.py
│ ├── storage/
│ │ ├── models.py
│ │ └── db.py
│ └── observability/
│ ├── logging.py
│ └── metrics.py
├── config/
│ └── settings.yaml
├── tests/
│ └── test_aliexpress.py
└── README.md
```


---

## Use Cases
- Affiliate product discovery bots  
- WhatsApp-based shopping assistants  
- Customer support with purchase links  
- Niche product recommendation services  
- Lead-to-purchase chat funnels  

---

## FAQs

**Q: Does this send messages automatically to users?**  
No. All responses are **user-initiated**, as required by WhatsApp policy.

**Q: Can this work without the WhatsApp Business API?**  
No. The official API is required for reliability and compliance.

**Q: Is scraping AliExpress allowed?**  
No. This repo uses the **AliExpress API** only.

**Q: Can I add product images or buttons later?**  
Yes. The message template system supports interactive extensions.

---

## Performance & Reliability Benchmarks
- Sub-second webhook handling  
- Deterministic affiliate link generation  
- Safe retries for transient API failures  
- No duplicate message delivery  
- Clear observability for debugging  

---
<p align="center">
<a href="https://cal.com/app-pilot-m8i8oo/30min" target="_blank">
 <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
 <a href="https://www.youtube.com/@Appilot-app/videos" target="_blank">
  <img src="https://img.shields.io/badge/ð¥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
 </a>
</p>


