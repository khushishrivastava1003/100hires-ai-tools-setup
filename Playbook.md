# AI-Powered SEO Content Production Playbook

## 1. Introduction

This playbook represents my synthesis of the research rather than a copy of any individual expert's methodology. It combines the strongest recommendations across ten experts into one operational workflow while documenting disagreements, rejected ideas, limitations, and original recommendations.

The scope covers the full content production cycle:

- Business understanding
- Research and planning
- AI-assisted creation
- Human validation and optimization
- Publishing
- Measurement, refreshing, and scaling

This SOP is intended for growth marketers, SEO specialists, content strategists, editors, and operators who need a repeatable process for AI-powered SEO content production.

This workflow was developed from the completed research artifacts in this repository: the expert shortlists, the master recommendation database, the recommendation matrix, and the cross-expert comparison. The research reviewed recommendations from 10 industry experts: Matt Kenyon, Nicolas Gorroño, Ivan Palii, Freddie Chatt, Aimee Jurenka, Kai Cromwell, Nathan Gotch, Mark Williams-Cook, Steve Toth, and Aleyda Solís.

This playbook represents my recommended workflow based on that research. It is not a universal truth. Different sites, industries, business models, and teams will need adjustments.

## 2. Workflow Overview

```text
┌────────────────────────┐
│ Business Understanding │
└───────────┬────────────┘
            ↓
┌─────────────────────┐
│ Research & Planning │◄──────────────┐
└──────────┬──────────┘               │
           ↓                          │
┌────────────────┐                    │
│ Create with AI │                    │
└────────┬───────┘                    │
         ↓                            │
┌─────────────────────┐               │
│ Validate & Optimize │               │
└──────────┬──────────┘               │
           ↓                          │
┌─────────┐                            │
│ Publish │                            │
└────┬────┘                            │
     ↓                                 │
┌───────────────────┐                  │
│ Measure & Improve │──────────────────┘
└───────────────────┘
```

The workflow starts with the business because content that is disconnected from the offer, audience, and commercial goal becomes noise. Research then defines what to create and why. AI accelerates drafting, analysis, and process documentation, but humans remain responsible for judgment, accuracy, quality, and final decisions. After publication, performance and AI-search visibility data feed the next round of improvement.

## Phase 1: Understand the Business

### Goal

Before doing SEO research or asking AI to create anything, define what the business sells, who it serves, what it wants to be known for, and what success looks like. AI-powered production only works when the model is guided by clear business context.

### Why this phase matters

This phase prevents the team from creating content that gets traffic but does not support the business. It gives every later decision a commercial and brand context, so AI is working from the right brief instead of guessing.

### Recommendations

1. Start every content project by clarifying the brand meaning, product meaning, target topics, and third-party signals that should reinforce the same story. This keeps the site from publishing content that ranks but fails to help AI systems or buyers understand the brand. (Source: Aimee Jurenka, LinkedIn, 22 May 2026)
2. Assign every content asset a commercial job before briefing it. A page should earn links, drive sales, build awareness, grow an email list, support a product page, answer a buyer objection, or serve another defined business purpose. (Source: Freddie Chatt, LinkedIn, 4 June 2026)
3. When SEO or AI tactics become overwhelming, simplify strategy back to the core offer. Start with “what do we sell?” and “what does the business need?” before choosing keywords, tools, prompts, or content formats. (Source: Matt Kenyon, LinkedIn, 10 June 2026)
4. Define success metrics before production starts. For a bottom-funnel page, that may be leads, trials, product clicks, or assisted conversions. For an AI-search visibility asset, that may be citations, brand presence, recommendation accuracy, or third-party source coverage. Aleyda Solís warns against overclaiming AI-search impact and recommends connecting presence, readiness, and business impact before reporting progress. (Source: Aleyda Solís, LinkedIn, 29 May 2026)

Before moving to the next phase, confirm that the following items are complete.

### Checklist

☐ Business goals defined  
☐ Consider creating an Entity Trust Map if AI-search visibility is a strategic objective.  
☐ Success metrics defined  
☐ Target audience identified  
☐ Brand positioning understood  
☐ Content asset job selected  
☐ Target product, offer, or conversion path confirmed  
☐ AI-search goal defined, if relevant  

### Common Mistakes

- Starting with a tool instead of the business problem.
- Publishing content because a keyword has volume, not because the page has a job.
- Treating AI visibility as a goal without defining which journeys, prompts, or buyers matter.
- Writing generic informational content that does not strengthen brand positioning.
- Measuring success only by rankings or traffic when the content is meant to support conversion, trust, or AI representation.

## Phase 2: Research & Planning

### Goal

Research determines content quality. AI can accelerate research, but it should not replace the work of understanding customers, demand, intent, competitors, and the role each page must play.

### Why this phase matters

Research is where the team decides whether a content idea deserves to exist. Strong planning reduces wasted AI output and makes the final brief specific enough for writers, editors, and AI tools to follow.

### Recommendations

1. Mine real audience pain points before drafting high-consideration content. For ecommerce and high-ticket products, collect buyer questions and objections from Reddit, Amazon reviews, YouTube comments, low-star competitor reviews, and similar sources, then convert those pain points into buying-guide sections. (Source: Kai Cromwell, LinkedIn, 12 June 2026)
2. Build topic architecture before producing content at scale, especially for smaller brands. Clarify core topics, turn them into indexable categories or hubs where appropriate, support those categories with focused content, and strengthen internal links. (Source: Aimee Jurenka, LinkedIn, 26 May 2026)
3. Expand research beyond traditional keywords. In AI search environments, research prompts, tasks, constraints, scenarios, follow-up journeys, local needs, product attributes, and buyer decision criteria. (Source: Aleyda Solís, LinkedIn, 24 May 2026)
4. Target realistic commercial opportunities first. Ecommerce teams should avoid broad head terms at the start and prioritize long-tail commercial queries tied to product USPs, conversion intent, and realistic ranking difficulty. (Source: Freddie Chatt, LinkedIn, 29 May 2026)
5. Turn product attributes into keyword and page opportunities. For ecommerce catalogs, classify products by commercially meaningful attributes and evaluate whether each attribute deserves an indexable category, collection, comparison, or support page. (Source: Kai Cromwell, LinkedIn, 5 June 2026)
6. Use real query data before trusting AI classification. Google Search Console regex filters can segment queries into informational, comparison, product/service, transactional, navigational, SaaS/tool, and long-question patterns. Use that data to identify existing demand and content gaps. (Source: Mark Williams-Cook, LinkedIn, 11 June 2026)
7. Use intent-proximity questions to build stronger briefs. Identify the next questions users are likely to ask, then check whether the target page fully answers, partially answers, or misses them. (Source: Mark Williams-Cook, LinkedIn, 17 June 2026)
8. Structure briefs for conversational and task-based search. Rewrite headings as complete questions where appropriate, answer the user’s task directly, add follow-up question blocks, and include multimodal assets when they help the user complete the task. (Source: Nicolas Gorroño, YouTube)
9. Evaluate comparison or AEO packages before paying for them. Check whether the brand owns the asset, can reuse the data, can update it, and whether the source is likely to be trusted more than competitor-created or third-party comparison tables. (Source: Ivan Palii, LinkedIn, 19 June 2026)
10. Create a written content brief before AI drafting. The brief should include the business goal, target audience, primary query or prompt set, search intent, competitor/SERP findings, required proof, internal-link targets, brand voice notes, conversion goal, and post-publication measurement plan. Matt Kenyon and Nathan Gotch both support structured workflows that move from keyword/intent and competitor research into outlines, drafting, QA, publishing, and refresh. (Source: Matt Kenyon, YouTube; Source: Nathan Gotch, YouTube)

