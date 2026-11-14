# Testing & Measurement — "let the thousands decide what the millions will do"

Sources: Hopkins Ch. 4, 15, 21 (keyed ads, cost per customer, test campaigns); Caples Ch. 7, 18 (LALALAL, opinion vs sales tests); Halbert Ch. 6–9, 22, 24 (staged mailings, RFM, unit economics); Kennedy Step 19 (pretest) and sequences; Bly (test small and cheaply online); Brunson (weekly iteration, live-to-automated).

## 1. Principles
1. **Judge by cost per customer / revenue per visitor / profit per send** — not clicks, likes, or awards.
2. **Test big levers first:** market/list > offer > idea > headline/lead > body > design.
3. **One variable per test**, a control, and a pre-declared success metric and sample size.
4. **Key everything:** unique URLs/codes/UTMs/phone numbers/discount codes so results trace to the source.
5. **Opinion tests are weak evidence** (people prefer clever, picture-ful ads; dislike appeals that embarrass them; split votes distort). Use them to screen, never to decide.
6. **Learn → adapt → learn (LALALAL).** Log every test and result.
7. **Test small, then scale** (Hopkins: a few towns; Halbert: 1–5k pieces then 20–100k then rollout; Kennedy: 45–60-day sequences).
8. **Protect the control.** New challengers must beat it on the primary metric with enough evidence.

## 2. Unit economics first (Halbert's back-of-envelope)
```
Revenue per order       = price (+ shipping)
– Fulfilment/COGS       = ...
= Contribution per order
Orders per 1,000 impressions/contacts = response rate × 1,000
Contribution per 1,000  = contribution per order × orders
– Cost per 1,000 (media/list/send)
= Profit (loss) per 1,000
```
Add: refund/chargeback rate, repeat purchase rate, customer lifetime value, payback period. Decide the maximum allowable cost per acquisition **before** you spend.

## 3. What to test, in order

| Level | Examples |
|---|---|
| **Market / audience** | Segments, lists, targeting, channels, geography |
| **Offer** | Price, payment plan, guarantee, premiums, trial length, deadline structure |
| **Big Idea / angle** | Promise, mechanism, story, emotion |
| **Headline/lead/subject** | Formula, lead archetype, hook length |
| **Body & structure** | Length, proof order, objection handling, close |
| **Format & design** | Page layout, CTA button, image, color, video vs text |
| **Sequencing** | Number of touches, timing, order of angles |

## 4. Test plan template
```
TEST ID / DATE:
HYPOTHESIS: (because ___ we expect ___ to improve ___ by ___)
VARIABLE (A vs B):
CONSTANTS:
AUDIENCE & SPLIT: (random? equal?)
PRIMARY METRIC: (revenue per visitor / CPA / qualified lead rate)
GUARDRAIL METRICS: (refunds, unsubscribes, complaints, brand safety)
MIN SAMPLE / DURATION: (and stop rule)
KEYING / TRACKING:
DECISION RULE: (e.g., ship B if +X% with ≥Y conversions per arm and guardrails OK)
RISKS / COMPLIANCE CHECK:
RESULT & LEARNING (post-test):
NEXT TEST:
```

## 5. Practical statistics (keep it honest)
- Sample size matters more than clever dashboards; tiny samples produce false winners.
- Don't peek and stop early on a lucky streak; pre-register the stopping rule.
- Beware novelty effects, seasonality, day-of-week, and audience overlap.
- Run A/A checks when infrastructure is new.
- Prefer directional learning at low volume (compare angles by qualified lead cost) and statistical significance at higher volume.
- For small businesses: sequential testing over a fixed time window with consistent traffic is often more feasible than multivariate tests.

## 6. Hidden-offer vs coupon tests (Caples)
Use a **coupon/direct response** when you want many replies of real value; use a **hidden offer** to avoid curiosity-seekers and measure quality. Count both **quantity** and **quality** of leads (sales per lead).

## 7. Sequence-level measurement (Kennedy)
Measure the sequence as a unit: letter 1 / 2 / 3 response curves; incremental response from touches 2–3; unsubscribe and complaint rates; payback.

## 8. Results log (keep a persistent file)
Columns: date, asset, audience, awareness/sophistication, idea, lead type, offer, channel, primary metric, result, sample size, winner?, learning, next action. The log is a **knowledge asset**: it feeds future prompts and prevents repeating failed tests.

## 9. AI-era testing
- AI makes **variant creation** cheap; the bottleneck is **traffic and measurement**. Resist testing 30 variants with 500 visitors.
- Ask Claude to propose **a small test tree**: 3–5 meaningfully different ideas first, then lead structures, then wording.
- Have Claude draft the **test brief and tracking plan**, but a human sets metrics and sample-size rules.
- Synthetic respondents/LLM "focus groups" are opinion tests at best: use only to find gaps and objections, never to pick winners.
- Treat any LLM-estimated conversion lift as fiction until measured.

## 10. Failure post-mortems
When a test loses, ask in order: wrong **audience**? wrong **offer**? **idea** not new/believable? mismatch of **awareness/sophistication**? **proof** missing? **friction**? **tracking** error? — before blaming the copy wording.
