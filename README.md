# Coptic Orthodox Ministry - AI Content Toolkit

A shared, open-source repository of AI skills, system prompts, and prepared content for Coptic Orthodox servants and ministers. Built for community reuse, not just one church.

---

## What This Is

This repo contains:
- **AI skills** that teach any compatible AI assistant how to prepare deeply Orthodox spiritual content
- **System prompts** you can paste into Claude, ChatGPT, Gemini, or any LLM
- **Prepared lessons, series, and study materials** ready to use or adapt
- **Style guides** for lesson structure, tone, and quality standards

Everything is grounded in ancient Orthodox Christianity, especially the Coptic Orthodox tradition: Christ-centered, biblical, patristic, sacramental, and pastorally serious.

---

## Who This Is For

- Servants preparing weekly adult meetings or Bible studies
- Deacons, teachers, or youth ministers creating lesson content
- Anyone in Coptic ministry who wants AI assistance that actually understands Orthodox theology - not generic Christian content

---

## How to Use This

### Option A - Just copy a system prompt (no technical setup)

1. Open [`spiritual-lessons/system-prompts/universal.md`](spiritual-lessons/system-prompts/universal.md)
2. Copy the full contents
3. Paste into the system/custom instructions field of Claude, ChatGPT, Gemini, or any other AI
4. Start asking it to prepare lessons, series, or WhatsApp promos

Platform-specific versions are also available:
- [`system-prompts/claude-projects.md`](spiritual-lessons/system-prompts/claude-projects.md) - for Claude.ai Projects
- [`system-prompts/chatgpt-custom-gpt.md`](spiritual-lessons/system-prompts/chatgpt-custom-gpt.md) - for ChatGPT GPT Builder

### Option B - Install as a skill (Claude Code, Cursor, Codex CLI, etc.)

```bash
npx skills add github.com/[your-username]/coptic-orthodox-ministry/spiritual-lessons
```

The skill will be available to your AI coding agent automatically.

### Option C - Browse and reuse prepared content

All lessons and series are in [`spiritual-lessons/series/`](spiritual-lessons/series/) and [`spiritual-lessons/standalone/`](spiritual-lessons/standalone/). Read them directly on GitHub, copy what you need, or adapt for your community.

---

## Repo Structure

```
coptic-orthodox-ministry/
│
├── README.md                        ← you are here
├── CONTRIBUTING.md                  ← how to contribute content or skills
│
├── spiritual-lessons/               ← Category 1: adult lessons and series
│   ├── SKILL.md                     ← installable AI skill
│   ├── system-prompts/              ← paste into any LLM
│   ├── style-guides/                ← lesson structure and promo format
│   ├── theology-references/         ← Orthodox doctrine and patristic approach
│   ├── series/                      ← multi-lesson series with overviews
│   │   ├── INDEX.md                 ← master list of all series
│   │   ├── encounters-with-christ/
│   │   └── old-testament-prophecies/
│   └── standalone/                  ← single topical lessons
│       └── INDEX.md                 ← master list of standalone lessons
│
├── deacon-guides/                   ← Category 2 (coming)
└── outreach/                        ← Category 3 (coming)
```

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for the theological standards, file format, and submission process.

Short version: content must be Orthodox, Christ-centered, patristically grounded, and practically useful. No generic Christian content. No invented patristic quotes.

---

## License

All content is released under [Creative Commons Attribution 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You are free to use, adapt, and share with attribution.

---

## Questions or Contributions

Open an issue or submit a pull request. If you are not familiar with GitHub, see the "Non-technical contribution" section in [CONTRIBUTING.md](CONTRIBUTING.md).
