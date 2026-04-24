# LienSocial — Contexte global du projet

## Description du projet

Application mobile (Android & iOS) de lien social gamifiée. Les utilisateurs gagnent des points en réalisant des interactions physiques réelles : scan mutuel de QR codes, rencontres validées, territoire revendiqué dans la ville. L'objectif est de réduire l'isolement social de manière subtile et ludique, sans que l'application ne ressemble à un réseau social ou une app de rencontre.

**Identité utilisateur** : anonyme ("Agent XXX") — pas de photo, pas de genre, pas de nom réel.  
**Public cible** : 18–30 ans, âge minimum 18 ans.  
**Lancement** : une ville pilote, puis France, puis international.  
**Langue** : français, structure prête pour l'anglais.

## Agents du projet

Les agents sont définis dans le dossier `agents/`. Chaque agent a son propre fichier de définition.

| Agent | Fichier | Rôle |
|---|---|---|
| Méthode & Besoin | `agents/discovery/methode_besoin.md` | Formalisation du besoin, CDCF, user stories, critères d'acceptation |
| *(à venir)* | `agents/_base/` | Agents futurs (Architecture, Développement, Test…) |

## Structure du projet

```
agents/          — Définitions des agents IA
livrables/       — Documents produits par les agents
memory/          — Mémoire partagée (contexte projet, décisions clés)
```

## Livrables de référence

- `livrables/besoin/note_de_cadrage.md` — v0001 validée le 24/04/2026

## Langue de travail

Français par défaut. Toute communication avec l'utilisateur se fait en français.