Before moving to the next phase, confirm that the following items are complete.

### Checklist

☐ Audience pain points collected  
☐ Business and conversion goal added to brief  
☐ Topic/category fit confirmed  
☐ Keyword and prompt research completed  
☐ Long-tail or commercial opportunity validated  
☐ Search intent documented  
☐ Competitor/SERP patterns reviewed  
☐ AI-search prompt or journey relevance checked  
☐ Internal-link targets identified  
☐ Content brief approved before drafting  

### Common Mistakes

- Asking AI to write before the brief is complete.
- Treating keyword research and AI prompt research as the same thing.
- Targeting broad keywords before commercial long-tail opportunities.
- Ignoring actual customer language from reviews, forums, sales calls, or support questions.
- Buying comparison content or AEO packages without checking ownership and durability.
- Creating new pages for every attribute without validating demand, duplication risk, or indexation value.

## Phase 3: Create with AI

### Goal

AI should accelerate research, outlining, drafting, analysis, and process documentation. It should not replace human strategy, brand judgment, or editorial standards.

### Why this phase matters

This phase turns approved research into draft material without losing control of strategy or quality. Clear prompts, knowledge bases, and reusable SOPs help the team compound what it learns instead of starting from scratch each time.

### Recommendations

1. Build a brand knowledge base before using AI for content. Include brand messaging, offers, FAQs, case studies, policies, objections, reviews, customer language, sales insights, and product details so AI outputs stay accurate and on brand. (Source: Nathan Gotch, YouTube)
2. Prompt from the approved brief, not from a vague instruction. Give the AI the business goal, audience, search intent, target page role, required sections, evidence requirements, internal-link targets, and brand voice constraints. Nathan Gotch’s knowledge-base approach and Matt Kenyon’s structured content workflow both support this controlled approach. (Source: Nathan Gotch, YouTube; Source: Matt Kenyon, YouTube)
3. Use AI to draft section by section instead of generating and accepting a full article in one pass. This keeps the draft closer to the brief and makes facts, examples, claims, and structure easier to review. Matt Kenyon’s workflow supports section-by-section drafting inside a broader intent-to-publish process. (Source: Matt Kenyon, YouTube)
4. Plan before letting AI agents build, edit, or change anything important. Use a setup phase where the AI defines the workflow and plan before execution, especially when working with code, CMS workflows, dashboards, or production systems. (Source: Nicolas Gorroño, LinkedIn, 6 June 2026)
5. Turn successful AI work sessions into reusable SOPs or master prompts. Before the context window is lost, ask the AI to summarize the refinements, guidelines, prompt logic, and process decisions into a reusable instruction set. (Source: Steve Toth, LinkedIn, 10 June 2026)
6. Use AI for options, not final judgment. AI can propose angles, outlines, questions, draft sections, and strategic options, but the team owns the final decision. Matt Kenyon’s AI strategy test supports validating AI outputs before they become recommendations. (Source: Matt Kenyon, YouTube)

Before moving to the next phase, confirm that the following items are complete.

### Checklist

☐ Brand knowledge base prepared  
☐ Brief loaded into AI context  
☐ Prompt includes business goal and audience  
☐ Prompt includes search intent and target query/prompt  
☐ Prompt includes evidence and citation requirements  
☐ AI draft generated section by section  
☐ AI agent plan reviewed before execution  
☐ Useful prompt/session converted into SOP  

### Common Mistakes

- Asking AI to “write an SEO article” without business or audience context.
- Publishing the first AI draft.
- Letting AI agents edit production assets without a plan.
- Losing useful prompt refinements when the context window ends.
- Using AI to decide strategy without human validation.
- Treating AI fluency as evidence of accuracy.

## Phase 4: Validate & Optimize

### Goal

AI drafts are starting points. The validation phase turns them into trustworthy, useful, differentiated, search-ready content.

### Why this phase matters

This phase is where the content becomes safe to publish. It catches unsupported claims, generic AI writing, weak structure, and SEO gaps before they reach users or search systems.

### Recommendations

1. Require human QA before publication. Tighten the writing, confirm accuracy, add proof, add real experience, add screenshots or documentation where useful, and remove anything generic that AI could easily produce. (Source: Nathan Gotch, YouTube)
2. Fact-check AI-generated strategies, claims, examples, and SEO recommendations before shipping. Manually inspect the site, verify the model used the right inputs, challenge outdated tactics, and replace weak ranking-only KPIs with business-relevant measures. (Source: Matt Kenyon, YouTube)
3. Use Google’s helpful-content questions as an editorial QA layer. Score the draft against content quality, expertise, people-first usefulness, and search-engine-first warning signs. Use the output to identify the top fixes, but do not treat a high score as a ranking guarantee. (Source: Steve Toth, LinkedIn, 12 June 2026)
4. Replace generic informational content with brand-specific assets. Add product differentiators, comparison content, case studies, real examples, proof, and clear positioning so the content helps AI systems and buyers understand the brand’s real value. (Source: Aimee Jurenka, LinkedIn, 29 May 2026)
5. Improve AI-search visibility through visible-page evidence. Add clear quotes, statistics, citations, technical terms where appropriate, and readable explanations. Avoid keyword stuffing. (Source: Mark Williams-Cook, LinkedIn, 28 May 2026)
6. Write AI-citable answer sections. Use short, declarative, self-contained statements after question-based headings. Reduce dependency hops between subject, predicate, and supporting detail so the answer can be understood without extra context. (Source: Steve Toth, LinkedIn, 18 June 2026)
7. Optimize commercial ecommerce pages before assuming the solution is more blog content. For large catalogs, prioritize collection/category pages, add useful copy, and connect them with relevant internal links. (Source: Kai Cromwell, LinkedIn, 2 June 2026)
8. Check AI-search readiness as part of optimization. For content intended to influence AI answers, confirm that the page clearly states the entity, category, product attributes, comparison claims, pricing or availability details where relevant, and supporting sources. This combines Aimee’s brand alignment, Aleyda’s source ecosystem thinking, and Steve’s citable answer structure. (Source: Aimee Jurenka, LinkedIn, 22 May 2026; Source: Aleyda Solís, LinkedIn, 29 May 2026; Source: Steve Toth, LinkedIn, 18 June 2026)

