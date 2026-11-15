---
title: "À lire avant publication"
type: interne
draft: true
publish: false
---

# Guide interne — à ne pas publier

Ce fichier est marqué `draft: true` (ignoré par Quartz) et `publish: false` (ignoré par Obsidian Publish).

## Contenu de la base

- `index.md` — page d'accueil
- `01-…` à `09-…` — 46 articles répartis en 9 thèmes ; le premier de chaque thème (`type: entree`) sert de page d'entrée
- `parcours/` — 3 parcours de lecture
- `glossaire/` — 23 définitions courtes, plus le hub `le-glossaire.md`

## Conventions

**Noms de fichiers** : slugs sans accents ni espaces, tous uniques dans la base. C'est ce qui permet aux liens `[[slug|Titre]]` de fonctionner partout, quel que soit le dossier.

**Pas de titre H1 dans les articles** : le titre est dans le frontmatter (`title`). Quartz l'affiche automatiquement. Dans Obsidian, si vous voulez voir le titre plutôt que le slug, activez l'option « Afficher le titre en ligne » ou utilisez un plugin comme *Front Matter Title*.

**Frontmatter type** :

```yaml
title: "…"
description: "…"        # utilisé pour les aperçus et le SEO
theme: "…"
type: entree | article | glossaire | parcours | hub
niveau: debutant | intermediaire | avance
tags: [...]
date: 2026-11-08
draft: false
```

**Structure d'un article** : En bref → sections → En pratique → À retenir → Pour aller plus loin / Dans ce thème.

## Publier avec Quartz (gratuit)

1. Cloner Quartz (`git clone https://github.com/jackyzha0/quartz.git`), puis `npm i` et `npx quartz create`.
2. Copier le contenu de ce dossier dans `content/`.
3. Dans `quartz.config.ts` : `locale: "fr-FR"`, renseigner `pageTitle` et `baseUrl`.
4. Prévisualiser avec `npx quartz build --serve`.
5. Déployer sur GitHub Pages, Netlify ou Cloudflare Pages.

Quartz gère nativement les liens `[[…]]`, les rétroliens, la vue graphe, la recherche et les tags.

## Publier avec Obsidian Publish

Ouvrir ce dossier comme coffre, puis publier toutes les notes sauf ce fichier. La page d'accueil se règle sur `index.md` dans les options du site.

## À relire avant mise en ligne

- **Personnaliser** : ajouter vos exemples terrain, anecdotes et références de posts LinkedIn. Les articles sont volontairement génériques.
- **Vérifier** les références citées (auteurs, dates d'ouvrages) avant publication.
- **Article `diagnose-structure-surface-sustain`** : il présente votre méthode en termes généraux ; ajustez-le à votre propre définition des quatre temps.
- **Page d'accueil** : ajouter le lien vers votre profil LinkedIn et, le moment venu, vers vos templates.
