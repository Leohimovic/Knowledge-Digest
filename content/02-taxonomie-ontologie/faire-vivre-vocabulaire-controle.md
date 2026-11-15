---
title: "Faire vivre un vocabulaire contrôlé dans la durée"
description: "Un référentiel de termes se dégrade s'il n'est pas gouverné. Rôles, processus et rituels pour le maintenir vivant et fiable."
theme: "Taxonomie & ontologie"
type: article
niveau: avance
tags: [km, taxonomie, vocabulaire-controle, gouvernance]
date: 2026-11-08
draft: false
---

> **En bref** — Construire un vocabulaire contrôlé prend quelques mois. Le maintenir prend des années. La différence entre un référentiel utile et un référentiel abandonné tient presque entièrement à sa gouvernance.

## Pourquoi un vocabulaire vieillit

Le langage d'une organisation bouge en permanence : nouveaux produits, réorganisations, nouveaux métiers, termes qui tombent en désuétude. Un [[vocabulaire-controle|vocabulaire contrôlé]] qui ne suit pas ces évolutions perd rapidement sa crédibilité. Les utilisateurs contournent alors le référentiel en créant leurs propres tags — et le désordre revient.

## Trois rôles indispensables

**Le responsable du référentiel** (*taxonomy owner*). Il garantit la cohérence d'ensemble, arbitre les demandes et porte la vision. C'est souvent un knowledge manager ou un spécialiste de l'information.

**Les référents métier**. Ils connaissent un domaine et valident les termes qui le concernent. Ils sont la garantie que le vocabulaire reste celui du terrain.

**Les contributeurs**. Toute personne qui indexe des contenus et peut proposer un nouveau terme ou signaler une anomalie.

## Un processus de demande clair

Chaque modification doit suivre un circuit simple et connu :

1. **Demande** : un formulaire ou un canal dédié, avec le terme proposé, sa définition et un exemple de contenu concerné.
2. **Vérification** : le terme existe-t-il déjà sous un autre nom ? Est-ce un synonyme ? Un concept trop spécifique ?
3. **Décision** : ajout, ajout comme synonyme, refus motivé.
4. **Publication** et communication du changement.

Fixez un délai de réponse. Un circuit trop lent pousse les utilisateurs à contourner le système.

## Les modifications sensibles

Certaines opérations ont un impact sur les contenus déjà indexés et demandent une attention particulière :

- **Renommer** un concept : conservez l'ancien libellé comme synonyme.
- **Fusionner** deux concepts : réindexez les contenus concernés.
- **Supprimer** un concept : ne supprimez jamais sans plan de réaffectation. Préférez un statut « déprécié ».

Tenez un **journal des modifications**. Il est précieux pour comprendre pourquoi un terme a changé, et pour expliquer les décisions.

## Des rituels de revue

Instaurez une revue périodique — trimestrielle pour un référentiel actif :

- termes jamais utilisés depuis un an ;
- termes surutilisés, qui mériteraient d'être subdivisés ;
- termes recherchés mais absents du référentiel ;
- demandes en attente.

Ces signaux se tirent des statistiques d'indexation et de recherche.

## En pratique

Publiez le référentiel de manière lisible pour tous, avec les définitions. Un vocabulaire que l'on peut consulter et comprendre est un vocabulaire que l'on utilise correctement. Le format [[skos-pour-non-techniciens|SKOS]] facilite aussi sa réutilisation par d'autres outils.

## À retenir

- La gouvernance compte plus que la construction initiale.
- Ne supprimez jamais un terme : dépréciez-le.
- Mesurez l'usage pour savoir quoi faire évoluer.

## Pour aller plus loin

- [[construire-une-taxonomie|Construire une taxonomie en 6 étapes]]
- [[raci-de-la-connaissance|Le RACI de la connaissance : qui fait quoi]]
- [[vocabulaire-controle]] dans le glossaire
