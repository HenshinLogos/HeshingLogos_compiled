# 📖 User Guide — HenshinLogos

**HenshinLogos** is a desktop application for advanced Bible study: read Scripture in multiple versions, consult commentaries and dictionaries, search with precision, build and project presentations, and organise your study work.

> **Note about citation language:** to navigate, the program recognises book names in **Spanish or English** (`Génesis 1:1`, `Genesis 1:1`, `gen 1:1`, `Gn 1:1`). The biblical text you read can be in any language, depending on the module you have installed.

---

## 📑 Table of contents

1. [Installation and first launch](#-1-installation-and-first-launch)
2. [The main window](#-2-the-main-window)
3. [Reading the Bible](#-3-reading-the-bible)
4. [The launcher: all tools](#-4-the-launcher-all-tools)
5. [Advanced search](#-5-advanced-search)
6. [Commentaries panel](#-6-commentaries-panel)
7. [Dictionaries panel](#-7-dictionaries-panel)
8. [Compare and compare-by-quote](#-8-compare-and-compare-by-quote)
9. [Bookmarks and history](#-9-bookmarks-and-history)
10. [Annotations and journal](#-10-annotations-and-journal)
11. [Presentations and viewers](#-11-presentations-and-viewers)
12. [Study resources](#-12-study-resources)
13. [Appearance and settings](#-13-appearance-and-settings)
14. [Interface language](#-14-interface-language)
15. [Creating modules with LogosBuilder](#-15-creating-modules-with-logosbuilder)
16. [Daily Verse](#-16-daily-verse)
17. [Troubleshooting](#-17-troubleshooting)

---

## 📥 1. Installation and first launch

1. Run `HenshinLogos.exe`.
2. On first launch the application automatically creates the `assets/` folder:

| Folder | Contents | Extension |
|--------|----------|-----------|
| `assets/bibles/` | Bible modules | `.bbl.mybible` |
| `assets/commentaries/` | Commentaries | `.cmt.mybible` |
| `assets/dictionaries/` | Dictionaries | `.dct.mybible` |
| `assets/presentations/` | Expositor presentations | `.pptx`, `.pdf` |
| `assets/mydata/` | Custom modules and notes | `.mybible` |

Databases use the **MySword** format, compatible with other tools in the ecosystem.

---

## 🖥️ 2. The main window

| Panel | Position | Function |
|-------|----------|----------|
| **Bible** | Left | Scripture reading, with navigation by book, chapter and verse. |
| **Commentaries** | Centre | Exegetical commentaries linked to the current passage. |
| **Dictionaries** | Right | Definitions of Hebrew and Greek words and theological terms. |

### Title bar
- **← →** — move forward and back through visited citations.
- The window has **no system frame**: drag it from the title bar.

### Panel layout (☰⁝ → Panel distribution)
- **📖 Bible only** — fills the screen.
- **📖📝 Bible + Commentaries** — screen split in two.
- **📖📝📚 All 3 panels** — full view (default).

> Each panel has a **📌 expand/collapse** button in its upper-right corner. When you change verse, the panels return to the normal view automatically.

---

## 📜 3. Reading the Bible

### Typing a citation directly
In the Bible panel's search box, type the reference and press **Enter**:

```
John 3:16
1 Corinthians 13:1-5
Psalms 23
Revelation 1
```

**Valid formats:**

| Type | Example |
|------|---------|
| Full name | `Genesis 1:1` · `Génesis 1:1` |
| Abbreviation | `gen 1:1` · `Gn 1:1` · `1Co 13:4` |
| In Spanish | `Juan 3:16` · `1Cor 13:4` |
| Verse range | `Romans 8:1-10` |
| Chapter only | `Psalms 23` → verse 1 |

### Navigation
- **◀** and **▶** change chapter.
- The **version combo** switches between installed Bibles.

### Features within the biblical text
- **Strong's numbers** — if the module includes them, they are clickable links that open the lexical definition.
- **Morphology** — grammatical analysis of Greek or Hebrew words, also clickable.
- **Footnotes (RF)** — appear as `refx` in green; click to read them.
- **Cross-references** — the icon shows how many there are; enabled or disabled from Settings.
- **Biblical promises** — if enabled, fulfilment verses are highlighted.
- **Interlinear text** — modules with an interlinear layout (word, gloss, translation) are typeset in a table, keeping fields aligned and readable even in a narrow column.
- **Bookmark verse** — click the ribbon icon to save it to bookmarks.

---

## 🧭 4. The launcher: all tools

The **:::** button in the title bar opens the launcher with **17 tools**, sorted alphabetically by their translated name.

| Tool | What it does |
|------|--------------|
| **⌕ Search** | Advanced search with fuzzy matching (section 5). |
| **≡ Compare quotes** | One passage in columns across all your versions (section 8). |
| **▣▣ Parallel view** | Same, with section navigation when there are many versions. |
| **▤ Annotations** | Personal notes editor linked to verses. |
| **▸ Expositor** | Imports and projects `.pptx` / `.pdf` presentations (section 11). |
| **✞︎ Bible Stories** | PDF viewer with children's Bible stories. |
| **〽 Timeline** | Biblical events in chronological order; click to jump to the reference. |
| **✎ Bookmarks** | Sliding panel with your saved verses, organised by section. |
| **𓆛 Biblical Typology** | Types and antitypes (e.g. the Passover lamb as a type of Christ). |
| **♡ Promises** | Viewer of biblical promises and their fulfilment. |
| **+ Add files** | Imports Bibles, commentaries, dictionaries and devotionals. |
| **☰⁝ Settings** | Panels, font, spacing, dictionaries, dyslexia mode (section 13). |
| **❃ Themes** | Changes the appearance of the whole application (section 13). |
| **𓀘 LogosBuilder** | Create and export your own modules (section 15). |
| **ⓘ Information** | Opens **this same guide** in the active language, plus active module info. |
| **𝄜 Autostart** | Configures the Daily Verse widget to start with Windows. |
| **文 Language** | Switch or add interface languages (section 14). |

> Windows left open but hidden behind the main one will **blink** on their button, to remind you they are still there.

---

## 🔍 5. Advanced search

Open the search engine with **⌕** in the launcher.

### Options
- **Modules** — which Bibles to search.
- **Range** — all Bible, Old or New Testament, or specific sections (Torah, Gospels…).
- **Search type**:
  - **Normal** — exact match.
  - **Fuzzy (approximate)** — finds similar results even with spelling errors.
- **Dynamic filter** — type at the top to filter the available modules.

Results appear highlighted; click any of them to navigate to that reference.

---

## 📝 6. Commentaries panel

1. Select a module in the top combo of the centre panel.
2. The commentary updates **automatically** when you change chapters in the Bible.
3. Use the panel's search bar to search a specific reference.

### Panel options
- **📊 Compare** — two commentary modules side by side.
- **ℹ Module information** — author, language, description.
- **Magnifying glass** — view the commentaries in a separate window.

---

## 📚 7. Dictionaries panel

1. Select one or more dictionaries in the right panel's combo.
2. Type a word and press **Enter**. Biblical references inside definitions are clickable.
3. **Search mode**:
   - **Current** — only in the selected dictionaries.
   - **Global** — across all available dictionaries.

---

## ⚖️ 8. Compare and compare-by-quote

Two distinct, complementary tools:

| | **≡ Compare quotes** | **▣▣ Parallel view** |
|---|---|---|
| Best for | Seeing many versions at once | Many versions with navigation |
| Layout | The passage in columns, all modules | By sections, with an index |
| Expandable | Yes | Yes |

Both support **Strong, morphology, RF notes and interlinear text**. Interlinear modules are typeset in tables so fields stay aligned and legible even in a narrow column.

---

## 🔖 9. Bookmarks and history

### Bookmarks (✎)
1. Navigate to the verse.
2. Click the ribbon icon next to the verse.
3. It is saved to the selected section of the panel.

Create thematic sections ("Sermons", "Personal Study", "Favorites"). They are stored in `bookmarks.json`.

### History
The **← →** buttons in the title bar move through the citations visited in the session.

---

## ✍️ 10. Annotations and journal

**Annotations (▤)**: personal notes editor with rich formatting (bold, italic, lists, colour), linked to a specific verse.

**Journal (`.bok.mybible`)**: devotional books open in the dictionaries panel. You can **edit the title and content** of each entry, and when you add a new entry the next reference and date are filled in automatically.

---

## 🎬 11. Presentations and viewers

**Expositor (▸)** imports `.pptx` and `.pdf` files and projects them with automatic transitions and keyboard shortcuts, with biblical integration: you can jump to a reference from the presentation itself.

**Bible Stories (✞︎)** is a PDF viewer with children's Bible stories, with page navigation.

---

## ⏳🕊️📚 12. Study resources

| Resource | What it offers |
|----------|----------------|
| **Timeline (〽)** | Biblical events in chronological order. Click an event to go to its reference. |
| **Biblical Typology (𓆛)** | Types and antitypes: links between figures and events of the Old and New Testaments. |
| **Promises (♡)** | Sliding panel with biblical promises and their fulfilment. |

---

## 🎨 13. Appearance and settings

### Themes (❃)
🌑 **Dark** (default) · ☀️ **Light** · 🔵 **Word** · 🌌 **Futuristic** · 💜 **Neon** · 🔷 **Future**

The selected theme is saved and applied to the whole interface, including secondary windows.

### Settings (☰⁝)

| Section | Options |
|---------|---------|
| **📐 Panel distribution** | Bible only · Bible + Commentaries · All 3 panels |
| **🔤 Font size** | From 8 px to 24 px, applied to all panels |
| **📏 Verse spacing** | From 4 px to 30 px |
| **📖 Strong's Dictionary** | Default · Custom Strong |
| **📚 Morphological Dictionary** | Default · Custom Morphological |
| **🔗 Cross-references** | Enabled · Disabled |
| **✨ Biblical promises** | Enabled · Disabled |
| **🔤 Dyslexia mode** | On · Off (**OpenDyslexic** font) |

All changes apply **in real time**, no restart needed.

### The `settings.json` file
Stores your configuration and can be edited by hand. The most useful keys:

```json
{
  "theme": "Dark",
  "language": "En_en",
  "paneles": 3,
  "font_size": 14,
  "verse_spacing": 8,
  "dyslexia_mode": false,
  "cross_refs_enabled": false,
  "promises_enabled": false,
  "strong_db_path": null,
  "morph_db_path": null,
  "ultima_cita": "John 3:16",
  "bible_version": "RV1960+",
  "modulos_seleccionados": []
}
```

`panelas` accepts `1`, `2` or `3`. A `null` in the dictionary paths means "use the default".

---

## 🌐 14. Interface language

**文** button in the launcher.

- 🇪🇸 **Español** · 🇬🇧 **English** · and any custom language you have imported.

> Changing the language translates the **interface**, but **not** the biblical book names used for navigation: those remain accepted in Spanish and English regardless of the interface language.

### Adding a new language
1. Click **📤 Export template** — generates a JSON with **every** interface key and its Spanish value.
2. Translate the **values** (not the keys). You can use DeepL, Google Translate, an AI, or do it by hand in Notepad.
3. Write the visible language name in the `_language_name` key (for example `"Français"`).
4. Save the file using the language code as its name (`Fr_fr.json`, `De_de.json`…).
5. Go back to **文** → **📥 Import translation** and select the file.

The language becomes available immediately and persists between sessions. Keys you do not translate automatically fall back to Spanish.

> The template also includes **content** keys (Bible stories, timeline, typologies), not just interface strings.

---

## 🛠️ 15. Creating modules with LogosBuilder

**𓀘** button in the launcher.

### What you can do
- Create custom Bibles (`.bbl`), commentaries (`.cmt`), dictionaries (`.dct`) and devotional books (`.book`).
- Edit existing records in `.hlgx` modules.
- **Export** any module to the standard **MySword** format to share it.

### Workflow
1. **➕ New Module** → choose the type (Bible, Commentary, Dictionary or Book).
2. Type the name and create the file.
3. Use the editor to add content verse by verse.
4. **Export to MySword** when finished. A **progress bar** appears during export, and references are converted automatically to the target format.

---

## 🔔 16. Daily Verse

An independent widget that displays verses in the corner of your screen.

- Open it with the **𝄜** launcher button, or configure it to start with Windows.
- Choose between different **reading plans** (for example, a year-long journey) and set the **rotation interval**.
- Progress is saved automatically.

---

## ❓ 17. Troubleshooting

| Problem | Solution |
|---------|----------|
| No Bibles appear in the combo | Check that there are `.bbl.mybible` files in `assets/bibles/`. |
| Commentaries won't load | Verify that `.cmt.mybible` files are in `assets/commentaries/`. |
| Error searching for a book | Use Spanish or English names: `gen 1`, `john 3`, `1co 13`. |
| An interlinear verse appears empty or with `()` | The module has tags in an unexpected format; try another view or report it. |
| Window is not responding | Wait a moment: indexing dictionaries can take time. |
| Secondary windows "disappear" | Click their button in the launcher; it will blink if minimised. |
| Settings are not saved | Check that `settings.json` is not read-only. |

---

## 📄 License

HenshinLogos is **proprietary** software. You are free to use it on your personal, ministry or academic devices, but you **may not modify, patch or distribute derivative versions** without the author's written permission.

The full license is in the `LICENSE` file. It is governed by the laws of the Republic of Honduras.

---

*User guide for HenshinLogos v5.1*
