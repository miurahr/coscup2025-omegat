---
marp: true
title: OmegaT: Desktop Translation Platform for Professionals and FLOSS Contributors
description: Presentation for COSCUP 2025 - Taiwan L10N in FLOSS Projects
theme: uncover
class: lead
paginate: true
---

<!-- Title Slide -->
# OmegaT
### Desktop Translation Platform for Professionals and FLOSS Contributors

**Hiroshi Miura**  
COSCUP 2025 · TR210 · August 9, 13:40–14:10  
🇹🇼 Taiwan L10N in FLOSS Projects

---

## 🌍 Why Localization (L10N) Matters

- Brings open‑source software to global users
- Breaks language barriers, fosters inclusivity
- Supports digital sovereignty and community growth
- FLOSS thrives when translated by communities themselves

---

## New Era: AI & Translation

- Generative AI services (e.g. ChatGPT, Gemini)
- Convenience, but vendor lock-in risk
- Privacy, licensing, and data concerns
- FLOSS needs **open** and **user-controlled** tools

---

## 🚀 OmegaT: What & Why?

- Free/open‑source Computer‑Assisted Translation (CAT) tool
- Developed by volunteers; cross‑platform Java app (Windows/macOS/Linux)
- Great starting point for professionals and newcomers alike

---

## 🛠 What Makes a CAT Tool Useful?

- Builds a **Translation Memory (TM)** for consistent reuse
- Supports **Glossaries** to standardize terminology
- Segment‑based interface ensures no text is missed
- Retains formatting across complex document types (DOCX, ODT, HTML etc.)

---

## ⏱ Instant‑Start

1. **Create a new project**: name, source and target languages
2. **Import source files** into `/source` folder via Project menu
3. **Translate segment by segment**: Ctrl + U to move through segments, inline editing
4. **Validate tags** before export: Ctrl + Shift + V
5. **Generate translated documents**: Ctrl + D → outputs in `/target` folder

---

## 🔎 Interface & Core Panes

- **Main panes**: Editing (source/target), Fuzzy Matches, Glossary
- **Optional panes**: MT, Dictionary, Notes, Comments
- Tag walls are grayed out, non‑editable to prevent corruption 

---

## Interface

![center: 80%](images/omegat-startup-screen.png)

---

## ✅ Feature Highlights

- Handles **fuzzy matches** from TMX Memory, AUTO‑propagates across segments
- Glossary lookup and **bi‑lingual dictionaries**
- Supports **multiple file types**, batch project translation
- Simple **keyboard-driven workflow**, efficient for power users

---

## 🤖 AI‑Augmented Workflow

- Plugins for major MT engines: DeepL, Google Translate, TexTra etc.
- Apply AI suggestions *when needed*, without being locked in
- Use TM and glossaries first; then machine translation as a helper


---

## 🧩 How FLOSS Users Can Benefit

- Volunteers/localizers can translate documentation, manuals, and UI
- Supports sharing TMX and glossaries across projects and translators
- Ideal for projects like LibreOffice, WeeklyOSM, local L10N initiatives

---

## 🤝 Join the OmegaT Community

- GitHub repo: *omegat-org/omegat*
- Active user group and forum support
- Contribute: code, plugins, translations, documentation

---

## What's Coming Next?

- 🧩 Plugin system improvements
- ✅ XLIFF 2.0 filter support
- 🔍 AI-assisted Quality Assurance
- 🌍 Better support for FLOSS localization workflows

---

## 🏃‍♂️ Call to Action

- Download OmegaT (**free**) → [omegat.org](https://omegat.org)
- Try it out with a FLOSS project or documentation
- Join our community: contribute plugins, ideas
- Help build a multilingual open-source ecosystem!

---

## 🙏 Thank You!

**Questions & discussion welcome!**  
Let’s make FLOSS truly global together with OmegaT.  

_Hiroshi Miura_ - [omegat.org](https://omegat.org) - GitHub: *omegat-org/omegat*


<!-- Add this anywhere in your Markdown file -->
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>
