
---
name: linkedin-post-writer
description: "Create original, high-quality LinkedIn posts for personal brands, founders, executives, professionals and businesses across industries. Understand the client's voice, audience, expertise and objective; select an appropriate storytelling structure from the existing 20 hook formulas; develop compelling hooks; write, refine and quality-check posts. Use for new LinkedIn posts, content angles, hooks and post development. For auditing an existing draft, use linkedin-humanizer --mode audit."
---

# LinkedIn Post Writer

## Purpose

Create distinctive, credible and engaging LinkedIn content that sounds like the person or brand it represents.

The goal is not simply to produce posts that look like LinkedIn content. The goal is to communicate a meaningful idea in a way that earns the intended audience's attention, trust and interest.

This skill supports personal brands, founders, executives, consultants, employees, creators and organisations across industries.

It must adapt to the subject and author rather than forcing every client into one writing style.

## When to use

- The user wants a new LinkedIn post.
- The user has an idea that needs a compelling angle.
- The user wants help selecting a hook or storytelling structure.
- The user wants multiple approaches to the same topic.
- The user wants a post developed from an interview, story, article, research brief or other source.
- The user wants a post adapted for a particular audience or business objective.

For an existing draft that primarily needs editing or auditing, use `linkedin-humanizer --mode audit`.

## Core principles

1. Audience relevance comes before clever writing.
2. A strong idea matters more than a clever hook.
3. The hook must accurately represent what the post delivers.
4. Specificity must come from real information, not invented details.
5. Storytelling should make the idea easier to understand, not distract from it.
6. The client's natural voice takes priority over generic LinkedIn conventions.
7. Content should be original, useful and credible.
8. Engagement is valuable only when it comes from genuine reader interest.
9. Do not promise virality, reach, rankings or a particular engagement result.
10. Never sacrifice accuracy or trust for an attention-grabbing opening.

## Step 1: Understand the author

Before drafting, inspect the available client context.

### Voice profile

If `../../references/voice-profile.md` has `filled: yes`, read it and follow its:

- Tone and personality.
- Vocabulary and preferred expressions.
- Sentence length and rhythm.
- Communication style.
- Opinions and professional positioning.
- Writing preferences and prohibited patterns.
- CTA and link preferences.

Do not imitate another client's voice.

If no completed voice profile exists, use the available writing samples and conversation context. If there is insufficient information, mention that a voice profile can be created using `linkedin-humanizer --mode profile`, then proceed without pretending the voice has been fully established.

### Story Bank

If `../../references/story-bank.md` has `filled: yes`, use relevant verified stories, experiences, milestones, failures, decisions, numbers and examples.

Never invent:
- First-person experiences.
- Client results.
- Revenue figures.
- Personal struggles.
- Customer testimonials.
- Dates, quotations or business milestones.

If a story would materially improve the post but the required facts are missing, ask the user for them or suggest using `linkedin-interviewer`.

### Founder mode

If the author is a founder and the topic concerns their founder experience, inspect `../../references/founder-topics.md`.

Use the relevant A1-A10 angle where appropriate. Do not force founder-specific angles onto professionals, employees or brands for whom they are irrelevant.

### Interview spine

If `linkedin-interviewer --mode post` provides a five-line spine (Moment, Number, Correction, Opposition, Ask), use it as the foundation.

Do not ask again for information already provided. Do not fill missing fields with invented details.

## Step 2: Understand the audience

Identify the intended reader before choosing the hook.

Consider:

- Who is the reader?
- What industry or professional context are they in?
- What problem, ambition or question matters to them?
- What do they already know about this topic?
- What misconception or knowledge gap could the post address?
- Why would this particular author be credible discussing it?

Do not assume every post is intended for a broad audience.

Prefer a specific audience and a meaningful problem over generic statements intended to appeal to everyone.

If the audience is unclear and materially affects the post, ask one concise clarification.

## Step 3: Establish the content objective

Identify the primary purpose of the post.

Possible objectives include:

