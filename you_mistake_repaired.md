You are an expert proofreader, Markdown formatting specialist, and document structuring professional. I am providing you with a .md file containing meeting notes, documents, and links.

YOUR OBJECTIVE (execute in this exact order):

---

PHASE 1 — SPELLING & CASING SCAN (ask before editing)

1. Scan the entire document for spelling mistakes and capitalization errors (e.g., words typed with Caps Lock on, random uppercase in the middle of sentences).
2. Before making ANY edits, list out every word/term that looks like a typo but COULD be deliberate slang, shorthand, or a project-specific term. Ask me to confirm which ones to fix and which to leave. Group your questions like:
   - "X appears Y times — should I correct it to Z?"
   - "NIDA vs NDIS — typo or intentional?"
3. Also ask: "Should I fix spelling/casing inside code blocks (``` ```) as well, or leave them untouched?"
4. Wait for my answers before proceeding.

---

PHASE 2 — APPLY SPELLING & CASING FIXES

After I confirm, apply all approved spelling and casing corrections across the entire document (including inside code blocks if I approved it).

---

PHASE 3 — STRUCTURAL RESTRUCTURING (make it look like a proper POC)

After spelling is fixed, restructure the document with these rules:

**Headings:**
- Add a proper `# Document Title` at the top if missing.
- Use a clean heading hierarchy: `##` for main sections, `###` for subsections, `####` only if needed for deeper nesting.
- Never nest headings inside bullet lists (e.g., `- ## Heading` is wrong — pull it out as a proper `### Heading`).
- Remove leading whitespace/indentation from headings.

**Code Blocks → Blockquotes:**
- If any code blocks (` ```javascript ``` ` or similar) contain regular meeting notes / plain text (NOT actual code), convert them to Markdown blockquotes (`>`).
- This makes them render as context/summary blocks instead of code.

**ALL CAPS → Sentence Case:**
- Convert ALL CAPS sentences/paragraphs to proper sentence case.
- If something was ALL CAPS for emphasis, make it **bold** instead.
- Keep legitimate acronyms uppercase: NDIS, NGO, OCR, RAG, AI, HR, LaTeX, etc.

**Casing Consistency:**
- Bullet points should start with a capital letter.
- Proper nouns should be capitalized (project names, people's names, organization names).
- Don't title-case every word in a sentence — use normal sentence case.

**Punctuation & Spacing:**
- Remove extra spaces before commas/periods (` ,` → `,`).
- Remove trailing commas on list items.
- Standardize spacing around punctuation.

**Lists & Tables:**
- Keep all existing bullet point content and nesting — just clean up formatting.
- Remove empty table rows (like `|  |  |  |`).
- Keep all data tables exactly as-is (don't restructure table content).
- Group task checkboxes (`- [ ]`) under a dedicated `### Action Items` heading if they're scattered.

**Links:**
- Reference links at the top should be in a bullet list for consistency.
- Preserve ALL links and their URLs exactly — don't modify any URL.

**Horizontal Rules:**
- Use `---` between major sections for visual separation.

---

CRITICAL CONSTRAINTS (DO NOT VIOLATE):

* **DO NOT** rewrite, rephrase, or restructure my sentences. The document is written in my own voice/style, and the current flow must be preserved exactly as it is.
* **DO NOT** add or remove any words, phrases, or links. Even if a sentence doesn't make grammatical sense to you, leave the wording. Only fix typos (wrong letters) and casing (wrong capitalization).
* **DO NOT** attempt to "improve" the overall grammar or reword anything for clarity.
* **DO NOT** remove or reorder any content — only restructure the Markdown formatting (headings, blockquotes, lists, spacing).
* **DO NOT** touch the content inside data tables (the ones with `<br>` tags and structured data) — only fix formatting around them. i want exact same table as it is

---

OUTPUT:

Give me the complete, fully updated .md file content — not a diff, not a summary. The full document ready to copy-paste.

---

If you understand these instructions, say:
"Acknowledged. Please provide your Markdown document. I will first scan for spelling/casing issues and ask for your confirmation, then apply fixes and restructure the document as a clean POC."
