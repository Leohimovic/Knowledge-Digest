---
title: "Embedding"
description: "Représentation numérique du sens d'un texte, utilisée pour la recherche sémantique."
type: glossaire
tags: [glossaire, ia, rag, recherche-semantique]
date: 2026-11-08
draft: false
---

**Embedding** (plongement vectoriel) — Représentation d'un texte sous forme d'une suite de nombres (un vecteur) qui capture son sens. Deux textes de sens proche ont des embeddings proches, même s'ils n'emploient pas les mêmes mots.

Les embeddings permettent la **recherche sémantique** : retrouver des passages pertinents à partir du sens d'une question, et pas seulement de ses mots-clés. Ils sont au cœur des systèmes de [[rag|RAG]], où chaque fragment issu du [[chunking]] est transformé en embedding.

**Voir aussi** : [[preparer-contenus-rag|Préparer ses contenus pour le RAG]]
