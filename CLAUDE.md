# Système multi-agents — Configuration universelle

## Profil utilisateur

- **Non-technicien** : pas de bagage en développement logiciel.
- **Testeur fonctionnel** : raisonne en comportements attendus, scénarios d'usage et résultats observables.
- **Guidé pas à pas** : une question à la fois, validation à chaque étape avant d'avancer. Ne pas surcharger.
- **Communication** : français uniquement sauf demande contraire. Zéro jargon technique sans explication préalable.

---

## Fonctionnement du système multi-agents

Ce projet est géré par une chaîne d'agents spécialisés. Chaque agent a un rôle précis et produit des livrables exploitables par le suivant.

**Structure des dossiers :**

```
agents/          — Définitions des agents (instructions, rôle, méthode)
  discovery/     — Agent Méthode & Besoin
  _base/         — Ressources partagées entre agents
livrables/       — Documents produits par les agents (markdown)
memory/          — Mémoire partagée : contexte projet et décisions clés
```

**Chaîne des agents (ordre d'intervention) :**

| Ordre | Agent | Dossier | Rôle |
|---|---|---|---|
| 1 | Méthode & Besoin | `agents/discovery/` | Formalisation du besoin, CDCF, user stories, critères d'acceptation |
| 2 | Architecture | *(à venir)* | Choix techniques, structure de l'application |
| 3 | Développement | *(à venir)* | Implémentation |
| 4 | Test | *(à venir)* | Validation fonctionnelle |

---

## Projet actif

**Projet actif : `memory/contexte_projet_JeuXplorer.md`**

---

## Règles de fonctionnement

1. **Lire le projet actif en premier** : avant toute action ou réponse, lire le fichier défini par "Projet actif" ci-dessus pour connaître le contexte, les décisions prises et les livrables existants.
2. **Ne jamais supposer** : tout ce qui n'est pas dans les fichiers doit être demandé à l'utilisateur.
3. **Un livrable à la fois** : produire, soumettre à validation, puis passer au suivant.
4. **Traçabilité** : chaque livrable est versionné (v0001, v0002…) avec date et historique des modifications.
5. **Langue** : français par défaut dans tous les livrables et toutes les communications.
