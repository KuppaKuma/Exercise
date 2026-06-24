# 🏋️ Workout & Exercise Repository

This repository contains logs, guidelines, and resource files for physical training, nutrition, and methodology. 

It is synchronized from a private source repository (`kuppabear/Exercise`) to a public hobbies repository (`KuppaKuma/Exercise`) with automated identity scrubbing (names, emails, and usernames removed).

---

## 📁 Repository Structure

*   **`inbox.md`**: The ingestion document for pasting raw articles, YouTube transcripts, subtitles, or mobile quick notes.
*   **`Push.md`**: Push day routines (Chest, Shoulders, Triceps).
*   **`Pull.md`**: Pull day routines (Back, Biceps, Rear Delts).
*   **`Legs.md`**: Leg day routines (Quads, Hamstrings, Glutes, Calves).
*   **`Training Principles & Methodology.md`**: Core rules, theories, and protocols for progressive overload and tracking.
*   **`Nutrition & Supplements.md`**: Diet guidelines, supplement schedules, and macros.
*   **`Food/`**: A subfolder for specific regional dishes, recipe ideas, and grocery items (e.g., `HongKong.md`).
*   **`attach/`**: Media assets, screenshots, and visual charts.
*   **`.archive/`**: Local-only folder used to stash processed raw sources. **This folder is completely ignored by Git and Obsidian.**

---

## 🔄 Automated Ingest & Clean Pipeline

```mermaid
flowchart LR
    Ingest[Raw Content / Transcripts] --> Inbox[inbox.md]
    Inbox --> Digest[Extract & Organize into Push/Pull/Legs/etc.]
    Digest --> Archive[Move source files to .archive/]
```

---

