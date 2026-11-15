---
title: "Obsidian comme base de connaissances"
description: "Fichiers Markdown, liens bidirectionnels, graphe : pourquoi Obsidian séduit les professionnels du KM, et dans quels cas il est pertinent."
theme: "Outils"
type: article
niveau: debutant
tags: [km, outils, obsidian, markdown, pkm]
date: 2026-11-08
draft: false
---

> **En bref** — Obsidian est un outil de prise de notes fondé sur des fichiers Markdown reliés entre eux. Il est idéal pour une base de connaissances personnelle ou une petite base publiée — comme celle que vous lisez.

## Le principe

Obsidian fonctionne sur un dossier de fichiers texte au format Markdown, appelé « coffre » (*vault*). Chaque note est un fichier. Les notes se relient par des liens internes, écrits entre doubles crochets : `[[nom-de-la-note]]`.

Ce principe simple a trois conséquences majeures :

- **vos contenus vous appartiennent** : ce sont de simples fichiers texte, lisibles par n'importe quel outil ;
- **les liens sont au cœur du système** : chaque note affiche aussi les notes qui pointent vers elle (rétroliens) ;
- **la structure émerge** des liens plutôt que d'une arborescence imposée.

## Ce qui le rend intéressant pour le KM

**La pensée en réseau.** Les liens bidirectionnels permettent de construire une connaissance reliée, plus proche de la manière dont on raisonne qu'une arborescence de dossiers.

**La vue graphe.** Obsidian affiche les notes et leurs liens sous forme de graphe. C'est un moyen visuel de repérer les notions centrales, les îlots isolés et les manques.

**Les métadonnées en frontmatter.** En tête de chaque fichier, un bloc de propriétés permet d'indiquer thème, type, statut, date. On retrouve les bonnes pratiques de [[metadonnees-minimum-vital|métadonnées]].

**La pérennité.** Le Markdown est un format ouvert. Votre base restera lisible dans vingt ans, quel que soit le devenir de l'outil.

**La publication.** Un coffre Obsidian peut être publié en site web, soit avec le service de publication de l'éditeur, soit avec des générateurs de sites statiques gratuits comme Quartz.

## Les limites

- **Un outil d'abord individuel.** La collaboration à plusieurs sur un même coffre est possible, mais moins fluide que sur une plateforme collaborative.
- **Pas de gestion fine des droits.** Tout ou rien, à l'échelle du coffre.
- **Pas de workflow de validation natif.** La gouvernance repose sur la discipline et les conventions.
- **Une liberté qui peut désorienter.** Sans conventions, un coffre devient aussi désordonné qu'un disque partagé.

## Les bonnes pratiques

1. **Des conventions de nommage** de fichiers stables et sans ambiguïté.
2. **Un frontmatter homogène**, défini dès le départ.
3. **Des notes d'entrée** (ou *Maps of Content*) qui structurent chaque thème, comme les articles d'entrée de cette base.
4. **Des notes atomiques** : une idée, un concept, une note. Elles se relient plus facilement.
5. **Des liens explicites** : chaque note devrait pointer vers au moins deux ou trois autres.

## Pour qui ?

Obsidian convient parfaitement :

- à une **base de connaissances personnelle** de professionnel ;
- à une **petite équipe** documentant un domaine ;
- à une **base publiée** destinée à une communauté.

Pour une base d'entreprise à grande échelle, avec des centaines de contributeurs et des exigences de droits, une plateforme collaborative reste plus adaptée.

## En pratique

Commencez par une vingtaine de notes sur un sujet que vous maîtrisez, reliées entre elles, puis ouvrez la vue graphe. Les notes sans lien et les notions très citées mais jamais rédigées vous montreront immédiatement quoi écrire ensuite.

## À retenir

- Des fichiers Markdown, des liens, un graphe.
- Pérenne, souple, publiable.
- Idéal en individuel ou petite équipe, moins à grande échelle.

## Pour aller plus loin

- [[choisir-outil-km|Choisir son outil de KM]]
- [[navigation-qui-tient|Concevoir une navigation qui tient quand la base grandit]]
