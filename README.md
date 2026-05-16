# Lalitha Sahasranamam Agent

A Claude Code agent that serves as a complete, searchable guide to **Sri Lalitha Sahasranamam** — the 1000 sacred names of Sri Lalitha Tripura Sundari.

## What it can do

- Look up any of the **1000 names** by number, Sanskrit name, or concept
- Return the **full sloka** (verse) for any name, with transliteration
- Explain the **Dhyanam** (meditation verses) with translations
- Share the **history and origin** — the 8 Vak Devis, the Agastya-Hayagriva narrative, the Brahmanda Purana
- Guide on **chanting practice** — Mantra form, Stotra form, auspicious days, prerequisites
- Find names related to specific **purposes** (victory, wealth, health, knowledge, etc.)

## Getting Started

### Step 1 — Create a Claude account

Go to [claude.ai](https://claude.ai) and sign up for a free account if you don't have one.

---

### Step 2 — Install Claude Code

Claude Code is a free app that lets you run AI agents like this one.

**On Mac:**
1. Go to [claude.ai/code](https://claude.ai/code)
2. Download and install the Mac app
3. Open it and sign in with your Claude account

**On Windows:**
1. Go to [claude.ai/code](https://claude.ai/code)
2. Download and install the Windows app
3. Open it and sign in with your Claude account

**Using the terminal (Mac/Linux/Windows):**
```bash
npm install -g @anthropic-ai/claude-code
```
Then run `claude login` and follow the prompts.

---

### Step 3 — Download this agent

**No-code option (recommended for most users):**

1. Go to [github.com/ramya-ssk/lalithas-guide](https://github.com/ramya-ssk/lalithas-guide)
2. Click the green **Code** button
3. Click **Download ZIP**
4. Unzip the downloaded file — you will get a folder called `lalithas-guide-main`
5. Move that folder anywhere on your computer (Desktop is fine)

**Using Git (if you are comfortable with the terminal):**
```bash
git clone https://github.com/ramya-ssk/lalithas-guide.git
cd lalithas-guide
```

---

### Step 4 — Open the folder in Claude Code

**On Mac:**
1. Open the Claude Code app
2. Click **Open Folder**
3. Navigate to and select the `lalithas-guide-main` folder
4. The agent starts automatically

**On Windows:**
1. Open the Claude Code app
2. Click **Open Folder**
3. Navigate to and select the `lalithas-guide-main` folder
4. The agent starts automatically

---

### Step 5 — Start asking questions

Claude Code will open and the Lalitha Sahasranamam agent is immediately ready. You will see a prompt where you can type your question.

---

### Step 6 — Ask anything

Try these to get started:

| Question | What it does |
|---|---|
| `What is name 1?` | Look up the very first name — Srimatha |
| `What does Ramya mean?` | Find a name by its Sanskrit word |
| `Give me the sloka for Vijaya` | See the full chantable verse |
| `Which names relate to wealth?` | Find all names connected to a theme |
| `Who wrote the Sahasranamam?` | Learn the origin and history |
| `What is the Dhyanam?` | Hear the meditation verses with meaning |
| `Which names help with success at work?` | Get purpose-specific guidance |

---

### Tips

- You do not need to spell names perfectly — the agent handles variations (e.g. "Sree Matha" finds "Srimatha")
- Ask follow-up questions naturally — "give me the sloka for that", "what about the next name", "explain that further"
- Type `exit` or press `Ctrl+C` to close the agent

## Files

| File | Description |
|---|---|
| `CLAUDE.md` | Agent instructions — read automatically by Claude Code |
| `knowledge_base.md` | Full structured content: history, Dhyanam, all 1000 names with meanings |
| `names.json` | Machine-searchable index of all 1000 names |
| `slokas.json` | All 183 grouped slokas with transliterated text |

## Sources

All content is drawn exclusively from these two sources:

1. **Meanings of Lalitha Sahasranamam** — compiled by Udaya Bhaaskar Bulusu
   https://srilalithatripurasundari.wordpress.com/home/lalita-sahasranama/impact-of-chanting-lalitha-sahasranama/sri-lalitha-sahasranamam-poorva-bhagam/meanings-of-lalitha-sahasranamam/

2. **Sree Lalitha Sahasranama Stotram** — Sri Siva Vishnu Temple, Lanham MD
   https://www.ssvt.org/wp-content/uploads/2021/07/Lalitha-Sahasranama-Stotram.pdf

This repository is shared for devotional and educational purposes only, with full credit to the original authors.

> **Content Notice:** The name meanings and sloka text in this repository are the work of Udaya Bhaaskar Bulusu and Sri Siva Vishnu Temple respectively, reproduced here for devotional and educational purposes with full attribution. No copyright is claimed over this content.

---

*Om Sri Matre Namaha*
