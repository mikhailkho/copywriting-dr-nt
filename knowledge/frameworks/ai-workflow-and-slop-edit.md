# The AI-Era Workflow and the Anti-Slop Edit

This file is the "neo" half of neo-traditionalism: how to use Claude (or any LLM) so the classic principles actually show up in the output.

## 1. What AI is good at and bad at (in this domain)

| Strong | Weak / risky |
|---|---|
| Producing many variants quickly | Knowing which facts are true (it will invent plausible specifics) |
| Restructuring copy into a chosen skeleton | Original mechanisms and insights from nothing |
| Extracting themes/language from large volumes of reviews/transcripts | Estimating real conversion effects |
| Editing for clarity, rhythm, length | Authentic voice and lived stories |
| Checking against checklists, spotting objections | Understanding legal/regulatory nuance in your jurisdiction |
| Drafting tests, plans, briefs | Making strategy decisions with incomplete data |

**Default failure mode: regression to the mean.** Left alone, an LLM writes the average of the internet: fluent, balanced, abstract, safe. Hopkins, Halbert, Caples and Schwartz all describe exactly the opposite of that.

## 2. The NT human-in-the-loop workflow

```
INTAKE       → fill the brief; list unknowns  (human supplies facts)
RESEARCH     → code voice-of-customer; BFD; objections; proof inventory
DIAGNOSE     → awareness × sophistication; mass desire; competitor claim map
IDEA         → Big Idea Card; mechanism type; proof ceiling   (human chooses)
OFFER        → proposition, guarantee, bonus, reason why, real scarcity
DRAFT        → one skeleton; long first; lead variants by archetype
EDIT         → strategic → style → passion → clarity → anti-slop
VERIFY       → fact/claim substantiation; compliance gate; source tags
TEST PLAN    → hypotheses, tracking, success metric
LOG          → results file updated after the test
```
Each arrow is a checkpoint where Claude should show its work and a human can veto.

## 3. Prompting rules for NT copy
1. **Provide facts, don't ask it to find them.** Paste product facts, customer quotes, numbers. If missing, say "unknown" and let Claude flag gaps.
2. **Require source tags** in drafts: `{S1}` etc. Unsourced numbers are rejected.
3. **Give the diagnosis** (audience, awareness, sophistication, desire, idea, offer). Don't ask for "compelling copy."
4. **Constrain the format:** channel, length, reading level, sentence-length range, banned phrases (see §5).
5. **Ask for variants that differ in idea/angle**, not paraphrases.
6. **Use roles for critique:** "Act as a skeptical buyer in <market>" / "regulator" / "Hopkins' salesperson test" — then verify with real data.
7. **Separate generation from judgment** (Bly's two stages): generate first, critique second, in separate steps.
8. **Temperature/variation:** explore broadly early, tighten late.
9. **Don't let the model self-grade as evidence.** Self-ranking is an opinion test.

## 4. Tells of AI-flavoured copy (and what to do)

| Tell | Why it fails | Fix |
|---|---|---|
| Opening with scene-setting platitudes ("In today's fast-paced world…", "Imagine a world where…") | Generic; reader opts out | Start with the reader's specific situation or the promise |
| Abstract nouns and verbs ("unlock", "elevate", "streamline", "leverage", "seamless", "transform", "empower", "cutting-edge", "game-changer") | Unfalsifiable; sophistication stage 1 | Replace with concrete outcomes, numbers, actions |
| Stock contrast frames ("It's not X — it's Y", "Not just A, but B") used repeatedly | Template feel | Use once if at all; state the claim directly |
| Triplets and perfect parallelism everywhere ("faster, smarter, better") | Rhythm sameness | Vary rhythm; use the most specific item only |
| Over-polished, balanced hedges ("can help", "may improve", "designed to") | Weakens belief; reads as lawyered | Say what it does, with proof; keep legally needed qualifiers precise |
| Uniform sentence length and paragraph shape | Hypnotic sameness | Mix short and long; fragments; one-line paragraphs sparingly |
| Em-dash and colon patterns repeated | Signature tell | Vary punctuation; cut |
| Vague social proof ("Thousands of happy customers") | No specificity | Real counts, named sources, quotes |
| Fake-personal anecdotes ("I remember when…") | Fabrication | Only real stories supplied by the user |
| Generic benefit lists with no hierarchy | Tossed salad | Pick one primary benefit; rank the rest |
| Closers like "Ready to take the next step?" | Empty CTA | Specific instruction, what happens next, what they get |
| Over-use of rhetorical questions | Annoying | Use for curiosity only when answer is strong (Whitman) |
| Emoji/hype punctuation in a serious category | Credibility loss | Match the audience |

## 5. Anti-slop edit — pass sequence
Run in order; each pass is separate.

1. **Specificity pass (Hopkins/Whitman):** highlight every abstract claim; replace with a number, name, scene or process step; delete if none exists.
2. **Mechanism & proof pass (Schwartz/Brown):** where does the reader ask "how?" and "who says so?" — is it answered right there?
3. **One-idea pass (Masterson/Forde):** circle anything not serving the single idea; cut.
4. **Salesperson test (Hopkins):** would a salesperson say this to a half-sold person? Cut cleverness.
5. **Voice pass:** read aloud (Halbert/Caples); fix every stumble; vary rhythm; use the audience's own words from the language bank.
6. **Sentence-length pass (Bly):** average 6–16 words in ads/email; allow outliers.
7. **Eye-relief & scan pass (Kennedy):** read only headings/bullets — does the offer survive?
8. **Cut pass:** remove 10–20% (redundancies, qualifiers, windups).
9. **Ethics/compliance pass:** claims substantiated; no fake urgency; no invented stories.
10. **Final cold read next day** (Caples #1).

## 6. Banned/controlled phrase list (starter; customise per brand)
Controlled (allowed only with concrete support): "revolutionary", "world-class", "best-in-class", "cutting-edge", "game-changing", "unlock", "supercharge", "seamless", "next-level", "unparalleled", "guaranteed results" (unless a real guarantee), "proven" (unless proof is cited), "scientifically" (unless study cited), "no-brainer", "once-in-a-lifetime".
Banned patterns: fake urgency, invented scarcity, invented customer names/quotes/statistics, medical/financial outcome promises without substantiation.

## 7. Use AI for what it's best at in this workflow
- **Coding VOC** and extracting language.
- **Variant explosion** from a fixed diagnosis (20 hooks across 6 lead archetypes).
- **Objection mining** and drafting objection-answer pairs that humans then ground in proof.
- **Format conversion:** same idea → email, landing page, ad, script, social post, outreach.
- **Editing assistants:** cut to length, adjust reading level, harmonise voice.
- **QA checklist runs** (4 U's, 46-point checklist, compliance prompts).
- **Test planning and results synthesis.**

## 8. What must stay human
Facts and permissions · choice of the Big Idea · story ownership and testimonials · price/offer decisions · legal/compliance sign-off · final taste · launch decisions.

## 9. Risk controls
- Keep an **assumption log** (every claim: source, owner, status).
- **Data hygiene:** don't paste personal data or confidential material into tools without authorisation.
- **IP:** don't reproduce copyrighted ads/books; use principles and your own words.
- **Disclosure:** follow platform/regulator rules on AI-generated content, endorsements, and advertising disclosures where applicable.
