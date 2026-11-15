---
title: "Préparer ses contenus pour le RAG"
description: "Le RAG permet à une IA de répondre à partir de vos documents. Comment il fonctionne, et ce que cela implique pour vos contenus."
theme: "KM × IA"
type: article
niveau: intermediaire
tags: [km, ia, rag]
date: 2026-11-08
draft: false
---

> **En bref** — Le RAG ne « comprend » pas votre base : il y cherche des passages, puis demande à un modèle de langage de rédiger une réponse à partir de ces passages. La qualité de la réponse dépend donc directement de la qualité de ce qu'il trouve.

## Le RAG en trois temps

Le [[rag|RAG]] (*Retrieval-Augmented Generation*, génération augmentée par la recherche) fonctionne en trois étapes :

1. **Préparation.** Les documents sont découpés en fragments (*chunks*), puis chaque fragment est transformé en une représentation numérique de son sens, appelée [[embedding]], et stocké dans un index.
2. **Recherche.** Quand un utilisateur pose une question, le système retrouve les fragments les plus proches de la question, par le sens et souvent aussi par les mots-clés.
3. **Génération.** Ces fragments sont transmis au modèle de langage avec la question. Le modèle rédige une réponse en s'appuyant dessus, idéalement en citant ses sources.

Le modèle ne connaît donc de votre organisation que les fragments qu'on lui a transmis à l'étape 2.

## Ce que cela implique pour vos contenus

**Chaque fragment doit se suffire à lui-même.** Un passage qui dit *« comme indiqué plus haut, la procédure s'applique »* perd tout son sens une fois isolé. Rédigez des sections autonomes, qui rappellent leur sujet.

**La structure guide le découpage.** Des titres et intertitres clairs permettent un [[chunking|découpage]] logique, section par section. Un long document sans structure sera découpé arbitrairement, au risque de couper une idée en deux.

**Les doublons créent de la confusion.** Si trois versions d'une même procédure coexistent, le système peut en remonter une ancienne, ou mélanger les trois.

**Les contradictions sont restituées.** Deux documents qui se contredisent produiront une réponse incohérente, ou une réponse qui choisit au hasard.

**Les métadonnées aident à filtrer.** Statut, date, type de contenu ou public permettent d'écarter les contenus archivés ou de privilégier les contenus de référence.

## Les formats qui posent problème

Certains contenus sont difficiles à exploiter :

- **les PDF scannés** sans couche texte ;
- **les présentations** où l'information tient dans des schémas ou des bribes de texte ;
- **les tableaux complexes**, souvent mal découpés ;
- **les images** porteuses d'information non décrite.

Pour les contenus critiques, une version texte structurée reste la meilleure garantie.

## Commencer par le bon périmètre

Ne branchez pas l'IA sur l'ensemble de vos espaces d'un coup. Commencez par un **corpus de référence**, restreint et maîtrisé : les procédures validées d'un domaine, une base de questions fréquentes, un guide métier. Mesurez la qualité des réponses, corrigez les contenus, puis étendez.

## En pratique

Prenez un document clé et lisez-en chaque section isolément, comme le ferait le système. Si une section n'est pas compréhensible seule, réécrivez-la. Cet exercice, répété sur les contenus les plus consultés, améliore sensiblement les réponses.

## À retenir

- Le RAG cherche des fragments, puis rédige à partir d'eux.
- Sections autonomes, structure claire, pas de doublons.
- Commencez par un corpus de référence restreint.

## Pour aller plus loin

- [[checklist-rag-ready|La checklist « RAG-ready »]]
- [[rag]], [[chunking]] et [[embedding]] dans le glossaire
