# 📊 Ecommerce Sales Analysis – Excel Dashboard

Projet de **dashboard interactif sous Excel** permettant d’analyser les ventes d’une entreprise e-commerce : performance globale, rentabilité par catégorie, comportement client et dynamique géographique.

> 🎯 Objectif : transformer un simple fichier Excel en **outil d’aide à la décision** clair, propre et directement présentable à un recruteur / manager.

---

## 🧾 Vue d’ensemble

- **Période couverte** : 2011 – 2014  
- **Volume de données** : 9 994 lignes, 22 variables  
- **Chiffre d’affaires total** : ~2,30 M€  
- **Profit total** : ~286 k€  

Le dashboard met en avant :

- Les **KPI clés** (Sales, Profit, Quantity, Profit Margin, …)  
- L’évolution **mensuelle / annuelle** des ventes et profits  
- La performance par **catégorie / sous-catégorie produit**  
- Les **Top 5 clients** et **Top produits**  
- La répartition des ventes par **région / état**

---

## 🧠 Questions business adressées

1. Quels sont les **revenus et profits** par année et par mois ?  
2. Quels **segments clients**, **régions** et **catégories produits** sont les plus rentables ?  
3. Quels sont les **Top 5 clients** et **produits** à forte valeur ?  
4. Quel est l’**impact des remises** (discount) sur la profitabilité ?  
5. Comment évoluent les KPIs **année après année (YoY)** ?

---

## 🗂 Jeu de données

Feuille **`Data`** (source principale) – 9 994 lignes, 22 colonnes :

| Colonne        | Description                                           |
|----------------|-------------------------------------------------------|
| `Row ID`       | Identifiant de ligne                                  |
| `Order ID`     | Identifiant unique de commande                        |
| `Year`         | Année de commande (2011–2014)                         |
| `Order Date`   | Date de commande                                      |
| `Ship Date`    | Date d’expédition                                     |
| `Ship Mode`    | Mode de livraison                                     |
| `Customer ID`  | Identifiant client                                    |
| `Customer Name`| Nom du client                                         |
| `Segment`      | Segment client (Consumer, Corporate, Home Office…)    |
| `Country`      | Pays (ici : principalement États-Unis)                |
| `City`, `State`, `Postal Code`, `Region` | Localisation géographique   |
| `Product ID`   | Identifiant produit                                   |
| `Category`     | Catégorie (Furniture, Office Supplies, Technology)    |
| `Sub-Category` | Sous-catégorie (Chairs, Phones, Binders, etc.)        |
| `Product Name` | Nom complet du produit                                |
| `Sales`        | Montant des ventes                                    |
| `Quantity`     | Quantité vendue                                       |
| `Discount`     | Remise appliquée                                      |
| `Profit`       | Profit réalisé                                        |

---

## 🧱 Structure du fichier Excel

Le classeur **`Ecommerce Sales Analysis.xlsx`** contient les feuilles suivantes :

- `Dashboard` → **Vue globale** et pilotage principal  
- `KPI` → Calcul des principaux indicateurs (Sales, Profit, Quantity, Margin…)  
- `KPI Year On Year` → Comparaisons **année vs année** (croissance, variation %)  
- `Combo chart` → Courbes combinées **Sales / Profit** dans le temps  
- `Waterfall chart` → Analyse de la contribution des catégories / segments au profit  
- `Pie chart` → Répartition des ventes / profits par catégorie ou région  
- `Map chart` → Carte des ventes par État / région  
- `Top 5` → Classement des clients / produits les plus contributeurs  
- `Data` → Données sources

> Ces feuilles sont organisées pour séparer **data**, **calculs** et **visualisation**, ce qui facilite la maintenance du fichier.

---

## 📌 Fonctionnalités du dashboard

- **Cartes de KPI** en haut de page (Sales, Profit, Quantity, Profit Margin…)  
- **Graphiques dynamiques** :
  - Évolution mensuelle des ventes et profits  
  - Répartition par catégorie / sous-catégorie  
  - Performance géographique (régions / états)  
- **Top 5** (clients & produits) pour cibler rapidement les comptes clés  
- **Analyse des remises** pour comprendre leur impact sur la profitabilité  
- **Slicers / segments** (selon ta version Excel) pour filtrer :
  - Année  
  - Région  
  - Segment client  
  - Catégorie produit  

---

## 🔁 Méthodologie (logique projet)

1. **Exploration & nettoyage des données**
   - Vérification des types (dates, numériques, texte)  
   - Contrôle des doublons et des valeurs manquantes  
   - Création de variables dérivées (Année, Mois, etc.)

2. **Modélisation dans Excel**
   - Construction de **tables structurées** + **Tableaux Croisés Dynamiques**  
   - Calcul des KPIs (Sales, Profit, Profit Margin, YoY, Top N, etc.)  
   - Mise en place de plages nommées pour alimenter les graphiques

3. **DataViz & storytelling**
   - Sélection des graphiques adaptés (combo, waterfall, pie, map, bar chart…)  
   - Application d’un thème visuel cohérent (couleurs, polices, mise en page)  
   - Organisation du dashboard pour **raconter une histoire** business claire

---

## ▶️ Comment utiliser ce projet

1. **Cloner le repo / télécharger le fichier Excel**

   ```bash
   git clone https://github.com/<ton-user>/<ton-repo>.git
