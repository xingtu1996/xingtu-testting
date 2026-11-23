# xingtu-testting · AI Testing Problems & Case Notes

> Under local construction, not published yet. Anything without cited evidence is a design draft, not a verified fact.

[![License: MIT](https://img.shields.io/badge/License-MIT-orange.svg)](./LICENSE) ![Status](https://img.shields.io/badge/status-local-lightgrey)

## In one line

A collection of real problems in testing AI: how people test it, and how AI systems get tested wrong. No model leaderboards — only test practice, judgment calls, and boundaries.

## Why this repo exists

Testing AI is not testing traditional software. Outputs are non-deterministic, acceptance criteria are hard to pin down, and failures are not always reproducible. This repo does not rebuild an evaluation framework. It does one thing: turn "what problem showed up / how we judged it / whether the conclusion holds" into reusable cases.

## Core content

- **Failure pattern library**: common failure types in AI testing, each with source and verification level.
- **Case breakdowns**: a uniform template separating hands-on runs from publicly sourced material.
- **Judgment notes**: what evidence a test conclusion needs, and when to call it a failure versus a false positive.

## Boundaries with neighboring repos

| Repo | Covers | Does not cover |
|---|---|---|
| `tokenhub-bench` | Reproducible model capability benchmarks | Test-practice problems and judgment |
| **xingtu-testting** (this repo) | Testing problems, judgment, and cases | Model rankings or evaluation frameworks |
| `xingtu-agent-skills` | Reusable installable skills | Testing failure cases |

## Home and Navigation

This repo belongs to the case-study section of the [XingTu open-source matrix](https://github.com/xingtu1996) and is maintained independently. The [profile repo](https://github.com/xingtu1996) only indexes; it does not duplicate this repo's content.

The four case repos divide by boundary and cross-reference each other:

- [xingtu-testting](https://github.com/xingtu1996/xingtu-testting) - AI testing
- [xingtu-bot](https://github.com/xingtu1996/xingtu-bot) - Bot form factors
- [xingtu-agent](https://github.com/xingtu1996/xingtu-agent) - Agent deployment
- [xingtu-bci](https://github.com/xingtu1996/xingtu-bci) - Collaboration bad cases

## Quick start

```bash
git clone <repo-url> xingtu-testting
cd xingtu-testting
# Copy cases/_TEMPLATE.md and fill in each section
```

Before adding a case, read `cases/_TEMPLATE.md`. Every case needs a status label and an evidence source. Inference without evidence is `design`; only locally run and recorded work is `verified`.

## Case status labels

| Label | Meaning |
|---|---|
| `design` | Design or idea only, not verified |
| `public-source` | Compiled from public material, not tested here; needs source link and check date |
| `verified` | Run locally with reproducible commands, output, or screenshots |
| `production` | In production use |

## Contribution rules

- De-identify every case: no client names, personal names, internal domains, or internal platform paths.
- Label the source and verification level of every number; second-hand star counts and prices are not criteria.
- For public cases, state who made it, where it was checked, and the check date. Do not present it as first-hand experience.

## License

[MIT](./LICENSE) · 行途 XingTu

## Author

行途 XingTu (engineering byline) · WeChat: 行途技术手记
