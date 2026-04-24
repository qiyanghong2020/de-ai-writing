# 中文去 AI 腔参考

Use this reference when the draft is Chinese, or when a mixed-language draft has Chinese as the main prose.

## Load more detail when needed

- Read `references/markers.md` for concrete examples of AI-like Chinese phrasing and preferred rewrites.
- Read `references/rewrite_patterns.md` for phrase-level before/after patterns.
- Read `references/risk_words_quicklist.md` for a fast sweep of high-risk words and natural alternatives.
- Read `references/thesis-medical.md` for theses, dissertations, medical papers, formal academic prose, and discussion sections.
- Read `references/execution-patterns.md` for long documents, layout-sensitive files, or staged rewriting.

## Core Chinese priorities

Keep facts fixed first:

- factual claim
- source type or document role
- sample size or key numbers
- effect direction
- limitation, scope, or evidence boundary

Then remove the machine-smoothed surface:

- replace vague slippery words with concrete subjects, actions, and outcomes
- replace translationese abstract nouns with natural Chinese when a direct expression exists
- cut low-information connective openers
- remove rhetorical booster words such as `真正`, `实际上`, and `最值得` when they only prop up tone
- remove commentary about the writing itself
- remove teacher-like prompts such as `可以这样理解`, `先看`, `再看`, and `读这篇文章时`
- reduce contrast-first framing such as `不是……而是……`, `并非……而是……`, and `不只是……而是……` when the contrast is not essential
- break over-even rhythm and repeated paragraph openings
- clean up punctuation habits that make the prose look machine-smoothed

## Prefer direct, flat, respectful statements

Prefer:

- direct declarative sentences
- concrete subjects and concrete verbs
- content-telling narrative instead of commentator voice
- calm explanation instead of correction-first rhetoric
- flat, respectful reader relationship

Avoid by default:

- `这一点很关键`
- `最值得记住的是`
- `可以这样理解`
- `更像是在提醒我们`
- `普通人最该记住的是`
- `放在一起看`
- `再往下看`

If contrast is genuinely needed to correct a likely misunderstanding, keep it once and make the correction concrete. Do not let contrast framing become the paragraph's default skeleton.

## Watch paragraph motion

Chinese AI flavor often comes from paragraph motion, not only vocabulary.

High-risk signs:

- too many connective openers such as `从方法学上看`, `从科学问题看`, `综上`, `据此`, `为此`, and `换句话说`
- too many academic transition words such as `此外`, `然而`, `总之`, `同时`, and `值得注意的是`
- several nearby paragraphs starting with the same discourse move
- repeated structures like `第一…第二…第三…` or `其一…其二…`
- repeated skeletons like `在 X 任务中，…`, `本文……并……`, or `若……则……`
- grammatically perfect paragraphs that feel over-packed, over-even, and overly managed

Preferred response:

- delete the connective if the sentence still stands without it
- if the relation is obvious from context, let context carry it
- if the relation must stay, express it through object, action, comparison, sequence, or consequence instead of stock markers

## Mode calibration

Public explainer or literature-sharing mode:

- be direct and readable
- avoid lecturer voice
- keep reader labels respectful or omit them
- use mild human texture only if the genre allows it

Report, PRD, README, or strategy mode:

- name the object, action, result, and owner
- avoid inflated nouns such as `赋能`, `闭环`, `抓手`, and `体系化` unless they are precise local terms
- keep technical names, commands, paths, and UI labels exact

Thesis, medical, or academic mode:

- preserve evidence-reporting verbs and field-typical terms
- do not add first person, oral markers, attitude words, or casual texture
- distinguish headings, captions, methods, results, discussion, and limitations as separate subgenres
- avoid turning study statements into colloquial observations
- prefer real research trace over generic completeness

## Final Chinese self-check

Ask:

- Did I preserve the claim and evidence boundary?
- Did I remove writing-about-writing?
- Did I replace vague abstractions with concrete objects or actions?
- Did I reduce repeated connectives and sentence skeletons?
- Does the result sound like a person writing this genre, not a model managing a paragraph?
