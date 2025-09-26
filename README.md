# Quran Resources

This repository contains **resource files** used by the [Maranaw Tafsir App](https://github.com/asharytamano/maranaw_tafsir_app) and related projects.  
It serves as an online storage for Qur’an translations and supplementary data.

---

## 📦 Contents
- **Tagalog Translation**
  - Per-surah JSON files (`tagalog_surahs_json/001.json` … `114.json`)
  - Original source formats (CSV, XML, XLS)
- **(Planned)** Other Philippine languages:
  - Bisayan Translation
  - Tausug Translation
  - More to follow

---

## 📑 JSON Format
Each surah file follows this structure:

```json
{
  "surah_number": 1,
  "ayahs": [
    {
      "ayah_number": 1,
      "translation_tl": "Sa ngalan ni Allāh, ang Napakamaawain, ang Maawain.",
      "footnotes": "Optional notes per ayah"
    }
  ]
}
