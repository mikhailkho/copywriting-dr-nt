# Contributing to copywriting-dr-nt

Thanks for wanting to help. This skill is early, built by one person with Claude, and tested so far only by its author. It gets better when people who do this work for a living try it, break it and tell me where it's wrong.

You don't need to write code. Almost everything here is plain Markdown.

## What helps most

1. **Trial reports.** Run the skill on a real brief and tell me what happened. Use the "Trial feedback" issue template. A report that says "it invented a stat" or "its diagnosis was wrong because..." is worth more than a polished pull request.
2. **Field-test results.** If you ran something the skill wrote against a control, send the result: what you tested, the sample, the metric and the outcome, with client details removed. Add a row to a copy of `templates/results-log.csv`. Negative results are welcome.
3. **Corrections.** Tactics go out of date, platform rules change and I will have things wrong. Point at the file and line, say what's wrong and, if you can, link a source.
4. **New or better channel guides.** For example: app store listings, podcast ads, SMS, LinkedIn, YouTube, B2B enterprise sales enablement, nonprofit fundraising.
5. **Sector and jurisdiction compliance signposts.** Practitioners in health, finance, legal, education, real estate, or a specific country can add the rules that matter. See "Compliance contributions" below.
6. **Localisation.** Notes on how idioms, proof norms and claims rules differ in your market.
7. **Better examples and prompts** for the README, using invented or fully anonymised material.
8. **Evals.** A set of briefs with a clear way to judge whether the skill's output was good would help everyone. If you want to build one, open an issue first so we agree on the format.

## Ground rules

These mirror the skill's own rules. Pull requests that break them will be asked to change.

- **No copied text.** Do not paste passages from books, ads, sales letters, courses or paid newsletters. Write in your own words. Quote at most a few words, for attribution.
- **No per-book notes.** Chapter-by-chapter summaries of copyrighted books are not accepted into this repo. Principles synthesised across sources, in your own words, are.
- **No invented facts.** No made-up statistics, studies, testimonials, customers, case studies or credentials. If you don't know, write `UNKNOWN`.
- **Sources for claims.** Any factual claim, number or rule needs a source (link, document or your own documented test) and a date. "I've seen it work" is fine as a labelled observation, not as a fact.
- **Real results only, with permission.** Case material must be real, anonymised, and shared with the client's or your employer's permission. Composites must be labelled as composites.
- **No confidential or personal data.** No customer lists, emails, names or private documents.
- **Honest persuasion only.** No fake urgency or scarcity, hidden billing, dark patterns, or advice that depends on the reader being misled.
- **Say what's dated.** Mark material as durable or dated, as the existing notes do.

## How to contribute

**Small fixes** (typos, a wrong link, a clearer sentence): open a pull request directly.

**Anything bigger** (a new file, a changed rule, a new mode): open an issue first, describe the problem and your proposal, and wait for a reply. This saves you from writing something I can't accept.

Steps:

1. Fork the repo and create a branch (for example `channel-sms` or `fix-offer-guarantee`).
2. Make your change. Keep each pull request to one idea.
3. Fill in the pull request template.
4. Be ready to revise. I'll comment on anything that doesn't meet the ground rules.

I review as time allows. I can't promise a response time.

## How the repo is organised

- `SKILL.md` is what Claude loads. Treat it carefully: a small change here changes the behaviour of the whole skill.
- `knowledge/` is loaded progressively. Claude reads only the files a job needs, so keep each file focused and reasonably short.
  - `00-neo-traditionalist-canon.md`: the ten principles and how conflicting advice is resolved.
  - `frameworks/`: the reusable methods (diagnosis, Big Idea, offer, leads, testing, and so on).
  - `channels/`: one guide per format (landing pages, email, ads, and so on).
  - `checklists/`: intake, review, compliance, test plan.
  - `books/`: empty on purpose. See `knowledge/books/README.md`.
- `templates/`: the deliverable format and the results log.

**If you add a file**, also add it to the table in `SKILL.md` ("Knowledge library") and to `knowledge/README.md`, or Claude won't know to load it.

## Style for knowledge files

- Plain words, short sentences, specific examples. The skill's own anti-slop rules apply to the docs too.
- Start with what the file is for and when to load it.
- Include a short "what's dated or risky" note where relevant.
- Give a source line for the ideas you draw on (author and work, or your own test), without reproducing it.
- Prefer a decision table or checklist over a long essay.
- Don't use hype words ("revolutionary", "game-changing", "unlock") or the AI tells listed in `knowledge/frameworks/ai-workflow-and-slop-edit.md`.

## Compliance contributions

The compliance gate in `knowledge/checklists/compliance-and-ethics.md` lists signposts, not legal advice. If you add one:

- Name the jurisdiction or platform and the specific rule, code or policy.
- Link the official text and give the date you checked it.
- State what it means for copy in one or two lines.
- Don't write it as legal advice or as a guarantee of compliance.
- If you are a qualified professional in the area, say so in the pull request (you don't have to give your name).

## Test your change

There are no automated tests yet. Before you open a pull request:

1. Run the skill on two or three briefs that your change affects, before and after. Paste the relevant before/after output in the pull request.
2. Check that `SKILL.md` still has valid frontmatter (the block between the first two `---` lines).
3. Check that every file path you mention exists.
4. Search your changes for anything copied, invented or confidential.

## AI-assisted contributions

Using Claude or another model to draft is fine, as I built this with Claude. You are responsible for what you submit:

- Say in the pull request that AI helped.
- Check every fact, number and source yourself. Models invent plausible specifics.
- Don't submit text you haven't read and edited.

## Licence

By contributing, you agree that your contribution is released under the project's [MIT licence](LICENSE), and that you have the right to submit it. Please don't submit anything you don't own or can't license.

## Behaviour

Be respectful. Disagree with ideas, not people. No harassment, no spam or self-promotion dressed as a contribution. Links to your own work are fine when they're a source for a claim. To report a problem, email mikhail@arpidy.com.

## Maintainer

Mikhail Kho, Marketing Manager.
