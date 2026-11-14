# Test Plan & Results Log Templates

Use with `frameworks/testing-and-measurement.md`.

## 1. Quick test plan (copy/paste)
```
TEST ID:
DATE / OWNER:
OBJECTIVE: (what decision will this inform?)
HYPOTHESIS: Because [insight], changing [variable] from A to B will improve [metric] by [expected effect].
ASSET / CHANNEL:
AUDIENCE & SEGMENTATION:
VARIABLE (only one): A = ___ ; B = ___ (; C = ___)
CONSTANTS:
PRIMARY METRIC:  (e.g., revenue per visitor, cost per qualified lead)
GUARDRAILS:      (refund rate, unsubscribes, complaints, brand safety)
SAMPLE / DURATION: min conversions per arm = __ ; run __ days ; stop rule = __
TRACKING / KEYS: UTM/code/phone/URL
DECISION RULE: ship B if ___ ; otherwise keep A ; if inconclusive then ___
COMPLIANCE CHECK: ✓ claims  ✓ disclosures  ✓ consent
RISKS & ASSUMPTIONS:
RESULT:
LEARNING:
NEXT TEST:
```

## 2. Test tree (suggested order)
1. **Audience/channel** × same offer & idea
2. **Offer** (price/terms/guarantee/bonus) × best idea
3. **Big Idea / angle** (3–5 distinct ideas)
4. **Lead archetype** (offer / promise / problem / secret / proclamation / story)
5. **Headline/subject structure** (formula)
6. **Body structure & proof order**
7. **CTA & friction**
8. **Design/format**

## 3. Results log (CSV/sheet columns)
```
date, test_id, channel, asset, audience, awareness, sophistication,
idea, lead_type, offer, variable, A_result, B_result, primary_metric,
sample_per_arm, confidence/decision, winner, revenue_impact, learning, next_action, link_to_assets
```

## 4. Post-mortem prompts
- Did the right people see it? (traffic quality)
- Did the message match the source? (message match)
- Was the idea new and believable? (sophistication fit)
- Was the proof sufficient? (promise ≤ proof)
- Was the offer clear and risk reversed?
- Was there friction (speed, forms, mobile)?
- Was tracking correct?
- What's the smallest change likely to teach us the most next?

## 5. Learning library entry
```
PATTERN: <what worked/failed and under what conditions>
EVIDENCE: <tests, dates, sample>
SCOPE: <audience/channel/offer>
CONFIDENCE: low / medium / high
REVIEW DATE:
```
