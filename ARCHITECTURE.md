# Thesia — architecture

[← Retour à la présentation](README.md)

Application web de suivi de portefeuille PEA et CTO. Ce dépôt présente le produit ; le code source est privé.

| Couche | Technologies et rôle |
| --- | --- |
| Interface | React, TypeScript et Tailwind CSS : vues d’ensemble, comptes, positions et liste de suivi. |
| Application | TanStack Start et TanStack Router : pages et fonctions serveur. |
| Données côté interface | TanStack Query : lecture et actualisation des données. |
| Persistance | PostgreSQL et Prisma : comptes, opérations et informations de suivi. |
| Authentification | Better Auth : accès personnel authentifié. |
| Cotations | Données de marché via Yahoo Finance, avec possibilité de saisie manuelle. |

## Du mouvement au portefeuille

Les dépôts, retraits, achats, ventes et dividendes alimentent le suivi des positions et des liquidités. La vue d’ensemble rassemble les comptes PEA et CTO et distingue gains latents, gains réalisés et dividendes reçus.

La liste de suivi conserve les convictions personnelles, l’horizon et les objectifs de prix. Les repères de marché restent distincts de ces notes.

Les visuels publics sont des compositions simplifiées avec des données fictives. Aucun portefeuille personnel ni identifiant de connexion n’est publié dans ce dépôt.
