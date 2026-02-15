# 🚀 Setup Guide

## How This Vault Works

**Sage** (me) lives on a VPS and:
1. Create/update notes in this vault
2. Auto-commit & push daily (11 PM IST)
3. You pull locally to see updates

**You** use Obsidian locally:
1. Pull latest from GitHub
2. Read my logs, memories, plans
3. Edit/add your own notes
4. Push back (I'll pull when needed)

## Folder Structure

```
sage-vault/
├── config/              # Core identity & settings
│   ├── SOUL.md         # My personality
│   ├── USER.md         # Your profile
│   └── IDENTITY.md     # My name/emoji
├── tools/              # Technical config
│   ├── TOOLS.md        # Available tools
│   ├── RATE_LIMITS.md  # Budget & limits
│   ├── HEARTBEAT.md    # Auto-tasks
│   └── TELEGRAM_SETUP.md
├── daily/              # Session logs (auto-synced)
│   └── 2026-02-15.md
├── memory/             # Long-term memory
│   └── MEMORY.md
├── projects/           # Active projects
│   └── expense-tracker.md
├── inbox/              # Quick notes (unsorted)
├── docs/               # Documentation
│   └── SETUP.md (this file)
└── INDEX.md            # Dashboard & overview
```

## Daily Log Format

Each day I create: `daily/YYYY-MM-DD.md` with:
- What I worked on
- Decisions made
- Blockers encountered
- Next steps
- Links to related notes

## How to Sync

**Pull latest from me:**
```bash
cd ~/path/to/sage-vault
git pull
```

**Push your changes:**
```bash
git add .
git commit -m "Your message"
git push
```

## Auto-Sync (My Side)

Every night at 11 PM IST:
- Commit daily logs
- Push to GitHub
- You pull next morning

## Setting Up Locally

1. **Clone vault:**
```bash
git clone https://github.com/yugeshr/sage-vault.git
cd sage-vault
```

2. **Open in Obsidian:**
- File → Open vault folder → select `sage-vault` folder
- Obsidian will index all notes

3. **Enable quick access:**
- Create a bookmark for the vault
- Pin important notes

## Tips

- Click on links like [[INDEX]] to navigate
- Use graph view (top right) to see connections
- Search with Cmd/Ctrl + F
- Backlinks show where notes reference each other
- Create your own folders alongside mine

---

*Last updated: 2026-02-15*
