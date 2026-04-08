# 🚛 Laourine Logistique — Plateforme Digitale

> *« Bienvenue sur la plateforme digitale de Laourine Logistique, où chaque trajet est une signature d'engagement. »*

---

## 🌍 À Propos

**Laourine Logistique** est une agence de transport et de services logistiques basée en **Tunisie**, fondée et dirigée par **Asma Laourine**.

Notre mission est simple : redéfinir la logistique tunisienne en alliant **rigueur opérationnelle** et **proximité humaine**. Chaque trajet, chaque livraison, chaque mission est traitée comme un engagement envers nos clients — pas simplement une prestation.

Cette plateforme digitale est le reflet de cette vision : un outil moderne, fluide et accessible, conçu pour faciliter la gestion et le suivi de nos services logistiques.

---

## ✨ Ce que nous offrons

- 🚚 **Transport de marchandises** — local, régional et national
- 📦 **Gestion logistique** — suivi, planification et coordination des flux
- 🤝 **Proximité client** — une équipe à l'écoute, réactive et engagée
- 📍 **Couverture nationale** — opérant à travers tout le territoire tunisien
- 🔒 **Fiabilité & ponctualité** — parce que votre confiance est notre priorité

---

## 🖥️ La Plateforme

La plateforme digitale de **Laourine Logistique** a été conçue pour offrir une expérience fluide et intuitive à nos clients et partenaires. Elle permet de :

- 📋 Consulter et gérer les missions de transport
- 📊 Suivre l'état des trajets en temps réel
- 📬 Faciliter la communication entre les équipes et les clients
- 🗂️ Centraliser les données logistiques en un seul endroit

---

## 🛠️ Tech Stack

| Couche | Technologie |
|---|---|
| 🖥️ Backend | [Symfony](https://symfony.com/) (PHP Framework) |
| 🗄️ Base de données | [MariaDB](https://mariadb.org/) |
| 🎨 Frontend | HTML / CSS / JavaScript |

---

## 🚀 Installation & Démarrage

### Prérequis

- PHP >= 8.1
- Composer
- MariaDB
- Symfony CLI *(recommandé)*

### Étapes

```bash
# 1. Cloner le dépôt
git clone https://github.com/your-username/laourine-logistique.git
cd laourine-logistique

# 2. Installer les dépendances PHP
composer install

# 3. Configurer l'environnement
cp .env .env.local
# Modifier .env.local et renseigner votre DATABASE_URL

# 4. Créer la base de données et exécuter les migrations
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate

# 5. Lancer le serveur de développement
symfony server:start
```

---

## 📁 Structure du Projet

```
├── src/
│   ├── Controller/        # Contrôleurs Symfony
│   ├── Entity/            # Entités Doctrine (Mission, Client, Trajet...)
│   ├── Repository/        # Requêtes base de données
│   └── Form/              # Formulaires Symfony
├── templates/             # Templates Twig
├── public/                # CSS, JS et assets statiques
├── migrations/            # Fichiers de migration
└── config/                # Configuration Symfony
```

---

## 👤 À la tête de l'agence

| | |
|---|---|
| 👩‍💼 **Dirigeante** | Asma Laourine |
| 🏢 **Agence** | Laourine Logistique |
| 🌍 **Pays** | Tunisie |
| 💼 **Secteur** | Transport & Logistique |

---

## 📄 Licence

Ce projet est sous licence [MIT](LICENSE).

---

> 🚛 *Laourine Logistique — Chaque trajet est une signature d'engagement.*
