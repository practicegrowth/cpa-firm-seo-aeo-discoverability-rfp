# AEO Readiness Checklist — AI Search Optimization Evaluation

> Use this checklist to evaluate whether a vendor has genuine capability in Answer Engine Optimization (AEO) and AI search visibility. In 2026, appearing in AI-powered search (Google AI Overviews, ChatGPT, Perplexity) is as important as traditional SEO.

---

## How to Use This Checklist

For each item, ask the vendor to provide:
- **Evidence** — Show me how you've done this for another client
- **Methodology** — Walk me through your process
- **Tools** — What tools do you use to measure this?
- **Reporting** — How will you report AI search visibility to me?

Mark each item: ✅ (demonstrated capability), ⚠️ (claimed but no evidence), ❌ (no capability or awareness)

---

## 1. Google AI Overviews (formerly SGE)

- [ ] Does the vendor optimize content specifically for Google AI Overviews?
- [ ] Do they understand how AI Overviews select and cite sources?
- [ ] Can they show examples of clients appearing in AI Overviews?
- [ ] Do they track AI Overview appearances as a KPI?
- [ ] What is their content formatting strategy for AI extractability?
- [ ] Do they optimize for Microsoft Copilot (formerly Bing Chat) citations?

**Vendor Response Quality:** [ ] Strong [ ] Adequate [ ] Weak [ ] No awareness

---

## 2. Structured Data Implementation

_Ask the vendor which schema types they implement and why. They should provide specific JSON-LD examples._

- [ ] **Organization schema** — Firm name, logo, address, contact, social profiles
- [ ] **LocalBusiness / ProfessionalService schema** — Location, hours, services, price range
- [ ] **Person schema** — Individual CPA bios with credentials (CPA, EA, CPA/PFS, etc.)
- [ ] **Article schema** — Blog posts, guides, thought leadership with author attribution
- [ ] **FAQ schema** — Frequently asked questions in Q&A format
- [ ] **HowTo schema** — Step-by-step guides (tax preparation, bookkeeping processes)
- [ ] **BreadcrumbList schema** — Site navigation hierarchy
- [ ] **Review / AggregateRating schema** — Review snippets (where compliant)
- [ ] **Speakable schema** — Content marked for voice/AI extraction
- [ ] **SameAs** — Links to authoritative profiles (LinkedIn, state board, professional associations)

**Example: What good looks like**

Ask the vendor to show you a JSON-LD example. Here's what Organization schema should include:

```json
{
  "@context": "https://schema.org",
  "@type": "AccountingService",
  "name": "Smith & Associates CPA",
  "image": "https://example.com/logo.png",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "123 Main St",
    "addressLocality": "Dallas",
    "addressRegion": "TX",
    "postalCode": "75201"
  },
  "telephone": "+1-214-555-0123",
  "priceRange": "$$",
  "openingHours": "Mo-Fr 09:00-17:00",
  "sameAs": [
    "https://www.linkedin.com/company/smith-cpa",
    "https://www.facebook.com/smithcpa"
  ]
}
```

**Red flag:** If they can't show you JSON-LD examples or don't know what structured data is, they're not AEO-ready.

**Vendor Response Quality:** [ ] Strong [ ] Adequate [ ] Weak [ ] No awareness

---

## 3. Featured Snippet Optimization

- [ ] Does the vendor have a featured snippet optimization strategy?
- [ ] Do they target paragraph snippets (40-60 word definitions/answers)?
- [ ] Do they target list snippets (step-by-step, ranked lists)?
- [ ] Do they target table snippets (comparison data, tax brackets, deadlines)?
- [ ] Can they show examples of snippets they've won for clients?
- [ ] Do they track snippet ownership over time?

**Example: What good looks like**

For a query like "What is the QBI deduction?", the content should be structured as:

```markdown
## What is the Qualified Business Income (QBI) Deduction?

The Qualified Business Income (QBI) deduction, also known as Section 199A deduction, allows eligible self-employed individuals and small-business owners to deduct up to 20% of their qualified business income on their tax returns. This deduction is available for tax years 2018 through 2025 (subject to congressional renewal) and can significantly reduce tax liability for pass-through entities.

### Who Qualifies for QBI?
- Sole proprietors
- Partners in partnerships
- S corporation shareholders
- Certain trusts and estates
- Independent contractors
```

**Why this works:** Clear H2 heading matching the query, concise 40-60 word answer in first paragraph, followed by supporting details in scannable format.

