# copywriting-dr-nt

A Claude skill for **neo-traditionalist direct-response copywriting in the AI era**. It makes Claude diagnose your audience before it writes, tells you its diagnosis so you can overrule it, marks the facts it doesn't have instead of inventing them, and ends every job with a test plan.

It applies classic direct-response method (research first, awareness x sophistication, one Big Idea, mechanism, specificity, offer, testing) and uses AI to amplify human truth, not replace it.

## Status: early

- Built by one person, with Claude. Used so far on a handful of my own jobs.
- **No performance data.** I have no case studies showing it lifts conversions, and I won't make any up.
- **One field test so far, and the skill lost.** I compared a cold email written with the skill against a plain Claude draft, unlabelled. I preferred the plain one: the skill's version sounded like fluff. I changed the skill's rule for cold outreach from unknown senders (plain statements, admit missing proof, no hook questions, keep the opt-out line). See `knowledge/channels/b2b-and-service-businesses.md` §3a.
- I want real trials and honest feedback. See "Feedback" below.

## Try it

Built and tested for **Claude Code**. Other Claude surfaces are untested.

Install in one project:

```
git clone https://github.com/mikhailkho/copywriting-dr-nt .claude/skills/copywriting-dr-nt
```

Or for all your projects, clone into `~/.claude/skills/copywriting-dr-nt`.

The folder name matters: `SKILL.md` refers to `.claude/skills/copywriting-dr-nt/knowledge/`.

Then run it:

```
/copywriting-dr-nt write a cold email to [audience] for [offer]
/copywriting-dr-nt review this landing page: <paste or path>
/copywriting-dr-nt give me 30 subject lines for a win-back email
```

Argument hint: `[what to write or review] [audience/offer/channel if known]`.

Give it real facts: your offer, customer quotes and proof. Where you have none, it leaves `UNKNOWN` or a `[NEED: …]` bracket instead of guessing. Please don't paste confidential or personal customer data into any AI tool without authorisation.

## What it does

Write, rewrite, critique, strategise or test persuasive copy:

- Headlines, hooks, subject lines and leads
- Sales letters, landing and sales pages, product pages
- Emails and sequences, ads, VSL/webinar scripts, B2B outreach
- Angles, Big Ideas, offers and test plans
- Traffic and audience planning: Dream 100, lead magnets, opt-in pages, retargeting, cold-traffic bridges

It diagnoses before it drafts (audience, awareness stage, sophistication stage, mass desire, Big Idea, offer), says the diagnosis out loud so you can veto it, and ends every deliverable with assumptions, three things to verify and the next test.

## Modes

| Mode | For |
|---|---|
| A. Create | Write a page, sequence, ad or script from scratch |
| B. Review | Critique copy and rank fixes by leverage |
| C. Upgrade | Rewrite existing copy in direct-response style |
| D. Strategy | Angles, Big Ideas, offers, lead types |
| E. Headlines/hooks | 20-50 variants, scored and shortlisted |
| F. Sequence/funnel | Value ladder, arc, per-touch angle and CTA |
| G. Test design | Test trees, plans, interpreting results |
| H. Library Q&A | What the classic authors said, with provenance |

## Ground rules baked in

- Never invents facts: missing information becomes `UNKNOWN` or a `[NEED: ...]` placeholder.
- Promise does not exceed proof; every claim goes in a claims register.
- Honest persuasion only: no fake urgency, dark patterns or hidden billing.
- Anti-AI-slop edit pass before delivery.
- Principles in its own words: it does not reproduce long passages from the source books.
- Every asset comes with a test plan; rankings (yours or the model's) are hypotheses.

## What it isn't

- It can't know your market. You supply the facts, quotes and proof.
- It isn't legal advice. The compliance gate lists regulatory signposts (for example Singapore SCAP/ASAS, CPFTA, PDPA, Spam Control Act, and US FTC rules). For health, finance, legal, income claims or children, get qualified review.
- It isn't one click. If you want a finished page from a single prompt with no inputs, this isn't it.

## Layout

```
SKILL.md                      skill definition and workflow (what Claude loads)
LICENSE                       MIT
knowledge/
  README.md                   index and decision guide for the library
  00-neo-traditionalist-canon.md
  frameworks/                 12 notes: awareness, Big Idea, offer, leads, body copy, psychology, testing, traffic...
  channels/                   landing pages, email, paid social, ecommerce, B2B, direct mail
  checklists/                 brief intake, copy review, compliance and ethics, test plan
  books/                      empty; add your own private notes (git-ignored), see books/README.md
templates/
  deliverable-template.md     output format for create/review/upgrade
  results-log.csv             test results log
```

The library is read progressively: Claude loads only the notes the task needs, not everything.

## Sources and attribution

The frameworks draw on the work of Hopkins, Halbert, Schwartz, Caples, Whitman, Masterson and Forde, Kennedy, Bly, Todd Brown and Brunson. They are named as influences and for attribution only. The notes are summaries and frameworks in my own words, not reproductions of any book, and I have not published the per-book notes. None of these authors, and not Anthropic, has reviewed or endorsed this project. "Claude" is a product of Anthropic.

## Feedback

Tried it? Tell me what worked, what sounded like fluff, and what it got wrong: open an issue on this repo.

## Work with me

I help marketers and businesses put Claude skills and workflows to work: setting them up around your own brand voice, customer language and proof, and training your team to use them. If you want a Claude-driven marketing consultation, email **mikhail@arpidy.com**.

Mikhail Kho, Marketing Manager

## License

MIT. See `LICENSE`.
