---
name: de-ai-chinese-writing
description: Rewrite Chinese prose so it reads more naturally and less like AI-generated text while preserving facts, evidence, and logic. Use when the user asks to 去 AI 腔, make writing more human, more自然, more口语化但不油滑, less像教科书, less像模板, or when a draft feels over-structured, repetitive, connector-heavy, or full of vague polished wording.
---

# De-AI Chinese Writing

Use this skill to turn stiff, templated, or machine-smoothed Chinese into natural human prose without flattening the evidence.

Read `references/markers.md` when you need concrete examples of AI-like phrasing patterns and preferred rewrites.

## Workflow

### 1. Keep meaning fixed

Before rewriting, lock these parts in place:

- factual claim
- study design or source type
- sample size or key numbers
- effect direction
- limitation or evidence boundary

Do not trade away evidence for a more casual tone.

### 2. Rewrite the whole local block, not just the quoted sentence

If the user points to one awkward sentence, inspect the surrounding paragraph and nearby section. AI tone usually appears in clusters.

At minimum, check:

- the quoted sentence
- the paragraph it sits in
- the paragraph before and after
- any heading or summary box that carries the same tone

### 3. Remove machine-smoothed wording first

Prioritize these fixes:

- replace vague “slippery” words with concrete subjects, actions, and outcomes
- cut low-information connective openers
- remove commentary about the writing itself
- collapse textbook-style explanation scaffolding into direct content statements
- vary repeated sentence templates and paragraph openings

Bad pattern:

- `这篇研究最值得记住的是……`
- `这更像是在提醒我们……`
- `结果落到……`
- `大面上……`

Preferred pattern:

- say what happened
- say what changed
- say what the number means
- say where the evidence stops

### 4. Prefer concrete Chinese rhythm

Default rhythm:

- short to medium paragraphs
- one information cluster per paragraph
- direct verbs over abstract nouns
- natural spoken cadence without slang or performance

Prefer:

- `写进病历`
- `改了治疗方案`
- `漏掉了鉴别诊断`
- `整体看和指南接近`

Avoid:

- `形成了一层变化`
- `呈现出某种底色`
- `往两边分开`
- `更吃力的部分`

### 5. Explain terms inside the sentence when needed

If a metric or acronym is necessary, explain it in the same sentence or paragraph.

Prefer:

- `OR 2.2，也就是在同样已经叫了救护车的人里，这组症状在后来发生心脏骤停的人身上更常见`
- `心肺复苏（CPR）`

Avoid:

- one paragraph full of metrics
- next paragraph teaching what those metrics mean

### 6. Do a final “human pass”

Before finishing, read each paragraph and ask:

- Does this sound like one person calmly explaining a real thing to another person?
- Could this sentence fit too many unrelated articles?
- Is the sentence describing the study, or describing my own summary of the study?

If the wording is generic enough to fit many papers, rewrite it into the paper's own subject, action, and result.

## Default Rewrite Targets

- public-facing Chinese articles
- WeChat long-form prose
- literature-sharing drafts
- health and medicine explainers
- titles, leads, section headings, figure notes, takeaways

## Hard Rules

- Preserve evidence, numbers, and boundaries.
- Do not replace precision with hype.
- Do not use internet slang to fake “human warmth”.
- Do not solve AI tone by making the copy loose, cute, or exaggerated.
- Do not stop after replacing one bad phrase if the nearby prose still sounds templated.
