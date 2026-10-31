# nexaeo-geo-checklist
https://nexaeo.com

# 2026 Generative Engine Optimization (GEO) & AI Search Visibility Technical Blueprint

Maintained by the engineering team at **[NEXAEO — AI Search Visibility Tool & GEO Platform](https://nexaeo.com/)** and **[NexAEO Ventures](https://nexaeo.com/agency)**.

This repository provides a production technical checklist and schema specification for engineering web applications to win citations across **OpenAI ChatGPT Search**, **Perplexity Sonar**, **Google Gemini**, **Google AI Overviews (AIO)**, and **Google AI Mode**.

---

## 🛠️ Free Live Diagnostic Tools (191 Countries — No Signup)

Before modifying your DOM or JSON-LD schema, benchmark how Google's Gemini-powered search engines currently cite your domain across 191 country codes:

* **[Free Google AI Mode Checker & Analyzer Tool](https://nexaeo.com/google-ai-mode-checker)** — Inspect live synthesized Google AI Mode responses, markdown tables, and deduplicated inline citation badges (`[1]`, `[2]`, `[3]`).
* **[Free Google AI Overview Checker & Analyzer Tool](https://nexaeo.com/google-ai-overview-checker)** — Check whether your target keywords trigger a Google AI Overview in any country and extract the exact cited source URLs.

---

## 📋 The 3-Layer Technical GEO Checklist

### Layer 1: Crawlability & SSR Completeness
- [ ] **Full Server-Side Rendering (SSR):** Serve complete HTML on initial HTTP response so non-JS RAG crawlers (`OAI-SearchBot`, `ChatGPT-User`, `PerplexityBot`, `Claude-SearchBot`) parse the full document.
- [ ] **Keep Inactive Tabs & Accordions Mounted:** Never conditionally unmount FAQ tabs or guide chapters in React (`{isOpen && <Panel/>}`). Keep all panels mounted in SSR HTML and toggle visibility using the native HTML `hidden` attribute.
- [ ] **Explicit AI Bot Permissions in `robots.txt`:** Allow `OAI-SearchBot`, `ChatGPT-User`, `PerplexityBot`, `ClaudeBot`, `Claude-SearchBot`, `Google-Extended`, and `Applebot`.
- [ ] **Dynamic `/sitemap.xml` & `/llms.txt`:** Expose a clean XML sitemap (with ISO `YYYY-MM-DD` `<lastmod>`) and a structured `/llms.txt` markdown index at the root domain.

### Layer 2: Passage Extractability & Grounding Chunks
- [ ] **40–60 Word Direct Answer Blocks:** Open every page and every major H2 section with a self-contained, high-density summary paragraph free of ambiguous pronouns.
- [ ] **Native Semantic HTML `<table>` Matrices:** Present feature, architectural, and pricing comparisons inside standard `<table><thead><tbody>` markup rather than flattened images.

### Layer 3: Unified `@graph` JSON-LD Knowledge Graph
- [ ] Connect `Organization`, `WebSite`, `WebPage`, `SoftwareApplication` (with verified `AggregateOffer` pricing), `BlogPosting`, and `FAQPage` via consistent `@id` references.
- [ ] Ensure 100% word-for-word parity between `FAQPage` JSON-LD items and visible SSR HTML questions/answers.

---

## 📚 Deep-Dive Engineering Playbooks

1. **[GEO vs. SEO vs. AEO: The 10-Dimension Search Architecture Matrix](https://nexaeo.com/blog/geo-vs-seo-vs-aeo)**
2. **[How to Track Brand Mentions in ChatGPT: 2026 GEO Playbook](https://nexaeo.com/blog/how-to-track-brand-mentions-in-chatgpt)**
3. **[Google AI Mode SEO: How to Track & Rank in AI Mode](https://nexaeo.com/blog/google-ai-mode-seo-tracking-guide)**
4. **[The 2026 Guide to Ranking in Google AI Overviews](https://nexaeo.com/blog/google-ai-overviews-guide)**
5. **[How to Choose an AI Search Visibility Tool: Buyer's Guide](https://nexaeo.com/blog/best-ai-search-visibility-tools)**
6. **[Automating GEO Content Workflows Without Losing Quality](https://nexaeo.com/blog/automating-geo-content-workflows)**

---

## 🚀 About NEXAEO
* **Self-Serve SaaS Platform:** Track 5 AI engines, audit competitor DOM gaps, ground content in locked Brand Fact Sheets, and publish to WordPress & Shopify in 1 click — **[Start a 7-Day Free Trial ($33 / $99 / $299 plans)](https://nexaeo.com/pricing)**.
* **Done-For-You Engineering & Automation:** Need custom **AI-SEO/GEO**, **n8n / Make.com marketing automation**, or **Meta Ads lead pipelines**? Explore **[NexAEO Ventures Agency Services](https://nexaeo.com/agency)**.
