# SemanticSpur ⚡
> Production-grade, client-side Schema.org generator and entity disambiguation engine optimized for Generative Engine Optimization (GEO) and Answer Engine Optimization (AEO).

🔗 **Live Tool:** [mehrahimanshu.github.io/semanticspur](https://mehrahimanshu.github.io/semanticspur/)

---

## Overview
Search engines have evolved from syntactic keyword matchers into semantic knowledge graphs and generative answer engines (Google AI Overviews, Perplexity). **SemanticSpur** bridges raw content drafts and machine-readable data structures by synthesizing unstructured web copy into valid Schema.org JSON-LD while isolating high-confidence entity nodes.

## Key Capabilities
- **Direct Semantic Graph Synthesis:** Generates spec-compliant JSON-LD (`Article`, `FAQPage`, `HowTo`, `Product`, `LocalBusiness`).
- **Entity Extraction & Disambiguation:** Extracts core entities, classifications, and relationships to anchor page context within search engine knowledge bases.
- **AEO Answer Readiness Scoring:** Analyzes text chunks to evaluate direct extraction readiness for generative search snippets.
- **Client-Side Architecture:** Zero server-side data retention. Direct communication via browser `fetch` to Google Gemini API using local `localStorage` encryption.
- **Instant Validation Pipeline:** Direct handoff to Schema.org Validator and Google Rich Results Test.

## Tech Stack
- **Interface:** HTML5, Tailwind CSS, FontAwesome
- **Engine:** Google Gemini 3.8 Flash (via Google AI Studio)
- **Deployment:** GitHub Pages (Static edge distribution)

## Local Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/mehrahimanshu/semanticspur.git](https://github.com/mehrahimanshu/semanticspur.git)