| Objective | What the post should achieve |
|---|---|
| Authority | Demonstrate expertise and informed thinking |
| Trust | Show judgement, experience and credibility |
| Education | Explain a useful concept or process |
| Discussion | Introduce a meaningful question or perspective |
| Reach | Make an idea relevant and accessible to more readers |
| Reposts | Present an insight worth sharing |
| Saves | Give readers a useful reference or framework |
| Inbound opportunities | Help the right audience understand the author's value |
| Personal connection | Communicate a genuine experience or perspective |
| Brand awareness | Build recognition around a relevant subject or point of view |

Choose one primary objective. A post may have secondary benefits, but it should not try to achieve everything at once.

## Step 4: Develop the content angle

Before writing the hook, identify the central idea.

Explore suitable approaches:

- Personal experience or lesson.
- An overlooked industry observation.
- A misconception worth challenging.
- A practical explanation.
- A comparison between two approaches.
- A researched insight.
- A professional opinion supported by reasoning.
- A customer or audience problem.
- A decision, mistake or turning point.
- A useful framework or process.
- A prediction, clearly labelled as an opinion when appropriate.

Choose an angle that combines audience relevance with the author's actual knowledge or experience.

Avoid repeating common advice without adding a useful perspective.

## Step 5: Select a hook formula

Read `../../references/hook-formulas.md`.

The reference contains 20 hook structures, F1-F20. Preserve their original names, skeletons, caveats and intended uses.

Use the engagement-goal split and topic-selection guidance in that file.

The formulas are creative structures, not guaranteed performance mechanisms.

Select a formula based on:

1. The subject.
2. The author's voice.
3. The intended audience.
4. The content objective.
5. The evidence or story available.
6. The natural narrative structure.

Do not force a formula when the topic does not suit it.

### Hook development process

Generate 10 original hook options by default.

Where useful, vary the approach:
- Specific observation.
- Story-led opening.
- Contrarian perspective.
- Number-led opening.
- Curiosity grounded in a real detail.
- Problem-led opening.
- Comparison.
- Clear educational promise.

Use the existing formulas as inspiration, not as templates to fill mechanically.

Rank the strongest three using this editorial assessment:

| Criterion | Question |
|---|---|
| Audience relevance | Will the intended reader care? |
| Specificity | Does the opening communicate something concrete? |
| Curiosity | Does it create a genuine reason to continue? |
| Credibility | Can the author support the claim? |
| Originality | Does it avoid sounding generic or copied? |

Give each criterion a score from 1 to 5. This is an editorial comparison, not a prediction of reach.

Show the recommended hook and briefly explain why it is the best fit. Do not make the user choose from 10 options unless they ask to.

## Step 6: Build the narrative

Construct the post around one central idea.

Choose the structure that best serves the content.

Possible structures:

### Story-led
Opening moment → context → tension or challenge → turning point → insight.

### Educational
Problem → explanation → example → practical understanding → conclusion.

### Opinion-led
Position → reasoning → evidence or example → implications → conclusion.

### Contrarian
Common belief → credible disagreement → supporting reasoning → qualification → takeaway.

### Research-led
Observation → sourced evidence → interpretation → limitations → implication.

### Framework-led
Problem → named framework → steps → example → practical application.

### Comparison-led
Two approaches → meaningful difference → consequences → conclusion.

These are options, not mandatory templates. Use a natural structure rather than mechanically following every stage.

## Step 7: Write the post

### Writing standards

- Write in the author's established voice.
- Use clear, natural and professional language.
- Prefer concrete explanations over abstract business language.
- Make complex ideas understandable without making them inaccurate.
- Use transitions that sound natural.
- Vary sentence length organically.
- Use paragraphs that are comfortable to read on mobile.
- Keep the opening promise and the actual content aligned.
- Give the reader a meaningful takeaway.
- Use personal details only when they are verified and relevant.

### Length

Follow the user's requested length.

If no length is specified, choose a suitable length based on the complexity of the idea. Do not stretch a simple point to meet a sentence or character target.

LinkedIn's current character limits and formatting capabilities should be checked when they materially affect the requested output.

### Calls to action

Use a CTA only when it serves the post.

Possible endings include:
- A thoughtful question.
- An invitation to share an experience.
- A practical next step.
- A concise conclusion.
- A relevant invitation to connect or learn more.

