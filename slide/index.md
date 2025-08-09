---
marp: true
title: "OmegaT: Desktop Translation Platform for Professionals and FLOSS Contributors"
description: Presentation for COSCUP 2025 - Taiwan L10N in FLOSS Projects
theme: gaia
class: lead
paginate: true
style: |
     :root {
         --color-background: #fff;
         --color-foreground: #333;
         --color-highlight: #f96;
         --color-dimmed: #888;
     }
---

<!-- Title Slide -->
<!-- _class: gaia lead -->
<!-- _paginate: false -->
<!-- _header: '' -->
<!-- _footer: '' -->

![bg right:40% 100%](images/banner-mobile.png)

# OmegaT
### Desktop Translation Platform for Professionals and FLOSS Contributors

**Hiroshi Miura**  
🇹🇼 L10N in FLOSS Projects

---

<!-- 講演者紹介 -->

![bg right:40% 50%](images/self-stand.jpg)

**Who am I**
- Hiroshi Miura from Tokyo
- **FLOSS** contributor: Linux, Python etc.
- Lead **developer** of OmegaT
- President of **OSM Foundation Japan**
- LinkedIn(@miurahr)

---

<!-- Opening hook -->

## 🌍 Why L10N Matters

- Bring open‑source software -> Local users
- ❌ language barriers, 💕 fosters inclusive
- Supports digital sovereignty and community growth
- FLOSS thrives when translated by communities themselves

---

<!-- What is OmegaT -->

## 🚀 OmegaT: What & Why?

- Free/Open‑source Computer‑Assisted Translation (CAT) tool
- Developed by volunteers; cross‑platform Java application (Windows/macOS/Linux)
- Great starting point for professionals and newcomers alike
- High speed / high-quality translation for each translator

![bg right:30% 30%](images/OmegaT_for_Beginners_en_htm_1bb6e15fce01258c.jpg)

---

## 🛠 What Makes a CAT Tool Useful?

- Builds a **Translation Memory (TM)** for consistent reuse
- Supports **Glossaries** to standardize terminology
- Combines AI-powered MT, and community knowledge
- Segment(片段)‑based interface ensures **no text is missed**
- Keeps formatting across various document types

---

## ⏱ Instant‑Start

1. **Create a new project**: name, source and target languages
2. **Import source files** into `/source` folder
3. **Translate segment by segment**: Ctrl + U to move through segments, inline editing
4. **Validate tags** before export result: Ctrl + Shift + V
5. **Generate translated documents**: Ctrl + D → outputs in `/target` folder

---

## 🔎 Interface & Panes

![](images/omegat-startup-screen.png)

--- 

## ✅ Feature Highlights

- Handles **fuzzy matches** from TMX Memory, AUTO‑propagates across segments
- Glossary lookup and **bi‑lingual dictionaries**
- Supports **multiple file types** such as ODT, DOCX, Markdown, PO-file, HTML, etc.
- Simple **keyboard-driven workflow**, efficient for power users
- Modular extension by bundled and 3rd party **Plugins** 

---

## 🔎 Interface and Panes

- **Main panes**: Editing (4), Fuzzy Matches(5), Glossary(2), Property(7)
- **Optional panes**: MT(3), Dictionary(6), Notes(1), Comments
- Tag walls are grayed out, non‑editable to prevent corruption

![bg right:40% 80%](images/omegat--screen-argumented.png)

---

## 🧩 How FLOSS Users Can Benefit

- Volunteers can translate documentation, manuals, and UI without know the formats
- Supports sharing *memories* and *glossaries* across projects
- Interoperable with Web platforms such as Transifex, Crowdin, and Wikimedia

---

## ⚽ Easy Team work 共作

<div class="mermaid">
graph TB
    %% GitHub Repository
    GH[GitHub Repository<br/>Team Project <br/>ex EN-ZH]
    XML[(Translation Memory DB<br/>XML File<br/>project-save.tmx)]
    %% OmegaT Desktop Applications
    T1[Translator 1<br/>OmegaT Desktop]
    T2[Translator 2<br/>OmegaT Desktop]
    T3[Translator 3<br/>OmegaT Desktop]
    T4[Translator N<br/>OmegaT Desktop]
    %% Connections from GitHub to Translators
    GH -->|Clone/Pull<br/>Project Files| T1
    GH -->|Clone/Pull<br/>Project Files| T2
    GH -->|Clone/Pull<br/>Project Files| T3
    GH -->|Clone/Pull<br/>Project Files| T4
    %% Connections from Translators to Auto-merge
    T1 -->|Translation<br/>Segments<br/>Merge| XML
    T2 -->|Translation<br/>Segments<br/>Merge| XML
    T3 -->|Translation<br/>Segments<br/>Merge| XML
    T4 -->|Translation<br/>Segments<br/>Merge| XML
    %% XML back to GitHub
    XML -->|Push/Commit<br/>Updated TM| GH
    %% Styling
    classDef translator fill:#e1f5fe,stroke:#0277bd,stroke-width:2px
    classDef github fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px
    classDef database fill:#e8f5e8,stroke:#2e7d32,stroke-width:2px
    class T1,T2,T3,T4 translator
    class GH github
    class XML database
</div>


---

## New Era: AI & Translation

- Generative AI services (e.g. ChatGPT, Gemini)
- Convenience, but vendor lock-in risk
- Privacy, licensing, and data concerns
- FLOSS needs **open** and **user-controlled** tools

![bg right:50% 50%](images/freedom_cat_presentation.svg)

---

## 🤖 AI‑Augmented Workflow

- Plugins for major AI/MT engines: DeepL, Google Tr, TexTra, Azure Tr, OpenAI etc.
- Apply AI suggestions **when needed**, without being locked in
- Use **memory** and **glossaries** first; machine translation is helper

---

## OmegaT 6.1 Beta: New features?

- Bundled spell checker dictionaries
- Better UI for Hi-resolution display
- Support Windows 11/Linux on ARM64
- Support M1/M2 Mac
- More Installer variants: DEB and RPM

---

## What's Coming in Future (plans)?

- 🧩 Online Plugin catalog and install
- ✅ Support for popular Gen-AI engines
- 🔍 AI-assisted Quality Assurance
- 🌍 Better support for FLOSS localization workflows

---

## 🤝 Join the OmegaT Community

- Web site: *omegat.org*
- GitHub repo: *omegat-org/omegat*
- Active user group and forum support
- Call for Contribution: code, plugins, **translations**, documentation

---

## 🏃‍♂️ Call to Action

- Download OmegaT (**free**) → [omegat.org](https://omegat.org)
- Join our community: contribute l10n, ideas
- Try it out with OmegaT L10N/zh-TW project
- Help build a multilingual free software/open-source ecosystem!

---

## 🙏 Thank You!

**Questions & discussion welcome!**  
Let’s make FLOSS truly global together with OmegaT.  
<!-- Add this anywhere in your Markdown file -->
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>
_Hiroshi Miura_ - [omegat.org](https://omegat.org) - GitHub: *omegat-org/omegat*



