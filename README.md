# Système multi-agents IA — Guide de démarrage

## Ce qu'est ce système

Un environnement de travail multi-agents IA conçu pour accompagner **n'importe quel projet** de manière structurée, étape par étape. Chaque agent a un rôle précis (formaliser le besoin, concevoir l'architecture, développer, tester…) et produit des livrables lisibles et réutilisables par le suivant.

Ce système est **réutilisable** : il suffit de changer le fichier de contexte pour travailler sur un autre projet.

---

## Profil utilisateur

- **Non-technicien** : pas de bagage en développement logiciel.
- **Testeur fonctionnel** : raisonnement par comportements attendus, scénarios d'usage et résultats observables.
- Les agents adaptent leur langage et leur rythme à ce profil.

---

## Comment démarrer

1. Ouvrir **WSL** (Windows Subsystem for Linux)
2. Aller dans ce dossier :
   ```
   cd /mnt/c/Users/Professionnnel/Documents/00_ProjetAgent_Restrict
   ```
3. Lancer Claude :
   ```
   claude
   ```
4. L'agent lit automatiquement `CLAUDE.md`, puis le fichier du **projet actif**, et se met en contexte avant de répondre.

---

## Structure des dossiers

```
agents/          — Définitions des agents IA (instructions, rôle, méthode)
  discovery/     — Agent Méthode & Besoin
  _base/         — Ressources partagées entre agents
livrables/       — Documents produits par les agents (fichiers markdown)
  besoin/        — Note de cadrage, CDCF, user stories, critères d'acceptation
  01_discovery/  — Livrables de la phase Discovery
memory/          — Mémoire partagée entre agents
```

| Dossier | Rôle |
|---|---|
| `agents/` | Contient les instructions de chaque agent IA |
| `livrables/` | Contient tous les documents produits au fil du projet |
| `memory/` | Contient le contexte du projet actif et les décisions clés |

---

## Projet actif

**Projet actif : `memory/contexte_projet_JeuXplorer.md`**

Ce fichier contient la description du projet en cours, les personas, les décisions prises et les livrables existants. L'agent le lit en priorité à chaque démarrage.

---

## Changer de projet

Pour travailler sur un autre projet :

1. Créer un nouveau fichier `memory/contexte_projet_NomDuProjet.md`
2. Modifier **uniquement** la ligne `Projet actif` dans `CLAUDE.md` :
   ```
   Projet actif : memory/contexte_projet_NomDuProjet.md
   ```
3. Le reste du système (agents, structure, règles) reste identique.

---

## Langue de travail

**Français par défaut.** Tous les livrables et échanges avec les agents se font en français, sauf demande contraire explicite.
