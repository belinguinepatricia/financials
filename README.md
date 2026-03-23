# 📊 Tableau de Bord Financier & Commercial — Financial Dataset (Power BI)

> **Analyse des performances commerciales et financières** de septembre 2013 à décembre 2014 — 5 pays, 6 produits, 5 segments de clientèle.

---

## 📋 Table des matières

1. [Vue d'ensemble du projet](#vue-densemble-du-projet)
2. [Pages du rapport](#pages-du-rapport)
   - [Performance Financière](#1--performance-financière)
   - [Prévisions 2015](#2--prévisions-2015)
   - [Performance Commerciale](#3--performance-commerciale)
   - [Direction Générale](#4--direction-générale)
   - [Simulation & Scénarios (Contrôle de Gestion)](#5--simulation--scénarios-contrôle-de-gestion)
   - [KPI Géographique](#6--kpi-géographique)
   - [Analyse des Remises](#7--analyse-des-remises)
3. [Démos interactives](#démos-interactives)
4. [Chiffres clés à retenir](#chiffres-clés-à-retenir)
5. [Recommandations stratégiques](#recommandations-stratégiques)
6. [Limites & points de vigilance](#limites--points-de-vigilance)
7. [Stack technique](#stack-technique)
8. [Licence](#licence)

---

## Vue d'ensemble du projet

Ce rapport Power BI analyse les données du dataset public **"Financial"** fourni nativement par Microsoft. Il couvre **16 mois d'activité** (septembre 2013 à décembre 2014) sur 5 marchés : **USA, Canada, France, Allemagne et Mexique**.

L'objectif est de répondre à trois questions business concrètes :
- **Où gagne-t-on de l'argent ?** (par pays, produit, segment)
- **Les remises accordées sont-elles rentables ?**
- **Peut-on anticiper 2015 ?**

> 💡 **Pourquoi cette disposition des pages ?**
> L'ordre des pages a été pensé selon une logique narrative : on part de la **santé financière** (ce qu'on a gagné), on projette vers **l'avenir** (ce qu'on va gagner), on comprend **comment** on a vendu, on remonte à la **vue d'ensemble dirigeante**, on teste des **hypothèses de risque**, et enfin on ancre tout cela dans une **réalité géographique**. Cette progression guide le lecteur du résultat vers la stratégie.

---

## Pages du rapport

### 1 · Performance Financière

![Performance financière](https://github.com/user-attachments/assets/2e70d734-4ef4-41c1-8b83-60514f7950e9)

**Ce que montre cette page :** Les indicateurs de santé financière de l'entreprise — cash flow mensuel, seuil de rentabilité, profit par année, et identification du mois où l'entreprise devient rentable.

**Ce qu'on apprend :**
- Le **profit réel 2014 (13,02M) dépasse l'objectif fixé (2M) de +551%** — les ambitions initiales étaient manifestement trop prudentes.
- Le **profit 2013 (3,88M)** est réalisé sur seulement 4 mois actifs, ce qui représente un rythme annualisé très comparable à 2014.
- Le **mois de rentabilité est avril** — l'entreprise couvre l'intégralité de ses coûts fixes dès le 4ème mois de l'année, laissant 8 mois de bénéfice net.
- Le **Cash Flow Moyen Brut Mensuel est de 1,06M**, signe d'une trésorerie régulière et maîtrisée.

**Ce que ça signifie concrètement :** La structure financière est solide. Atteindre la rentabilité aussi tôt dans l'année est un signal très positif. En revanche, l'écart massif entre objectif et réalisé révèle un problème de calibrage des prévisions — un sujet à corriger en priorité pour les exercices futurs.

---

### 2 · Prévisions 2015

![Prévisions 2015](https://github.com/user-attachments/assets/d2915ba7-9c74-4f33-ba59-b7f990e3747c)

**Ce que montre cette page :** Les projections de ventes, profit et seuil de rentabilité pour l'année 2015, ventilées par segment de clientèle, par pays et par produit.

**Ce qu'on apprend :**
- Les **ventes 2015 sont projetées à 92,31M**, avec un **profit attendu de 13,02M**.
- Le **seuil de rentabilité prévisionnel est de 46,87M** — l'entreprise devra générer ce niveau de CA avant de commencer à être bénéficiaire.
- L'**indice de survie prévu est de 1,97** — autrement dit, l'entreprise génère presque le double de ce dont elle a besoin pour couvrir ses coûts vitaux.
- Par segment, les **Petites Entreprises (139M) et le Secteur Public (119M)** dominent les projections, en cohérence avec les tendances observées.
- Par pays, les marchés sont relativement équilibrés, entre **16M (Mexique) et 20M (USA / Canada)**.

⚠️ **Limites importantes documentées dans le rapport :**
- Seulement 2 années de données disponibles, dont une incomplète.
- Aucune saisonnalité modélisée.
- Les facteurs externes (concurrence, conjoncture) ne sont pas intégrés.
- Ces prévisions sont des **extrapolations linéaires** — pour une fiabilité réelle, il faudrait 3 à 5 ans d'historique et un modèle de régression statistique.

**Ce que ça signifie concrètement :** Les prévisions donnent une direction utile mais ne sont pas à prendre comme des certitudes. Elles constituent une base de travail, pas un engagement contractuel.

---

### 3 · Direction Générale
![Direction generale](https://github.com/user-attachments/assets/786401e3-b22a-4bb3-b2fd-20fce0704cf8)

**Ce que montre cette page :** Un résumé exécutif destiné aux décideurs — vue synthétique du chiffre d'affaires total, du profit, du panier moyen et de la répartition par segment de clientèle.

**Ce qu'on apprend :**
- Le **Secteur Public représente 44% du CA total** avec 52,5M — c'est le segment le plus stratégique.
- Les Petites Entreprises arrivent en 2ème position avec 42,43M, suivies des Grandes Entreprises (19,61M).
- Les segments Moyennes Entreprises (2,38M) et Partenaires Commerciaux (1,8M) sont très marginaux — leur potentiel est clairement sous-exploité.
- Le **CA total sur la période atteint 118,73M**, avec un panier moyen global de 105,46 €.

**Ce que ça signifie concrètement :** Cette page est le "tableau de bord du dirigeant". Elle confirme que l'activité repose essentiellement sur deux segments (Public + Petites Entreprises). Développer les Moyennes Entreprises et les Partenaires Commerciaux représente un levier de croissance significatif pratiquement inexploité.

---

### 4 · Performance Commerciale

![Performance commerciale](https://github.com/user-attachments/assets/dbd33f93-55e6-4092-9f2d-15f248bc9018)

**Ce que montre cette page :** Les ventes décomposées par produit, par pays et par mois, avec un filtre interactif par année pour comparer 2013 et 2014.

**Ce qu'on apprend :**
- **Paseo** est le produit champion avec **33M de ventes totales** — très loin devant VTT (21M) et Vélo (18M).
- Les ventes sont **bien réparties entre les 5 pays** (entre 14M et 20M chacun) — pas de dépendance excessive à un seul marché.
- **Octobre est systématiquement le meilleur mois de l'année**, probablement lié aux cycles d'achat du Secteur Public ou à des campagnes commerciales de fin d'année.
- Le **panier moyen chute de 448 € en 2013 à 138 € en 2014** — plus de volume, mais des ventes moins chères à l'unité.

**Ce que ça signifie concrètement :** L'entreprise vend bien et sur plusieurs marchés, ce qui est une force. Mais la dépendance à Paseo est un risque réel : si ce produit perd de l'attrait ou fait face à un concurrent, le CA global en souffrirait fortement.

---

### 5 · Simulation & Scénarios (Contrôle de Gestion)

![Simulation et scénario](https://github.com/user-attachments/assets/a980a550-2910-4d09-84ab-3b2b7d9d8044)


**Ce que montre cette page :** Un outil de simulation permettant de tester l'impact d'une hausse des coûts (de 0% à 4%) sur le profit de l'entreprise, accompagné d'un graphique en cascade (waterfall) illustrant la variation du Free Cash Flow produit par produit.

**Ce qu'on apprend :**
- Une hausse des coûts de seulement **1% entraîne un impact négatif de -353 600 €** sur le profit — la structure de coûts est sensible aux variations.
- Le **graphique waterfall** montre que chaque produit contribue négativement à la variation du Free Cash Flow, ce qui signale une pression généralisée sur les marges.
- L'**objectif profit 2014 avait été fixé à 2M** — écrasé par le réalisé de 13,02M, ce qui confirme le problème de calibrage des objectifs évoqué en page 1.
- Le **profit réel 2013 est de 3,88M** pour 4 mois d'activité seulement.

**Ce que ça signifie concrètement :** Cette page est un outil d'aide à la décision précieux pour les équipes financières. Elle montre que l'entreprise, bien que rentable, reste vulnérable à une inflation des coûts. Anticiper ces hausses via des contrats fournisseurs sécurisés ou une révision tarifaire préventive est fortement conseillé.

---

### 6 · KPI Géographique

![kpi géographique](https://github.com/user-attachments/assets/16021258-437f-463d-8e50-4cd51aba88fa)

**Ce que montre cette page :** Une carte du monde interactive colorant les pays où l'entreprise est active, avec un filtre par année permettant de visualiser l'évolution de la présence géographique.

**Ce qu'on apprend :**
- L'entreprise opère sur **3 zones** : Amérique du Nord (USA, Canada), Europe de l'Ouest (France, Allemagne) et Amérique Latine (Mexique).
- La répartition géographique est **équilibrée** — aucun pays ne concentre la majorité des ventes.
- **Aucune présence en Asie, Afrique ou Europe de l'Est** — des marchés à fort potentiel entièrement absents du portefeuille.

**Ce que ça signifie concrètement :** La diversification sur 5 pays est une bonne pratique de gestion du risque. Cependant, tous ces marchés sont des économies matures à croissance modérée. Explorer des marchés émergents à forte croissance pourrait significativement amplifier les projections long terme.

---

### 7 · Analyse des Remises

![Analyse des remises](https://github.com/user-attachments/assets/a84b3037-16dd-46f8-967b-743bd90ae539)

**Ce que montre cette page :** L'impact des politiques de remises commerciales sur les volumes vendus et sur la rentabilité, réparti par groupe de remise : Aucun, Bas, Moyen et Élevé.

**Ce qu'on apprend :**
- Le **taux de remise moyen global est de 7%** — modéré, mais l'effet cumulé sur le profit est significatif.
- Les remises **"Élevées"** attirent le plus grand volume de ventes — mais au détriment de la marge.
- Le groupe **"Moyen"** offre le meilleur équilibre entre volume vendu et profit généré — c'est le point idéal de la courbe.
- La **marge bénéficiaire globale est de 14%**, un niveau correct mais perfectible.
- Le **Profit Cumulé toutes remises confondues est de 16,89M**, Paseo étant le plus contributeur (4,8M).

**Ce que ça signifie concrètement :** Offrir de grosses remises n'est pas toujours une bonne affaire. Cette page démontre que la politique de remise "Moyenne" est celle qui rapporte le plus, en combinant attractivité commerciale et préservation des marges. Réduire les remises élevées sur les produits déjà très demandés comme Paseo permettrait de gagner 2 à 3 points de marge supplémentaires.

---

## Démos interactives

### 🎥 Carte du monde interactive

https://github.com/user-attachments/assets/c6708a85-f439-4038-af2c-01635c2f4f19

La démo montre la navigation entre les années 2013 et 2014 sur la carte géographique. Les pays s'activent et se désactivent selon l'année sélectionnée, permettant de suivre visuellement l'évolution de la présence commerciale dans le temps.

### 🎥 Slicers interactifs

https://github.com/user-attachments/assets/9f30b92a-f646-41d1-9e56-6b2c48dc9d1f

La démo illustre comment les filtres (année, pays, produit, segment) sont **synchronisés sur toutes les pages du rapport**. Une sélection sur une page se répercute instantanément sur l'ensemble des visuels — ce qui permet une exploration rapide, intuitive et cohérente des données sans avoir à reconfigurer chaque graphique manuellement.

---

## Chiffres clés à retenir

| Indicateur | Valeur |
|---|---|
| CA Total (2013–2014) | 118,73M |
| Profit Total | 16,89M |
| Marge Bénéficiaire | 14% |
| Meilleur produit | Paseo (33M) |
| Segment dominant | Secteur Public (44% du CA) |
| Mois de rentabilité | Avril |
| Cash Flow Mensuel Moyen | 1,06M |
| Taux de remise moyen | 7% |
| Prévision CA 2015 | 92,31M |
| Indice de survie 2015 | 1,97 |

---

## Recommandations stratégiques

### 🔴 Priorité haute

**1. Diversifier le portefeuille produit**
Paseo porte à lui seul une part disproportionnée du CA. Investir dans la montée en puissance de VTT et Vélo — via des promotions ciblées ou un élargissement de gamme — réduit le risque de concentration et sécurise le chiffre d'affaires global.

**2. Revoir la politique de remises élevées**
Les remises fortes génèrent du volume mais rongent la marge. En plafonnant les remises à un niveau "Moyen" sur les produits à forte demande comme Paseo, l'entreprise pourrait préserver 2 à 3 points de marge supplémentaires — sans nécessairement perdre de clients.

**3. Sécuriser les coûts variables**
Une hausse de seulement 1% des coûts détruit 353 600 € de profit. Négocier des contrats fournisseurs à prix fixe ou mettre en place une couverture partielle des coûts logistiques est une mesure de protection indispensable.

### 🟡 Priorité moyenne

**4. Analyser et exploiter le pic d'octobre**
Ce pic récurrent est bien réel mais mal compris. Identifier son origine précise (fin de budget institutionnel ? campagne commerciale ?) permettrait de le piloter activement et de réduire les creux observés entre janvier et août.

**5. Recalibrer les objectifs commerciaux**
Des objectifs dépassés de 551% ne motivent personne et faussent la lecture de la performance. Fixer des cibles ambitieuses mais réalistes — basées sur les tendances réelles observées — donnera plus de sens aux résultats.

**6. Améliorer le modèle de prévision**
Les projections 2015 sont des extrapolations linéaires simples. Intégrer la saisonnalité, un historique plus long et des variables externes (conjoncture, concurrence) améliorera significativement la fiabilité des prévisions.

### 🟢 Priorité long terme

**7. Développer les segments sous-représentés**
Les Moyennes Entreprises (2,38M) et les Partenaires Commerciaux (1,8M) sont quasi absents du CA. Une stratégie commerciale dédiée à ces segments représente un levier de croissance organique important, sans avoir à conquérir de nouveaux marchés.

**8. Explorer des marchés à fort potentiel**
La présence actuelle se limite à 5 pays à économies matures. Des marchés en forte croissance (Europe de l'Est, Asie du Sud-Est, Afrique francophone) pourraient ouvrir des perspectives de développement significatives à l'horizon 2026–2028.

---

## Limites & points de vigilance

- **Données sur 16 mois seulement** (dont 4 mois incomplets en 2013) — insuffisant pour établir des tendances statistiquement robustes.
- **Pas de décomposition fine des coûts** — impossible de distinguer précisément coûts fixes et variables.
- **Dataset de démonstration Microsoft** — les valeurs sont simulées et ne reflètent pas une entreprise réelle.
- **Seuil de rentabilité** — la mesure DAX a nécessité plusieurs itérations de correction en raison de la structure particulière du dataset (colonne année non reconnue par les slicers).
- **Prévisions 2015** — extrapolations linéaires à interpréter avec prudence, sans valeur prédictive garantie.

---

## Stack technique

| Outil | Usage |
|---|---|
| **Power BI Desktop** | Visualisation, modélisation, navigation entre pages |
| **DAX** | Mesures calculées (seuil de rentabilité, cash flow, simulations, prévisions) |
| **Dataset Financial (Microsoft)** | Source de données native Power BI |
| **Visuels natifs Power BI** | Cartes géographiques, barres, scatter, waterfall, slicers synchronisés |

---

## Licence

```
📄 Licence MIT
Copyright (c) 2026 BELINGUINE Patricia

L'autorisation est accordée, gracieusement, à toute personne acquérant une copie de ce logiciel
et des fichiers de documentation associés (le « Logiciel »), de l'utiliser sans restriction,
y compris sans limitation les droits d'utiliser, de copier, de modifier, de fusionner, de publier,
de distribuer, de sous-licencier et/ou de vendre des copies du Logiciel, et de permettre
aux personnes auxquelles le Logiciel est fourni de le faire, sous réserve des conditions suivantes :

La notice de copyright ci-dessus et la présente autorisation doivent être incluses dans toutes
les copies ou parties substantielles du Logiciel.

LE LOGICIEL EST FOURNI « EN L'ÉTAT », SANS GARANTIE D'AUCUNE SORTE, EXPRESSE OU IMPLICITE,
Y COMPRIS MAIS SANS S'Y LIMITER, LES GARANTIES DE QUALITÉ MARCHANDE, D'ADÉQUATION À
UN USAGE PARTICULIER ET D'ABSENCE DE CONTREFAÇON. EN AUCUN CAS LES AUTEURS OU TITULAIRES
DU DROIT D'AUTEUR NE POURRONT ÊTRE TENUS POUR RESPONSABLES D'UNE RÉCLAMATION, DOMMAGES
OU AUTRE RESPONSABILITÉ, QUE CE SOIT DANS LE CADRE D'UN CONTRAT, D'UN DÉLIT OU AUTRE,
DÉCOULANT DE, OU EN RELATION AVEC LE LOGICIEL OU L'UTILISATION OU AUTRES RAPPORTS AVEC LE LOGICIEL.

```

---

*Rapport conçu et réalisé par **BELINGUINE Patricia** — sur le dataset public Financial de Microsoft, à des fins d'analyse et de démonstration des capacités de Power BI.*

Analyste de données en recherche d'opportunités professionnelles
📧 [LinkedIn](https://www.linkedin.com/in/patricia-belinguine-434b01233/) | 🐙 [GitHub](https://github.com/belinguinepatricia)

---
---

# 📊 Financial & Commercial Dashboard — Financial Dataset (Power BI)

> **Analysis of commercial and financial performance** from September 2013 to December 2014 — 5 countries, 6 products, 5 customer segments.

---

## 📋 Table of Contents

1. [Project Overview](#project-overview)
2. [Report Pages](#report-pages)
   - [Financial Performance](#1--financial-performance)
   - [2015 Forecasts](#2--2015-forecasts)
   - [Commercial Performance](#3--commercial-performance)
   - [Executive Summary](#4--executive-summary)
   - [Simulation & Scenarios (Management Control)](#5--simulation--scenarios-management-control)
   - [Geographic KPIs](#6--geographic-kpis)
   - [Discount Analysis](#7--discount-analysis)
3. [Interactive Demos](#interactive-demos)
4. [Key Figures](#key-figures)
5. [Strategic Recommendations](#strategic-recommendations)
6. [Limitations & Caveats](#limitations--caveats)
7. [Tech Stack](#tech-stack)
8. [License](#license)

---

## Project Overview

This Power BI report analyzes the **"Financial"** public dataset natively provided by Microsoft. It covers **16 months of activity** (September 2013 to December 2014) across 5 markets: **USA, Canada, France, Germany, and Mexico**.

The report answers three core business questions:
- **Where is the money being made?** (by country, product, segment)
- **Are the discounts we offer actually profitable?**
- **Can we anticipate what 2015 will look like?**

> 💡 **Why this page order?**
> The page sequence follows a deliberate narrative logic: we start with **financial health** (what was earned), project toward **the future** (what will be earned), understand **how** sales happened, zoom out to an **executive overview**, stress-test with **risk scenarios**, and finally ground everything in **geographic reality**. This flow guides the reader from results to strategy.

---

## Report Pages

### 1 · Financial Performance

![Financial performance](https://github.com/user-attachments/assets/2e70d734-4ef4-41c1-8b83-60514f7950e9)

**What this page shows:** The company's core financial health indicators — monthly cash flow, break-even point, profit by year, and the month when profitability is reached.

**What we learn:**
- **Actual 2014 profit (13.02M) exceeded the target (2M) by +551%** — initial ambitions were clearly too conservative.
- **2013 profit (3.88M)** was achieved in only 4 active months, representing an annualized pace very comparable to 2014.
- **The break-even month is April** — the company covers all its fixed costs by month 4, leaving 8 full months of net profit.
- **Average Monthly Gross Cash Flow is 1.06M**, indicating stable and controlled cash generation.

**What this means in practice:** The financial structure is solid. Reaching break-even this early in the year is a very positive signal. However, the massive gap between target and actual reveals a forecasting calibration issue — a priority to address for future planning cycles.

---

### 2 · 2015 Forecasts

![2015 Forecasts](https://github.com/user-attachments/assets/d2915ba7-9c74-4f33-ba59-b7f990e3747c)

**What this page shows:** Sales, profit, and break-even projections for 2015, broken down by customer segment, country, and product.

**What we learn:**
- **2015 sales are projected at 92.31M**, with an **expected profit of 13.02M**.
- The **forecast break-even point is 46.87M** — the company must generate this level of revenue before turning profitable.
- The **projected survival index is 1.97** — meaning the company generates nearly twice what it needs to cover its essential operating costs.
- By segment, **Small Businesses (139M) and the Public Sector (119M)** lead the projections, consistent with observed trends.
- By country, markets are relatively balanced, ranging from **16M (Mexico) to 20M (USA / Canada)**.

⚠️ **Important limitations documented in the report:**
- Only 2 years of data available, one of which is incomplete.
- No seasonality modeled.
- External factors (competition, market conditions) are not factored in.
- These forecasts are **linear extrapolations** — for real predictive reliability, 3 to 5 years of history and a statistical regression model would be required.

**What this means in practice:** The forecasts provide a useful direction but should not be treated as certainties. They are a working baseline, not a contractual commitment.

---

### 3 · Commercial Performance

![Commercial Performance](https://github.com/user-attachments/assets/dbd33f93-55e6-4092-9f2d-15f248bc9018)

**What this page shows:** Sales broken down by product, country, and month, with an interactive year filter to compare 2013 and 2014.

**What we learn:**
- **Paseo** is the star product with **33M in total sales** — well ahead of MTB (21M) and Bike (18M).
- Sales are **well distributed across the 5 countries** (between 14M and 20M each) — no excessive dependency on a single market.
- **October is consistently the best month of the year**, likely tied to Public Sector procurement cycles or year-end commercial campaigns.
- The **average basket dropped from €448 in 2013 to €138 in 2014** — higher volume, but cheaper unit sales.

**What this means in practice:** The company sells well across multiple markets, which is a genuine strength. But the dependency on Paseo is a real risk: if this product loses appeal or faces competition, the overall revenue would suffer significantly.

---

### 4 · Executive Summary

![Direction generale](https://github.com/user-attachments/assets/786401e3-b22a-4bb3-b2fd-20fce0704cf8)

**What this page shows:** A high-level executive dashboard — a synthetic view of total revenue, profit, average basket, and distribution by customer segment, designed for decision-makers.

**What we learn:**
- The **Public Sector accounts for 44% of total revenue** at 52.5M — the most strategic segment by far.
- Small Businesses come second at 42.43M, followed by Large Enterprises (19.61M).
- Medium Enterprises (2.38M) and Commercial Partners (1.8M) are nearly absent — their potential is clearly under-exploited.
- **Total revenue over the period reached 118.73M**, with an overall average basket of €105.46.

**What this means in practice:** This page is the "CEO dashboard." It confirms that the business rests on two pillars (Public Sector + Small Businesses). Growing Medium Enterprises and Commercial Partners represents a significant, largely untapped organic growth lever.

---

### 5 · Simulation & Scenarios (Management Control)

![Simulation & Scenarios (Management Control)](https://github.com/user-attachments/assets/a980a550-2910-4d09-84ab-3b2b7d9d8044)

**What this page shows:** A simulation tool to test the impact of cost increases (from 0% to 4%) on company profit, alongside a waterfall chart showing the Free Cash Flow variation product by product.

**What we learn:**
- A cost increase of just **1% creates a negative impact of -€353,600** on profit — the cost structure is sensitive to variations.
- The **waterfall chart** shows every product contributing negatively to FCF variation, signaling broad margin pressure across the portfolio.
- The **2014 profit target had been set at 2M** — dwarfed by the actual 13.02M, confirming the target calibration issue flagged on page 1.
- **Actual 2013 profit was 3.88M** achieved in only 4 months of activity.

**What this means in practice:** This page is a valuable decision-support tool for finance teams. It shows that while the company is profitable, it remains vulnerable to cost inflation. Anticipating these increases through secured supplier contracts or preventive pricing adjustments is strongly advisable.

---

### 6 · Geographic KPIs

![Geographic KPIs](https://github.com/user-attachments/assets/16021258-437f-463d-8e50-4cd51aba88fa)

**What this page shows:** An interactive world map highlighting the countries where the company is active, with a year filter to visualize how geographic presence evolves over time.

**What we learn:**
- The company operates across **3 zones**: North America (USA, Canada), Western Europe (France, Germany), and Latin America (Mexico).
- Geographic distribution is **balanced** — no single country concentrates the majority of sales.
- **No presence in Asia, Africa, or Eastern Europe** — high-potential markets entirely absent from the portfolio.

**What this means in practice:** Operating across 5 countries is good risk management practice. However, all of these are mature, slow-growth economies. Exploring emerging markets with stronger growth trajectories could significantly amplify long-term projections.

---

### 7 · Discount Analysis

![Discount analysis](https://github.com/user-attachments/assets/a84b3037-16dd-46f8-967b-743bd90ae539)

**What this page shows:** The impact of commercial discount policies on sales volumes and profitability, broken down by discount group: None, Low, Medium, and High.

**What we learn:**
- The **overall average discount rate is 7%** — moderate, but with a significant cumulative effect on profit.
- **"High" discounts** attract the largest sales volume — but at the expense of margin.
- The **"Medium" group** delivers the best balance between volume sold and profit generated — the sweet spot.
- The **overall profit margin is 14%**, a correct but improvable level.
- **Total Cumulative Profit across all discount groups is 16.89M**, with Paseo as the top contributor (4.8M).

**What this means in practice:** Offering large discounts is not always a good deal. This page demonstrates that a "Medium" discount policy is the most profitable combination of commercial attractiveness and margin preservation. Capping high discounts on already in-demand products like Paseo could recover 2 to 3 additional margin points — with minimal risk of losing customers.

---

## Interactive Demos

### 🎥 Interactive World Map

https://github.com/user-attachments/assets/c6708a85-f439-4038-af2c-01635c2f4f19

The demo shows navigation between 2013 and 2014 on the geographic map. Countries activate and deactivate based on the selected year, providing a clear visual of how commercial presence evolved over time.

### 🎥 Interactive Slicers

https://github.com/user-attachments/assets/9f30b92a-f646-41d1-9e56-6b2c48dc9d1f

The demo illustrates how filters (year, country, product, segment) are **synchronized across all report pages**. A selection on one page instantly updates all visuals throughout the report — enabling fast, intuitive, and consistent data exploration without manually reconfiguring each chart.

---

## Key Figures

| Indicator | Value |
|---|---|
| Total Revenue (2013–2014) | 118.73M |
| Total Profit | 16.89M |
| Profit Margin | 14% |
| Top product | Paseo (33M) |
| Dominant segment | Public Sector (44% of revenue) |
| Break-even month | April |
| Average Monthly Cash Flow | 1.06M |
| Average discount rate | 7% |
| 2015 Revenue Forecast | 92.31M |
| 2015 Survival Index | 1.97 |

---

## Strategic Recommendations

### 🔴 High Priority

**1. Diversify the product portfolio**
Paseo alone carries a disproportionate share of revenue. Investing in the growth of MTB and Bike — through targeted promotions or range expansion — reduces concentration risk and protects overall revenue.

**2. Revise the high-discount policy**
Large discounts generate volume but erode margins. Capping discounts at "Medium" level on high-demand products like Paseo could preserve 2 to 3 extra margin points — without necessarily losing customers.

**3. Secure variable costs**
A mere 1% cost increase destroys €353,600 in profit. Negotiating fixed-price supplier contracts or partially hedging logistics costs is an essential protective measure.

### 🟡 Medium Priority

**4. Analyze and leverage the October peak**
This recurring peak is real but poorly understood. Pinpointing its exact cause (end-of-budget institutional spending? commercial campaign?) would allow it to be actively managed and the January–August slump to be reduced.

**5. Recalibrate commercial targets**
Targets exceeded by 551% motivate no one and distort performance reading. Setting ambitious but realistic goals — based on actual observed trends — will give results more meaningful context.

**6. Upgrade the forecasting model**
2015 projections are simple linear extrapolations. Incorporating seasonality, longer historical data, and external variables (market conditions, competition) will significantly improve forecast reliability.

### 🟢 Long-term Priority

**7. Develop under-represented segments**
Medium Enterprises (2.38M) and Commercial Partners (1.8M) are virtually absent from revenue. A dedicated commercial strategy for these segments represents a significant organic growth lever, without requiring new market entry.

**8. Explore high-potential markets**
Current presence is limited to 5 mature-economy countries. Fast-growing markets (Eastern Europe, Southeast Asia, French-speaking Africa) could open significant development opportunities on a 2026–2028 horizon.

---

## Limitations & Caveats

- **Only 16 months of data** (including 4 incomplete months in 2013) — insufficient for statistically robust trend analysis.
- **No detailed cost breakdown** — unable to precisely distinguish fixed from variable costs.
- **Microsoft demo dataset** — values are simulated and do not reflect a real company.
- **Break-even measure** — the DAX measure required several correction iterations due to the dataset's particular structure (year column not recognized by slicers).
- **2015 forecasts** — linear extrapolations to be interpreted with caution; no guaranteed predictive value.

---

## Tech Stack

| Tool | Usage |
|---|---|
| **Power BI Desktop** | Visualization, modeling, inter-page navigation |
| **DAX** | Calculated measures (break-even, cash flow, simulations, forecasts) |
| **Financial Dataset (Microsoft)** | Native Power BI data source |
| **Native Power BI visuals** | Geographic maps, bar charts, scatter plots, waterfall charts, synchronized slicers |

---

## License

```
MIT License

Copyright (c) 2026 BELINGUINE Patricia

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

*Report designed and created by **BELINGUINE Patricia** — using the Microsoft public Financial dataset, for analytical and Power BI capability demonstration purposes.*

Data Analyst actively loooking for a new challenge

📧 [LinkedIn](https://www.linkedin.com/in/patricia-belinguine-434b01233/) | 🐙 [GitHub](https://github.com/belinguinepatricia)
