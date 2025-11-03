# 💸 Projet P12 – Détectez des faux billets avec R ou Python

## 🧭 Contexte du projet
Ce projet marque une étape importante de ma formation : la mise en œuvre concrète du **machine learning** pour résoudre un problème de **détection de fraude**.  
L’objectif était de créer un **modèle d’apprentissage supervisé** capable de distinguer les **vrais billets** des **faux billets** à partir de leurs caractéristiques géométriques.

À travers ce projet, j’ai mobilisé mes compétences en **préparation de données**, **analyse exploratoire**, **modélisation**, et **évaluation de performances** des modèles prédictifs.

---

## 🎯 Objectifs pédagogiques
- Utiliser un **modèle d’apprentissage supervisé** pour prédire un phénomène  
- Entraîner un **modèle non supervisé** afin d’en exploiter la structure et les similarités dans les données  
- Comparer et interpréter les résultats de plusieurs approches (supervisée et non supervisée)  
- Présenter clairement les résultats et recommandations à un public non technique  

---

## ⚙️ Démarche et méthodes

1. **Exploration et préparation des données**
   - Chargement du jeu de données contenant les mesures des billets (longueur, largeur, diagonale, etc.).  
   - Vérification de la qualité des données et traitement des valeurs manquantes.  
   - Visualisation des relations entre variables pour détecter d’éventuelles séparations naturelles entre vrais et faux billets.

2. **Analyse exploratoire et visualisation**
   - Création de graphiques pour observer la répartition des mesures et des classes.  
   - Étude des corrélations et identification des variables discriminantes.

3. **Modélisation**
   - Mise en place de modèles d’apprentissage :
     - **Supervisé :** régression logistique, SVM, arbre de décision, KNN.  
     - **Non supervisé :** clustering (k-means, ACP).  
   - Séparation des données en jeu d’entraînement et de test.

4. **Évaluation et interprétation**
   - Évaluation des modèles à l’aide de métriques (accuracy, recall, precision, F1-score).  
   - Interprétation des résultats et choix du modèle le plus performant.  
   - Présentation des conclusions et de la démarche dans un notebook complet.

---

## 🧩 Livrables réalisés
- 📓 **Notebook d’analyse complet** (Python / R)  
- 🧠 **Modèles d’apprentissage** entraînés et évalués  
- 📊 **Visualisations** illustrant la séparation entre vrais et faux billets  
- 🧾 **Rapport d’analyse** (PDF ou slides de présentation)  
- 📄 **Fiche d’autoévaluation** (discussion mentor)

---

## 🧠 Compétences développées
- Manipulation et préparation de jeux de données pour le machine learning  
- Maîtrise des **modèles supervisés** et **non supervisés**  
- Évaluation et comparaison de performances  
- Interprétation des résultats de modélisation  
- Communication claire des conclusions techniques  

---

## 💡 Enseignements tirés
> “Ce projet m’a permis d’appliquer concrètement le machine learning à un cas de détection de fraude.  
> J’ai appris à choisir le bon modèle, à interpréter les résultats avec rigueur et à vulgariser mes conclusions pour un public non technique.”

---

## 🖼️ Exemple de visuels
*(à ajouter une fois le projet finalisé)*  
```markdown
![Nuage de points – vrais vs faux billets](../../assets/images/faux_billets_scatter.png)
![Courbe ROC du modèle de classification](../../assets/images/faux_billets_ROC.png)
