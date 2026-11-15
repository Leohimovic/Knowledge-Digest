---
title: "Copilot sur SharePoint : ce que l'IA voit de votre intranet"
description: "Un assistant IA intégré à Microsoft 365 voit tout ce que l'utilisateur peut voir. Pourquoi c'est un sujet KM autant que sécurité, et comment s'y préparer."
theme: "KM × IA"
type: article
niveau: intermediaire
tags: [km, ia, copilot, sharepoint, permissions]
date: 2026-11-08
draft: false
---

> **En bref** — Copilot ne contourne pas les permissions : il les respecte. Le problème, c'est qu'il révèle tout ce que des années de partages approximatifs ont rendu accessible.

## Le principe : les droits de l'utilisateur

Microsoft 365 Copilot répond à partir des contenus auxquels l'utilisateur a déjà accès : sites SharePoint, fichiers OneDrive, conversations Teams, courriels. Il n'ouvre aucune porte nouvelle.

Mais auparavant, un document mal partagé restait protégé par l'obscurité : il fallait savoir qu'il existait et où le chercher. Avec un assistant qui parcourt l'ensemble des contenus accessibles pour répondre à une question, cette protection disparaît. Un fichier de rémunérations partagé par erreur avec « Tout le monde » peut ressurgir dans une réponse anodine.

## Le surpartage, angle mort classique

Les causes de surpartage sont bien connues des administrateurs :

- sites créés en mode **public** par défaut ;
- **liens de partage** ouverts à toute l'organisation, jamais révoqués ;
- **héritage de permissions** rompu puis oublié ;
- groupes trop larges utilisés par commodité ;
- **sites orphelins**, sans propriétaire actif pour les surveiller.

Aucun de ces problèmes n'est nouveau. L'IA les rend simplement visibles, et urgents.

## Ce que le KM apporte

Ce chantier est souvent traité comme un sujet purement sécurité. C'est une erreur : il est aussi profondément lié au KM.

**Savoir ce qui existe.** L'inventaire des sites, de leurs propriétaires et de leur contenu relève de l'[[auditer-fonds-documentaire|audit documentaire]].

**Savoir à qui c'est destiné.** La question « qui doit voir ce contenu ? » est une question de gouvernance de contenu, pas seulement de configuration technique.

**Assainir avant d'exposer.** Supprimer l'obsolète et les doublons réduit à la fois le risque et le bruit dans les réponses.

**Distinguer la référence du brouillon.** Un assistant qui puise dans des notes de travail répond moins bien qu'un assistant qui puise dans des contenus validés.

## Les actions prioritaires

1. **Cartographier les sites** : propriétaire, visibilité, sensibilité, activité.
2. **Traiter les sites orphelins** : réattribuer ou archiver.
3. **Revoir les sites publics et les liens larges**, en priorité sur les espaces sensibles.
4. **Appliquer des étiquettes de sensibilité** aux contenus confidentiels.
5. **Restreindre la découverte** de certains sites par l'IA tant qu'ils n'ont pas été revus, grâce aux options d'administration prévues à cet effet.
6. **Mettre en place une revue périodique** des accès par les propriétaires de sites.

## Une opportunité, pas seulement un risque

Le déploiement d'un assistant IA offre une occasion rare : obtenir les moyens et l'attention de la direction pour un chantier de remise en ordre que l'on repoussait depuis des années. Un intranet assaini profite à tous, avec ou sans IA.

## En pratique

Demandez à quelques utilisateurs pilotes de poser à l'assistant des questions volontairement sensibles : salaires, évaluations, projets confidentiels. Ce test simple révèle rapidement les zones de surpartage à traiter en priorité.

## À retenir

- L'IA respecte les permissions… et expose leurs failles.
- Le surpartage est un sujet de gouvernance autant que de sécurité.
- Assainir avant d'étendre l'accès.

## Pour aller plus loin

- [[sharepoint-online-km|SharePoint Online pour le KM : forces et limites]]
- [[gouvernance-par-ou-commencer|Gouvernance de contenu : par où commencer]]
