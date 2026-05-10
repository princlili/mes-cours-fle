# mes-cours-fle — FLE Teaching Tools
*Resources for teaching French as a Foreign Language — levels A1–B1*

---

## What is this?

A collection of practical tools for preparing and teaching French as a Foreign Language: ready-to-use lesson canvases, reusable templates, course plans and interactive presentations.

Everything is built around an **inductive and communicative approach**, structured with a clear pedagogical arc: **Hinführung → Erarbeitung → Festigung → Sicherung** (warm-up → discovery → consolidation → transfer).

---

## Lesson Canvases — core of this repo

Canvases are HTML documents designed to be consulted on a tablet (Remarkable 2) during class. They contain what the teacher says, what they do, follow-up questions and timing — nothing else.

### Reusable templates

| File | Usage |
|------|-------|
| `canevas/canevas_h2_lundi_template.html` | 3 × 45 min · buffers 8/8/7 · autonomous workshop in session 3 |
| `canevas/canevas_h2_mercredi_template.html` | 2 × 45 min + Lernatelier · buffers 2 × 7 min |

**How to use a template:**
1. Download the HTML file + both CSS files below
2. Open in any text editor (Notepad++, Geany, VS Code…)
3. Replace all `[brackets]` with your content
4. Duplicate the variable phase blocks as needed

### Stylesheets

| File | Usage |
|------|-------|
| `canevas/remarkable-style.css` | Full preparation version — all notes and details visible |
| `canevas/remarkable-compact.css` | In-class consultation version — instructions and timing only |

To switch between versions: change one line in the HTML `<head>`.

### AI-assisted preparation

This system is designed to work with Claude (Anthropic). The file `canevas/meta-prompt-FLE.md` contains the complete prompt to use Claude as a co-planner: how to brief it, what to ask, how the templates fit into the workflow.

---

## Other resources

### Interactive presentations (Reveal.js)
HTML slideshows for classroom use, built with [Reveal.js](https://revealjs.com/).

- [Base template](https://princlili.github.io/mes-cours-fle/cours-fle.html)
- [Course index](https://princlili.github.io/mes-cours-fle/cours.html)

### Course plans (Kursplans)
Semester schedules generated from Org-mode.

- [Français B1 (3/3) — 2026](https://princlili.github.io/mes-cours-fle/kursplans/B1-3/kursplan_B1-3.html)
- [Français A2 (2/3) — 2026](https://princlili.github.io/mes-cours-fle/kursplans/A2-2/kursplan_A2-2.html)
- [Français H2 — 2026](https://princlili.github.io/mes-cours-fle/kursplans/H2/Kursplan_FrancaisH2.html)

---

## Pedagogical approach

- **Inductive first**: learners observe and hypothesize before seeing the rule
- **Oral production as a priority**: grammar serves communication, not the other way around
- **Noticing**: explicit real-time valorization of learner successes
- **Visual scaffolding**: no instruction is ever given without a visual support

---

## Questions / contributions

This repo is shared freely. If you have questions or want to contribute, open an [Issue](https://github.com/princlili/mes-cours-fle/issues).

---

*Princlili · FLE A1–B1 · Lucerne, Switzerland*
