---
title: "SKOS pour les non-techniciens"
description: "Le standard du W3C pour décrire taxonomies et thésaurus, expliqué sans jargon : à quoi il sert et pourquoi il vous concerne."
theme: "Taxonomie & ontologie"
type: article
niveau: intermediaire
tags: [km, taxonomie, skos, web-semantique]
date: 2026-11-08
draft: false
---

> **En bref** — SKOS est un format standard pour écrire un vocabulaire contrôlé de manière à ce que n'importe quel outil puisse le lire. Vous n'avez pas besoin de savoir le coder pour comprendre ce qu'il vous apporte.

## Le problème que SKOS résout

Imaginez votre taxonomie gérée dans un tableur. Elle fonctionne, mais elle reste prisonnière de ce fichier. Pour l'importer dans un intranet, un outil de recherche ou un projet d'IA, il faut à chaque fois la retraiter, avec le risque d'erreurs que cela implique.

[[skos|SKOS]] (*Simple Knowledge Organization System*) est une recommandation du W3C publiée en 2009. Il propose une manière commune de décrire un vocabulaire, pour qu'il puisse circuler d'un système à l'autre sans perte.

## Les briques de base

SKOS repose sur un petit nombre de notions, faciles à saisir :

- **Concept** : l'idée que l'on veut représenter, identifiée de manière unique (par une adresse web, appelée URI).
- **prefLabel** : le libellé préférentiel. *« Effets visuels »*.
- **altLabel** : les libellés alternatifs, synonymes, sigles. *« VFX »*.
- **definition** : la définition du concept.
- **broader / narrower** : les relations hiérarchiques, plus général / plus spécifique.
- **related** : les termes associés.
- **ConceptScheme** : le vocabulaire lui-même, qui regroupe les concepts.

Si vous avez déjà construit un thésaurus, vous connaissez déjà ces notions. SKOS leur donne simplement un nom standard.

## Un exemple lisible

```turtle
:effets-visuels a skos:Concept ;
    skos:prefLabel "Effets visuels"@fr ;
    skos:altLabel "VFX"@fr ;
    skos:broader :production ;
    skos:related :compositing .
```

On lit : *« Effets visuels » est un concept, aussi appelé « VFX », rattaché à « Production » et associé à « Compositing ».* Les mentions `@fr` permettent de gérer plusieurs langues pour un même concept — un atout majeur pour les organisations internationales.

## Pourquoi c'est utile pour vous

**Portabilité.** De nombreux outils de gestion de taxonomie exportent et importent du SKOS. Vous n'êtes pas enfermé dans un logiciel.

**Multilinguisme.** Un concept, plusieurs libellés par langue, une seule identité.

**Liaison avec d'autres vocabulaires.** SKOS permet d'indiquer qu'un de vos concepts correspond à celui d'un référentiel externe, ce qui ouvre la voie à l'interopérabilité.

**Préparation à l'IA.** Un vocabulaire structuré et standardisé peut alimenter un [[graphe-de-connaissances|graphe de connaissances]] ou enrichir les métadonnées utilisées par un système de RAG.

## Ce que SKOS ne fait pas

SKOS décrit des vocabulaires, pas des modèles de domaine complexes. Pour exprimer des relations typées comme « est développé par » ou « est situé dans », on passe à une [[ontologie]], généralement en OWL. SKOS reste volontairement simple.

## En pratique

Vous n'avez pas à écrire du SKOS à la main. Demandez simplement, lors du choix d'un outil de gestion de vocabulaire : *« Peut-on importer et exporter en SKOS ? »* Si la réponse est non, méfiance.

## À retenir

- SKOS = format standard pour taxonomies et thésaurus.
- Il garantit portabilité, multilinguisme et interopérabilité.
- C'est un critère de choix d'outil, pas une compétence à acquérir.

## Pour aller plus loin

- [[taxonomie-thesaurus-ontologie|Taxonomie, thésaurus, ontologie : quelles différences ?]]
- [[graphes-de-connaissances-llm|Graphes de connaissances et LLM : le retour des ontologies]]
