Use this skill whenever the user wants to write, create, draft, or generate a blog post or article. Trigger on phrases like "write a blog", "create a blog post", "draft an article", "write content for", "write a post about", or any request to produce SEO-optimised written content. Also trigger when the user provides keywords, a topic, or a content brief and asks for written output. This skill ensures every blog follows Cutover's brand voice, SEO best practices, keyword usage rules, correct structure, and a punchy tone — always ending with a CTA and FAQ section.Blog Creation Skill
Produce well-structured, SEO-optimised blog posts that are punchy, direct, and on-brand for Cutover. Follow every rule below without exception.

Step 1 — Gather Inputs (if not already provided)
Read all three reference files before writing:

references/keywords.md — all tracked Cutover keywords by category, search volumes, rankings, and validated internal link URLs
references/messaging.md — approved messaging: hero statements, pain points, value props, proof points, product positioning, and words to avoid
references/examples.md — example blogs and scripts showing Cutover's hook style, analogy bank, tone patterns, structure, and what to avoid. Mirror these when writing

Use references/keywords.md to:

Suggest the best primary keyword for the topic (high volume + weak/no current rank = biggest opportunity)
Select relevant secondary keywords from the same or adjacent categories
Identify the right internal link URLs (use the "Key Internal Link Destinations" table)

Before writing, confirm you have:

Primary keyword (H1 keyword) — the top keyword to use 6–8 times throughout
Secondary keywords — each used 1–2 times throughout
Internal links — URLs from cutover.com (blogs, webpages, videos, resources); at least one, ideally within first ~200 words; highest-value link goes nearest the top
External links — 0–2 maximum; omit unless clearly valuable
CTA — what action should the reader take? (e.g. "Book a demo", "Read our guide", "Watch the video"). If not provided, ask the user before writing
Target word count — default to 700–1200 words if not specified
Topic / angle — what the post is about and who it's for

If any of these are missing, ask the user before writing.

Step 2 — Structure Rules
Every blog must follow this structure:

H1 Title — include the primary keyword; make it compelling and direct
Introduction (no subheading) — hook the reader in 2–4 sentences; include the top internal link and primary keyword within the first ~200 words
Body Sections — 3–6 sections, each with an H2 or H3 subheading that includes a keyword where natural; must include at least one of: bullet list, numbered list, or table
FAQ Section — always include at the bottom of the body (before the CTA); minimum 3 questions relevant to the topic and reader
CTA Section — final section with a clear, direct call to action linking to a cutover.com page (demo, resource, product page, etc.)


Step 3 — Keyword Rules

Primary keyword: use 6–8 times across the full post, including in the H1, at least one subheading, and the intro
Secondary keywords: use each 1–2 times; spread naturally across sections
Keywords can be split or reordered for natural flow — e.g. "IT DR plan steps" → "steps to building an IT DR plan" still counts
Prioritise the reader's experience: if a keyword placement feels forced or unnatural, reword the sentence
Use as many secondary keywords as possible within the 1–2 usage rule — don't leave them on the table


Step 4 — Link Placement Rules

All internal links must go to cutover.com — blogs, product pages, videos, guides, webinars, etc.
Place the highest-value internal link as early as possible — ideally within the first 200 words
All other internal links can appear throughout the body and FAQ
Limit external links to 1–2 maximum; omit entirely if not clearly valuable
The CTA link must always go to a cutover.com destination


Step 5 — Cutover Brand Voice & Tone
Use references/messaging.md for approved language and references/examples.md for tone, hook style, and analogy patterns. Pull value statements, pain points, proof points, and positioning directly from the messaging file. Never invent stats — only use the verified proof points listed there.
Write in Cutover's brand voice at all times. The five voice pillars are:

Expert — speak with authority; use specific examples; explain complex things simply; echo the reader's terminology
Clear — no jargon; precise structure; plain language; short sentences; active voice
Authentic — warm, human, and passionate; avoid being robotic or overly formal
Visionary — confident and optimistic; inspire the reader to think bigger
Accountable — provide useful, practical information; make the reader feel supported

Language rules (US English):

Use: organize, program, defense, revenue, resume
Serial comma before "and" when listing 3+ items
Em dashes with no spaces — like this
No period at the end of bullet points
No corporate slang: avoid "circle back," "touch base," "workshopping ideas"

Words and phrases to avoid (Cutover differentiators — do not use these to describe what Cutover does):

Projects / project management
Task management
Work(flow) management

Tone in practice:

✅ "Change is complex but critical. To stay successful, organizations need to adapt, transform, and manage perceived risks."
❌ "Successfully executing big change delivers the steps organizations need to get their strategy into action and get ahead. Each organization's ability to transform to adapt to present and future requirements is critical to its success."
✅ "Deliver change faster with a clear plan of action, visible to everyone who's involved."
❌ "Optimize change windows through greater predictability of delivery and the provision of an early enterprise view of planned activities."


Step 6 — Word Count

Target: 700–1200 words (excluding SEO summary note)
Aim for ~900 words unless specified otherwise
Every sentence must earn its place — no padding


Step 7 — CTA Section Rules

Always the final section of the blog
Keep it short: 2–3 sentences max + a clear linked CTA
Match the CTA to the blog topic (e.g. a DR blog → link to the DR product page or a demo)
Use positive, action-oriented language: "See how Cutover can help", "Book a demo today", "Read our guide"
Link must go to cutover.com


Step 8 — FAQ Section Rules

Always include immediately before the CTA section
Minimum 3 questions; maximum 6
Questions should reflect what the target reader (Head of Resilience, Head of Infrastructure & Operations, CISO) would genuinely ask
Answers should be 2–4 sentences — concise, expert, and useful
Format: ### Frequently Asked Questions as the heading, then **Q: ...** followed by the answer on the next line


Step 9 — Final Check Before Delivering
Before outputting the blog, verify:

 Primary keyword appears 6–8 times
 Each secondary keyword appears 1–2 times
 H1 contains primary keyword
 At least one subheading contains a keyword
 Highest-value internal link is within the first ~200 words
 All internal links go to cutover.com
 External links ≤ 2
 At least one bullet list, numbered list, or table in the body
 FAQ section included (3–6 Qs) before the CTA
 CTA section included at the end, linking to cutover.com
 Word count is within 700–1200 words
 Tone matches Cutover voice: expert, clear, authentic, visionary, accountable
 No banned vocabulary used (project management, task management, workflow management, corporate slang)
 US English spelling and punctuation throughout


Output Format
Deliver the blog post in clean Markdown:

# H1 Title
## H2 Subheadings
### H3 Subheadings (if needed)
Bullet lists with -
Tables using standard Markdown table syntax
FAQ heading: ### Frequently Asked Questions, then **Q: ...** + answer
CTA as a final ##  section

After the blog, include a brief SEO summary note (always include this):

Primary keyword count
Secondary keywords used and count
Internal link placement notes
Word count
CTA destination
Any flags or suggestions for improvement
