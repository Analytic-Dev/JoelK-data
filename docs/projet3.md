# 🌐 Projet — Tableau de Bord de Suivi des Ventes

## 🎯 Contexte du projet

Ce projet consiste à développer un tableau de bord Power BI permettant de suivre les performances commerciales d'une entreprise spécialisée dans la vente de produits électroniques.  
L'objectif est de fournir aux équipes dirigeantes, financières et commerciales un outil d'analyse moderne, interactif et automatisé pour comprendre les tendances de ventes, identifier les leviers de croissance et améliorer la prise de décision.

## 🎯 Objectifs

Le tableau de bord répond aux objectifs suivants :

• Offrir une vision globale du chiffre d'affaires, des volumes de ventes et des marges.  
• Permettre une analyse détaillée par pays, marque, catégorie et sous-catégorie de produits.  
• Identifier les magasins performants et les axes d'amélioration.  
• Analyser l'évolution des ventes dans le temps et comparer les performances annuelles.  
• Automatiser le suivi des indicateurs clés pour réduire le temps d'analyse.  
• Faciliter l'exploration des données grâce à des fonctionnalités de drill-down et filtres interactifs.

---

## 🧩 Modèle de données

Les données utilisées proviennent d'un dataset retail contenant :

• les produits et leurs catégories  
• les marques  
• les pays  
• les magasins et nombre d'employés  
• les transactions de ventes  
• un calendrier analytique

### 📐 Modélisation : Star Schema

Le modèle repose sur une structure en étoile avec :

• **Tables de dimensions** : Produit, Marque, Pays, Date, Boutique  
• **Table de faits** : Ventes

### 🔧 Étapes de préparation

• Nettoyage des données sous Power Query  
• Création de relations entre tables  
• Création des métriques nécessaires en DAX :  
  • Chiffre d'affaires total  
  • Nombre de ventes  
  • Taux de marge brute  
  • Évolution CA N vs N-1  
  • Taux de retour  
  • CA moyen par boutique  
  • CA par catégorie / sous-catégorie

---

## 🖥️ Structure du tableau de bord

Le tableau de bord est composé de trois pages complémentaires permettant une navigation fluide du global vers le détail.

### 🔹 Page 1 — Vue d'ensemble des ventes

**Objectif** : fournir une vision synthétique et stratégique.

**Indicateurs affichés :**  
• CA total  
• Nombre de ventes  
• Taux de marge brute  
• Évolution CA (N vs N-1)  
• Taux de retour

**Analyses visuelles :**  
• CA et marge par pays  
• CA par marque  
• Répartition du CA par catégorie de produits  
• Évolution du CA dans le temps

**Fonctionnalités :**  
• Filtres dynamiques : année, pays, marque, catégorie produit  
• Drill-down :  
  • clic sur un pays → Page 2  
  • clic sur une marque → Page 3

### 🔹 Page 2 — Analyse des ventes par pays

**Objectif** : analyser la performance commerciale d'un pays sélectionné.

**Indicateurs affichés :**  
• Pays sélectionné  
• CA total  
• Nombre de ventes  
• CA moyen par boutique  
• Taux de marge brute  
• Taux de retour

**Analyses visuelles :**  
• CA par sous-catégorie de produit  
• CA par marque  
• Liste des boutiques (CA, marge, ventes, nb employés)  
• Répartition du CA par catégorie produit

**Fonctionnalités :**  
• Filtres : année, marque, catégorie produit, fabricant  
• Drill-through automatique depuis la page 1  
• Navigation via un bouton Retour

### 🔹 Page 3 — Analyse des ventes par marque

**Objectif** : évaluer la performance d'une marque spécifique.

**Indicateurs affichés :**  
• Marque sélectionnée  
• CA total  
• Nombre de ventes  
• Évolution CA N vs N-1  
• Taux de marge brute  
• Taux de retour

**Analyses visuelles :**  
• CA par pays  
• CA par catégorie et sous-catégorie  
• Répartition du CA par boutiques

**Fonctionnalités :**  
• Filtres : année, pays, catégorie produit  
• Drill-through depuis la page 1  
• Navigation via bouton Retour

---

## 🖌️ Design & UX

Le dashboard suit des principes de data-visualisation professionnels :

• Palette de couleurs cohérente et lisible  
• Mise en avant des KPIs dans des cartes hautes  
• Organisation logique : du global au détaillé  
• Filtres placés à gauche pour une utilisation intuitive  
• Icônes de navigation claire  
• Alignement et cohérence visuelle entre les trois pages

---

## 🧠 Compétences démontrées

Ce projet démontre la maîtrise de :

• Power BI Desktop  
• Modélisation de données (Star Schema)  
• Power Query (nettoyage et transformations)  
• DAX (création de mesures avancées)  
• Visualisation de données  
• UX/UI pour tableaux de bord  
• Analyse commerciale  
• Automatisation du reporting  
• Création d'interactions (drill-down & drill-through)

---

## 📊 Impact métier

Ce tableau de bord offre un impact réel sur la performance de l'entreprise :

• **Pilotage commercial amélioré** grâce à une vision claire du CA, des marges et des ventes.  
• **Décisions plus rapides et pertinentes**, basées sur des indicateurs fiables et actualisés.  
• **Identification immédiate** des pays, marques et produits performants ou en difficulté.  
• **Optimisation des performances des boutiques** grâce aux analyses détaillées.  
• **Gain de temps important** grâce à la centralisation et à l'automatisation des analyses.  
• **Meilleure compréhension du mix produits**, facilitant les décisions marketing et d'approvisionnement.
