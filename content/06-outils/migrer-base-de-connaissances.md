---
title: "Migrer une base de connaissances sans tout casser"
description: "Une migration est l'occasion idéale de faire le ménage — ou de déplacer le désordre. Les étapes pour réussir le passage d'un outil à l'autre."
theme: "Outils"
type: article
niveau: avance
tags: [km, outils, migration]
date: 2026-11-08
draft: false
---

> **En bref** — Une migration réussie se joue bien avant le transfert technique. Ce qui compte, c'est ce que l'on choisit de ne pas migrer, et la manière dont on structure ce qui reste.

## L'erreur la plus coûteuse : tout migrer

La tentation du « on migre tout, on fera le tri après » est forte. Elle est presque toujours une erreur. Le tri n'est jamais fait après, et le nouvel outil hérite de tous les défauts de l'ancien — doublons, obsolète, arborescences illisibles — avec en prime la perte de repères des utilisateurs.

Une migration est le meilleur moment pour assainir : les moyens sont là, l'attention aussi.

## Étape 1 — Auditer

Tout commence par un [[auditer-fonds-documentaire|audit du fonds existant]] : volumes, état, usages. L'objectif est de classer les contenus en trois catégories :

- **à migrer** tel quel ou presque ;
- **à retravailler** avant ou pendant la migration ;
- **à ne pas migrer** : archiver dans l'ancien système ou supprimer.

## Étape 2 — Concevoir la cible

Avant de déplacer quoi que ce soit, définissez la structure d'arrivée :

- architecture des espaces ;
- [[taxonomie]] et métadonnées ;
- modèles de contenus ;
- règles de gouvernance et propriétaires.

C'est l'occasion de corriger les défauts identifiés lors de l'audit, plutôt que de reproduire l'ancienne arborescence à l'identique.

## Étape 3 — Établir la table de correspondance

Pour chaque espace ou lot de contenus source, documentez sa destination et la transformation à appliquer : emplacement cible, métadonnées à affecter, conversion de format. Cette table est le contrat de la migration. Elle sert aussi, plus tard, à expliquer aux utilisateurs où sont passés leurs contenus.

## Étape 4 — Tester sur un pilote

Migrez d'abord un périmètre restreint mais représentatif. Vérifiez :

- l'intégrité des contenus (mise en forme, pièces jointes, images) ;
- les liens internes, souvent cassés par une migration ;
- les métadonnées ;
- les permissions ;
- la trouvabilité, avec de vrais utilisateurs.

Corrigez la méthode avant de passer à l'échelle.

## Étape 5 — Migrer par vagues

Procédez par lots successifs, avec pour chacun une validation par les propriétaires. Prévoyez une période de gel des contributions sur l'ancien système pour chaque lot, ou un mécanisme de synchronisation, pour éviter les écarts.

## Étape 6 — Accompagner et fermer

La migration n'est terminée que lorsque l'ancien système est fermé. Entre-temps :

- **redirigez** les anciens liens quand c'est possible ;
- **communiquez** sur les nouveaux emplacements ;
- **formez** les contributeurs aux nouvelles règles ;
- **passez l'ancien système en lecture seule**, puis fermez-le à une date annoncée.

Un ancien système laissé ouvert « au cas où » continue d'être alimenté, et la migration n'est jamais vraiment achevée.

## En pratique

Fixez dès le départ un objectif de réduction du volume migré, fondé sur l'audit. Afficher cet objectif aide à résister à la pression du « on garde tout » et donne un indicateur de réussite concret.

## À retenir

- Ne migrez pas le désordre.
- Concevez la cible avant de déplacer quoi que ce soit.
- Une migration n'est finie que lorsque l'ancien système est fermé.

## Pour aller plus loin

- [[retention-et-obsolescence|Rétention et obsolescence : savoir supprimer]]
- [[parcours-structurer-fonds-documentaire|Parcours : structurer un fonds documentaire]]
