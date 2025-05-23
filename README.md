# mon-projet-docker-nell

Ce projet est un environnement Docker pour déployer l'application **Odoo**.

## 🚀 Objectifs

- Créer un environnement de développement Odoo basé sur Docker
- Utiliser `docker-compose` pour orchestrer les services
- Préparer une architecture prête à être utilisée en production

## 📦 Contenu

- `Dockerfile` : Installation d'Odoo dans un conteneur personnalisé
- `docker-compose.yml` : Lancement de plusieurs services (Odoo, PostgreSQL)
- `pgdata/` : Volume persistant pour PostgreSQL
- `addons/` : Modules Odoo personnalisés

## ▶️ Lancer le projet

```bash
docker-compose up --build
