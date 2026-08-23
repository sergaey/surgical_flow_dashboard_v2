# Surgical Flow Dashboard — Bloc central (Lot 1\)

**Hôpital Foch · ESPIC Suresnes · Fil Rouge Groupe 16**

Dashboard de pilotage du bloc opératoire — version statique autonome (single-file HTML \+ Chart.js).

## 🌐 Accès en ligne (v5 — version courante)

> [**▶ Ouvrir le dashboard v5**](https://sergaey.github.io/surgical_flow_dashboard_v2/surgical_flow_dashboard_v5.html) `https://sergaey.github.io/surgical_flow_dashboard_v2/surgical_flow_dashboard_v5.html`

---

## Démarrage rapide (Windows)

Lancer\_Dashboard.bat

Double-cliquez sur `Lancer_Dashboard.bat` — le dashboard s'ouvre directement dans votre navigateur. Aucune installation requise.

**Ou ouvrez directement** `surgical_flow_dashboard_v5.html` dans Chrome / Edge.

**Accès en ligne** : [https://sergaey.github.io/surgical\_flow\_dashboard\_v2/surgical\_flow\_dashboard\_v5.html](https://sergaey.github.io/surgical_flow_dashboard_v2/surgical_flow_dashboard_v5.html)

---

## Comptes de démonstration

| Profil | Login | Mot de passe |
| :---- | :---- | :---- |
| Directeur général | `dg` | `foch2026` |
| Chef de bloc | `chefbloc` | `foch2026` |
| Chirurgien | `chirurgien` | `foch2026` |
| Anesthésiste | `anesthesiste` | `foch2026` |
| Cadre | `cadre` | `foch2026` |
| Admin | `admin` | `foch2026` |

Chaque profil ne voit que ses onglets et ses données (RBAC appliqué côté interface).

## Nouveautés v5

- **TROS** ajouté dans tous les onglets  
- **Démarrages tardifs** (ex-Ponctualité) renommé partout  
- **Débordements** (cas) dans tous les bilans  
- **Suspensions et abandons** dans tous les bilans  
- **Nombre de vacations** dans tous les onglets  
- **Seuil TVO relevé à 85 %**  
- **5 nouveaux blocs** : OPH, AMP, Endo-Uro, Salle de naissance, Radio-Bloc  
- **Durée moyenne opératoire** (renommé)  
- IMPACT TVO, TAUX D'ANNULATION, TURN-OVER MOYEN supprimés des KPIs

## Contenu du dashboard

- **Vue globale** — KPIs synthèse, TOP5/FLOP5 salles, récap mensuel  
- **Bilans** — BCentral 2025, BFastTrack 2025, Robot 2025  
- **Alertes** — suivi des déviations (seuil 85 %)  
- **Modules analytiques** — TVO/TROS, démarrages tardifs, activité, qualité, RH, éco  
- **Autres blocs** — OPH, AMP, Endo-Uro, Salle de naissance, Radio-Bloc

## Stack technique

| Composant | Technologie |
| :---- | :---- |
| Frontend | HTML5 \+ CSS3 \+ JavaScript (vanilla) |
| Graphiques | Chart.js 4.4.0 |
| Déploiement | Single-file · GitHub Pages |

---

*Projet pédagogique — données anonymisées — usage interne STBF*  