_Note: Tax law changes frequently. Always verify current year applicability and consult IRS guidance._

**Vendor Response Quality:** [ ] Strong [ ] Adequate [ ] Weak [ ] No awareness

---

## 4. E-E-A-T Signal Optimization

_E-E-A-T (Experience, Expertise, Authoritativeness, Trustworthiness) is critical for both traditional and AI search. AI models heavily weight E-E-A-T signals when deciding which sources to cite._

- [ ] **Author bios** — Do they create detailed author pages with credentials, photo, bio, social links?
- [ ] **Credential display** — CPA license numbers, state board membership, professional designations
- [ ] **Citations** — Do they cite authoritative sources (IRS, state departments, professional standards)?
- [ ] **About page** — Comprehensive firm history, team credentials, mission, contact information
- [ ] **Editorial standards** — Documented content review process, fact-checking, update cadence
- [ ] **Trust signals** — Professional association memberships (AICPA, state societies), awards, media mentions
- [ ] **Content attribution** — Every piece of content has a named author with verifiable credentials

**Example: What good looks like**

Every blog post should have an author byline with a linked bio page:

```
By Jane Smith, CPA, MST
Jane is a tax partner at Smith & Associates with 15 years of experience 
specializing in small business tax planning. She is a member of the AICPA 
and Texas Society of CPAs.
[View full bio →]
```

The bio page should include: professional photo, full credentials, license number, years of experience, areas of expertise, professional memberships, media appearances, published works, and LinkedIn profile link.

**Why this matters:** AI models use author credentials to assess content reliability. Anonymous or uncredentialed content is less likely to be cited.

**Vendor Response Quality:** [ ] Strong [ ] Adequate [ ] Weak [ ] No awareness

---

## 5. AI Citation Tracking & Measurement

_How does the vendor measure AI search visibility? This is critical because different AI platforms source information differently:_

- **Google AI Overviews**: Appears in ~50% of searches, only 13.7% overlap with AI Mode citations
- **ChatGPT**: 200-700M weekly users, now integrates real-time Yelp data (July 2026 partnership)
- **Perplexity**: Real-time web search for every query, favors Reddit/community sources, 11x conversion rate
- **Google AI Mode**: Different citation sources than AI Overviews (86.3% non-overlap)

**Key Questions:**

- [ ] Do they have tools to track when your firm is cited in AI-generated answers?
- [ ] Can they track citations across multiple AI platforms (Google AI Overviews, ChatGPT, Perplexity, AI Mode)?
- [ ] Do they provide baseline measurement of current AI visibility?
- [ ] What is their reporting cadence for AI citation metrics?
- [ ] Can they show trend data over time (are citations increasing)?
- [ ] Do they track competitor AI citations for comparison?
- [ ] Do they understand platform-specific optimization (Yelp for ChatGPT, Reddit for Perplexity, structured data for Google)?
- [ ] Can they explain the difference between Google AI Overviews and AI Mode citations?

**Specific Tools Mentioned:** [List any tools the vendor names — e.g., Profound, Otterly, Surfer SEO AI, custom methodologies]

**Red Flag:** If they say "we track AI citations" but can't explain platform-specific differences or the July 2026 ChatGPT-Yelp integration, they're not current.

**Vendor Response Quality:** [ ] Strong [ ] Adequate [ ] Weak [ ] No awareness

---

## 6. Voice Search Optimization

- [ ] Does the vendor optimize for voice search queries (Siri, Alexa, Google Assistant)?
- [ ] Do they target conversational, long-tail queries ("How do I reduce my tax liability as a small business owner?")?
- [ ] Do they implement natural language content formatting?
- [ ] Do they optimize for question-based queries (who, what, when, where, why, how)?
- [ ] Is local voice search optimization included (near me, local service queries)?

**Example: What good looks like**

Voice queries are conversational and question-based. Content should be structured to answer these directly:

**Voice query:** "Hey Google, find a CPA near me who specializes in small business taxes"

**Optimized content structure:**
```markdown
## Small Business CPA in Dallas, TX

Looking for a CPA who specializes in small business taxes in Dallas? Smith & Associates has helped over 200 Dallas small businesses reduce their tax liability.

### Our Small Business Tax Services
- Entity selection (LLC, S-Corp, C-Corp)
- Quarterly estimated tax planning
- Year-end tax optimization strategies
- IRS audit representation
- Bookkeeping and payroll

**Serving:** Dallas, Fort Worth, Plano, Frisco, and surrounding areas
**Call us:** (214) 555-0123
```

