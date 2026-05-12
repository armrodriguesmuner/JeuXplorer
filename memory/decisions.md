# Décisions — JeuXplorer

Historique des décisions structurantes prises au fil du projet.

---

## Phase 0 — Initialisation (24/04/2026)

| # | Date | Décision |
|---|---|---|
| 1 | 24/04/2026 | **Nom du projet** : JeuXplorer |
| 2 | 24/04/2026 | **Reconnaissance entre utilisateurs** : NFC (geste signature) + QR code (alternative universelle) |
| 3 | 24/04/2026 | **Public cible initial** : 18–30 ans, âge minimum 18 ans, anonymat complet ("Agent XXX") — élargi en Phase 1 |
| 4 | 24/04/2026 | **Lancement** : ville pilote → France → international |
| 5 | 24/04/2026 | **Framework multi-agents** : manuel d'abord, migration vers LangGraph en phase ultérieure |
| 6 | 24/04/2026 | **Blockchain** : prévue pour la confiance et la gestion des points, implémentation en phase ultérieure |
| 7 | 24/04/2026 | **Structure** : CLAUDE.md universel (profil + règles), contexte projet isolé dans `memory/` |

---

## Phase 1 — Note de cadrage v0002 (24/04/2026)

| # | Date | Décision |
|---|---|---|
| 8 | 24/04/2026 | **Personas v1** : Geek Social (23–30 ans) + Actif Isolé (25–60 ans) + Vintage (60+) |
| 9 | 24/04/2026 | **Croyant Déçu** : persona mis en réserve pour la v2 — arrivera naturellement via le Geek Social |
| 10 | 24/04/2026 | **Le Vintage** : profil rare, +40 points quand scanné (au lieu de +10). Premier usage du terme "Vintage" pour désigner les 60+ |
| 11 | 24/04/2026 | **Actif Isolé élargi** : tranche d'âge étendue de 25–30 ans à 25–60 ans — l'isolement actif ne s'arrête pas à 30 ans |
| 12 | 24/04/2026 | **Stratégie de lancement** : Option B — Geek Social comme moteur de diffusion dès la v1, qualité irréprochable pour les 3 profils simultanément dès le lancement |
| 13 | 24/04/2026 | **Mémoire privée des rencontres** : exclue de la v1, prévue pour la v2 |
| 14 | 24/04/2026 | **Objectif ville pilote** : 3 000 utilisateurs actifs en 6 mois (actif = ouverture app ≥ 3 fois/semaine) |
| 15 | 24/04/2026 | **Vision long terme — 4 modules** : (1) Lien humain v1, (2) Défis collectifs & partenariats commerçants, (3) Impact citoyen en réflexion, (4) Échange de services entre proches |
| 16 | 24/04/2026 | **Exigence qualité** : design accessible à tous les âges (de 18 à 80+) dès le lancement — pas une amélioration future |

---

## Phase 1 — Note de cadrage v0003 (29/04/2026)

| # | Date | Décision |
|---|---|---|
| 17 | 29/04/2026 | **Âge minimum** : 16 ans (RGPD sans consentement parental obligatoire) — remplace la décision initiale de 18 ans |
| 18 | 29/04/2026 | **Mécanique de capture** : GPS + timestamp comme mécanisme principal — remplace QR code seul |
| 19 | 29/04/2026 | **High-five social** : NFC prioritaire (contact physique = validation) + fallback Bluetooth (RSSI + token chiffré + tap simultané) |
| 20 | 29/04/2026 | **Plancher GPS dynamique** : lecture en temps réel de la précision GPS (getAccuracy / horizontalAccuracy) · minimum absolu 14 m |
| 21 | 29/04/2026 | **Chaîne de points** : 5 pts → 3 pts → 1 pt → 0,5 pt (prédécesseurs) + 5 pts au visiteur lui-même |
| 22 | 29/04/2026 | **Croissance des zones** : 4 stades (vocabulaire provisoire : Graine / Pousse / Plante / Arbre) — vocabulaire définitif lié au choix du narratif |
| 23 | 29/04/2026 | **Économie keynésienne** : 7 mécanismes d'équilibre (K1–K7) intégrés dès la v1 |
| 24 | 29/04/2026 | **Deux types de points** : PA (Points Actifs) + PE (Points Écho) — profil personnel uniquement, pas de classement global |
| 25 | 29/04/2026 | **Mode Dispo / Spectateur** : Mode Spectateur par défaut · Mode Dispo opt-in · mélodie partagée à < 15 m via Bluetooth |
| 26 | 29/04/2026 | **Profils joueurs v2** : Arpenteur sensible + Tisseur de passage + Gardien de la trace — remplacent Geek Social / Actif Isolé / Vintage |
| 27 | 29/04/2026 | **Ton du jeu** : sérieux dans ses intentions, léger dans sa voix — notifications narratives, titres contextuels, Pépite mystère |

---

## Phase 1 — Exploration active (01/05/2026)

| # | Date | Décision |
|---|---|---|
| 28 | 01/05/2026 | **Séparation mécanique / narratif** : principe de conception formel — la mécanique (GPS, points, high-five) est stable et indépendante du narratif (vocabulaire, ton, images) |
| 29 | 01/05/2026 | **QR code physique** : mécanisme de capture alternatif au GPS (Option C) — QR codes officiels (pré-placés par l'équipe ou partenaires) + QR codes joueurs (créés et posés par les joueurs). Détails de modération à préciser |
