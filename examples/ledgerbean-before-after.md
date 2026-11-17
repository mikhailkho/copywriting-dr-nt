# Example: the same brief, with and without the skill

One brief, run twice in Claude Code. Nothing below was edited after the run except section headings and heading levels. The product, **Ledgerbean**, is invented for this example.

## What was run

- **Without the skill:** plain Claude Code in an empty folder, all skills disabled, no tools.
- **With the skill:** the same Claude Code, with this repo installed at `.claude/skills/copywriting-dr-nt`, started with `/copywriting-dr-nt` followed by the brief.
- One run each, same day, default model. Outputs vary between runs, so treat this as one sample, not a benchmark.

## The brief (identical for both)

> Write the top of a landing page (headline, subheadline, opening paragraph and button text) for Ledgerbean, a bookkeeping app for small independent cafes. Facts I can give you: it connects to Square and Stripe and sorts each transaction into a category automatically; it costs $29 a month; there is a 14-day free trial; the owners we are aimed at have no accounting background and do their own books on Sunday nights. I have no customer quotes, results or case studies yet.

## Without the skill (plain Claude)

**Headline**
Your Sunday-night books, done before you sit down.

**Subheadline**
Ledgerbean connects to Square and Stripe and sorts every transaction into the right category automatically. No accounting degree required.

**Opening paragraph**
You didn't open a cafe to spend your Sunday nights squinting at spreadsheets. Ledgerbean pulls in your sales from Square and Stripe and categorizes each transaction for you, so there's no sorting, no guessing which bucket something belongs in, and no wondering whether you did it right. You get a clear picture of your cafe's money without needing to speak accountant. It's $29 a month, and you can try it free for 14 days.

**Button text**
Start your 14-day free trial

**Notes on choices**
- I kept every claim to what you gave me. With no quotes, results or case studies, I left out anything like "saves hours" or "trusted by cafes," since those would be unsupported numbers or social proof.
- "Done before you sit down" is a mild promise. If the categorization still needs the owner to review or correct anything, you may want something like "mostly done" or "sorted for you" instead, so the headline doesn't overpromise.
- Alternate headline if you prefer plainer: "Bookkeeping for cafe owners who aren't accountants."
- Alternate button: "Try Ledgerbean free for 14 days." Worth adding a small line under the button like "$29/month after trial" if you want pricing visible up front. I'm not certain whether a card is required at signup, so I haven't claimed "no credit card needed." Add that if it's true.


---

## With the skill (`/copywriting-dr-nt`)

### Ledgerbean: top of landing page

## Diagnosis (veto any of this)
- **Audience:** owners of small independent cafes who aren't accountants and do their own books on Sunday nights.
- **Awareness:** problem-aware. They know the Sunday-night chore, and many have tried a spreadsheet or a bookkeeping tool. They don't know your product yet.
- **Sophistication:** stage 2–3. "Easy bookkeeping" is a crowded claim. Your usable difference is a concrete mechanism: it connects to Square and Stripe and sorts each transaction itself.
- **Desire:** get the evening back and stop feeling out of their depth with money. This is a hypothesis; no customer language has been collected yet.
- **Lead type:** problem-solution, short. This is a considered but low-price ($29) purchase with a free trial, so the first screen has to work alone.
- **Big idea (30 seconds):** the sorting you do by hand on Sunday night, Ledgerbean does as sales come in from Square and Stripe.
- **Proof ceiling:** product facts and price only. No results, quotes or time-saved numbers, so the copy makes none.

## The copy

**Headline**
> Your cafe's books, sorted before Sunday night.

**Subheadline**
> Ledgerbean connects to Square and Stripe and puts every transaction in a category for you. Made for cafe owners who never studied accounting.

**Opening paragraph**
> Sunday night, the café's closed, and you're scrolling through the week's sales deciding which line goes where. You didn't open a cafe to do that. Ledgerbean connects to your Square and Stripe accounts and sorts each transaction into a category automatically, so when you sit down to do the books, the sorting is already done. It's $29 a month, and the first 14 days are free.

**Button**
> Start my 14-day free trial

**Microcopy under the button**
> $29/month after the trial. [NEED: is a card required to start? how do you cancel?]

## Headline alternatives (different ideas, for testing)
1. **Mechanism:** "Square and Stripe, sorted into categories automatically."
2. **Pain:** "Stop sorting the week's sales by hand."
3. **Identity:** "Bookkeeping for cafe owners who never studied bookkeeping."

## Claims register
| Claim | Evidence | Status |
|---|---|---|
| Connects to Square and Stripe | Your fact | OK |
| Sorts each transaction into a category automatically | Your fact | OK |
| $29/month, 14-day free trial | Your fact | OK |
| "Sorted before Sunday night" | Implied by automatic sorting; not tested | **Verify.** Confirm sorting happens on sync, not on a schedule or manual trigger. |
| "Sorting is already done" | Same | **Verify.** Don't imply 100% accuracy. If owners must review or correct some items, say so. |
| "Never studied accounting" | Your audience description | OK as targeting. Don't promise the product replaces an accountant or makes tax filing easy. |

I left out time-saved figures, "tax-ready," "accurate," and "trusted by," because none are backed yet.

## Assumptions and unknowns
- Whether a card is needed for the trial, and the cancellation terms. These must be visible near the button.
- What a "category" means: your own, or standard ones such as COGS and rent.
- Your brand voice. This draft is plain and warm.

## Top 3 things to verify before launch
1. The timing and accuracy of the auto-sorting, so the headline and paragraph don't over-promise.
2. The trial and billing terms shown beside the button.
3. That the Sunday-night pain is real for your owners. Check it in 3–5 short conversations and use their exact words in the next draft.

## Single next test
Run the headline as the one variable, since it's the biggest lever with no proof to lean on. Compare the pain version ("Stop sorting the week's sales by hand") against the control. The primary metric is trial starts per unique visitor. Guardrails are trial-to-paid rate and bounce rate. Don't call a winner before each version has about 100 trial starts or two full weeks of traffic. Tag each variant with its own UTM so the results can be logged.


---

## How to read this

- **Neither draft invented proof.** Both stuck to the facts in the brief, with no "saves hours" or "trusted by cafes". Made-up claims are a common failure in AI copy, and plain Claude avoided them on this brief.
- **The copy is similar in quality.** Judge the two headlines and paragraphs yourself. The skill's version is not clearly better, and you may prefer the plain one.
- **What the skill adds is the work around the copy:** a diagnosis you can overrule, a claims register with a status per claim, `[NEED: ...]` markers for facts it does not have, three things to verify, and a single next test with a metric and a sample rule.
- **What it costs:** a longer reply and more to read. For a quick one-off line, plain Claude is faster.

To try your own brief, see "Try it" in the [README](../README.md).
