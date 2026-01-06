# DR!NKME.md

# ⬡ KERN — Kit d'Éveil et de Résistance Numérique

> **Plateforme citoyenne open-source pour l'investigation, l'organisation et l'action collective.**

![Version](https://img.shields.io/badge/version-2.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-beta-orange)

---

## 🎯 C'est quoi KERN ?

KERN est une **boîte à outils numérique** conçue pour les citoyens, journalistes, activistes et chercheurs qui veulent :

- 📁 **Documenter** des enquêtes et investigations
- 🕸️ **Cartographier** des réseaux d'influence et de pouvoir
- 🔗 **Organiser** leurs contacts et sources
- 🧠 **Structurer** leurs connaissances
- 🎮 **Progresser** grâce à un système de gamification motivant
- 🤝 **Collaborer** avec un écosystème de partenaires

**100% local, 100% privé** — Vos données restent sur votre appareil.

---

## 🚀 Démarrage rapide

### Installation

1. **Téléchargez** le dossier `outils/`
2. **Ouvrez** `index.html` dans votre navigateur
3. **C'est tout !** Aucun serveur, aucune installation requise.

```
outils/
├── index.html          ← Point d'entrée
├── kern-core.js        ← Moteur unifié
├── 00-kern-nexus.html  ← Dashboard principal
└── ...                 ← Modules
```

### Premier lancement

1. Ouvrez `index.html` → Redirection automatique vers KERN::NEXUS
2. Un **profil agent** est créé automatiquement avec un nom de code unique
3. Explorez les modules via le menu latéral
4. Gagnez de l'XP en utilisant les outils !

---

## 🏗️ Architecture

```
                           ┌─────────────────────┐
                           │    KERN::NEXUS      │
                           │  Dashboard Central  │
                           └──────────┬──────────┘
                                      │
                    ┌─────────────────┼─────────────────┐
                    │                 │                 │
                    ▼                 ▼                 ▼
         ┌──────────────┐  ┌──────────────┐  ┌──────────────┐
         │   DOSSIERS   │  │  PANOPTICON  │  │   NETWORK    │
         │  Enquêtes &  │  │   Graphe     │  │   Contacts   │
         │  Documents   │  │  d'Entités   │  │  & Sources   │
         └──────┬───────┘  └──────┬───────┘  └──────┬───────┘
                │                 │                 │
                └─────────────────┼─────────────────┘
                                  │
                    ┌─────────────┴─────────────┐
                    │       KERN-CORE.js        │
                    │  ═══════════════════════  │
                    │  • Profil Agent Unifié    │
                    │  • Système XP & Niveaux   │
                    │  • 6 Compétences          │
                    │  • Recherche Globale      │
                    │  • Événements Cross-Module│
                    └─────────────┬─────────────┘
                                  │
         ┌────────────────────────┼────────────────────────┐
         │                        │                        │
         ▼                        ▼                        ▼
┌──────────────┐       ┌──────────────┐       ┌──────────────┐
│  KNOWLEDGE   │       │   MISSIONS   │       │   JOURNAL    │
│    Graph     │       │    Quêtes    │       │   de Bord    │
│  Zettelkasten│       │  Citoyennes  │       │              │
└──────────────┘       └──────────────┘       └──────────────┘
```

---

## 📦 Modules

### 🔷 Modules Principaux (intégrés KERN-CORE)

| Module | Fichier | Description |
|--------|---------|-------------|
| **📊 NEXUS** | `00-kern-nexus.html` | Dashboard central avec stats, activité récente, recherche globale |
| **📁 DOSSIERS** | `11-kern-dossiers.html` | Gestion d'enquêtes avec timeline, preuves, statuts |
| **🕸️ PANOPTICON** | `12-panopticon.html` | Graphe interactif d'entités (personnes, organisations, médias...) |
| **🔗 NETWORK** | `17-contact-network.html` | Carnet de contacts avec visualisation réseau |
| **🧠 KNOWLEDGE** | `16-knowledge-graph.html` | Notes interconnectées style Zettelkasten/Obsidian |
| **🎯 MISSIONS** | `02-mission-creator.html` | Système de quêtes et objectifs citoyens |
| **📓 JOURNAL** | `03-journal.html` | Journal de bord personnel avec tags |
| **🎮 NEXUS PRIME** | `13-nexus-prime.html` | Interface gamifiée complète avec skill tree |
| **🤝 PARTNERS** | `18-kern-partners.html` | Marketplace partenaires B2B |
| **📊 PARTNER DASH** | `19-kern-partner-dashboard.html` | Dashboard pour partenaires |

### ⬜ Modules Utilitaires (standalone)

| Module | Fichier | Description |
|--------|---------|-------------|
| **💰 Finance** | `01-finance-tracker.html` | Suivi finances personnelles |
| **📅 Agenda** | `05-agenda-politique.html` | Calendrier politique belge |
| **📚 Bibliothèque** | `06-bibliotheque.html` | Base de ressources |
| **📄 Générateur** | `06-generateur-documents.html` | Création de documents |
| **🎨 Forge Studio** | `08-forge-studio.html` | Studio créatif |
| **🇧🇪 BelData** | `09-beldata-complet.html` | Données politiques belges |
| **🇧🇪 BelData v2** | `10-beldata-citoyen-v2.html` | Version citoyenne étendue |
| **🎮 ARG** | `14-nexus-arg.html` | Jeu en réalité alternée |
| **♟️ Wargames** | `15-wargames.html` | Mini-jeux stratégiques |
| **📖 Wiki** | `wiki.html` | Documentation |

---

## 🎮 Système de Progression

### Profil Agent

Chaque utilisateur reçoit automatiquement :
- **Nom de code** unique (ex: SHADOW-LYNX, CIPHER-WOLF)
- **Niveau** (1-∞)
- **Points d'expérience** (XP)
- **Clearance** (grade de sécurité)

### Niveaux de Clearance

| Niveau | Clearance | XP requis |
|--------|-----------|-----------|
| 0 | 🔰 INITIÉ | 0 |
| 1 | 🎖️ AGENT | 500 |
| 2 | ⚡ OPÉRATEUR | 2,000 |
| 3 | 🔍 ANALYSTE | 5,000 |
| 4 | 📡 COORDINATEUR | 10,000 |
| 5 | 🎯 STRATÈGE | 25,000 |
| 6 | 🏛️ ARCHITECTE | 50,000 |
| 7 | 👑 MAÎTRE | 100,000 |

### Compétences (Skills)

| Skill | Développé par |
|-------|---------------|
| 🔍 **Investigation** | Créer des dossiers, ajouter des preuves |
| 🔗 **Network** | Ajouter des contacts, créer des connexions |
| 📊 **Analysis** | Créer des entités, lier des éléments |
| 📝 **Documentation** | Écrire des notes, tenir le journal |
| 🏃 **Fieldwork** | Compléter des missions |
| 🔒 **Opsec** | Actions de sécurité opérationnelle |

### Gains d'XP

| Action | XP | Skills |
|--------|-----|--------|
| Connexion quotidienne | +25 | — |
| Créer un dossier | +25 | Investigation, Documentation |
| Créer une entité | +15 | Analysis |
| Lier des entités | +10 | Analysis, Investigation |
| Ajouter un contact | +20 | Network |
| Connecter des contacts | +10 | Network |
| Créer une note | +15 | Documentation |
| Écrire dans le journal | +10 | Documentation |
| Compléter une mission | +50 | Fieldwork |

---

## 🔍 Fonctionnalités Clés

### Recherche Globale

Depuis NEXUS, recherchez instantanément dans :
- 📁 Tous vos dossiers
- 🕸️ Toutes les entités
- 🔗 Tous les contacts
- 🧠 Toutes les notes

### Interopérabilité

Les modules communiquent entre eux :
- Un dossier peut référencer des entités PANOPTICON
- Un contact peut être lié à une entité
- Une note peut mentionner un dossier
- Tout est interconnecté !

### Confidentialité

- ✅ **100% local** — Données stockées dans votre navigateur (localStorage)
- ✅ **Aucun serveur** — Pas de compte, pas de tracking
- ✅ **Export possible** — Sauvegardez vos données en JSON
- ✅ **Open source** — Code vérifiable

---

## 🤝 Espace Partenaires

KERN inclut une marketplace B2B permettant à des organisations de proposer leurs services.

### Grille Tarifaire

| Tier | CA Estimé | Prix/mois | Produits |
|------|-----------|-----------|----------|
| 🌱 Gratuit | < 100K€ | 0€ | 3 |
| 🥉 Bronze | 100K - 500K€ | 49€ | 5 |
| 🥈 Silver | 500K - 2M€ | 149€ | 7 |
| 🥇 Gold | 2M - 10M€ | 349€ | 9 |
| 💎 Platinum | 10M - 50M€ | 749€ | 45 |
| 👑 Diamond | > 50M€ | 1,499€ | ∞ |

### Devenir Partenaire

1. Ouvrez `18-kern-partners.html`
2. Cliquez sur "Pipeline" (admin)
3. Ajoutez votre organisation
4. Configurez vos produits (jusqu'à 9)

---

## 📊 Cas d'Usage

### 🔎 Journaliste d'Investigation

```
1. Créer un DOSSIER pour l'enquête
2. Ajouter des ENTITÉS (personnes, entreprises impliquées)
3. Cartographier les LIENS dans PANOPTICON
4. Documenter les sources dans NETWORK
5. Prendre des NOTES dans KNOWLEDGE
6. Suivre la progression via les MISSIONS
```

### 🏛️ Militant Citoyen

```
1. Suivre l'AGENDA POLITIQUE
2. Consulter BELDATA pour les votes des élus
3. Créer des DOSSIERS thématiques
4. Partager via la BIBLIOTHÈQUE
5. Coordonner via le JOURNAL
```

### 🔬 Chercheur OSINT

```
1. Cartographier un réseau dans PANOPTICON
2. Documenter les sources dans NETWORK
3. Croiser les informations dans KNOWLEDGE
4. Exporter les visualisations
```

---

## 🛠️ Personnalisation

### Thème

Les modules utilisent des variables CSS facilement modifiables :

```css
:root {
    --bg-void: #0a0a0f;      /* Fond principal */
    --accent: #6366f1;        /* Couleur accent */
    --green: #4ade80;         /* Succès */
    --amber: #fbbf24;         /* Attention */
    --cyan: #22d3ee;          /* Info */
}
```

### Extension

KERN-CORE expose une API globale :

```javascript
// Récupérer le profil agent
const agent = KERN.getAgent();

// Ajouter de l'XP
KERN.awardXP(50, 'Action personnalisée');

// Entraîner une compétence
KERN.trainSkill('investigation', 25);

// Émettre un événement
KERN.emit('custom:event', { data: 'payload' });

// Écouter un événement
KERN.on('dossier:created', (dossier) => {
    console.log('Nouveau dossier:', dossier);
});
```

---

## 📁 Structure des Fichiers

```
outils/
├── index.html                    # Point d'entrée (redirection)
├── kern-core.js                  # Moteur central (28 KB)
│
├── 00-kern-nexus.html            # Dashboard principal (52 KB)
│
├── 02-mission-creator.html       # Missions (42 KB)
├── 03-journal.html               # Journal (32 KB)
│
├── 11-kern-dossiers.html         # Dossiers (43 KB)
├── 12-panopticon.html            # Entités (47 KB)
├── 13-nexus-prime.html           # Gamification (104 KB)
│
├── 16-knowledge-graph.html       # Notes (38 KB)
├── 17-contact-network.html       # Contacts (53 KB)
│
├── 18-kern-partners.html         # Marketplace (62 KB)
├── 19-kern-partner-dashboard.html # Dashboard partenaire (49 KB)
│
├── 01-finance-tracker.html       # Finance (34 KB)
├── 05-agenda-politique.html      # Agenda (37 KB)
├── 06-bibliotheque.html          # Bibliothèque (42 KB)
├── 06-generateur-documents.html  # Générateur (52 KB)
├── 08-forge-studio.html          # Studio (74 KB)
├── 09-beldata-complet.html       # BelData (42 KB)
├── 10-beldata-citoyen-v2.html    # BelData v2 (52 KB)
├── 14-nexus-arg.html             # ARG (85 KB)
├── 15-wargames.html              # Jeux (44 KB)
├── wiki.html                     # Documentation (18 KB)
│
└── _archive/                     # Modules archivés
    ├── 00-citadel-command.html
    ├── 00-nexus-hq.html
    ├── 04-network-map.html
    └── 07-dashboard.html

Total: ~1 MB (22 modules actifs)
```

---

## 🔐 Stockage des Données

Toutes les données sont stockées localement via `localStorage` :

| Clé | Module | Contenu |
|-----|--------|---------|
| `kern_agent` | KERN-CORE | Profil agent, XP, skills |
| `kern_dossiers` | DOSSIERS | Liste des dossiers |
| `kern_entities` | PANOPTICON | Entités et liens |
| `kern_network_contacts` | NETWORK | Contacts |
| `kern_knowledge` | KNOWLEDGE | Notes |
| `kern_missions` | MISSIONS | Quêtes |
| `kern_journal` | JOURNAL | Entrées journal |
| `kern_partners` | PARTNERS | Partenaires |

### Export/Import

Chaque module propose des fonctions d'export :
- Format JSON pour backup complet
- Format CSV pour analyse externe

---

## 🤝 Contribuer

KERN est un projet open-source. Contributions bienvenues !

### Comment contribuer

1. **Fork** le projet
2. **Créez** une branche (`git checkout -b feature/ma-feature`)
3. **Committez** (`git commit -m 'Ajout de ma feature'`)
4. **Push** (`git push origin feature/ma-feature`)
5. **Ouvrez** une Pull Request

### Idées de contribution

- [ ] Mode sombre/clair
- [ ] PWA avec Service Worker
- [ ] Sync multi-appareils (optionnel)
- [ ] Import depuis d'autres outils (Notion, Obsidian)
- [ ] Visualisations D3.js avancées
- [ ] Mode collaboratif temps réel
- [ ] Intégration APIs externes (OpenCorporates, Wikidata...)

---

## 📜 Licence

MIT License — Utilisez, modifiez, distribuez librement.

---

## 🙏 Crédits

- **Concept & Design** : Projet citoyen collaboratif
- **Développement** : Claude (Anthropic) + Communauté
- **Icônes** : Emojis natifs
- **Graphes** : D3.js
- **Inspiration** : Obsidian, Notion, Maltego, Roam Research

---

## 📞 Support

- **Bugs** : Ouvrez une issue GitHub
- **Questions** : Discussions GitHub
- **Contact** : [À définir]

---

<div align="center">

**⬡ KERN — Parce que l'information, c'est le pouvoir.**

*Fait avec 💚 pour les citoyens engagés*

</div>
