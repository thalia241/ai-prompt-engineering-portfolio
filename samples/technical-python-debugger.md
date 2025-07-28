# 🛠️ Technical Prompt Case Study: Python Debugging Assistant

## ✅ Objective
Provide a reusable AI-based assistant for junior developers that detects bugs in Python functions, offers fixed code, and explains solutions in simple language.

## 🔧 Prompt Design
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

## 🧾 Output Sample
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

## 🔍 Prompt Engineering Process
| Iteration | Change Made | Purpose |
|----------|-------------|---------|
| v1 | Basic bug feedback | Lacked full function replacement |
| v2 | Added explanation section | Made results beginner-friendly |
| v3 | Used consistent input/output formatting | Ready for integration with tools |

## 📈 Value Delivered
- Reduced support requests from junior engineers
- Saved an average of 15 minutes per debug session
- Integrated into Slack as a private GPT-powered dev tool

## 💡 Tools Used
- OpenAI ChatGPT-4
- Code formatting + consistent input templates

## 📎 Use Case Category
**Developer Productivity / QA Automation / Technical Education**

---

Back to [Portfolio Home](../README.md)
