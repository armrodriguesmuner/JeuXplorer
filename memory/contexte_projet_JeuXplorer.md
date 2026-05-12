# Contexte projet — JeuXplorer

## Description

Application mobile (Android & iOS) de lien social gamifiée. Les utilisateurs gagnent des points en réalisant des interactions physiques réelles : scan mutuel de QR codes, rencontres validées, territoire revendiqué dans la ville. L'objectif est de réduire l'isolement social de manière subtile et ludique, sans que l'application ne ressemble à un réseau social ou une app de rencontre.

## Identité utilisateur

Anonyme ("Agent XXX") — pas de photo, pas de genre, pas de nom réel.

## Public cible

- Âge : 18–30 ans
- Âge minimum légal : 18 ans
- Premiers utilisateurs visés : jeunes adultes urbains (étudiants, actifs en télétravail, profils sociables)

## Lancement

Une ville pilote (à définir) → France → international.  
Application en français, structure prête pour l'anglais dès la v1.

## Prototype

| Élément | Détail |
|---|---|
| Dépôt GitHub | https://github.com/armrodriguesmuner/JeuXplorer |
| Application en ligne | https://armrodriguesmuner.github.io/JeuXplorer/ |
| Technologie | Application web (HTML / JS / Leaflet.js) — testable dans Chrome Android |
| Mécanique implémentée | Bouton Capturer → zone GPS 100 m → +10 pts |
| Rayon | 100 m (paramétrable) |
| Statut | Prototype v0001 — déployé le 12/05/2026 |

## Agents actifs sur ce projet

| Agent | Fichier | Statut |
|---|---|---|
| Méthode & Besoin | `agents/discovery/methode_besoin.md` | En cours |
| Chercheur Expert Jeux | `agents/discovery/chercheur_expert_jeux.md` | Actif |
| Innovant Game Systems | `agents/discovery/innovant_game_systems.md` | Actif |
| Architecture | *(à venir)* | — |
| Développement | *(à venir)* | — |
| Test | *(à venir)* | — |

## Livrables de référence

| Livrable | Fichier | Version | Date |
|---|---|---|---|
| Note de cadrage | `livrables/besoin/note_de_cadrage.md` | v0004 | 01/05/2026 |
| Prototype web | `docs/index.html` | v0001 | 12/05/2026 |

## Points ouverts (à affiner)

- Mécanique de rareté (Interaction Rare quotidienne)
- Système de streak et règles de perte/récupération
- Détail du "Pacte de rencontre" et mécanismes de signalement
- Portée du leaderboard (ville, quartier, amis ?)
- Sécurité des transactions de points (blockchain vs alternative)
