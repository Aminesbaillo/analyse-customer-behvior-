# Analyse et Modélisation de la Rétention des Avis Clients dans le Domaine du Commerce Électronique

Analyse et modélisation de la rétention des avis clients dans le domaine du commerce électronique en utilisant la régression logistique. Évaluation approfondie des performances avec des métriques telles que ROC et la perte logarithmique.

## Partie 1: Analyse Descriptive des Données

1.1 Importation des bibliothèques nécessaires et chargement du jeu de données "Amazon Customer behavior Survey"  
1.2 Analyse exploratoire de données  
1.3 Distributions des variables  

## Partie 2: Modélisation

2.1 Test d'indépendance entre les variables quantitatives  
2.2 Gestion des variables dans l'analyse de données  
2.3 Encodage one-hot des variables nominales  
2.4 Encodage ordinal des variables qualitatives  
2.5 Analyse de corrélation Point-Biserial entre 'Review_Left_Yes' et la variable quantitative 'age'  
2.6 Sélection des caractéristiques par tests statistiques  
2.7 Analyse du facteur d'inflation de la variance (VIF) pour les variables sélectionnées  

## Partie 3: Modélisation et Évaluation d'un Modèle de Régression Logistique

3.1 Calcul des erreurs standards des coefficients et test de Wald  
3.2 Analyse du modèle de régression logistique  
3.3 Modélisation et évaluation d'un modèle de régression logistique avec variables sélectionnées  
3.4 Test du rapport de vraisemblance pour la significativité du modèle  
3.5 Test de l'ajustement du modèle avec la statistique de Hosmer-Lemeshow  
3.6 Courbe Précision-Rappel avec Aire sous la Courbe (AUC-PR)  
3.7 Calcul de la perte logarithmique  
3.8 Courbe d'étalonnage du modèle  
3.9 Critère d'information bayésien (BIC)  
3.10 Courbe ROC (Receiver Operating Characteristic)
