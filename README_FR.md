# Phasmo Bingo – Objectives API

👉 English version available here:
[Read the README in English](./README.md)

---

Repo simple et clean :
une liste d’objectifs pour un Bingo Phasmophobia, au format JSON, pensée pour être facile à utiliser, facile à maintenir et facile à enrichir par la communauté.

Le but est clair :
centraliser les objectifs pour éviter que chacun refasse son bingo dans son coin.

---

## Fichier principal

phasmo-objectives.json

C’est la source de vérité du projet.
Il contient tous les objectifs utilisables pour générer un bingo Phasmophobia.

---

## Structure du JSON

Chaque objectif respecte une structure simple et cohérente.

Exemple générique :
```json
{
  "id": "unique_id",
  "label": "Texte affiché au joueur",
  "difficulty": "easy | medium | hard",
  "type": "gameplay | challenge | random"
}
```
Respecte toujours le format déjà en place dans le fichier.

---

## Cas d’usage

Ce fichier peut servir à :
- Générer un bingo aléatoire
- Créer un bingo personnalisable
- Overlay OBS / outil de stream
- Bot Discord
- Site web ou application Phasmophobia

Tu prends le JSON, tu l’exploites comme tu veux.

---

## Utilisation

JavaScript :
```js
fetch('https://raw.githubusercontent.com/dearvoodoo/phasmo-bingo/main/phasmo-objectives.json')
  .then(res => res.json())
  .then(data => {
    console.log(data);
  });
```
Backend :
Compatible avec n’importe quel langage (PHP, Node, Python, etc.)
via l’URL raw GitHub ou en local.

---

## Ajouter un objectif

Les contributions sont bienvenues.

Règles :
- Pas de doublon
- Texte clair et compréhensible
- Objectif réalisable en jeu
- Cohérent avec Phasmophobia
- Respect du format existant

Comment contribuer :
1. Fork le repo
2. Ajouter l’objectif dans phasmo-objectives.json
3. Commit propre
4. Pull Request

---

## Ce repo ne fait PAS

- Pas de génération de bingo
- Pas d’interface utilisateur
- Pas de logique de jeu
- Pas de règles

Ce repo fournit uniquement les données.

---

## Licence

Libre d’utilisation.
Crédit apprécié si utilisé dans un projet public.

---

## Disclaimer

Projet non affilié à Kinetic Games.
Phasmophobia appartient à ses créateurs.

Bon hunt.
