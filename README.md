# 📊 Tableau de Bord Financier & Commercial — Financial Dataset (Power BI)

Dashboard exécutif d'analyse commerciale et financière, construit sur le jeu de
données Financial Sample, avec modélisation en étoile, paramètre de simulation
"Quoi si ?", prévisions 2015 et audit complet du modèle DAX.
 
 · 📄 [Audit technique complet](Audit_DAX_Complet_Financials_v3.docx](https://github.com/user-attachments/files/31826765/Audit_DAX_Complet_Financials_v3.docx)
 
---
 
## 🎯 Contexte & objectif
 
[2-3 phrases : quelle question business le dashboard répond-il ? Ex. "Ce dashboard
donne à une direction commerciale une vue consolidée de la performance
2013-2014, des moteurs de croissance par segment/pays/produit, et une
projection 2015 avec analyse de scénario sur les coûts."]
 
## 🗂️ Contenu du rapport
 
| Page | Ce qu'elle montre |
|---|---|
| Executive Business Overview | KPI de synthèse : CA, marge, croissance YoY |
| Sales Performance & Drivers | Moteurs de croissance par segment/pays/produit |
| Sales Forecast & Business Planning | Prévision 2015, méthode et limites documentées |
| Forecast Drivers & Risk | Concentration du CA, risques de dépendance |
| Scenario Analysis & Decision Support | Simulation "+X % de coûts" via paramètre Quoi si ? |
| Pricing & Discount Effectiveness | Effet des remises sur la marge |
| Geographic Performance | Répartition et performance par pays |
media/Financial_ameliorer.mp4
 
## 🧠 Mesures DAX clés
 
Le modèle compte 77 mesures au total ([liste complète ici](formules_dax_financial.csv)).
Sélection de mesures illustrant des techniques DAX spécifiques :
 
- **`Taux de croissance`** — comparaison YoY à périmètre calendaire constant
  (VAR, CALCULATE + FILTER)
- **`Ventes Cumulees`** — cumul temporel avec TOTALYTD sur table de dates dédiée
- **`% CA Top 3 Segments`** — analyse de concentration avec TOPN + ALLSELECTED
- **`COGS Simulé`** — simulation de scénario pilotée par un paramètre
  "Quoi si ?" (SELECTEDVALUE)
- **`Marge de securité`** — traduction DAX d'un indicateur financier standard
  (seuil de rentabilité)
- **`Predictions Ventes 2015 par Segment`** — prévision avec taux de croissance
  comparable (voir section débogage ci-dessous)
 
## 🔍 Qualité des données & débogage
 
Ce projet a fait l'objet d'un audit ligne par ligne du code Power Query, du
modèle de données et des 77 mesures DAX. Quelques exemples de bugs réels
identifiés et corrigés :
 
| Problème trouvé | Impact | Correction |
|---|---|---|
| `DIVIDE(x, 0)` codé en dur dans le taux de croissance | La mesure renvoyait
toujours BLANK, invalidant en silence 4 mesures de prévision 2015 | Dénominateur
corrigé + comparaison à périmètre calendaire constant |
| `ALL(Table[Année])` à l'intérieur d'une mesure de total | Neutralisait tout
filtre direct sur l'année dans certains visuels | Modificateur retiré |
| Comparaison 4 mois (2013) vs 12 mois (2014) | Croissance 2013→2014
artificiellement gonflée dans toutes les prévisions | Comparaison ramenée
au même périmètre calendaire (Sept-Déc) |
 
[Audit complet avec les 77 mesures passées en revue →](assets/Audit_DAX_Financial.docx)
 
## 🗺️ Modèle de données
 
Schéma en étoile : table de faits `financials`, table `Calendrier` dédiée
(relation 1-à-plusieurs), et une table déconnectée `% Augmentation Couts`
servant de paramètre "Quoi si ?" pour l'analyse de scénario.
 
## 🛠️ Outils utilisés
 
Power BI Desktop · DAX · Power Query (M) · Modélisation en étoile ·
Paramètres "Quoi si ?" · 
 
## 📎 Fichiers du dépôt
 
- `Financials_commercial_financier.pbix` — le fichier Power BI complet
- `/docs` — audit technique détaillé et blueprint de conception
- `/screenshots` — capture de chaque page du rapport
- `/dax` — export complet des 77 formules DAX
- /video - navigation dans les pages
## 👤 Contact
 
**Patricia Belinguine** — [LinkedIn] · [email] · [portfolio]
