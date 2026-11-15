---
title: "Métadonnées : le minimum vital"
description: "Les quelques métadonnées qui changent tout pour la recherche, la gouvernance et l'IA — et comment obtenir qu'elles soient renseignées."
theme: "Architecture de l'information"
type: article
niveau: debutant
tags: [km, metadonnees, architecture-information]
date: 2026-11-08
draft: false
---

> **En bref** — Inutile de demander quinze champs à chaque contributeur. Une poignée de métadonnées bien choisies, et renseignées de manière fiable, suffit à transformer la trouvabilité d'une base.

## Ce qu'est une métadonnée

Une [[metadonnee|métadonnée]] est une information *sur* un contenu : son auteur, sa date, son sujet, son statut. Elle ne fait pas partie du contenu lui-même, mais elle permet de le classer, de le filtrer, de le retrouver et de le gérer.

Les métadonnées servent trois publics :

- **les utilisateurs**, qui filtrent et jugent de la fiabilité d'un contenu ;
- **les gestionnaires**, qui pilotent les revues et l'archivage ;
- **les machines** : moteurs de recherche, outils d'automatisation et, de plus en plus, systèmes d'IA.

## Le socle recommandé

Pour une base de connaissances, sept métadonnées couvrent l'essentiel :

| Métadonnée | Pourquoi |
|---|---|
| **Titre** explicite | Premier critère de pertinence, en recherche comme en IA |
| **Résumé** court | Aide l'utilisateur à juger sans ouvrir |
| **Type de contenu** | Procédure, guide, retour d'expérience, modèle… |
| **Thème** (issu du vocabulaire contrôlé) | Classement et filtrage |
| **Propriétaire** | Qui contacter, qui maintient |
| **Date de dernière revue** | Fiabilité et pilotage de l'obsolescence |
| **Statut** | Brouillon, validé, à revoir, archivé |

Ajoutez éventuellement le **public cible** ou la **langue** selon votre contexte.

## Saisie libre ou valeurs contrôlées ?

Chaque fois que c'est possible, proposez des **listes de valeurs** plutôt qu'une saisie libre. Un champ « Thème » en texte libre produit rapidement « RH », « Ressources Humaines », « rh » et « HR ». Les listes de valeurs s'appuient sur votre [[vocabulaire-controle|vocabulaire contrôlé]].

La saisie libre reste pertinente pour le titre et le résumé.

## Obtenir des métadonnées fiables

C'est le vrai défi. Quelques leviers efficaces :

- **Réduire l'effort** : moins de champs, des valeurs par défaut intelligentes, des métadonnées héritées de l'espace de publication.
- **Automatiser** ce qui peut l'être : auteur, dates, langue.
- **Rendre visible l'utilité** : si les métadonnées alimentent des filtres que les contributeurs utilisent eux-mêmes, elles sont mieux renseignées.
- **Contrôler** : un rapport régulier des contenus sans propriétaire ou sans thème, partagé avec les responsables d'espace.

## Le cas de l'IA

Les assistants d'IA générative s'appuient souvent sur les métadonnées pour sélectionner les contenus pertinents et juger de leur fraîcheur. Un contenu sans date ni statut peut être restitué comme s'il était à jour. Voir [[checklist-rag-ready|La checklist « RAG-ready »]].

## En pratique

Auditez un échantillon de cent contenus : pour chaque métadonnée du socle, quel pourcentage est correctement renseigné ? Ce simple chiffre est un excellent indicateur de départ, et un argument solide pour lancer un chantier.

## À retenir

- Peu de métadonnées, mais fiables.
- Des listes de valeurs plutôt que du texte libre.
- Propriétaire et date de revue sont non négociables.

## Pour aller plus loin

- [[facettes-ou-hierarchie|Facettes ou hiérarchie : choisir son modèle]]
- [[cycle-de-vie-contenu|Le cycle de vie d'un contenu, de la création à l'archivage]]