Avoid repetitive engagement-bait questions and generic requests to tag people.

### Hashtags and links

Use relevant hashtags sparingly when appropriate.

Do not add hashtags merely to fill space.

Follow the client's link preferences. If a link is better placed separately, explain the recommendation rather than treating external links as universally prohibited.

## Step 8: Research and factual accuracy

When the post contains factual or time-sensitive claims, use the available research capability where appropriate.

For every important claim:

- Identify whether it is a fact, opinion, interpretation or prediction.
- Verify statistics and dates against credible sources when research is available.
- Preserve the meaning of quoted or cited information.
- Do not invent research, studies or source references.
- Do not present correlation as causation.
- Do not imply that an illustrative example is a real case.
- Flag claims that could not be verified.

For regulated or sensitive industries, avoid unsupported professional, medical, legal or financial claims. Respect the client's applicable compliance and editorial requirements.

If the post is based solely on user-provided information, distinguish that information from independently verified research.

## Step 9: Humanizer pass

Use the relevant guidance from `linkedin-humanizer` and `references/humanizer-checklist.md`.

Review for:

- Generic AI-sounding phrases.
- Repetitive sentence structures.
- Unnatural transitions.
- Overly polished corporate language.
- Empty motivational statements.
- Repetitive rhetorical contrasts.
- Excessive fragments and artificial one-line paragraphs.
- Unnecessary adjectives and jargon.
- Repetitive CTAs.
- Manufactured vulnerability.
- Claims that sound more certain than the evidence allows.

Preserve strong original expressions and the author's natural personality.

Do not add fabricated personal details to make the post appear human.

## Step 10: Quality check


Every post must be evaluated for both LinkedIn search discoverability and feed engagement potential.

These are separate objectives. Optimising one does not guarantee the other.

### A. LinkedIn Search Optimisation

Before drafting:

1. Identify the main subject of the post.
2. Identify the primary keyword a relevant reader might search for.
3. Identify 3-5 closely related secondary keywords.
4. Identify the search intent:
   - Informational
   - Problem-solving
   - Comparison
   - Educational
   - Professional or industry-specific
5. Understand the terminology used by the intended audience.

While writing:

- Introduce the main topic naturally near the beginning.
- Use relevant keywords in the opening and body where appropriate.
- Include natural variations and related terminology.
- Make the subject of the post immediately understandable.
- Use descriptive language rather than vague or ambiguous references.
- Maintain consistency with the author's professional positioning.
- Use relevant hashtags sparingly, only where they add value.

Never:

- Stuff keywords into sentences.
- Add unrelated trending keywords.
- Repeat phrases unnaturally.
- Sacrifice readability for search optimisation.
- Claim a post will rank first or guarantee a particular search position.

### B. Viral Content Engineering

Treat virality as an objective to optimise for, not a guaranteed outcome.

For every post, evaluate five stages:

1. STOP: Does the opening give the intended reader a compelling reason to pause?
2. RETAIN: Does the next section reward the reader for continuing?
3. ENGAGE: Does the content create an insight, emotional connection, useful lesson or meaningful disagreement?
4. REMEMBER: Is there a distinctive idea, example or conclusion worth remembering?
5. SHARE: Would someone have a genuine reason to send or repost this content?

Use the existing 20 hook formulas in `references/hook-formulas.md`.

Study successful content structures, but never copy another creator's post or distinctive wording.

Prefer:
- Specific and original observations.
- Strong storytelling with genuine stakes.
- Unexpected but defensible insights.
- Evidence-backed contrarian opinions.
- Practical frameworks and explanations.
- Relevant industry developments.
- Real experiences and lessons.
- Memorable conclusions.

Avoid:
- Manufactured controversy.
- Fake personal stories.
- Unsupported statistics.
- Empty motivational content.
- Artificial engagement bait.
- Misleading hooks.
- Recycled viral templates without original insight.

### C. Pre-Publication Scoring

Score each draft out of 100.

SEARCH DISCOVERABILITY — 25 POINTS
- Keyword relevance: 10
- Search intent alignment: 5
- Topic clarity: 5
- Natural keyword integration: 5

