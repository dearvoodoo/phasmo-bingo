# Phasmo Bingo – Objectives API

👉 French version available here:
[Lire le README en français](./README_FR.md)

---

This repository simply exposes the objective list used by my Phasmophobia Bingo:

👉 https://the-coven.fr/bingo/

Nothing more, nothing less.

I made the data public so others can reuse it instead of recreating their own objective lists from scratch.

---

## What this is

- A public JSON file
- Containing all objectives used by my Phasmo Bingo
- Kept clean, consistent, and game-accurate

This is the exact data source used by the live bingo.

---

## Main file

phasmo-objectives.json

This is the single source of truth.
If it’s not in this file, it’s not used by the bingo.

---

## JSON structure

Each objective follows the same structure.
```json
{
  "text": {
    "fr": "Faire une photo de Démon",
    "en": "Take a photo of a Demon"
  },
  "image": "https://placehold.co/300x300/161616/C0FE04/png?text=Photo+Demon"
}
```
---

## Requests, changes & new objectives

All requests happen on my Discord.

If you want to:
- Suggest a new objective
- Modify an existing one
- Report an issue or inconsistency

Join here:
https://linktr.ee/dearvoodoo

Then go to the channel:
#phasmophobia-data

I review everything manually to keep the bingo consistent and balanced.

---

## Support the project

If this data helps you and you want to support my work:

Ko-fi:
[https://ko-fi.com/voodoo_](https://ko-fi.com/voodoo_)

Totally optional, always appreciated.

---

## Disclaimer

This project is not affiliated with Kinetic Games.
Phasmophobia belongs to its respective owners.

Happy hunting.
