---
title: "Taxonomie, thésaurus, ontologie : quelles différences ?"
description: "Trois outils d'organisation de la connaissance souvent confondus. Ce que chacun permet, et comment choisir."
theme: "Taxonomie & ontologie"
type: entree
niveau: debutant
tags: [km, taxonomie, ontologie, thesaurus, entree]
date: 2026-11-08
draft: false
---

> **En bref** — Taxonomie, thésaurus et ontologie sont trois niveaux de richesse sémantique. Plus on monte, plus on décrit finement les relations entre les concepts — et plus l'effort de construction et de maintenance augmente.

## Le point commun : un vocabulaire maîtrisé

Les trois reposent sur la même idée : plutôt que de laisser chacun nommer les choses à sa manière, on définit un **[[vocabulaire-controle|vocabulaire contrôlé]]**. Un concept, un libellé de référence, des règles d'usage. C'est la condition pour que l'on puisse classer, rechercher et relier des contenus de façon fiable.

Ce qui les distingue, c'est la nature des relations qu'ils décrivent.

## La taxonomie : une hiérarchie

Une [[taxonomie]] organise les concepts en arbre, du général au particulier. *Production > Animation > Animation faciale*. La seule relation est « est un sous-ensemble de ».

**Points forts** : simple à comprendre, idéale pour la navigation et le classement.
**Limites** : un concept ne trouve sa place qu'à un seul endroit, ce qui force des choix parfois arbitraires.

## Le thésaurus : des relations sémantiques

Un [[thesaurus|thésaurus]] ajoute à la hiérarchie deux types de relations normalisées :

- les **synonymes** et variantes (terme préférentiel / termes non retenus) : *« VFX »* renvoie vers *« Effets visuels »* ;
- les **termes associés**, liés sans être hiérarchiques : *« Effets visuels »* est associé à *« Compositing »*.

**Points forts** : améliore fortement la recherche, en reconnaissant les différentes manières de nommer une même chose.
**Limites** : les relations restent génériques ; on sait que deux termes sont liés, pas *comment*.

## L'ontologie : un modèle du domaine

Une [[ontologie]] décrit des **classes** d'objets, leurs **propriétés** et des **relations typées** entre elles. *Un Jeu est développé par un Studio ; un Studio est situé dans une Ville ; un Jeu appartient à une Franchise.*

**Points forts** : permet de raisonner, de croiser des informations et d'alimenter un [[graphe-de-connaissances|graphe de connaissances]].
**Limites** : demande des compétences spécifiques et une gouvernance rigoureuse.

## Comment choisir

| Besoin principal | Outil adapté |
|---|---|
| Classer et naviguer | Taxonomie |
| Améliorer la recherche, gérer le jargon | Thésaurus |
| Relier des objets métier, alimenter une IA | Ontologie |

Dans la pratique, les trois cohabitent souvent : une taxonomie pour la navigation, enrichie de synonymes, et une ontologie légère pour les objets métier critiques.

## En pratique

Ne commencez pas par l'ontologie. Commencez par la question : *quel problème concret voulons-nous résoudre ?* Si les utilisateurs ne trouvent pas les documents, une taxonomie bien conçue et des synonymes règlent déjà une grande partie du problème.

## À retenir

- Taxonomie = hiérarchie ; thésaurus = hiérarchie + synonymes + associations ; ontologie = relations typées.
- Plus de richesse = plus de maintenance.
- Choisissez selon l'usage, pas selon la sophistication.

## Dans ce thème

- [[construire-une-taxonomie|Construire une taxonomie en 6 étapes]]
- [[faire-vivre-vocabulaire-controle|Faire vivre un vocabulaire contrôlé dans la durée]]
- [[skos-pour-non-techniciens|SKOS pour les non-techniciens]]
- [[facettes-ou-hierarchie|Facettes ou hiérarchie : choisir son modèle]]
