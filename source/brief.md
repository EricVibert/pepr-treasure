# Project brief

<!-- TEMPLATE: the setup skill fills this in during the first session.
     If you are the AI and this file still contains TODO markers, run
     .claude/skills/setup/SKILL.md before doing anything else. -->

## Who

- **Owner**: Pr Éric Vibert — chirurgien, directeur chirurgical de la transplantation hépatique au Centre Hépato-Biliaire (Hôpital Paul-Brousse, AP-HP), co-porteur du PEPR TREASURE (avec Agnès Audier, Alexandre Loupy, François Pattou). Non technique côté web.
- **The project**: **PEPR TREASURE** (*Transplantation, REgeneration And preservation of OrganS*) — Programme d'Équipement Prioritaire de Recherche dédié à la transplantation d'organes, financé par France 2030 et piloté par l'Agence de programmes de recherche en Santé au sein de l'INSERM (2025-2030). Approche « tous organes » (rein, foie, cœur, poumon, trachée, îlots, tissus composites) qui fédère toute la communauté française de la transplantation. Organisé en work packages (WP1 données augmentées, WP2 parcours du greffon/perfusion, WP3 cellules et tissus, WP4 immuno-monitoring, etc.).
- **Audience**: communauté de la transplantation (chercheurs, cliniciens, ingénieurs), institutions et tutelles (INSERM, France 2030), partenaires industriels (médicament, MedTech), sociétés savantes et associations de patients.

## The site

- **Domain**: TODO (pour l'instant sur pages.dev)
- **Live URL**: https://pepr-treasure.pages.dev (Cloudflare Pages ; branche de production = `main`)
- **Languages**: français (défaut). Anglais à ajouter plus tard.
- **Pages**: Accueil (`site/src/pages/index.astro`) — présentation synthétique du programme (acronyme, ambition, approche unifiée « tous organes », axes d'innovation). Le reste du site est à construire.
- **Collections**: candidates — work packages, équipe (co-porteurs + leads par organe), partenaires, actualités. À décider en construisant.

## Derivatives

- **Decks**: TODO (list decks under site/public/decks/, each with its purpose and audience)
- **Apps**: TODO (list apps under apps/, each with what it does and where it's published)

## Governance

<!-- Filled during setup, in plain terms; revisit whenever someone new joins. -->

- **Who owns the accounts**: TODO (the GitHub and Cloudflare accounts belong to the owner, not to a helper or vendor)
- **Who can ask for changes**: TODO (just the owner? a teammate? anyone at the organization?)
- **Who publishes**: TODO (solo mode: owner + AI push to main, pushing is publishing; team mode: changes become proposals — pull requests — and a named person approves before anything goes live)
- **Access granted so far**: TODO (each person added to the repo, with their level: read = can look, write = can propose changes, maintain/admin = can publish and change settings)

## Current priorities

- TODO (what the owner cares about right now; keep this list short and current)

## History and decisions

The **detail** of how hypotheses and positioning evolved, and **why** (tied to each discussion),
lives in [`decisions.md`](decisions.md). Keep the milestones below; **after a discussion that moves
a hypothesis or the positioning, update `decisions.md`.**

<!-- Append dated one-liners for decisions worth remembering, newest first.
     Example: 2026-07-18 · dropped the blog idea, energy goes to the gallery. -->
