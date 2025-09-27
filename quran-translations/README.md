# Quran Translations (Maranao Project)

This repository contains multiple translations of the Qur'an in JSON format, ready for integration into apps.

## Available Translations
- `quran_english.json` – English (Sahih International style, via QuranEnc)
- `quran_tagalog.json` – Tagalog (Philippines)
- `quran_bisayan.json` – Bisayan (Philippines)
- (Maranao JSON managed separately in the Tafsir repo)

## Format Example
```json
{
  "surah_number": 1,
  "ayah_number": 1,
  "text_en": "In the name of Allah, the Most Compassionate, the Most Merciful.",
  "text_tl": "Sa ngalan ng Allah, ang Pinakamaawain, ang Pinakamaawain.",
  "text_bis": "Sa ngalan sa Allah, ang Maloloy-on, ang Maloloy-on."
}
```

## Source & Attribution
- English: [QuranEnc.com](https://quranenc.com)
- Tagalog & Bisayan: Collected & digitized by project contributors
- Maranao: By Engr. Abdulbasit Tamano (Tafsir sa Basa Maranao)

---
This combined repo ensures consistent ayah numbering across all translations for easy multilingual integration.
