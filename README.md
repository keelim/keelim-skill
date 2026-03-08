# keelim-skill

Personal skill collection for Claude and Codex.

## Layout
- `skills/`: source-of-truth skill folders
- Each skill is docs-first and centered on `SKILL.md`

## Current skills
- `release-automation`: date-based Android release checklist for `develop -> main`, including dry-run, confirm, and execute flows.

## Manual install
### Codex
```bash
ln -s /Users/keelim/Desktop/keelim-skill/skills/release-automation ~/.agents/skills/release-automation
```

### Claude
```bash
ln -s /Users/keelim/Desktop/keelim-skill/skills/release-automation ~/.claude/skills/release-automation
```
