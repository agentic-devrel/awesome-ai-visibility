# Awesome AI Visibility

## AI Visibility Playbook

- [ ] **Publish `llms.txt` (emerging convention)**
  - Add `/llms.txt` that maps to canonical docs, API references, examples, and changelogs.
  - Treat `llms.txt` as an emerging convention, not a replacement for crawlability, indexing, or SEO fundamentals.

- [ ] **Publish machine-readable documentation and API specifications**
  - Keep docs in accessible HTML/Markdown with stable URLs.
  - Publish OpenAPI, AsyncAPI, GraphQL schema, SDK docs, and versioned references when applicable.

- [ ] **Use retrieval-friendly content structure**
  - Use descriptive `H1`–`H3` headings.
  - Keep each section focused on one question or task.
  - Make sections understandable when retrieved independently.
  - Include relevant product/API/version terminology in context.
  - Split at natural semantic boundaries rather than arbitrary token or word limits.
  - Keep code, prerequisites, explanation, and expected output together.
  - Avoid ambiguous references whose subject may be lost.
  - Test retrieval quality rather than assuming smaller chunks perform better.
  - Treat chunking-friendly formatting as a documentation/retrieval quality practice, not a proven AI-search ranking factor.

- [ ] **Create answer-ready content and executable examples**
  - Answer common developer questions directly (what it does, when to use it, trade-offs).
  - Provide quickstarts, troubleshooting, migration guides, and runnable examples with expected output.

- [ ] **Improve technical discoverability**
  - Maintain `robots.txt`, XML sitemaps, canonical URLs, and clean internal linking.
  - Return correct status codes and ensure key content is server-rendered and crawlable.

- [ ] **Add structured metadata and consistent entity/product signals**
  - Use consistent product/org names, URLs, and descriptions across docs, repos, and registries.
  - Add accurate structured metadata (for example JSON-LD) where it helps disambiguation.

- [ ] **Improve GitHub repository quality and metadata**
  - Keep README setup/usage current; add topics, releases, tags, contribution and security guidance.
  - Link packages/SDKs back to canonical documentation.

- [ ] **Publish trustworthy sources and reproducible technical claims**
  - Prefer verifiable claims with methodology, dates, limitations, and reproducible steps.
  - Update or remove stale technical content.

- [ ] **Distribute through developer ecosystems**
  - Publish and maintain packages, SDKs, integrations, templates, and reference apps in relevant channels.

- [ ] **Measure and iterate**
  - Track prompts, mentions, citations, accuracy, and source usage across models over time.
  - Re-test after releases and documentation updates; improve weak source pages first.
