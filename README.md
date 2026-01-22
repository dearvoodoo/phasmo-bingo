# Phasmo Bingo – Objectives API

👉 Version française disponible ici:
[Lire le README en français](./README_FR.md)

---

Simple and clean repository:
a Phasmophobia Bingo objectives list stored as JSON, designed to be easy to use, easy to maintain, and easy to expand by the community.

The goal is simple:
centralize bingo objectives instead of everyone reinventing their own list.

---

## Main file

phasmo-objectives.json

This is the single source of truth.
It contains all objectives used to generate a Phasmophobia bingo.

---

## JSON structure

Each objective follows a simple and consistent structure.

Generic example:

{
  "id": "unique_id",
  "label": "Text displayed to the player",
  "difficulty": "easy | medium | hard",
  "type": "gameplay | challenge | random"
}

Always respect the existing structure in the file.

---

## Use cases

This file can be used for:
- Random bingo generation
- Custom bingo creation
- OBS / stream overlays
- Discord bots
- Websites or Phasmophobia tools

You take the JSON and do whatever you want with it.

---

## Usage

JavaScript:

fetch('https://raw.githubusercontent.com/dearvoodoo/phasmo-bingo/main/phasmo-objectives.json')
  .then(res => res.json())
  .then(data => {
    console.log(data);
  });

Backend:
Works with any backend language (PHP, Node, Python, etc.)
either via the GitHub raw URL or locally.

---

## Adding an objective

Contributions are welcome.

Rules:
- No duplicates
- Clear and readable text
- Must be achievable in-game
- Stay consistent with Phasmophobia
- Respect the existing format

How to contribute:
1. Fork the repo
2. Add the objective to phasmo-objectives.json
3. Clean commit
4. Open a Pull Request

---

## What this repo does NOT do

- No bingo generation logic
- No UI
- No game rules
- No gameplay systems

This repo only provides data, by design.

---

## License

Free to use.
Credits are appreciated if used in a public project.

---

## Disclaimer

This project is not affiliated with Kinetic Games.
Phasmophobia belongs to its respective owners.

Happy hunting.