**Why this works:** Direct answer to "CPA near me," includes location modifiers, conversational tone, clear service list, and prominent contact info for voice assistants to read.

_Illustrative example — replace with actual client results and metrics._

**Vendor Response Quality:** [ ] Strong [ ] Adequate [ ] Weak [ ] No awareness

---

## 7. Content Formatting for AI Extractability

- [ ] Do they use clear, descriptive headings (H1, H2, H3) that match search queries?
- [ ] Is content structured with concise, direct answers in the first 1-2 paragraphs?
- [ ] Do they use bullet points, numbered lists, and tables for scannable content?
- [ ] Is content modular (self-contained sections that can be extracted independently)?
- [ ] Do they avoid jargon-heavy content that AI models can't parse?
- [ ] Is there a clear information hierarchy (most important → supporting details)?

**Vendor Response Quality:** [ ] Strong [ ] Adequate [ ] Weak [ ] No awareness

---

## 8. Knowledge Graph Optimization

- [ ] Does the vendor understand Google's Knowledge Graph and how entities are recognized?
- [ ] Do they implement strategies to ensure your firm is recognized as an entity?
- [ ] Do they optimize Wikipedia, Wikidata, or other knowledge base entries (where appropriate)?
- [ ] Do they ensure consistency across structured data, website content, and external profiles?
- [ ] Can they explain how entity recognition affects AI search citations?

**Vendor Response Quality:** [ ] Strong [ ] Adequate [ ] Weak [ ] No awareness

---

## 9. Brand Entity Recognition in AI Models

- [ ] Does the vendor have a strategy for improving brand recognition in LLMs?
- [ ] Do they understand how AI models learn about and recommend businesses?
- [ ] Do they optimize for "best CPA near me" or "recommend a tax accountant" type queries in AI chat?
- [ ] Do they build brand mentions across authoritative, AI-crawled sources?
- [ ] Can they explain the relationship between brand authority and AI citation likelihood?

**Vendor Response Quality:** [ ] Strong [ ] Adequate [ ] Weak [ ] No awareness

---

## 10. Competitor AI Citation Analysis

- [ ] Does the vendor analyze which competitors are being cited in AI search results?
- [ ] Can they provide a competitive analysis of AI visibility in your market?
- [ ] Do they track competitor structured data implementations?
- [ ] Can they identify gaps where competitors are winning AI citations that you're not?
- [ ] Do they provide recommendations based on competitor AI citation patterns?

**Vendor Response Quality:** [ ] Strong [ ] Adequate [ ] Weak [ ] No awareness

---

## Summary Scorecard

| Category | Max Score | Vendor Score | Notes |
|----------|-----------|--------------|-------|
| Google AI Overviews | 10 | | |
| Structured Data | 10 | | |
| Featured Snippets | 10 | | |
| E-E-A-T Signals | 10 | | |
| AI Citation Tracking | 10 | | |
| Voice Search | 10 | | |
| Content Formatting | 10 | | |
| Knowledge Graph | 10 | | |
| Brand Entity Recognition | 10 | | |
| Competitor AI Analysis | 10 | | |
| **TOTAL** | **100** | | |

**Scoring:** Strong = 10, Adequate = 6, Weak = 3, No awareness = 0

---

## Red Flags 🚩

If the vendor exhibits any of these, proceed with caution:

- ❌ Claims "AEO is just like SEO" without explaining the differences
- ❌ Cannot name specific AI search platforms they optimize for
- ❌ Has no methodology for tracking AI citations
- ❌ Suggests "gaming" AI models rather than building genuine authority
- ❌ Cannot explain how structured data affects AI search visibility
- ❌ Has no case studies or examples of AI search optimization work
- ❌ Dismisses AI search as "not important yet" (it's 2026)

---

## Green Flags ✅

Strong vendors will demonstrate:

- ✅ Deep understanding of how AI models select and cite sources
- ✅ Specific tools and methodologies for AI citation tracking
- ✅ Case studies showing measurable AI search visibility improvements
- ✅ Integration of AEO into broader SEO strategy (not siloed)
- ✅ Proactive approach to emerging AI search platforms
- ✅ Clear reporting on AI citation metrics alongside traditional SEO KPIs

---

*Checklist developed by [PracticeGrowth](https://www.practicegrowth.tech/?utm_source=github&utm_medium=repository&utm_campaign=seo-aeo-discoverability-rfp) for evaluating AI search optimization vendors.*
