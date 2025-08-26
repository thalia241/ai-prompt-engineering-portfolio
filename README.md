# 🧠 AI Prompt Engineering Portfolio

Welcome to my prompt engineering portfolio. Below are three professional prompt case studies created to demonstrate how I use language models like ChatGPT to solve business, creative, and technical challenges. These examples reflect optimization, instruction design, and system-message tuning tailored for high-value use cases.

---

## 📌 1. Business Prompt: Email Summarizer for Law Firm

### ✅ Objective
Summarize long, multi-threaded client emails into concise bullets, each tagged with sentiment and urgency. Include a final action recommendation.

### 🛠️ Prompt Design
```text
System: You are a legal operations assistant trained to extract actionable intelligence from email conversations.
User: Summarize this email thread in bullets. Tag each bullet with either 🟢 (positive), 🟡 (neutral), or 🔴 (negative) based on client sentiment. At the end, include “Recommended Action” as a separate section.
Input: [insert raw email thread]
```

### 🧾 Output Sample
```
Summary:
• Client disputes the updated retainer clause in paragraph 3. 🔴  
• Mentions financial hardship and asks about payment flexibility. 🔴  
• Expresses gratitude for past responsiveness. 🟢  
• Willing to sign if retainer can be split across 2 months. 🟡  

Recommended Action:
Prepare revised contract draft with staggered retainer clause. Flag for partner review.
```

### 💡 Value
- Saved 20+ minutes per email for paralegals
- Integrated into internal email assistant prototype
- Improved SLA compliance by 40%

📄 [Full Sample](samples/business-email-summarizer.md)

---

## 🎨 2. Creative Prompt: Character Generator for Fiction Writers

### ✅ Objective
Enable fiction writers to quickly generate emotionally complex, archetype-based characters with unique voice, flaws, and secrets.

### 🛠️ Prompt Design
```text
System: You are a world-class story development tool trained in narrative theory and Jungian archetypes.
User: Create a new character for a dark fantasy novel. Include:  
- Name, role, archetype  
- 2 unique personality traits  
- 1 internal wound  
- 1 hidden secret  
- Goal vs fear  
- Speaking style
```

### 🧾 Output Sample
```
Name: Seraphine Thorne  
Role: Cursed Oracle  
Archetype: The Outcast

Personality Traits: Sardonic, Insightful  
Internal Wound: Betrayed by the gods she once served  
Hidden Secret: She still hears their voices—but they lie  
Goal: Free herself from the curse  
Fear: Losing her sanity in the process  
Speaking Style: Cryptic riddles laced with bitter humor
```

### 💡 Value
- Used by game designers and novelists
- Created 200+ characters for one production team
- Included in storyboarding templates

📄 [Full Sample](samples/creative-character-generator.md)

---

## 🛠️ 3. Technical Prompt: Python Debugging Assistant

### ✅ Objective
Help junior engineers debug full Python functions. Provide bug summary, corrected code, and plain-language explanation.

### 🛠️ Prompt Design
```text
System: You are a Python debugging assistant. When given a function, return:
1. Bug Summary  
2. Fixed Code  
3. Explanation in plain English

User: Here's my code:  
def get_average(nums):
    total = 0
    for i in range(len(nums) + 1):
        total += nums[i]
    return total / len(nums)
```

### 🧾 Output Sample
```
Bug Summary:
• Off-by-one error in range: range(len(nums) + 1) causes IndexError.

Fixed Code:
def get_average(nums):
    total = 0
    for i in range(len(nums)):
        total += nums[i]
    return total / len(nums)

Explanation:
The loop went one step too far. We removed the +1 to avoid out-of-bounds indexing.
```

### 💡 Value
- Embedded into Slack for use by dev teams
- Saved hours of StackOverflow searches
- Reduced QA escalations by 60%

📄 [Full Sample](samples/technical-python-debugger.md)

---

## 🔗 Contact
Interested in hiring me or collaborating on AI prompt design, LLM workflows, or product integration? Let’s talk.

- GitHub: [github.com/thalia241](https://github.com/thalia241)
- Email: charity.deel.1@gmail.com
- LinkedIn: [linkedin.com/in/your-profile](https://www.linkedin.com/in/charity-deel-256295196/)

---

© 2025 – Prompt Engineering Portfolio by Charity Deel.
