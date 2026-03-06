---
title: "Parcours Professionnel"
date: 2026-03-02
draft: false
---

## Lead Developer & Solution Architect — RCF Notre Dame (64 Radios)
*Lyon | Depuis 2024*

**Rôle :** Responsable de l'architecture logicielle et de l'infrastructure de l'écosystème web (64 radios locales). Direction technique d'une équipe de 2 développeurs et référent sur les choix technologiques.

### 🏗️ Architecture Headless & Front-end (Nuxt 3/4)
* **Migration Framework :** Pilotage de la transition vers **Nuxt 3** (moteur Nitro). Travail actuel sur l'interopérabilité avec **Nuxt 4**.
* **Back office commun :** Pilotage des évolutions d'un back office **Drupal** commun aux 64 radios. Gestion de étanchéité de données et des droits utilisateurs.
* **Découplage API :** Evolution de l'**API** Drupal pour servir le site média et l'application mobile. Surveillance des performances et gestion de la charge BDD. 
* **Optimisation des performances :** Gestion d'un trafic de **460 000 sessions/mois**. Optimisation du rendu (SSR), suivi des Core Web Vitals, gestion de cache, réécriture de requêtes SQL.
* **Productivité IA :** Intégration systématique de l'IA générative (**Gemini, ChatGPT, Mistral**) dans le workflow (sécurité, optimisation, performances), et de **GitHub Copilot** / **Claude Code** pour l'accélération du développement quotidien. Ces outils permettent non seulement d'augmenter significativement ma productivité, mais aident également à voir plus loin et différemment, à ne pas rester figer dans ma zone de confort et à inventer de nouvelles solutions fiables.

### ☁️ Ingénierie Cloud & Middleware CRM (Stack AWS)
Conception et maintenance d'un middleware serverless assurant la liaison entre différents services et le CRM propriétaire (gestion des donateurs et leads).

* **Pipeline Serverless :** Orchestration via **AWS CloudFormation** (Infrastructure as Code).
* **Flux de données :** Exposition des endpoints via **API Gateway**, logique métier traitée par **AWS Lambda** (Producer / Worker).
* **Résilience & Découplage :** Utilisation de files d'attente **AWS SQS** pour l'ingestion asynchrone des données. Ce choix technique garantit la persistance des données et l'absorption des pics de charge lors des campagnes nationales de dons, sans impacter les temps de réponse.
* **Sécurité & État :** Sécurisation de données sensible via **Secrets Manager**, prévention des doublons grâce à **DynamoDB**.
* **Infrastructure:** Supervision et mises à jour des enregistrements DNS (zones, alias, entrées TXT) pour l'ensemble du parc de domaines chez **OVH**.. Supervision des serveurs de recette avec configuration nginx, mise en place des certificats de sécurité et administration de base de données.

---

## Développeur Fullstack — Union RCF
*Lyon | 2022 – 2024*

### Conception & Industrialisation
* **Outil métier "Programmation Radio" :** Développement complet d'une application web interne permettant aux radios de partager et collaborer sur leurs grilles de programmes, leurs métadonnées.
* **Refonte Orientée Objet :** Migration du code legacy procédural vers une architecture **POO (PHP/Drupal)**. Mise en place de classes d'objets et de composants réutilisables.  Factorisation du code dans les classes et des services communs dédiés. Forte plus value en terme de performances et de maintenabilité du code.
* **Optimisation de base de données:** Structuration et requêtage complexe sous **MySQL**.
* **API First :** Normalisation des flux pour garantir une consommation identique par le site média et les applications mobiles.
