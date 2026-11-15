---
title: "La checklist « RAG-ready » : découpage, métadonnées, qualité"
description: "Une liste de contrôle opérationnelle pour évaluer si un corpus est prêt à alimenter un assistant IA."
theme: "KM × IA"
type: article
niveau: avance
tags: [km, ia, rag, checklist]
date: 2026-11-08
draft: false
---

> **En bref** — Avant de brancher un assistant IA sur un corpus, passez-le au crible de cette checklist. Chaque case non cochée est une source probable de mauvaises réponses.

## Comment l'utiliser

Appliquez la checklist à un corpus délimité : un espace, un domaine, une collection de documents. Notez chaque critère *oui / partiellement / non*. Les « non » sur les blocs 1 et 2 sont bloquants ; les autres sont des axes d'amélioration.

## Bloc 1 — Périmètre et fiabilité

- [ ] Le corpus a un **périmètre défini** et un propriétaire identifié.
- [ ] Les **doublons** ont été identifiés et supprimés ou fusionnés.
- [ ] Les **contenus obsolètes** ont été archivés et exclus de l'index.
- [ ] Les **contradictions** entre documents ont été résolues.
- [ ] Les contenus de référence sont **distingués** des brouillons et notes de travail.

## Bloc 2 — Accès et sécurité

- [ ] Les **permissions** ont été revues : aucun contenu sensible n'est partagé trop largement.
- [ ] Les **données personnelles** et confidentielles sont identifiées et protégées.
- [ ] Les contenus exclus de l'IA sont **explicitement listés**.

## Bloc 3 — Structure et découpage

- [ ] Les documents ont des **titres explicites**.
- [ ] Les contenus longs sont structurés en **sections titrées**.
- [ ] Chaque section est **compréhensible isolément** (pas de « voir ci-dessus »).
- [ ] Les sigles et le jargon sont **explicités** au moins une fois par document.
- [ ] Les informations clés ne sont pas **enfermées dans des images** ou des schémas non décrits.
- [ ] Les PDF ont une **couche texte** exploitable.

## Bloc 4 — Métadonnées

- [ ] Chaque contenu a une **date de dernière revue**.
- [ ] Chaque contenu a un **statut** (validé, à revoir, archivé).
- [ ] Le **type de contenu** est renseigné.
- [ ] Le **thème** est issu d'un [[vocabulaire-controle|vocabulaire contrôlé]].
- [ ] La **langue** est renseignée pour les corpus multilingues.

## Bloc 5 — Évaluation

- [ ] Un **jeu de questions de test** représentatives a été constitué avec les utilisateurs.
- [ ] Les **réponses attendues** ont été validées par des référents.
- [ ] Les réponses de l'assistant **citent leurs sources**.
- [ ] Un **circuit de signalement** des réponses erronées existe.
- [ ] Les signalements sont **traités à la source**, dans les contenus.

## Interpréter le résultat

- **Blocs 1 et 2 majoritairement cochés** : le corpus peut faire l'objet d'un pilote.
- **Bloc 3 faible** : attendez-vous à des réponses incomplètes ou hors contexte.
- **Bloc 4 faible** : l'assistant risque de restituer des contenus périmés comme s'ils étaient à jour.
- **Bloc 5 absent** : vous ne saurez pas si l'assistant fonctionne.

## Le principe à garder en tête

Chaque mauvaise réponse se corrige **dans le contenu**, pas dans l'assistant. Reformuler les consignes du système peut masquer un problème, mais seul le contenu corrigé le règle durablement.

## En pratique

Utilisez cette checklist comme support d'atelier avec les propriétaires du corpus. Elle transforme une discussion abstraite sur « la qualité des données » en une liste d'actions concrètes, réparties entre les personnes concernées.

## À retenir

- Fiabilité et sécurité d'abord, structure et métadonnées ensuite.
- Sans jeu de test, pas d'évaluation possible.
- On corrige le contenu, pas l'assistant.

## Pour aller plus loin

- [[preparer-contenus-rag|Préparer ses contenus pour le RAG]]
- [[metadonnees-minimum-vital|Métadonnées : le minimum vital]]
- [[parcours-contenus-prets-ia|Parcours : rendre ses contenus prêts pour l'IA]]
