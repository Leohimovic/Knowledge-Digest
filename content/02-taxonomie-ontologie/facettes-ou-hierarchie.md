---
title: "Facettes ou hiérarchie : choisir son modèle"
description: "Arbre unique ou combinaison d'axes indépendants ? Les forces et limites des deux approches de classification, et quand les combiner."
theme: "Taxonomie & ontologie"
type: article
niveau: intermediaire
tags: [km, taxonomie, facettes, classification]
date: 2026-11-08
draft: false
---

> **En bref** — Une hiérarchie range chaque contenu à un seul endroit. Les facettes le décrivent selon plusieurs axes à la fois. La seconde approche est plus souple, mais elle exige des métadonnées fiables.

## Le modèle hiérarchique

Dans une classification hiérarchique, chaque contenu prend place dans un arbre unique. *Ressources humaines > Recrutement > Entretiens*. C'est le modèle des arborescences de dossiers et de nombreux intranets.

**Avantages** :
- intuitif, chacun comprend un arbre ;
- adapté à la navigation par exploration ;
- simple à mettre en place.

**Limites** :
- un contenu qui concerne plusieurs sujets doit être rangé à un seul endroit, ou dupliqué ;
- l'ordre des niveaux impose un point de vue : faut-il classer d'abord par pays, puis par type de document, ou l'inverse ?
- l'arbre gonfle vite et devient difficile à maintenir.

## Le modèle à facettes

Une [[facette]] est un axe de description indépendant. Plutôt que de choisir un chemin unique, on décrit chaque contenu selon plusieurs facettes : **Type** (procédure, modèle, retour d'expérience), **Thème** (recrutement, formation), **Pays** (France, Canada), **Public** (managers, tous salariés).

L'utilisateur combine ensuite les facettes comme il l'entend : *toutes les procédures de recrutement pour le Canada*. C'est le principe des filtres d'un site de commerce en ligne.

**Avantages** :
- un contenu se retrouve par plusieurs chemins ;
- chaque facette reste courte et simple à maintenir ;
- les combinaisons sont illimitées sans multiplier les branches.

**Limites** :
- exige que chaque contenu soit correctement décrit sur chaque facette ;
- moins adapté à l'exploration libre, quand l'utilisateur ne sait pas encore ce qu'il cherche ;
- demande un outil capable de filtrer sur les métadonnées.

## Le bon critère de choix

Posez-vous deux questions :

1. **Les contenus relèvent-ils naturellement de plusieurs axes ?** Si oui, la hiérarchie va vous forcer à des choix arbitraires.
2. **Pouvez-vous garantir la qualité de l'indexation ?** Si les métadonnées sont absentes ou approximatives, les facettes ne fonctionneront pas.

## La combinaison gagnante

Dans la plupart des bases de connaissances, le meilleur modèle est **mixte** :

- une hiérarchie courte, à deux niveaux, pour la navigation principale ;
- trois à cinq facettes pour affiner la recherche et le filtrage.

Chaque facette peut elle-même être une petite taxonomie, gérée dans le [[vocabulaire-controle|vocabulaire contrôlé]].

## En pratique

Listez les questions que posent vos utilisateurs : *« Je cherche le modèle de contrat pour un freelance au Canada. »* Chaque élément de la phrase — modèle, contrat, freelance, Canada — est un candidat facette. Si vos phrases contiennent systématiquement trois ou quatre critères, les facettes s'imposent.

## À retenir

- Hiérarchie : simple, mais un seul chemin.
- Facettes : plusieurs chemins, mais une indexation rigoureuse.
- Le modèle mixte convient à la majorité des cas.

## Pour aller plus loin

- [[metadonnees-minimum-vital|Métadonnées : le minimum vital]]
- [[navigation-qui-tient|Concevoir une navigation qui tient quand la base grandit]]
- [[facette]] dans le glossaire