Before moving to the next phase, confirm that the following items are complete.

### Checklist

☐ Human editor reviewed the draft  
☐ Claims fact-checked  
☐ Sources, examples, and proof added  
☐ Generic AI sections removed or rewritten  
☐ Helpful-content QA completed  
☐ Search intent still matches the page  
☐ Answer sections are clear and self-contained  
☐ Internal links added where relevant  
☐ On-page SEO elements checked  
☐ AI-search readiness checked  

### Common Mistakes

- Treating AI output as publication-ready.
- Checking grammar but not facts.
- Adding citations without verifying whether they support the claim.
- Writing vague claims that AI systems cannot verify.
- Optimizing for a score instead of usefulness.
- Creating more content when existing category or product pages need optimization.
- Ignoring internal links and page structure.

## Phase 5: Publish

### Goal

Publishing should make the content accessible, crawlable, understandable, and ready for measurement. A good draft can fail if the page is not technically accessible or if the publishing handoff is sloppy.

### Why this phase matters

Publishing turns the approved asset into a live search experience. This phase protects the work from technical, CMS, tracking, and accessibility mistakes that can undermine otherwise strong content.

### Recommendations

1. Keep important content available in raw HTML whenever possible. Do not assume AI assistants will render JavaScript when grounding answers. If important content is injected client-side, lazy-loaded, or hidden behind hydrated tabs, verify accessibility with server logs or technical checks. (Source: Aleyda Solís, LinkedIn, 18 June 2026)
2. Treat publishing as a QA checkpoint, not an upload task. Confirm the title, H1, headings, metadata, canonical, indexability, internal links, structured sections, image metadata, conversion modules, and tracking plan before the page goes live. Nicolas Gorroño’s foundation-first recommendation supports fixing indexation, performance, service-page clarity, schema, useful content, and entity consistency before chasing AI visibility. (Source: Nicolas Gorroño, LinkedIn, 26 May 2026)
3. Validate implementation before and after launch. Mark Williams-Cook warns that SEO recommendations have no impact unless implemented correctly; discuss implementation difficulty, QA changes before launch, and monitor afterward because sites change and things break. (Source: Mark Williams-Cook, LinkedIn, 26 May 2026)
4. Publish with a refresh plan already attached. Matt Kenyon’s structured content workflow includes revisiting performance at 30/60/90 days, and Nicolas Gorroño’s production loop includes reporting and revival rather than treating publication as the finish line. (Source: Matt Kenyon, YouTube; Source: Nicolas Gorroño, YouTube)

Before moving to the next phase, confirm that the following items are complete.

### Checklist

☐ Important content visible in raw HTML or verified accessible  
☐ Page indexability checked  
☐ Canonical and metadata checked  
☐ H1 and headings checked  
☐ Internal links checked  
☐ Conversion path checked  
☐ Tracking plan confirmed  
☐ Implementation QA completed  
☐ Refresh date or review trigger assigned  

### Common Mistakes

- Publishing JavaScript-injected content without verifying accessibility.
- Assuming a CMS preview equals what crawlers or AI systems can access.
- Launching without checking indexability, links, or canonical tags.
- Treating publication as the end of the workflow.
- Shipping developer or CMS changes without QA.

## Phase 6: Measure & Improve

### Goal

Content production should become smarter over time. Measure traditional SEO performance, AI-search visibility, content quality signals, and business impact separately. Use those findings to refresh, restructure, or scale.

### Why this phase matters

This phase closes the loop between production and learning. Measurement shows what to refresh, what to scale, and what to stop doing, so the workflow improves instead of only producing more content.

### Recommendations

1. Measure AI-search visibility with repeated samples, not screenshots. One AI answer is not evidence of a trend, so use repeated runs and larger samples before drawing conclusions. (Source: Aimee Jurenka, LinkedIn, 8 June 2026)
2. Build a representative AI-search prompt library. It should cover the products, audiences, markets, journey stages, competitors, and buyer constraints that matter to the business. Do not rely only on default prompts from a tool. (Source: Aleyda Solís, LinkedIn, 8 June 2026)
3. Track AI visibility with multiple metrics. Record presence, citations, brand mentions, sentiment, competitor visibility, position, share of voice, source/entity coverage, and where relevant product-level visibility. (Source: Ivan Palii, LinkedIn, 8 June 2026; Source: Nathan Gotch, YouTube; Source: Freddie Chatt, LinkedIn, 17 June 2026)
4. Separate AI presence, citations, traffic, page type, traffic owner, and business impact. Do not create one blended “AI search traffic” KPI and treat it as the full story. (Source: Aleyda Solís, LinkedIn, 27 May 2026)
5. Track third-party citation surfaces. Identify which Reddit threads, G2 profiles, review platforms, news sites, listicles, LinkedIn posts, and other third-party sources shape how LLMs describe the brand. (Source: Steve Toth, LinkedIn, 28 May 2026)
6. Connect AI content decisions to live performance data. Use GSC, GA, YouTube, or other available performance data to decide what to create, update, repurpose, or retire rather than relying on generic AI advice. (Source: Nicolas Gorroño, YouTube)
7. Detect synthetic AI-tracker prompts before interpreting GSC query data. Very long queries with multiple “or” rules and ICP-style parameters may come from AI visibility trackers rather than real users. (Source: Ivan Palii, LinkedIn, 7 June 2026)
8. Refresh before scaling when the issue is structure, cannibalization, or under-optimized existing assets. Diagnose cannibalization in GSC, merge or realign pages where needed, and restructure content around clearer topic entities and internal links. (Source: Matt Kenyon, LinkedIn, 10 June 2026; Source: Aimee Jurenka, LinkedIn, 3 June 2026)
9. Scale with systems, not random output. Use automation for repetitive SEO data collection, treat Claude or similar tools as auxiliary automation layers, run a consistent monthly ecommerce cadence where relevant, and maintain a production loop that includes creation, distribution, reporting, and revival. (Source: Freddie Chatt, LinkedIn, 5 June 2026; Source: Ivan Palii, LinkedIn, 25 May 2026; Source: Kai Cromwell, LinkedIn, 5 June 2026; Source: Nicolas Gorroño, YouTube)
10. Keep AI agents scoped and supervised. AI can handle well-defined tasks, but high-stakes SEO campaigns need guardrails, testing, QA, and experienced human direction. (Source: Nathan Gotch, LinkedIn, 3 June 2026)

