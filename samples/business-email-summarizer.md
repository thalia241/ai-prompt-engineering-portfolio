# 📌 Business Prompt Case Study: Email Summarizer for Law Firm

## ✅ Objective
A mid-sized law firm needed to reduce the time paralegals spent reading and interpreting long email chains. The goal was to automate summaries that included sentiment tagging, urgency detection, and actionable recommendations.

## 🔧 Prompt Design
```text
System: You are a legal operations assistant trained to extract actionable intelligence from email conversations.
User: Summarize this email thread in bullets. Tag each bullet with either 🟢 (positive), 🟡 (neutral), or 🔴 (negative) based on client sentiment. At the end, include “Recommended Action” as a separate section.
Input: [Insert full client-attorney email thread here]
```

## 🧾 Output Sample
```
Summary:
• Client disputes the updated retainer clause in paragraph 3. 🔴
• Mentions financial hardship and asks about payment flexibility. 🔴
• Expresses gratitude for past responsiveness. 🟢
• Willing to sign if retainer can be split across 2 months. 🟡

Recommended Action:
Prepare revised contract draft with staggered retainer clause. Flag for partner review.
```

## 🔍 Prompt Engineering Process
| Iteration | Change Made | Purpose |
|----------|-------------|---------|
| v1 | Basic summarization | No tagging or structure |
| v2 | Added sentiment emojis | Highlighted client tone |
| v3 | Added 'Recommended Action' section | Created task-ready output for assistants |

## 📈 Value Delivered
- Reduced average email processing time by 20–30 minutes
- Integrated into an internal GPT-4-based summarization assistant
- Enabled faster partner review cycles and higher SLA compliance

## 💡 Tools Used
- OpenAI ChatGPT-4 with system messages
- M365 integration for email parsing (planned)

## 📎 Use Case Category
**Business Ops / Legal Automation / AI Workflow Optimization**

---

Back to [Portfolio Home](../README.md)
