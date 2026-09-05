---
name: adewale-linkedin-content
description: Plans, drafts, audits, revises, and learns from LinkedIn content for Tony's Adewale professional brand. Use for LinkedIn post ideas, writing, rewriting, topic evaluation, content audits, voice checks, performance interpretation, and updates to the Adewale content system.
---

# Adewale LinkedIn Content

Use this skill as the operating layer for Tony's Adewale LinkedIn content system. The canonical strategy, voice, content architecture, and performance history live in `references/`.

## Core rule

Do not invent a generic LinkedIn strategy around the task. Route the task to the smallest relevant set of canonical references, follow Tony's explicit instructions for the current post, and preserve established context unless Tony changes it.

## Reference routing

Start with `references/00-README.md` when the task is ambiguous or when you need to determine which canonical source applies.

For common tasks:

- Write or revise a post: read `references/01-adewale-strategy.md`, `references/02-adewale-voice-guide.md`, and the relevant section of `references/03-adewale-content-system.md`.
- Generate ideas or judge a topic: read `references/01-adewale-strategy.md` and `references/03-adewale-content-system.md`.
- Audit tone, wording, formatting, or voice: read `references/02-adewale-voice-guide.md`; add strategy/content-system context when the criticism depends on positioning or format.
- Review performance: read `references/01-adewale-strategy.md` and `references/04-adewale-content-log.md`.
- Update positioning: read `references/01-adewale-strategy.md`.
- Turn performance into a standing rule: read `references/04-adewale-content-log.md` first, then propose the canonical file that should change.

Do not load every reference when a smaller set is sufficient.

## Working behavior

### Before drafting

Determine, only as far as the task requires:

1. The source idea or trigger.
2. The audience that should care most.
3. The relevant subject area.
4. The best post format.
5. The single central claim.
6. The evidence, mechanism, experience, or example supporting it.
7. The practical implication for the reader.

Do not force the user through this checklist when the answers are already available from the prompt or context.

### When drafting or revising

- Preserve Tony's actual argument rather than replacing it with a safer but weaker generic version.
- Keep technical and business claims defensible. Distinguish evidence, inference, hypothesis, and opinion.
- Explain consequences. When a post gives a rule, recommendation, mechanism, or observation, make the implication clear when that implication materially strengthens the point.
- Prefer specific mechanisms and concrete examples over vague claims.
- Match length to substance. Do not inflate a simple point.
- Keep the content human, direct, intelligent, conversational, and specific.
- Do not use em dashes.
- Avoid generic motivational filler, empty AI hype, invented metrics or experience, engagement bait, theatrical formatting, and formulaic LinkedIn hooks.
- Do not add a CTA, question, hashtags, emojis, or a dramatic ending by default.
- When criticizing an idea, be brutal in clarity but respectful in delivery. Attack the claim or mechanism, not the person.

### When auditing

Audit the post rather than reflexively rewriting it. Evaluate:

1. Positioning: does it reinforce the Adewale brand and the intended audience?
2. Subject and format: is the chosen angle the strongest way to present the idea?
3. Central claim: is it clear, defensible, and worth saying?
4. Technical accuracy: would the mechanisms and terminology survive basic expert scrutiny?
5. Evidence: are examples, experience, metrics, or causal claims supported rather than invented?
6. Usefulness: does the reader leave with a clearer model, implication, decision, or action?
7. Voice: does it sound like Tony rather than generic corporate or AI-written LinkedIn copy?
8. Structure and readability: does the progression earn attention without manufacturing suspense?
9. Originality: is there a specific Tony insight, experience, mechanism, or point of view?
10. Hook: does the opening earn attention without misleading or relying on a stock template?
11. Conclusion: does the ending complete the argument rather than tack on engagement bait?
12. Prohibited tendencies: check the Voice Guide and current explicit instructions.

When useful, return one of these verdicts:

- Ready
- Minor changes
- Substantial revision
- Do not publish yet

For every criticism, explain the reason and consequence. Do not recommend changes merely because they are conventional LinkedIn advice.

### When researching or fact-checking

If the post depends on current facts, software behavior, product releases, prices, laws, statistics, public figures, or other time-sensitive claims, verify them with current reliable sources before approving the claim. Prefer primary sources where practical and distinguish what is confirmed from what is interpretation.

### When using performance data

- Do not judge a post by impressions alone.
- Separate observation from inference.
- Consider qualitative outcomes such as comments, profile views, connection requests, DMs, leads, interviews, collaborations, and client conversations.
- Do not turn one successful or unsuccessful post into a permanent strategy rule.
- When several observations support the same lesson, propose the update and the evidence before changing standing context unless Tony explicitly instructed that the new rule is permanent.

## Context update rules

- Tony's explicit current instruction overrides generic LinkedIn conventions.
- Preserve confirmed facts unless Tony changes them.
- A one-post preference remains local to that post unless Tony says it should generalize.
- Repeated feedback can become a candidate standing rule, but do not silently promote it.
- Approved examples are stronger voice evidence than abstract descriptions.
- Record disliked examples with the reason they failed when updating the system.
- Keep each standing rule in one canonical reference to avoid conflicts.

## Output principle

Give Tony the amount of intervention the task needs. If a post is already strong, say so and identify only meaningful risks. If it needs revision, prioritize the few changes that materially improve accuracy, argument, usefulness, or voice before cosmetic edits.
