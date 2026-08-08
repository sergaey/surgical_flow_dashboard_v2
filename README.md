# Surgical Flow Dashboard — Bloc central (Lot 1)
**Hôpital Foch · ESPIC Suresnes · Fil Rouge Groupe 16**

Dashboard de pilotage du bloc opératoire — version statique autonome (single-file HTML + Chart.js).

## Démarrage rapide (Windows)

```
Lancer_Dashboard.bat
```

Double-cliquez sur `Lancer_Dashboard.bat` — le dashboard s'ouvre directement dans votre navigateur. Aucune installation requise.

**Ou ouvrez directement** `surgical_flow_dashboard_v2.html` dans Chrome / Edge.

**Accès en ligne** : https://sergaey.github.io/surgical_flow_dashboard_v2/surgical_flow_dashboard_v2.html

## Comptes de démonstration

| Profil | Login | Mot de passe |
|---|---|---|
| Directeur général | `dg` | `foch2026` |
| Chef de bloc | `chefbloc` | `foch2026` |
| Chirurgien | `chirurgien` | `foch2026` |
| Anesthésiste | `anesthesiste` | `foch2026` |
| Cadre | `cadre` | `foch2026` |
| Admin | `admin` | `foch2026` |

Chaque profil ne voit que ses onglets et ses données (RBAC appliqué côté interface).

## Contenu du dashboard

- **Vue globale** — KPIs synthèse, TOP5/FLOP5 salles, récap mensuel
- **Interventions** — liste filtrée avec 7 critères (salle, spécialité, chirurgien…)
- **Bilans** — BCentral 2025, BFastTrack 2025, Robot 2025
- **Alertes** — suivi des déviations temps réel
- **Paramètres** — configuration des seuils et périodes

## Stack technique

| Composant | Technologie |
|---|---|
| Frontend | HTML5 + CSS3 + JavaScript (vanilla) |
| Graphiques | Chart.js 4.4.0 |
| Déploiement | Single-file · GitHub Pages |

---
*Projet pédagogique — données anonymisées — usage interne STBF*
