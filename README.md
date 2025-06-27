# 📊 Dashboard de Suivi des Réclamations et de la Satisfaction Client

## 🎯 Objectifs du Projet

Ce projet vise à concevoir un tableau de bord interactif et dynamique permettant de :

- **Améliorer l’expérience client**, en identifiant les points de friction les plus fréquents.
- **Optimiser les processus internes**, à travers l’analyse des délais de traitement et des types de réclamations.
- **Surveiller la performance opérationnelle**, notamment en évaluant les retards de vols et leur impact sur la satisfaction.

---

## 🧠 Démarche Adoptée

Pour structurer les données de manière optimale, un **modèle en étoile** a été mis en place au sein de l'entrepôt de données.  
Ce modèle repose sur une **table de faits principale** : `Réclamations et Interactions`, liée à trois **dimensions** :

- `Vols`
- `Clients`
- `Temps`

Ce schéma permet une analyse rapide, souple et multi-angulaire des données.

---

## 📌 Indicateurs Clés de Performance (KPI)

Les indicateurs ont été soigneusement sélectionnés pour fournir une vision stratégique à la fois sur la **satisfaction client** et la **performance opérationnelle** :

- **Total des Réclamations** : Volume global des plaintes reçues, utile pour évaluer la qualité perçue du service.
- **Moyenne de Satisfaction** : Score moyen donné par les clients, indicateur clé de la perception générale.
- **Nombre de Vols Retardés** : Permet de mesurer l’efficacité logistique et son influence sur l'expérience client.
- **Répartition des Réclamations par Statut** : Visualisation des réclamations résolues, en attente ou non traitées.
- **Évolution de la Satisfaction par Mois** : Suivi temporel des scores de satisfaction pour détecter les variations saisonnières ou les pics d’insatisfaction.
- **Top 5 des Vols par Satisfaction** : Identification des trajets les mieux évalués afin d’identifier les meilleures pratiques.
- **Top 5 des Aéroports par Satisfaction** : Mise en lumière des destinations offrant la meilleure expérience client.

> Ces KPI constituent une base solide pour le **storytelling des données**, en aidant à **prioriser les efforts d’amélioration**.

---

## 🧰 Outil Utilisé

Le tableau de bord a été développé avec **Power BI**, qui permet de centraliser, modéliser et visualiser efficacement les données. Cet outil a permis :

- Une analyse claire des données multi-sources,
- Un suivi en temps réel des indicateurs critiques,
- Une aide à la **prise de décision éclairée** pour les parties prenantes.

---

## 📷 Aperçu du Dashboard

![Aperçu du Dashboard](/dashboard.png)


