# Note de cadrage — v0001
*Date : 24 avril 2026 | Statut : Validé*

---

## 1. Problème résolu

Malgré l'omniprésence des réseaux sociaux numériques, les 18–30 ans se sentent de plus en plus isolés dans la vie réelle. Les liens en ligne ne remplacent pas les interactions physiques et le sentiment d'appartenance à un groupe. Il n'existe pas d'outil ludique et non-intrusif pour encourager et récompenser les rencontres réelles entre personnes.

---

## 2. Personas

**Lucas, 22 ans — L'étudiant déraciné**
Arrivé à Paris pour ses études, il a un réseau en ligne actif mais peu d'amis proches sur place. Il cherche un prétexte léger pour aborder des inconnus sans paraître bizarre. Il est à l'aise avec les applications mobiles.

**Camille, 28 ans — L'active en télétravail**
Jeune professionnelle, elle travaille depuis chez elle 3 jours sur 5. Ses amis sont dispersés en France. Elle ressent un vide social réel malgré un Instagram bien rempli. Elle veut renouer avec des interactions spontanées sans que cela ressemble à une "thérapie".

**Rayan, 24 ans — Le sociable en quête de sens**
Naturellement extraverti, il sort souvent et rencontre beaucoup de gens — mais ces rencontres restent superficielles. Il aimerait un outil qui lui permette de matérialiser et valoriser ses connexions humaines.

---

## 3. Valeur unique

Une application qui **récompense les interactions humaines réelles** sous forme de points, avec un mécanisme de territoire (QR codes placés dans la ville) et un système d'identité anonyme ("Agent XXX"). Elle crée du lien social **sans en avoir l'air** : l'utilisateur vient pour le jeu, il reste pour les rencontres.

**Ce qui la différencie de tout ce qui existe :**
- Ce n'est pas une app de rencontre amoureuse (pas de photo, pas de genre, identité anonyme)
- Ce n'est pas un réseau social (pas de fil d'actualité, pas de "like")
- Ce n'est pas une simple chasse aux trésors (le QR code mène à une vraie rencontre humaine)

---

## 4. Analyse de concurrence

| Concurrent | Ce qu'il fait | Ce qui manque |
|---|---|---|
| **Pokémon GO** | Exploration urbaine gamifiée, lieux à capturer | Solo, aucun lien humain direct |
| **Foursquare / Swarm** | Check-in de lieux, "maire" d'un endroit | Pas orienté rencontre, pas de récompense relationnelle |
| **Geocaching** | Chasse aux trésors en ville | Pas social, pas gamifié, peu grand public |

**Notre différenciation** : la seule application qui utilise la gamification de territoire comme **déclencheur de rencontre humaine réelle**, avec un système de points anti-triche et une identité anonyme protectrice.

---

## 5. Périmètre de la v1

**Dans la v1 :**
- Application mobile Android et iOS
- Système de QR codes (génération, affichage, scan)
- Mécanisme "High-five numérique" (scan mutuel → points)
- Mécanisme "Territoire" (propriétaire d'un QR code, points passifs, invitation à la rencontre)
- Identité anonyme "Agent XXX"
- Système de confiance visible (score, nombre de high-fives, niveau de confiance)
- Classement des Agents dans la ville (leaderboard)
- Interactions normales illimitées + 1 "Interaction Rare" par jour (points x5, badge spécial)
- Système de série quotidienne (streak) : multiplicateur croissant selon les jours consécutifs d'activité
- "Pacte de rencontre" : confirmation mutuelle de présence avant le high-five avec un inconnu
- Système de points sécurisé, crypté, infalsifiable *(architecture à affiner par l'Agent Architecture)*
- Lancement dans une première ville (à définir)
- Application en français, structure prête pour l'anglais

**Hors périmètre v1 :**
- Défis Flash, Validation croisée, Cadeau surprise, Série de rencontres
- Partenariats commerçants
- Fonctionnalités d'échange ou de don de points
- Déploiement national ou international

---

## 6. Critères de succès (v1)

- L'utilisateur réalise son premier high-five numérique en moins de 3 minutes après inscription
- Un QR code placé dans un lieu public génère au moins un scan dans les 7 jours
- Aucune interaction ne peut être simulée ou fraudée
- L'utilisateur ouvre l'application au moins 3 jours sur 7 (rétention hebdomadaire)
- L'application n'est jamais perçue comme une application de rencontre amoureuse

---

## 7. Points ouverts — à affiner

Les éléments suivants ont été identifiés mais nécessitent un avis complémentaire avant intégration définitive dans le cahier des charges :

- **Mécanique de rareté** : calibrage exact de l'"Interaction Rare" (fréquence, points, conditions de déclenchement)
- **Système de streak** : règles de perte et de récupération de la série
- **Sécurité des rencontres** : détail du "Pacte de rencontre" et des mécanismes de signalement
- **Classement** : portée du leaderboard (ville, quartier, amis uniquement ?)
- **Blockchain / smart contracts** : évaluation de la pertinence pour la v1 vs solutions alternatives

---

## Historique des versions

| Version | Date | Modifications |
|---|---|---|
| v0001 | 24/04/2026 | Création initiale — validée par l'utilisateur |
