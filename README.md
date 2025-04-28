# Projet Odoo avec Docker

Ce projet utilise Docker pour déployer Odoo 16.0 avec PostgreSQL 15.

## Prérequis

- Docker
- Docker Compose

## Installation

1. Clonez ce dépôt
2. Créez les dossiers nécessaires :

```bash
mkdir -p config addons
```

3. Lancez les conteneurs :

```bash
docker-compose up -d
```

## Accès

- Odoo : http://localhost:8069
- Identifiants par défaut :
  - Email : admin
  - Mot de passe : admin

## Structure des dossiers

- `config/` : Fichiers de configuration Odoo
- `addons/` : Modules personnalisés
- `docker-compose.yml` : Configuration Docker
