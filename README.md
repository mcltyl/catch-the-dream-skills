# Catch the Dream 🌙

**You have 30 seconds before your dream disappears. Make them count.**

Ever woken up from a vivid dream, reached for your phone, and by the time you opened the notes app... it's gone? That's because dreams evaporate within seconds of waking. Most dream journaling fails because of friction.

This Agent Skill captures dreams fast (voice or text dump), structures them automatically, and tracks recurring symbols over time. Stop losing your dreams to the snooze button.

Works with Claude Code, Codex CLI, OpenClaw, and any Agent Skills-compatible tool.

---

## The Problem

- Dreams fade within 30-60 seconds of waking
- Traditional dream journals are too slow
- Random notes don't reveal patterns
- Symbol meanings are personal, not generic

**This skill solves it:** Capture first, structure later, patterns emerge.

---

## Installation

### npx skills
```bash
npx skills add git@github.com:mcltyl/catch-the-dream.git
```

### Claude Code / Codex CLI
```bash
git clone https://github.com/mcltyl/catch-the-dream.git ~/.claude/skills/catch-the-dream
```

### OpenClaw
```bash
git clone https://github.com/mcltyl/catch-the-dream.git ~/.openclaw/skills/catch-the-dream
```

---

## Skills

| Skill | Description |
|-------|-------------|
| [catch-the-dream](skills/catch-the-dream) | Voice/text → structured dream log with symbol tracking |

---

## How It Works

```
[Wake up] → [Voice note or text dump] → [AI structures it] → [Patterns emerge over time]
```

1. **Capture immediately** — Just speak or type everything you remember
2. **AI extracts** — Setting, people, events, emotions, symbols
3. **Track over time** — See what keeps appearing
4. **Discover patterns** — Connect dreams to waking life

---

## Example

**Voice note (messy, half-asleep):**
```
I was in my old high school but it was also my office... 
my mom was there but she was my boss... running through 
hallways that kept getting longer... then I was flying...
```

**Structured output:**
```markdown
## Dream: The Endless Hallway
**Date:** 2026-03-24  |  **Vividness:** 4 ⭐

### Setting
High school merged with office — identity/role confusion

### People
- Mom — appeared as boss (authority, expectations)

### Events
1. Hybrid school/office space
2. Running late for unknown obligation  
3. Hallways kept extending
4. Transitioned to flying
5. Felt relief, woke up

### Symbols
| Symbol | Possible Meaning |
|--------|-----------------|
| Old high school | Past pressures, formative experiences |
| Mom as boss | Authority, approval seeking |
| Endless hallways | Feeling stuck, moving goalposts |
| Flying | Escape, freedom, rising above |
```

---

## Symbol Tracking

Over weeks, see what keeps appearing:

| Symbol | Count | Pattern |
|--------|-------|---------|
| Water | 12 | Turbulent when stressed |
| Flying | 8 | Usually positive, freedom |
| Teeth falling | 3 | Before big presentations |
| Old house | 6 | Nostalgia, childhood |

---

## Quick Commands

```
"Log this dream: [description]"
"What symbols have I dreamed about most?"
"Show dreams from last month"
"Any patterns in my recent dreams?"
```

---

## Why This Works

| Traditional Journaling | This Skill |
|------------------------|------------|
| Open app, create note, think about structure | Just talk/type, done |
| Manual symbol tracking | Automatic pattern detection |
| Generic dream dictionaries | Your personal symbol meanings |
| Isolated entries | Connected, searchable log |

---

## License

MIT

---

## Support

If this helps you catch your dreams:

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-yellow?style=flat&logo=buy-me-a-coffee)](https://buymeacoffee.com/mclty)
