# Upstream Notes

## Source

- upstream repo: `https://github.com/qiyanghong2020/de-ai-chinese-writing.git`
- local active skill path: `/home/hongqy/.codex/skills/de-ai-chinese-writing`
- current branch: `main`

## Local organization

This local skill now uses a single `main` branch:

- `origin/main` tracks the upstream repository
- local `main` is the active integrated version
- local enhancements are committed on top of upstream instead of being kept on a separate branch

## Local additions kept on top of upstream

- stronger academic / thesis / medical guidance
- explicit checks for transition-word overload such as `此外` / `然而` / `总之`
- explicit checks for overly uniform grammar and sentence landing
- extra quick references for phrase-level rewrites and risk words
- local reference file: `references/thesis-medical.md`

## Practical sync workflow

To review upstream changes later:

```bash
git -C /home/hongqy/.codex/skills/de-ai-chinese-writing fetch origin
git -C /home/hongqy/.codex/skills/de-ai-chinese-writing diff --stat origin/main..main
git -C /home/hongqy/.codex/skills/de-ai-chinese-writing diff origin/main..main
```

To see only local edits on top of upstream:

```bash
git -C /home/hongqy/.codex/skills/de-ai-chinese-writing status --short
git -C /home/hongqy/.codex/skills/de-ai-chinese-writing log --oneline origin/main..main
```

## Reminder

The active skill is the local directory under `~/.codex/skills`, not the remote repository by itself.