Before moving to the next phase, confirm that the following items are complete.

### Checklist

☐ Traditional SEO performance reviewed  
☐ AI-search prompt library updated  
☐ Prompt samples repeated before conclusions  
☐ AI presence measured  
☐ AI citations measured  
☐ AI traffic measured separately  
☐ Business impact assessed  
☐ Third-party citation sources reviewed  
☐ GSC data checked for synthetic prompts  
☐ Refresh opportunities identified  
☐ Scaling cadence reviewed  
☐ AI-agent tasks scoped and QA’d  

### Common Mistakes

- Treating one ChatGPT or AI Overview screenshot as proof.
- Blending AI traffic, AI citations, and AI presence into one KPI.
- Measuring brand mentions but ignoring product-level or source-level visibility.
- Ignoring third-party sources that shape AI answers.
- Scaling content before fixing cannibalization or weak existing pages.
- Automating reports without human interpretation.
- Letting agents run important work without guardrails.

## Where Experts Disagree

The research contains more differences in emphasis than direct contradictions. I would treat the following as strategic tensions, not winner-takes-all disagreements.

### 1. Should AI-search optimization start with AI diagnostics or SEO foundations?

- **Question:** Before producing AI-search content, should the team start with AI-search prompt/source diagnostics or with classic SEO foundations?
- **Author A recommendation:** Aleyda Solís recommends diagnosing prompts, journeys, source ecosystems, gaps, visibility, and business impact before changing content. (Source: Aleyda Solís, LinkedIn, 29 May 2026)
- **Author B recommendation:** Nicolas Gorroño recommends fixing SEO foundations first: indexed pages, fast performance, clear service pages, schema, useful content, entity consistency, and aligned profiles before AI-specific tactics. (Source: Nicolas Gorroño, LinkedIn, 26 May 2026)
- **My Decision:** I recommend doing both, but in sequence: first confirm the site is crawlable, indexable, understandable, and useful; then run AI-search prompt/source diagnostics.
- **Why I chose this approach:** AI-search diagnostics are more valuable when the site has a stable SEO foundation. If pages are not accessible, useful, or clearly structured, AI-search optimization becomes premature. Once the foundation is stable, Aleyda’s diagnostic framework helps decide where to optimize next.

### 2. How much should AI automate?

- **Question:** Should AI automate large parts of SEO operations, or should it remain a limited auxiliary layer?
- **Author A recommendation:** Freddie Chatt recommends using AI and APIs to automate repetitive SEO data collection such as reporting, keyword seed lists, competitor monitoring, AI-search visibility tracking, rankings, backlinks, on-page audits, and SERP composition. (Source: Freddie Chatt, LinkedIn, 5 June 2026)
- **Author B recommendation:** Ivan Palii recommends treating Claude as an auxiliary automation layer, while recognizing unresolved problems such as team training, hallucinations, context limits, API cost unpredictability, and tasks better handled in native tools. (Source: Ivan Palii, LinkedIn, 25 May 2026)
- **My Decision:** I recommend automating data collection and repetitive preparation, but keeping strategy, prioritization, final recommendations, and publishing decisions human-owned.
- **Why I chose this approach:** Freddie’s automation categories are useful for scaling, but Ivan’s cautions are important operational guardrails. Nathan Gotch’s warning that AI agents need scope, testing, QA, and experienced supervision supports the same decision. (Source: Nathan Gotch, LinkedIn, 3 June 2026)

### 3. Should we produce new content or improve existing content first?

- **Question:** When a site needs more organic visibility, should the team create new AI-assisted content or fix existing content first?
- **Author A recommendation:** Matt Kenyon and Nathan Gotch both provide structured content-production workflows that move from keyword/intent research through drafting, QA, publishing, and post-publish optimization. (Source: Matt Kenyon, YouTube; Source: Nathan Gotch, YouTube)
- **Author B recommendation:** Aimee Jurenka recommends improving structure and internal linking before defaulting to more content, while Matt Kenyon separately recommends diagnosing cannibalization before producing more content after a traffic drop. (Source: Aimee Jurenka, LinkedIn, 3 June 2026; Source: Matt Kenyon, LinkedIn, 10 June 2026)
- **My Decision:** I recommend auditing existing content first when performance has dropped, when the site already has many similar pages, or when structure is unclear. I recommend creating new content when the brief identifies a validated gap with a clear business job.
- **Why I chose this approach:** The research supports both production and restraint. New content is valuable when it fills a validated intent or buyer-journey gap. Existing content should be fixed first when cannibalization, poor structure, or weak internal linking is the likely constraint.

## What I Rejected and Why

### 1. I rejected adopting `llms.txt` or agent-readiness files as a required step

- **What the recommendation was:** Nicolas Gorroño’s research includes `llms.txt` and agentic-readiness ideas as part of AI-search adaptation.
- **Which expert suggested it:** Nicolas Gorroño.
- **Why I rejected it:** The completed research flags this as experimental and warns that Google guidance does not support treating `llms.txt` as required for Google AI visibility. Because this playbook needs to be immediately usable and evidence-based, I do not include it as a required SOP step. (Source: Nicolas Gorroño, YouTube; Source: Nicolas Gorroño, LinkedIn, 26 May 2026)
- **When it might still be useful:** It may be worth testing later for non-Google AI agents or experimental AI-crawler workflows, but it should be tracked as a test, not a standard requirement.

