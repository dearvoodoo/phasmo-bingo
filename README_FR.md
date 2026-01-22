# Phasmo Bingo – API des objectifs

👉 Version anglaise disponible ici :  
[Read the README in English](./README.md)

---

Ce dépôt expose simplement la liste des objectifs utilisée par **mon Bingo Phasmophobia** :

👉 https://the-coven.fr/bingo/

Rien de plus, rien de moins.

J’ai rendu ces données publiques afin que d’autres puissent les réutiliser, plutôt que de recréer leur propre liste d’objectifs depuis zéro.

---

## Ce que c’est

- Un fichier JSON public
- Contenant tous les objectifs utilisés par mon Bingo Phasmo
- Maintenu propre, cohérent et fidèle au jeu

Il s’agit de **la source de données exacte** utilisée par le bingo en ligne.

---

## Fichier principal

**phasmo-objectives.json**

C’est la seule source de vérité.  
Si un objectif n’est pas dans ce fichier, il n’est pas utilisé par le bingo.

---

## Structure JSON

Chaque objectif suit la même structure.

```json
{
  "text": {
    "fr": "Faire une photo de Démon",
    "en": "Take a photo of a Demon"
  },
  "image": "https://placehold.co/300x300/161616/C0FE04/png?text=Photo+Demon"
}
