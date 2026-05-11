<div align="center">

# 🤝 Contributing to awesome-ml-llm-case-studies

### Help us build the world's most complete ML & LLM system design database

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)
![Contributors](https://img.shields.io/github/contributors/hackthacker/awesome-ml-llm-case-studies?style=for-the-badge&color=blue)
![Last Commit](https://img.shields.io/github/last-commit/hackthacker/awesome-ml-llm-case-studies?style=for-the-badge&color=orange)

</div>

<div align="center">

[📋 Before You Start](#-before-you-start) • [✅ What We Accept](#-what-we-accept) • [❌ What We Reject](#-what-we-reject) • [📝 How to Contribute](#-how-to-contribute) • [🗂️ Entry Format](#️-entry-format) • [🔍 Quality Checklist](#-quality-checklist) • [🐛 Reporting Issues](#-reporting-issues) • [📜 Code of Conduct](#-code-of-conduct)

</div>

---

## 📋 Before You Start

Thank you for taking the time to contribute! This repository is a **curated database** — quality always beats quantity. Every entry must be a real, published engineering resource from a company's production system.

Please read this entire guide before opening a Pull Request. PRs that do not follow the format will be closed without review.

> **Quick Rule:** If a reader can learn something real about how a production ML or LLM system was actually built, it belongs here. If it's a tutorial, course, or opinion piece — it does not.

---

## ✅ What We Accept

| ✅ Accepted Type | Examples |
|-----------------|---------|
| **Engineering blog posts** | Company tech blogs (Netflix Tech Blog, Uber Engineering, Airbnb Engineering) |
| **Research papers** | arXiv papers, ACM/IEEE papers written by company engineers describing a deployed system |
| **Conference talks (video)** | MLconf, NeurIPS industry track, QCon, recorded internal talks made public |
| **System design write-ups** | Architecture deep-dives, post-mortems, retrospectives on AI/ML systems |
| **Official case studies** | AWS, GCP, Azure case studies that describe a real company's ML implementation |

### ✅ Accepted Technologies

Only entries from one of these six categories:

```
🤖  AI Agents          — agentic systems, tool-use, multi-agent, autonomous workflows
🧠  Generative AI & LLM — fine-tuning, prompt engineering, text-to-SQL, multimodal, code gen
🔍  RAG                — retrieval-augmented generation, vector search, hybrid retrieval
📊  Predictive ML      — recommendations, fraud detection, forecasting, ranking, causal ML
👁️  CV                 — image classification, object detection, visual search, OCR
💬  NLP                — text classification, entity extraction, content moderation, embeddings
```

### ✅ Accepted Industries

```
🚗  Delivery and mobility
🛒  E-commerce and retail
🎓  Education
🏦  Fintech and banking
🎮  Gaming
🏭  Manufacturing
📺  Media and streaming
🌐  Social platforms
💻  Tech
✈️  Travel and E-commerce
```

> If a company belongs to a new industry not listed above, open an **Issue** first to discuss before submitting a PR.

---

## ❌ What We Reject

| ❌ Rejected Type | Reason |
|----------------|--------|
| Generic AI tutorials | No company attribution, not production |
| Medium posts by individuals (non-company) | Not an engineering team case study |
| Courses, MOOCs, YouTube playlists | Educational, not a case study |
| GitHub repos / tools / libraries | This is a case study database, not an awesome-tools list |
| Vendor marketing content | Content that promotes a product without technical depth |
| Paywalled articles | Must be freely accessible |
| Duplicate links | Already in the database |
| Dead links | URL must resolve at time of submission |
| Opinion / thought leadership posts | Must describe an actual implemented system |
| Anything without a named company | Anonymous or unattributed sources not accepted |

---

## 📝 How to Contribute

There are **three ways** to contribute:

### 1. 🆕 Add a New Case Study (Most Common)

**Step 1 — Fork the repository**
```bash
# Click "Fork" on GitHub, then clone your fork
git clone https://github.com/YOUR-USERNAME/awesome-ml-llm-case-studies.git
cd awesome-ml-llm-case-studies
```

**Step 2 — Create a new branch**
```bash
# Always create a new branch — never commit directly to main
git checkout -b add/company-name-case-study
```

**Step 3 — Edit `README.md`**

Find the correct industry section and company heading. Add your entry in the correct format (see [Entry Format](#️-entry-format) below). Keep entries sorted **newest year first** within each company block.

**Step 4 — Commit with a clear message**
```bash
git add README.md
git commit -m "add: [CompanyName] Title of Case Study (Year)"

# Examples of good commit messages:
# add: [Stripe] How we built Stripe Radar (2023)
# add: [Netflix] Foundation Model for Personalized Recommendation (2025)
# add: [Airbnb] Embedding-Based Retrieval for Airbnb Search (2025)
```

**Step 5 — Push and open a Pull Request**
```bash
git push origin add/company-name-case-study
```

Then open a Pull Request on GitHub using the **PR template** provided.

---

### 2. 🐛 Fix a Broken Link

If you find a link that returns 404 or has moved:

```bash
git checkout -b fix/broken-link-company-name
# Update the URL in README.md
git commit -m "fix: update broken link for [CompanyName] (Year)"
git push origin fix/broken-link-company-name
```

---

### 3. 💡 Suggest a Case Study (No Fork Needed)

If you found a great case study but don't want to edit the README yourself, open an **Issue** using the `Case Study Suggestion` template and fill in all required fields. A maintainer will review and add it.

---

## 🗂️ Entry Format

Every case study must follow **this exact format** — no exceptions:

```markdown
- EMOJI **[YEAR]** [Title of the Case Study](https://link-to-the-article) `Technology`
```

### Format Rules

| Field | Rule |
|-------|------|
| **EMOJI** | Must match the technology: 🤖 AI Agents · 🧠 Generative AI & LLM · 🔍 RAG · 📊 Predictive ML · 👁️ CV · 💬 NLP |
| **[YEAR]** | Four-digit publication year in bold brackets: `**[2024]**` |
| **Title** | Exact title of the article/paper/talk — do not paraphrase or shorten |
| **Link** | Direct URL to the article — must be publicly accessible |
| **`Technology`** | Backtick-wrapped technology tag — must be one of the six accepted values |

### ✅ Correct Examples

```markdown
- 🧠 **[2025]** [Foundation Model for Personalized Recommendation](https://netflixtechblog.com/foundation-model-for-personalized-recommendation-1a0bd8e02d39) `Generative AI & LLM`
- 📊 **[2024]** [Real-time Fraud Detection with Yoda and ClickHouse](https://tech.instacart.com/real-time-fraud-detection-with-yoda-and-clickhouse-bd08e9dbe3f4) `Predictive ML`
- 🔍 **[2024]** [Enterprise-Grade RAG Systems](https://www.harvey.ai/blog/enterprise-grade-rag-systems) `RAG`
- 🤖 **[2025]** [Building production-ready agentic systems: Lessons from Shopify Sidekick](https://shopify.engineering/building-production-ready-agentic-systems) `AI agents`
```

### ❌ Incorrect Examples

```markdown
# WRONG — emoji doesn't match technology
- 🤖 **[2024]** [Real-time Fraud Detection](https://example.com) `Predictive ML`

# WRONG — year not bold
- 📊 [2024] [Some ML Article](https://example.com) `Predictive ML`

# WRONG — technology tag has wrong casing or spelling
- 🧠 **[2024]** [Some LLM Article](https://example.com) `LLM`
- 🧠 **[2024]** [Some LLM Article](https://example.com) `generative ai`

# WRONG — title paraphrased/shortened
- 📊 **[2024]** [How Instacart Uses ML for Replacements](https://example.com) `Predictive ML`

# CORRECT technology tag values (copy exactly):
# AI agents
# Generative AI & LLM
# RAG
# Predictive ML
# CV
# NLP
```

### Where to Place Your Entry

```
## 🏭 [Industry Section]        ← Find the right industry
  ### 🏢 [Company Name]         ← Find or create the company block
    - 🧠 **[2025]** ...         ← Newest year first
    - 📊 **[2024]** ...
    - 📊 **[2023]** ...         ← Oldest year last
```

**New company not in the list?**

Add a new `### 🏢 CompanyName` heading in **alphabetical order** within the correct industry section.

---

## 🔍 Quality Checklist

Before opening your Pull Request, verify every item:

```
□  The article is written by or directly attributed to a company's engineering team
□  The article describes a system that is (or was) in production — not a prototype or demo
□  The link is publicly accessible and works right now
□  The link is not already in the README (search with Ctrl+F before adding)
□  The entry uses the exact format: EMOJI **[YEAR]** [Title](URL) `Technology`
□  The technology tag matches exactly one of the six accepted values
□  The emoji matches the technology tag
□  The year is the publication year of the article (four digits, bold, in brackets)
□  The title is the exact title from the article — not paraphrased
□  The entry is placed under the correct industry section
□  The entry is placed under the correct company heading
□  Entries within a company are sorted newest-to-oldest by year
□  If a new company was added, it is in alphabetical order within its industry section
□  Only README.md was modified — no other files changed
□  The commit message follows the format: add: [CompanyName] Title (Year)
```

---

## 🐛 Reporting Issues

Use GitHub Issues to report problems. Choose the right template:

| Issue Type | When to Use |
|-----------|------------|
| 🔗 **Broken Link** | A URL returns 404, redirects incorrectly, or is behind a paywall |
| ➕ **Case Study Suggestion** | You found a great case study but don't want to submit a PR |
| 🏢 **Wrong Category** | An entry is in the wrong industry or wrong technology tag |
| 📝 **Formatting Error** | An existing entry doesn't follow the format |
| 💬 **General Question** | Anything else |

**When reporting a broken link, always include:**
- The company name and article title
- The current (broken) URL
- The correct/updated URL if you found it

---

## 🔀 Pull Request Guidelines

### PR Title Format

```
add: [CompanyName] Short Title (Year)
fix: [CompanyName] broken link updated
fix: [CompanyName] wrong technology tag corrected
```

### PR Description

When you open a PR, fill in the provided template completely. A PR without a description will be closed.

The template asks for:
- Company name and industry
- Link to the article
- Why this meets the quality bar
- Confirmation that you ran through the Quality Checklist

### Review Process

| Status | Meaning |
|--------|---------|
| ✅ **Merged** | Entry meets all standards — thank you! |
| 💬 **Changes requested** | Minor issues to fix before merge |
| ❌ **Closed** | Does not meet the quality bar or format requirements |

Maintainers aim to review PRs within **7 days**. Please be patient — this is a community project.

---

## 🌟 Recognition

All accepted contributors are credited in the repository's **Contributors** section (auto-generated by GitHub). There is no manual hall of fame — GitHub's contributor graph is the source of truth.

---

## 📜 Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/).

**In short:**

- Be respectful and constructive in all interactions
- Disagreements about content should be technical, not personal
- Low-quality spam PRs will result in a block
- No self-promotion — if you are submitting your own company's article, follow the same quality bar as everyone else

Violations can be reported by opening a private issue or contacting the maintainer directly.

---

## ❓ FAQ

**Q: Can I add a case study from my own company?**
Yes — as long as it meets the quality bar. Self-promotion is not disqualifying; low quality is.

**Q: Can I add multiple case studies in one PR?**
Yes, but keep it to a maximum of **5 entries per PR**. Bulk PRs with 20+ entries are harder to review and will be asked to be split.

**Q: The company I want to add is in two industries. Which one do I use?**
Use the industry that best represents the case study's domain, not the company's primary industry.

**Q: Can I suggest adding a new industry?**
Yes — open an Issue with the label `new industry` and provide at least 5 case studies that would belong to it.

**Q: The article is in a language other than English. Can I add it?**
Currently we only accept English-language case studies to keep the database accessible globally.

**Q: Can I add a case study from before 2017?**
The database starts from 2017. Earlier case studies are out of scope.

---

<div align="center">

Made with ❤️ by [hackthacker](https://github.com/hackthacker)

</div>