### 2. I rejected regular link insertions as a default AI-search or SEO tactic

- **What the recommendation was:** Ivan Palii’s comparison-package evaluation notes that money might be better spent on regular link insertions on pages that have already been cited a lot.
- **Which expert suggested it:** Ivan Palii.
- **Why I rejected it:** The research itself flags that this may carry search-policy risk depending on whether links are paid and how they are qualified. This playbook is intended as an internal SOP that a new employee can follow safely, so I do not include link insertions as a default workflow. (Source: Ivan Palii, LinkedIn, 19 June 2026)
- **When it might still be useful:** Source outreach and third-party citation improvement may still be useful when done transparently and editorially, especially for correcting inaccurate brand information or improving legitimate profiles, reviews, and listings.

## My Original Idea: Entity Trust Map

My original recommendation is to create an **Entity Trust Map** before beginning AI-powered SEO campaigns.

Search engines and AI systems increasingly build an understanding of brands from a broader ecosystem of trusted references, not backlinks alone. Before scaling AI-powered SEO, I propose creating an Entity Trust Map to identify, classify, and evaluate every major source that contributes to the brand's credibility and discoverability.

The map should classify trusted sources into categories such as:

- Official brand website
- Editorial backlinks
- Industry publications
- News coverage
- Review platforms (for example G2 and Capterra)
- Reddit discussions
- LinkedIn mentions
- Partner websites
- Community forums
- Expert roundups

Rather than measuring these sources only for link equity or referral traffic, evaluate how each contributes to:

- Brand authority
- Entity understanding
- AI citation opportunities
- Recommendation trust
- Consistency of brand messaging

The Entity Trust Map is not a backlink-building checklist. It is a planning framework that helps teams prioritize the trust signals most likely to improve brand understanding across search engines and AI systems.

I believe this could strengthen AI-powered SEO because modern AI search systems increasingly rely on a broader ecosystem of trusted references rather than evaluating individual pages in isolation. Mapping these trust signals makes it easier to identify where a brand is well represented, inconsistently described, or missing from influential sources before scaling content production.

No expert explicitly recommended creating an Entity Trust Map. This idea emerged from combining recurring themes around entity understanding, citation ecosystems, third-party trust signals, and AI-search visibility into a single planning framework.

The supporting inspiration came from:

- Steve Toth on third-party citation surfaces.
- Aimee Jurenka on brand alignment and entity understanding.
- Ivan Palii on brand mentions and entity tracking.
- Nathan Gotch on brand authority and knowledge bases.

This is my own synthesis built from recurring themes across multiple experts, not a framework proposed by any one expert.

## Weaknesses of this Playbook

This playbook is practical, but it has limitations.

1. **It assumes the business already has enough clarity to define goals and positioning.** If the offer, audience, or positioning is unclear, the content workflow will expose that problem but not solve it fully.
2. **It has stronger evidence for research, measurement, QA, and AI-search visibility than for AI drafting itself.** The recommendation matrix shows no primary-stage AI Drafting recommendation, even though AI-assisted drafting appears inside broader workflows.
3. **SERP Analysis, EEAT, Internal Linking, Publishing, Reporting, Fact Checking, Audience Research, and Competitor Research are thinner evidence areas as primary stages.** Some appear inside broader recommendations, but they are not as strongly represented as AI Search Visibility, Keyword Research, Strategy, and Scaling.
4. **Some recommendations are tool-influenced.** Nathan Gotch’s workflows reference Rankability, Matt Kenyon’s content workflow references Surfer, Freddie Chatt references DataForSEO, Ivan Palii works at Sitechecker, and Mark Williams-Cook’s query fan-out recommendation is tied to his own tool. The playbook keeps the principles but avoids making any single tool mandatory.
5. **AI-search measurement methods are still unstable.** Experts agree that measurement matters, but they differ on prompt libraries, product visibility, citation surfaces, share of voice, and business impact. This workflow should be validated with real client/project data.
6. **Some AI-search tactics are early or experimental.** `llms.txt`, agentic-readiness claims, JavaScript rendering behavior, citation-surface influence, and exact GEO uplift claims require future testing before they become hard rules.
7. **This playbook is stronger for ecommerce and B2B SEO than for news, local-only, marketplace-only, or publisher-specific workflows.** The research contains ecommerce and B2B patterns, but not enough specialist evidence for every vertical.
8.  **This playbook is based on expert recommendations rather than controlled experiments.** The workflow was synthesized from publicly available content produced by ten SEO experts, not from controlled testing across multiple websites or industries. Recommendations that appeared consistently across experts were given greater weight, but they should still be validated against a company's own business model, website maturity, and market before becoming permanent operating procedures.

## Experts I Would Not Use as My Primary Framework and Why

This section is not a personal criticism of any expert. It identifies whose advice is least suitable as the primary model for this specific beginner-friendly internal SOP.

### I would not use Kai Cromwell as the primary blueprint for non-ecommerce teams

Kai Cromwell contributes strong ecommerce SEO recommendations: high-ticket buying guides, product-attribute category expansion, collection-page optimization, and monthly ecommerce SEO cadence. Those are valuable, but their applicability is narrow. A SaaS, service, publisher, or local business team should not copy Kai’s category-page and product-roundup cadence without adapting it heavily. His research also includes caveats around self-reported revenue and backlink policy risk. (Source: Kai Cromwell, LinkedIn, 12 June 2026; Source: Kai Cromwell, LinkedIn, 5 June 2026)

### I would not use Ivan Palii as the sole blueprint for beginners

Ivan Palii is useful for AI-search analytics, synthetic prompt detection, and automation-layer thinking. However, several recommendations are better suited to teams that already understand GSC, GA4, AI visibility tools, dashboards, and reporting systems. The research also flags commercial interest around Sitechecker and warns that some recommendations, such as regular link insertions, may carry policy risk. (Source: Ivan Palii, LinkedIn, 8 June 2026; Source: Ivan Palii, LinkedIn, 19 June 2026)

### I would not use tool-specific workflows as mandatory playbook steps

Several experts provide useful workflows through specific tools: Rankability, Surfer, DataForSEO, Sitechecker, Claude Code, Windsor.ai, QueryFan, and others. The underlying recommendations are useful, but the SOP should stay tool-neutral unless the company officially adopts those tools. (Source: Nathan Gotch, YouTube; Source: Matt Kenyon, YouTube; Source: Freddie Chatt, LinkedIn, 5 June 2026; Source: Mark Williams-Cook, LinkedIn, 30 May 2026)

