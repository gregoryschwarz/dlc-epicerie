# DLC Épicerie

PWA de suivi des dates limites de consommation (DLC) pour les produits d'épicerie — usage interne, synchronisée entre appareils via Google Sheets.

## App en ligne

https://gregoryschwarz.github.io/dlc-epicerie/DLC_Epicerie.html

## Fonctionnalités

- Suivi des DLC avec statuts colorés (expiré / ce mois / prochain / ok)
- Charte de retrait à J-15 : un produit doit être retiré du rayon 15 jours avant sa DLC
- Installable comme application (PWA, Android + PC)
- Synchronisation multi-appareils via Google Sheets (Google Apps Script)
- Catégories de produits, tri, historique des actions, export CSV/PDF
- Alerte email quotidienne pour les produits à retirer ou proches du retrait

## Configuration

L'URL du script et la clé d'accès se configurent directement dans l'app (menu ⋯ → Configurer Google Sheets). Aucune donnée sensible n'est stockée dans ce dépôt.

## Stack

HTML/CSS/JS (PWA, aucune dépendance), Google Apps Script + Google Sheets comme backend.
