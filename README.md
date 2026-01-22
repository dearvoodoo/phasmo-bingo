# Phasmo Bingo – Objectives API

👉 Version française disponible ici:  
[Lire le README en français](./README_FR.md)

---

This repository simply exposes the objective list used by **my Phasmophobia Bingo**:

👉 https://the-coven.fr/bingo/

Nothing more, nothing less.

I made the data public so others can reuse it instead of recreating their own objective lists from scratch.

---

## What this is

- A public JSON file
- Containing all objectives used by my Phasmo Bingo
- Kept clean, consistent, and game-accurate

This is the **exact data source** used by the live bingo.

---

## Main file

**phasmo-objectives.json**

This is the single source of truth.  
If it’s not in this file, it’s not used by the bingo.

---

## JSON structure

Each objective follows the same structure.

```json
{
  "text": {
    "fr": "Faire une photo de Démon",
    "en": "Take a photo of a Demon",
  }
  "image": "https://placehold.co/300x300/161616/C0FE04/png?text=Photo+Demon"
}