VIRAL CONTENT POTENTIAL — 40 POINTS
- Hook strength: 10
- Audience relevance: 10
- Storytelling and retention: 10
- Originality and shareability: 10

EDITORIAL QUALITY — 35 POINTS
- Author voice: 10
- Accuracy and credibility: 10
- Readability: 5
- Meaningful conclusion: 5
- Overall audience value: 5

A score of 85 or higher is the preferred editorial target.

If a draft scores below 85, identify its weakest areas and improve it before presenting it.

The score is an internal editorial benchmark, not a prediction of search position, impressions or virality.

### D. Performance Learning Loop

When actual LinkedIn analytics are available:

- Compare impressions and engagement across posts.
- Examine comments, reposts and other available engagement indicators.
- Identify which topics and formats resonate with the intended audience.
- Identify which hooks and storytelling structures perform well.
- Compare results across multiple posts rather than drawing conclusions from one post.
- Update future content recommendations using observed evidence.

Never invent performance data or claim an improvement without evidence.

## Search Discoverability and Viral Potential Engine

## Step 11: Present the output

Unless the user requests a different format, provide:

1. **Content angle:** One sentence explaining the chosen approach.
2. **Recommended hook:** The strongest opening.
3. **Hook alternatives:** Two additional options.
4. **Final LinkedIn post:** The complete draft, ready for review.
5. **Editorial notes:** Briefly explain the formula, objective and any important factual limitations.

When multiple genuinely different approaches would help, offer alternatives such as:
- Intellectual and analytical.
- Storytelling and personal.
- Educational and practical.
- Opinion-led and thought-provoking.

Do not generate unnecessary versions when one strong draft is sufficient.

## Step 12: Approval and publishing

The user must review and explicitly approve the final content before publishing or scheduling.

Never publish, schedule, edit a live post or cancel a scheduled post without the user's explicit instruction for that action.

If the existing publishing integration is configured and available, follow its documented workflow.

Use the existing `lib.publish` and `lib.unpublish` functions only when their implementation and required parameters are available.

If publishing functionality is unavailable, provide the final post for manual publishing. Never claim that a post has been published or scheduled without confirmation from the publishing tool.

## Agency mode: multiple clients

This skill must support multiple ghostwriting clients.

For every client:

- Use only that client's approved voice profile and Story Bank.
- Keep client facts, experiences, opinions and examples separate.
- Do not transfer one client's personal stories to another client.
- Do not assume the agency owner's voice is the client's voice.
- Respect client-specific industries, audiences, positioning and compliance boundaries.
- Record feedback as a client-specific preference when the available workflow supports it.
- Never invent expertise or credentials for a client.

If the active client is unclear, ask which client the content is for before using client-specific information.

## Hard rules

- Never fabricate personal experiences, numbers, statistics, sources or testimonials.
- Never copy another creator's post or distinctive wording.
- Never promise virality, guaranteed reach or first-place search ranking.
- Never use a hook that the post fails to deliver on.
- Never force vulnerability into a post.
- Never force founder angles onto unrelated authors.
- Never sacrifice factual accuracy for engagement.
- Never use a formula simply because its historical reference number looks impressive.
- Never publish without explicit user approval.
- Never mix the information or voice profiles of different clients.

## Resources

- `../../references/hook-formulas.md` — 20 hook structures, examples, selection guidance and caveats.
- `../../references/founder-topics.md` — founder-specific content angles A1-A10.
- `../../references/voice-profile.md` — author voice and brand profile.
- `../../references/story-bank.md` — verified stories, milestones and experiences.
- `../../references/algorithm-heuristics.md` — platform and content heuristics; treat evidence according to its source and date.
- `../../references/industry-benchmarks.md` — industry-specific reference material where relevant.
- `references/humanizer-checklist.md` — humanizer review guidance.

## Related skills

- `linkedin-humanizer` — voice refinement and draft auditing.
- `linkedin-hook-extractor` — analysis of existing hooks and reusable structures.
- `linkedin-interviewer` — extraction of personal stories and expertise.
- `linkedin-content-planner` — strategic content planning.
- `linkedin-repurposer` — adapting existing material into LinkedIn content.
