---
name: fi-legal-mcp-skill
description: Official Finland (FI) legislation, multi-tier court precedent research, and citation verification skill.
version: 2.0.0
author: JurisAtlas
license: MIT
---

# Finland Legal Research & Multi-Tier Case Law Skill (`fi-legal-mcp`)

Use this skill whenever the user asks a legal question, drafts a pleading or contract, or researches case law across any judicial instance in **Finland (FI)**.

## Verification & Research Rules

1. **Citation Verification:** Never fabricate a statutory provision or case citation. Query `search_legislation`, `search_case_law`, `search_tiered_court_decisions`, or `verify_citation` before citing any authority (e.g., `KKO:2024:15 or 731/1999`).
2. **Multi-Tier Judicial Coverage:**
   - **First Instance (Trial / Municipal / District):** 20 Käräjäoikeudet (District Courts), 6 Hallinto-oikeudet (Regional Administrative Courts) & Markkinaoikeus (Market Court)
   - **Second Instance (Cantonal / Regional / Appellate):** 5 Hovioikeudet (Courts of Appeal: Helsinki, Turku, Vaasa, Itä-Suomi, Rovaniemi) & Vakuutusoikeus
   - **Supreme & Constitutional Instance:** Korkein oikeus (KKO — Supreme Court) & Korkein hallinto-oikeus (KHO — Supreme Administrative Court)
   - **Primary Tiered Database:** Finlex Oikeuskäytäntö (finlex.fi/fi/oikeus — KKO, KHO, Hovioikeudet & Hallinto-oikeudet) (`https://www.finlex.fi/fi/oikeus/`)
