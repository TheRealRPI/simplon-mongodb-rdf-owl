# 🎬 StreamVault — MongoDB & Ontologies OWL/RDF

![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white)
![OWL](https://img.shields.io/badge/-OWL-FF6F00?style=flat)
![RDF](https://img.shields.io/badge/-RDF-0052CC?style=flat)
![Protégé](https://img.shields.io/badge/-Protégé-6B46C1?style=flat)
![WebVOWL](https://img.shields.io/badge/-WebVOWL-3B82F6?style=flat)
![Academic](https://img.shields.io/badge/-Projet%20académique-8B5CF6?style=flat)

## 📖 Description

StreamVault mandate la structuration de son catalogue de films hétérogènes via **MongoDB**, puis la modélisation d'une ontologie cinéma en **OWL/RDF**. Ce projet académique explore deux approches complémentaires de modélisation de données : le stockage flexible NoSQL et la représentation sémantique formelle.

## ✨ Fonctionnalités

- **Partie 1 — MongoDB** : import de données JSON, requêtes de filtrage (`$gt`, `$lt`, `$or`), opérations CRUD via MongoDB Compass
- **Partie 2 — Ontologie OWL/RDF** : modélisation d'un domaine cinéma avec classes, sous-classes, Object/Data Properties, individus et raisonneur
- **Visualisation** : graphe d'entités via WebProtégé et schéma interactif via WebVOWL
- **Export RDF/OWL** : ontologie exportée au format RDF/XML (`cinema_paradiso.rdf`)
- **Veille technologique** : document de synthèse sur MongoDB, RDF et OWL (PDF)

## 🔧 Prérequis

> [!IMPORTANT]
> Ce projet utilise des outils graphiques externes. Aucun environnement d'exécution (Node.js, Python) n'est requis.

| Outil | Version | Lien |
|-------|---------|------|
| MongoDB Compass | ≥ 1.40 | [mongodb.com/products/compass](https://www.mongodb.com/fr-fr/products/compass) |
| Protégé Desktop | 5.6.9 | [protege.stanford.edu](https://protege.stanford.edu/) |
| WebVOWL | — | [service.tib.eu/webvowl](https://service.tib.eu/webvowl/) |
| WebProtégé | — | [webprotege.stanford.edu](https://webprotege.stanford.edu/) |

## 🚀 Utilisation

### Partie 1 — MongoDB

Prise en main de MongoDB Compass sur `livres.json` : observation, filtrage (`$gt`, `$lt`, `$or`) et opérations CRUD.
→ [`rendus/MongoDB_Jalon01_Part01.md`](rendus/MongoDB_Jalon01_Part01.md)

### Partie 2 — Ontologie OWL/RDF

Création d'une ontologie cinéma « Cinéma Paradiso » avec Protégé Desktop (classes, Object/Data Properties, individus) et visualisation via WebVOWL.
→ [`rendus/OWL-RDF_Brief1_Partie2.md`](rendus/OWL-RDF_Brief1_Partie2.md)

## 🗂️ Structure du projet

```
.
├── src/
│   └── livres.json                    # Données source MongoDB (8 livres)
├── rendus/
│   ├── MongoDB_Jalon01_Part01.md      # Partie 1 : MongoDB (Compass)
│   ├── OWL-RDF_Brief1_Partie2.md      # Partie 2 : Ontologie (Protégé)
│   ├── cinema_paradiso.rdf            # Ontologie exportée (RDF/XML)
│   ├── MongoDB, RDF, OWL.pdf          # Veille technologique
│   └── screenshots/                  # Captures d'écran (Compass, WebVOWL, …)
└── README.md
```

## 🔗 Ressources

- [MongoDB Compass](https://www.mongodb.com/fr-fr/products/compass)
- [Protégé Desktop](https://protege.stanford.edu/)
- [WebProtégé](https://webprotege.stanford.edu/)
- [WebVOWL](https://service.tib.eu/webvowl/)
- [MongoDB — Query Predicates (Comparison)](https://www.mongodb.com/docs/manual/reference/mql/query-predicates/comparison/)

## ✍️ Auteurs

[TheRealRPI](https://github.com/TheRealRPI) - 🧙 Sorcier de la Data | Data Engineer en formation - Simplon.co

## 📜 Licence

Projet académique - Simplon.co
