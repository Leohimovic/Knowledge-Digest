---
title: "Graphes de connaissances et LLM : le retour des ontologies"
description: "Pourquoi les graphes de connaissances, longtemps jugés trop complexes, reviennent au cœur des projets d'IA générative."
theme: "KM × IA"
type: article
niveau: avance
tags: [km, ia, ontologie, graphe-de-connaissances, graphrag]
date: 2026-11-08
draft: false
---

> **En bref** — Les modèles de langage sont forts pour rédiger, plus fragiles pour relier des faits précis entre eux. Les graphes de connaissances leur apportent ce qui leur manque : des relations explicites et vérifiables.

## Le rappel : qu'est-ce qu'un graphe de connaissances ?

Un [[graphe-de-connaissances|graphe de connaissances]] représente l'information sous forme d'**entités** reliées par des **relations typées**. *Le Jeu A — est développé par → le Studio B. Le Studio B — est situé à → Montréal.* Sa structure est définie par une [[ontologie]], qui précise les types d'entités et de relations autorisés.

Pendant des années, ces dispositifs sont restés l'apanage de grandes organisations, faute de cas d'usage simples justifiant l'investissement.

## Ce que les LLM font mal seuls

Un modèle de langage, même alimenté par un système de [[rag|RAG]], rencontre des difficultés récurrentes :

- **les questions de mise en relation** : *« Quels projets ont impliqué à la fois l'équipe X et le prestataire Y ? »* La réponse n'est écrite dans aucun document unique ;
- **les questions d'agrégation** : *« Combien de studios travaillent sur cette technologie ? »* ;
- **la désambiguïsation** : deux entités qui portent le même nom, une entité qui porte plusieurs noms ;
- **la traçabilité** : savoir précisément d'où vient chaque élément de la réponse.

Le RAG classique retrouve des passages de texte proches de la question. Il ne raisonne pas sur les liens entre entités.

## Ce que le graphe apporte

**Des relations explicites.** Le lien entre deux entités n'a pas à être deviné : il est déclaré.

**Une identité stable.** Chaque entité a un identifiant unique et ses différents noms, comme dans un [[thesaurus|thésaurus]]. Les ambiguïtés diminuent.

**Des parcours multi-étapes.** On peut suivre une chaîne de relations — projet, équipe, personne, compétence — pour répondre à des questions complexes.

**Une base vérifiable.** Les faits du graphe sont des affirmations contrôlables, gouvernées, datées.

## Les approches combinées

Plusieurs architectures associent graphe et modèle de langage, souvent regroupées sous le nom de *GraphRAG* :

- le graphe sert à **enrichir la recherche** : on identifie les entités de la question, puis on récupère les documents qui leur sont liés ;
- le graphe est **interrogé directement** pour les faits précis, le modèle se chargeant de formuler la réponse ;
- le modèle de langage aide à **construire le graphe**, en extrayant entités et relations des documents — sous contrôle humain.

## Ce que cela change pour le KM

Les compétences de structuration — taxonomie, [[vocabulaire-controle|vocabulaire contrôlé]], ontologie — redeviennent stratégiques. Les organisations qui disposent déjà de référentiels bien gouvernés ont une longueur d'avance considérable : leurs référentiels sont la colonne vertébrale d'un futur graphe.

## Rester pragmatique

Inutile de modéliser toute l'entreprise. Commencez par un domaine où les questions de mise en relation sont fréquentes et coûteuses, avec quelques types d'entités seulement. Un petit graphe bien gouverné vaut mieux qu'une ontologie ambitieuse jamais terminée.

## En pratique

Recensez les questions que vos utilisateurs posent et auxquelles aucun document ne répond directement, parce que la réponse demande de croiser plusieurs sources. Si elles sont nombreuses et à fort enjeu, un graphe de connaissances mérite d'être étudié.

## À retenir

- Les LLM rédigent, les graphes relient.
- Les référentiels existants sont la base d'un graphe.
- Commencer petit, sur un domaine à forte valeur.

## Pour aller plus loin

- [[taxonomie-thesaurus-ontologie|Taxonomie, thésaurus, ontologie : quelles différences ?]]
- [[skos-pour-non-techniciens|SKOS pour les non-techniciens]]
