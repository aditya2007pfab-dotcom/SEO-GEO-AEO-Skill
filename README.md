# SEO / GEO / AEO Audit — Skill for Claude

Automatically audits any website across three dimensions of modern search visibility:

- **SEO** — Traditional search engine optimization (Google, Bing): title tags, meta descriptions, heading structure, schema markup, internal links, content quality
- **GEO** — Generative Engine Optimization for AI-powered search (Perplexity, ChatGPT Search, Google AI Overviews, Gemini): E-E-A-T signals, entity clarity, factual density, author authority
- **AEO** — Answer Engine Optimization for featured snippets and voice search: FAQ schema, HowTo schema, question-phrased headings, direct answer formatting

---

## How to use

Once installed, just give Claude a URL and ask about search performance:

> "Can you audit burningstickcreative.com for SEO?"
> "Check my site example.com — why isn't it ranking?"
> "Audit this URL for AI search readiness: example.com"
> "Run a full SEO, GEO, and AEO audit on my website"

Claude will ask whether you want a **Quick Audit** (top issues and scores) or a **Full Audit** (comprehensive breakdown), then crawl the site across multiple pages before delivering a structured report with a downloadable Word doc and PDF.

---

## Installation

This tool is distributed as a Cowork Skill (`.skill` file) for use in **Claude's Cowork desktop app**.

1. Download `seo-geo-aeo.skill` from this repository
2. Open the Claude desktop app
3. Go to **Settings → Skills** and click **Install Skill**
4. Select the downloaded `.skill` file

The skill will then be available in all your Cowork sessions.

---

## Repository structure

```
SEO-GEO-AEO-Skill/
├── seo-geo-aeo.skill    ← Install this in the Claude desktop app
├── SKILL.md             ← Audit instructions (source of truth)
└── README.md
```

---

## Version history

**1.0.0** — Initial release
- Quick and Full audit modes
- Multi-page site crawl (up to 15 pages for Quick, unlimited for Full)
- SEO, GEO, and AEO scoring with priority recommendations matrix
- Downloadable audit report as both Word (.docx) and PDF