## Conclusion

I selected this workflow because the research repeatedly points to the same operating principle: AI improves SEO content production when it is grounded in business goals, real audience insight, structured research, human judgment, and continuous measurement.

AI should support the team by accelerating research, drafting, analysis, QA, documentation, and reporting. It should not replace human expertise. The strongest experts in this research consistently add guardrails: knowledge bases, planning phases, human QA, fact-checking, source validation, implementation QA, and measurement discipline.

Continuous improvement matters because AI search and traditional search both change. A page is not finished when it is published. It needs measurement, refresh, source monitoring, internal-link improvement, and periodic reassessment against business outcomes.

## References

1. Aimee Jurenka, LinkedIn, 22 May 2026 — “AI visibility isn’t just about content—it’s about alignment.” [https://www.linkedin.com/posts/advanced-web-ranking_aivisibility-seo-searchstrategy-activity-7463546808716316672-ldSX](https://www.linkedin.com/posts/advanced-web-ranking_aivisibility-seo-searchstrategy-activity-7463546808716316672-ldSX)
2. Aimee Jurenka, LinkedIn, 26 May 2026 — “For small brands, the challenge isn’t just ranking - it’s getting understood.” [https://www.linkedin.com/posts/advanced-web-ranking_aiseo-searchstrategy-digitalmarketing-activity-7464996368730951681-FKDm](https://www.linkedin.com/posts/advanced-web-ranking_aiseo-searchstrategy-digitalmarketing-activity-7464996368730951681-FKDm)
3. Aimee Jurenka, LinkedIn, 29 May 2026 — “Informational content isn’t dead - it’s just being redefined.” [https://www.linkedin.com/posts/advanced-web-ranking_aiseo-contentstrategy-searchmarketing-activity-7466156940461629441-tXNP](https://www.linkedin.com/posts/advanced-web-ranking_aiseo-contentstrategy-searchmarketing-activity-7466156940461629441-tXNP)
4. Aimee Jurenka, LinkedIn, 3 June 2026 — “Sometimes you don’t need more content - you need better structure.” [https://www.linkedin.com/posts/advanced-web-ranking_aiseo-contentstrategy-searchstrategy-activity-7467969439871799296-bg8](https://www.linkedin.com/posts/advanced-web-ranking_aiseo-contentstrategy-searchstrategy-activity-7467969439871799296-bg8)_
5. Aimee Jurenka, LinkedIn, 8 June 2026 — “Finally.” [https://www.linkedin.com/posts/aimee-jurenka_finally-it-was-starting-to-get-lonly-activity-7469750347478093824-D0zN](https://www.linkedin.com/posts/aimee-jurenka_finally-it-was-starting-to-get-lonly-activity-7469750347478093824-D0zN)
6. Aleyda Solís, LinkedIn, 24 May 2026 — “Google just shared a new report on how people are using AI Mode in the US.” [https://www.linkedin.com/posts/aleyda_google-just-shared-a-new-report-on-how-activity-7464243547047813120-8AJM](https://www.linkedin.com/posts/aleyda_google-just-shared-a-new-report-on-how-activity-7464243547047813120-8AJM)
7. Aleyda Solís, LinkedIn, 27 May 2026 — “AI Traffic vs AI Citations: What Clicks and Cited Pages Show About the AI Search Journey.” [https://www.linkedin.com/posts/aleyda_ai-traffic-vs-ai-citations-what-clicks-activity-7465347600397959168-4s8B](https://www.linkedin.com/posts/aleyda_ai-traffic-vs-ai-citations-what-clicks-activity-7465347600397959168-4s8B)
8. Aleyda Solís, LinkedIn, 29 May 2026 — “I’ve just updated my AI Search Optimization Checklist (and worksheet).” [https://www.linkedin.com/posts/aleyda_ive-just-updated-my-ai-search-optimization-activity-7466150460299857921-664d](https://www.linkedin.com/posts/aleyda_ive-just-updated-my-ai-search-optimization-activity-7466150460299857921-664d)
9. Aleyda Solís, LinkedIn, 8 June 2026 — “How to Build a Representative AI Search Prompt Library for Better AI Visibility Measurement.” [https://www.linkedin.com/posts/aleyda_how-to-build-a-representative-ai-search-activity-7469723521947131905-6DVK](https://www.linkedin.com/posts/aleyda_how-to-build-a-representative-ai-search-activity-7469723521947131905-6DVK)
10. Aleyda Solís, LinkedIn, 18 June 2026 — “Do AI Assistants Actually Render Your JavaScript when Grounding?” [https://www.linkedin.com/posts/aleyda_do-ai-assistants-actually-render-your-activity-7473307747128733697-YIWg](https://www.linkedin.com/posts/aleyda_do-ai-assistants-actually-render-your-activity-7473307747128733697-YIWg)
11. Freddie Chatt, LinkedIn, 29 May 2026 — “The #1 mistake ecommerce sites make with SEO:” [https://www.linkedin.com/posts/freddiechatt_the-1-mistake-ecommerce-sites-make-with-activity-7466016740032819200-1Txv](https://www.linkedin.com/posts/freddiechatt_the-1-mistake-ecommerce-sites-make-with-activity-7466016740032819200-1Txv)
12. Freddie Chatt, LinkedIn, 30 May 2026 — “10 signs that your ecommerce website may have SEO problems.” [https://www.linkedin.com/posts/freddiechatt_10-signs-that-your-ecommerce-website-may-activity-7466507467309428736-3Q3F](https://www.linkedin.com/posts/freddiechatt_10-signs-that-your-ecommerce-website-may-activity-7466507467309428736-3Q3F)
13. Freddie Chatt, LinkedIn, 4 June 2026 — “Most content is forgotten the second it’s published.” [https://www.linkedin.com/posts/freddiechatt_most-content-is-forgotten-the-second-its-activity-7468194950720024578-rddU](https://www.linkedin.com/posts/freddiechatt_most-content-is-forgotten-the-second-its-activity-7468194950720024578-rddU)
14. Freddie Chatt, LinkedIn, 5 June 2026 — “I’ve spent the last 6 months trying to automate myself out of my own business.” [https://www.linkedin.com/posts/freddiechatt_ive-spent-the-last-6-months-trying-to-automate-activity-7468557424497553408-9fFf](https://www.linkedin.com/posts/freddiechatt_ive-spent-the-last-6-months-trying-to-automate-activity-7468557424497553408-9fFf)
15. Freddie Chatt, LinkedIn, 17 June 2026 — “One of my products showed up in every single ChatGPT shopping answer I tracked last week.” [https://www.linkedin.com/posts/freddiechatt_one-of-my-products-showed-up-in-every-single-activity-7472937957172211712-wU6](https://www.linkedin.com/posts/freddiechatt_one-of-my-products-showed-up-in-every-single-activity-7472937957172211712-wU6)_
16. Ivan Palii, LinkedIn, 25 May 2026 — “This is the first study on how SEO agencies use Claude for automation.” [https://www.linkedin.com/posts/ivanpalii_how-agencies-use-claude-for-seo-automations-activity-7464596131444846594-jBLV](https://www.linkedin.com/posts/ivanpalii_how-agencies-use-claude-for-seo-automations-activity-7464596131444846594-jBLV)
17. Ivan Palii, LinkedIn, 7 June 2026 — “A pattern that says that such a long query is from an AI prompt tracker, not from a real user.” [https://www.linkedin.com/posts/ivanpalii_a-pattern-that-says-that-such-a-long-query-activity-7469322115637243904-nIKd](https://www.linkedin.com/posts/ivanpalii_a-pattern-that-says-that-such-a-long-query-activity-7469322115637243904-nIKd)
18. Ivan Palii, LinkedIn, 8 June 2026 — “GSC will never build an AI performance tracking report the way it should be.” [https://www.linkedin.com/posts/ivanpalii_gsc-will-never-build-an-ai-performance-tracking-activity-7469719044682797056-OLA7](https://www.linkedin.com/posts/ivanpalii_gsc-will-never-build-an-ai-performance-tracking-activity-7469719044682797056-OLA7)
19. Ivan Palii, LinkedIn, 12 June 2026 — “The worst thing you can do in your AEO strategy is to choose only one metric for tracking AI search visibility.” [https://www.linkedin.com/posts/ivanpalii_how-to-monitor-ai-search-visibility-properly-activity-7471197539103301632-cTh6](https://www.linkedin.com/posts/ivanpalii_how-to-monitor-ai-search-visibility-properly-activity-7471197539103301632-cTh6)
20. Ivan Palii, LinkedIn, 19 June 2026 — “A brand asked if G2’s $3,700 AEO comparison package is worth it.” [https://www.linkedin.com/posts/ivanpalii_a-brand-asked-if-g2s-3700-aeo-comparison-activity-7473632825259323392-occj](https://www.linkedin.com/posts/ivanpalii_a-brand-asked-if-g2s-3700-aeo-comparison-activity-7473632825259323392-occj)
21. Kai Cromwell, LinkedIn, 2 June 2026 — “There’s only one thing to do if you… have a large product catalog…” [https://www.linkedin.com/posts/kai-cromwell_theres-only-one-thing-to-do-if-you-1-activity-7467665942974746624-9Q8a](https://www.linkedin.com/posts/kai-cromwell_theres-only-one-thing-to-do-if-you-1-activity-7467665942974746624-9Q8a)
22. Kai Cromwell, LinkedIn, 5 June 2026 — “99% of SEO campaigns leave money on the table.” [https://www.linkedin.com/posts/kai-cromwell_99-of-seo-campaigns-leave-money-on-the-table-activity-7468519591481319424-mx5l](https://www.linkedin.com/posts/kai-cromwell_99-of-seo-campaigns-leave-money-on-the-table-activity-7468519591481319424-mx5l)
23. Kai Cromwell, LinkedIn, 5 June 2026 — “The most boring SEO campaign in the world made $369k in the last 12 months.” [https://www.linkedin.com/posts/kai-cromwell_the-most-boring-seo-campaign-in-the-world-activity-7468791102972694528-GX6a](https://www.linkedin.com/posts/kai-cromwell_the-most-boring-seo-campaign-in-the-world-activity-7468791102972694528-GX6a)
24. Kai Cromwell, LinkedIn, 12 June 2026 — “You paid $2,000 for an SEO audit. What you got was fleeced.” [https://www.linkedin.com/posts/kai-cromwell_you-paid-2000-for-an-seo-audit-what-you-activity-7470994874130075648-i2I](https://www.linkedin.com/posts/kai-cromwell_you-paid-2000-for-an-seo-audit-what-you-activity-7470994874130075648-i2I)_
25. Kai Cromwell, LinkedIn, 12 June 2026 — “Do this if you sell a $500+ product.” [https://www.linkedin.com/posts/kai-cromwell_do-this-if-you-sell-a-500-product-1-activity-7471056302073569280-c2v-](https://www.linkedin.com/posts/kai-cromwell_do-this-if-you-sell-a-500-product-1-activity-7471056302073569280-c2v-)
26. Mark Williams-Cook, LinkedIn, 26 May 2026 — “Unsolicited #SEO tip: Your SEO audit has no impact unless it is actually implemented correctly…” [https://www.linkedin.com/posts/markseo_seo-activity-7464975887546044417-RPhP](https://www.linkedin.com/posts/markseo_seo-activity-7464975887546044417-RPhP)
27. Mark Williams-Cook, LinkedIn, 28 May 2026 — “Unsolicited #SEO tip: If you're interested in 'GEO', there is a Princeton peer-reviewed paper from 2024…” [https://www.linkedin.com/posts/markseo_seo-activity-7465784114206523393-Z5S4](https://www.linkedin.com/posts/markseo_seo-activity-7465784114206523393-Z5S4)
28. Mark Williams-Cook, LinkedIn, 30 May 2026 — “Casual AI search tool weekend free launch for those paying attention: QueryFan . com.” [https://www.linkedin.com/posts/markseo_casual-ai-search-tool-weekend-free-launch-activity-7466557456635207680-32dL](https://www.linkedin.com/posts/markseo_casual-ai-search-tool-weekend-free-launch-activity-7466557456635207680-32dL)
29. Mark Williams-Cook, LinkedIn, 11 June 2026 — “Unsolicited #SEO tip: Instead of spicy 'probably ok' AI, you can reliably* filter your GSC query data…” [https://www.linkedin.com/posts/markseo_seo-activity-7470766265666580480-FvFN](https://www.linkedin.com/posts/markseo_seo-activity-7470766265666580480-FvFN)
30. Mark Williams-Cook, LinkedIn, 17 June 2026 — “Unsolicited #SEO tip: Google uses TTR (Time To Result) as an internal success metric…” [https://www.linkedin.com/posts/markseo_seo-activity-7472946532959457281-1Hbz](https://www.linkedin.com/posts/markseo_seo-activity-7472946532959457281-1Hbz)
31. Matt Kenyon, LinkedIn, 10 June 2026 — “So many brands lose their way by getting caught in the weeds of SEO/marketing tactics while losing sight of first principles.” [https://www.linkedin.com/posts/matt-kenyon-50959964_so-many-brands-lose-their-way-by-getting-activity-7470444870248349696-uDTa](https://www.linkedin.com/posts/matt-kenyon-50959964_so-many-brands-lose-their-way-by-getting-activity-7470444870248349696-uDTa)
32. Matt Kenyon, LinkedIn, 10 June 2026 — “If your Search traffic has dropped after Google's March/April Core Algo update — STOP CREATING CONTENT FOR A SECOND.” [https://www.linkedin.com/posts/matt-kenyon-50959964_if-your-search-traffic-has-dropped-after-activity-7470505312207413248-rUdE](https://www.linkedin.com/posts/matt-kenyon-50959964_if-your-search-traffic-has-dropped-after-activity-7470505312207413248-rUdE)
33. Matt Kenyon, YouTube — “How to Write SEO Content That Ranks in Google and AI Search.” [https://www.youtube.com/watch?v=QL_fgTOS4pI](https://www.youtube.com/watch?v=QL_fgTOS4pI)
34. Matt Kenyon, YouTube — “How to Get ChatGPT to Recommend Your Brand Over Competitors.” [https://www.youtube.com/watch?v=TsjS69LLKOk](https://www.youtube.com/watch?v=TsjS69LLKOk)
35. Matt Kenyon, YouTube — “ChatGPT, Claude & Gemini Built My SEO Strategy.” [https://www.youtube.com/watch?v=APKFGK85-oE](https://www.youtube.com/watch?v=APKFGK85-oE)
36. Nathan Gotch, LinkedIn, 3 June 2026 — “AI = terrible at SEO.” [https://www.linkedin.com/posts/nathangotch_ai-terrible-at-seo-ai-led-by-experienced-activity-7468049593822281728-pa4I](https://www.linkedin.com/posts/nathangotch_ai-terrible-at-seo-ai-led-by-experienced-activity-7468049593822281728-pa4I)
37. Nathan Gotch, YouTube — “How To Rank SEO Content In Google And AI Platforms.” [https://www.youtube.com/watch?v=AaSyn9YSNYQ](https://www.youtube.com/watch?v=AaSyn9YSNYQ)
38. Nathan Gotch, YouTube — “6 AI SEO Skills That Will Matter Most in 2026.” [https://www.youtube.com/watch?v=mbCfRlY7elM](https://www.youtube.com/watch?v=mbCfRlY7elM)
39. Nicolas Gorroño, LinkedIn, 26 May 2026 — “Everyone is overcomplicating AI SEO.” [https://www.linkedin.com/posts/nico-gorrono_everyone-is-overcomplicating-ai-seo-or-activity-7465069837351014401-NldI](https://www.linkedin.com/posts/nico-gorrono_everyone-is-overcomplicating-ai-seo-or-activity-7465069837351014401-NldI)
40. Nicolas Gorroño, LinkedIn, 6 June 2026 — “If you are using Claude Code for anything important, do not start with ‘just build this.’” [https://www.linkedin.com/posts/nico-gorrono_if-you-are-using-claude-code-for-anything-activity-7469146117503614976-hhR7](https://www.linkedin.com/posts/nico-gorrono_if-you-are-using-claude-code-for-anything-activity-7469146117503614976-hhR7)
41. Nicolas Gorroño, YouTube — “AI SEO Systems for Content Creation, Distribution, Reporting, and Revival.” [https://www.youtube.com/watch?v=uXbEXwSL_7M](https://www.youtube.com/watch?v=uXbEXwSL_7M)
42. Nicolas Gorroño, YouTube — “Google AI Mode and AI Search Content Strategy.” [https://www.youtube.com/watch?v=xbEAH1NzB5c](https://www.youtube.com/watch?v=xbEAH1NzB5c)
43. Nicolas Gorroño, YouTube — “Claude Code Dashboard for SEO, Analytics, and YouTube Data.” [https://www.youtube.com/watch?v=jE7J00zNNHI](https://www.youtube.com/watch?v=jE7J00zNNHI)
44. Steve Toth, LinkedIn, 28 May 2026 — “Profoundly expensive trackers: '$25,000/year to track 200 prompts.'” [https://www.linkedin.com/posts/stevetothjr_profoundly-expensive-trackers-25000year-activity-7465749165684178944-BHbb](https://www.linkedin.com/posts/stevetothjr_profoundly-expensive-trackers-25000year-activity-7465749165684178944-BHbb)
45. Steve Toth, LinkedIn, 2 June 2026 — “'95% of our citations come from third-party content. So why bother creating our own?'” [https://www.linkedin.com/posts/stevetothjr_seonotebook-ainotebook-activity-7467561003183050752-dh2B](https://www.linkedin.com/posts/stevetothjr_seonotebook-ainotebook-activity-7467561003183050752-dh2B)
46. Steve Toth, LinkedIn, 10 June 2026 — “AI Tip: Before you run out of context window, make Claude write the SOP for the all the hard work you just put in.” [https://www.linkedin.com/posts/stevetothjr_ai-tip-before-you-run-out-of-context-window-activity-7470459834891395073-umZM](https://www.linkedin.com/posts/stevetothjr_ai-tip-before-you-run-out-of-context-window-activity-7470459834891395073-umZM)
47. Steve Toth, LinkedIn, 12 June 2026 — “I built a GPT/Claude Project that grades any page against Google's own 32 helpful-content questions.” [https://www.linkedin.com/posts/stevetothjr_i-built-a-gptclaude-project-that-grades-activity-7471184588908785665-26rR](https://www.linkedin.com/posts/stevetothjr_i-built-a-gptclaude-project-that-grades-activity-7471184588908785665-26rR)
48. Steve Toth, LinkedIn, 18 June 2026 — “AI citable content and 'old school' featured snippet optimization share the same structural rule.” [https://www.linkedin.com/posts/stevetothjr_seonotebook-ainotebook-activity-7473358900809883648-yaP](https://www.linkedin.com/posts/stevetothjr_seonotebook-ainotebook-activity-7473358900809883648-yaP)_

