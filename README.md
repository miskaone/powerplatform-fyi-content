# powerplatform.fyi — article library

The published source of every article, pattern, and lab on
[powerplatform.fyi](https://powerplatform.fyi), as MDX.

This repository exists so that corrections are visible. Power Platform licensing,
limits, and product naming move quarterly; anything written about them will be
wrong eventually. When it is, the fix lands here as a dated, attributed commit
with a diff — not as a silent edit to a database row. You can see what a claim
used to say, when it changed, and why.

That matters because the writing makes checkable claims. Where an article states
a rate, a cap, or a licensing rule, it links to the Microsoft documentation the
claim was verified against, and tells you to confirm the current figure yourself.
The commit history is the other half of that promise.

## Layout

```
content/articles/    longform architecture writing
content/patterns/    reference patterns — the shape a solution should take
content/labs/        hands-on walkthroughs
standards/           the editorial standard the writing is held to
```

Some entries are short placeholders standing in for pieces not yet written. They
say so in their own text.

## Frontmatter

```yaml
title:       string
description: string
date:        YYYY-MM-DD
category:    string
tags:        [string]
featured:    boolean
status:      published | draft
```

Drafts are excluded from the site build.

## Found something wrong?

Open an issue or a pull request. Corrections to a factual claim are more welcome
than anything else here — particularly ones that cite the Microsoft
documentation that settles it. A claim that cannot be checked is a claim that
should not have shipped.

## Not in this repository

The site itself — Next.js app, components, build pipeline — is separate and not
public. This repository is the writing.

## Licence

The writing is licensed [CC BY 4.0](LICENSE). Use it, quote it, adapt it,
including commercially, with attribution to powerplatform.fyi.
