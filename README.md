# Lalitha Sahasranamam Agent

A Claude Code agent that serves as a complete, searchable guide to **Sri Lalitha Sahasranamam** — the 1000 sacred names of Sri Lalitha Tripura Sundari.

## What it can do

- Look up any of the **1000 names** by number, Sanskrit name, or concept
- Return the **full sloka** (verse) for any name, with transliteration
- Explain the **Dhyanam** (meditation verses) with translations
- Share the **history and origin** — the 8 Vak Devis, the Agastya-Hayagriva narrative, the Brahmanda Purana
- Guide on **chanting practice** — Mantra form, Stotra form, auspicious days, prerequisites
- Find names related to specific **purposes** (victory, wealth, health, knowledge, etc.)

## How to use

1. Install [Claude Code](https://claude.ai/code)
2. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/lalithas-guide.git
   cd lalithas-guide
   ```
3. Start the agent:
   ```bash
   claude
   ```
4. Ask anything:
   - *"What is name 307?"*
   - *"What does Ramya mean?"*
   - *"Give me the full sloka for Moola Prakrithi"*
   - *"Which names relate to success at work?"*
   - *"Tell me the history of who wrote the Sahasranamam"*

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

---

*Om Sri Matre Namaha*
