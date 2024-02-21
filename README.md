# Qu'est-ce que le Machine Learning (Aprentissage automatique)

## Contexte du projet

Il s'agit d'une veille documentaire sur des sujets liés au Machine Learning afin d'appréhender et essayer de comprendre ces concepts avant de débuter des projets. 

## Définitions

### A. La science des données

La science des données combine les mathématiques, statistiques, la programmation, l'analyse avancée, l'intelligence artificielle et l'apprentissage automatique dans le but d'extraire des données pertinentes permettant de guider les décisions et le plan stratégique d'une entreprise. 

![data science](https://www.compta-online.net/images/expert-comptable-data-science.jpg)

### B. L’apprentissage automatique et/ou l’apprentissage profond

L'apprentissage automatique ou **machine learning** c'est une mise en application de l'intelligence artificielle comprenant des algorithmes qui analysent les données, apprennent de ces données et appliquent ce qu'ils ont appris pour prendre des décisions informées. 

L'apprentissage profond ou **deep learning** est une discipline du machine learning qui structure les algorithmes en couches pour créer un 'réseau neuronal artificiel' capable d'apprendre et de prendre des décisions intelligentes de façon autonome. 

Réseau neuronal artificiel : s'inspirant du réseau neuronal biologique il s'agit d'un réseau constitué de:
* une couche d'entrée
* une ou plusieurs couches cachées
* une couche de sortie

Chaque neuronne est connecté et possède un poid et seuil associé. Si le seuil est atteint la donnée est alors transféré à la couche suivante du réseau, sinon rien n'est transmis. 

![machine learning vs deep learnign](https://praedictia.com/wp-content/uploads/sites/107/2021/06/AI_and_MachineLearning.svg)

### C. L’apprentissage supervisé

Dans cette méthode de machine learning la machine apprend à l'aide d'exemples concrets qui contiennent un input et output. Le but étant d'entraîner la machine pour qu'elle puisse arriver à l'output en lui présentant uniquement des inputs.

Exemple: on des images de chiens & chats avec des labels *chien* & *chat*. Lorsqu'on va entraîner notre machine on lui présente les 2 informations, l'input qui est la photo et l'output qui est le label. 

Dans l'apprentissage sueprvisé on retrouve :
* classification : filtrage des nouvelles données en apportant des observations basée sur la donnée étudié au préalable
* regression : ici le programme estime et comprend la relation entre les différentes variables
* prédiction : il s'agit du procesus de prédiction basé sur la donnée étudiée et en étude

![apprentissage supervisé](https://fr.linedata.com/sites/default/files/inline-images/Schema-wide-fr.png)

### D. L’apprentissage non supervisé,

L'apprentissage non supervisé quant à lui est similaire à l'apprentissage supervisé, cependant l'ouput n'est pas présenté lors de l'entraînement de la machine. On fournis uniquement des inputs (exemple uniquement des images d'animaux) et l'algorithme s'entraîne pour identifier des patterns dans la donnée présentée. 

Ici on retrouve : 
* clustering : il s'agit du groupement de données similaires qui est utile pour la segmentation de la donnée dans plusieurs groupes afin de focaliser l'analyse de ces groupes
* dimension reduction : ici on va réduire le nombre de variables prise en considération lors de l'entraînement pour identifier les informations importantes à extraire

  ![apprentissage non supervisé](https://brightcape.co/wp-content/uploads/2019/01/unsupervisedLearning-1024x401.png)

### E. La classification supervisée

Similaire à l'apprentissage supervisé ici on va mettre en place des règles d'associations pour les différentes variables. Pour ce faire on utilise une *training area data* qui représente les différents types de variables que nous avons à notre disposition. Pour reprendre l'exemple précédent il s'agit de *chien* ou *chat*. On va donc utiliser de la donnée déjà classifiée dans un premier pour donner les patterns nécessaire à l'algorithme. Suite à cela il pourra classifier les nouvelles données en se basant sur la classification déjà existante. 

### F. La classification non supervisée

Ici on va classifier les données en se basant sur les pattern identifié lors de l'analyse de donnée et non en se basant sur des pattern pré-établits. L'avantage de cette méthode c'est qu'on ne définit pas de limite lors de l'identificatio de pattern ce qui signifie que l'algorithme peut potentiellement découvrir des patterns auxquels nous n'avions pas précédemment pensé. 

![classification supervisée vs non supervisée](https://datascientest.com/wp-content/uploads/2021/01/Apprentissage_Supervise%CC%81_Vs_Non_Supervise%CC%81.png)

### G. La régression

La regression est un model de machine learning qui permet d'estimer les relations entre les différentes variables. Là ou la classification identifie les catégories ou les observations doivent être, la regression estime la valeur de ces observation. C'est donc une analyse de donnée qui prédit la valeur de données inconnues en utilisant une autre valeur de données apparentée et connue. On va donc modéliser mathématiquement la variable inconnue ou dépendante et la variable connue ou indépendante sous forme d'équation linéaire. 

![regression linéaire](https://bookdown.org/AODiakite/r4econometrics/Pictures/lm.png)

ex : si on essaie d'estimer nos dépenses en 2024 on va utiliser nos dépenses en 2022, 2023 comme base d'analyse. Si le pattern remarqué lors de cette analyse est que 30% de notre revenu est utilisé dans nos dépenses on peut estimer qu'en 2024 on utilisera également +/- 30% de nos dépenses. On va donc déterminer une valeur basée sur nos revenus estimé en 2024. 

### H. La validation croisée

C'est une méthode statistique qui permet l'évaluation des performances des modèles d'apprentissage automatique. Cette méthode permet de déterminer un score lorsque notre algorithme de machine learning a été entraîné et a analysé un dataset inconnu. On va donc analyser la pertinence de l'analyse faite par l'algorithme. Cela nous permettra de choisir l'algorithme le mieux conçu pour analyser un dataset spécifique en comparant plusieurs algorithme et en choisissant celui avec la meilleure note. 

![validation croisée](https://www.kevindegila.com/images/cv.png)

### I. Les données d’entraînement, les données de test et/ ou de validation

Données d'entraînement : permettent au modèle d'apprendre des patterns ou des relations entre les différentes varibles / observations

Données de test : Permettent de vérifier que le modèle comprends les données d'entraîtenement et que l'apprentissage a bel et bien été entamé

Données de validation : utilisées avant les données de test elles permettent de s'assurer que le modèle est capable d'émettre des hypothèses, classifier, identifier etc la donnée inconnue

![entrainment / validation / test](https://stanford.edu/~shervine/teaching/cs-229/illustrations/train-val-test-fr.png?9ebf3eabcf1d1223ffa3b441a758e829)

### J. Corrélation linéaire (de Pearson) entre deux variables

Le coefficient de corrélation linéaire de Pearson est la méthode la plus commune pour mesurer la corrélation linéaire. Cette méthode nous donne un résultat en -1 et 1 ou -1/1 représente la corrélation la plus forte entre 2 variables.

![corrélation pearson](https://datatab.fr/assets/tutorial/%C3%89quation_de_la_corr%C3%A9lation_de_Pearson.png)

Si la corrélation est entre 0 et 1 on peut comprendre que lorsque la première variable change la deuxième variable change dans la même direction. Une corrélation négative signifie que la deuxième variable change dans une direction opposée. 0 signifie qu'il n'y a pas de corrélation entre les 2 variables. 

| Valeur | Force | Direction |
|---|---|---|
| > 0,5 | Forte | Positive |
| 0,3 - 0,5 | Modérée | Positive |
| 0 - 0,3 | Faible | Positive |
| 0 | Nulle | Nulle |
| 0 - (-0,3) | Faible | Négative |
| -0,3 - (-0,5) | Modérée | Négative |
| < -0,5 | Forte | Négative |

### K. Une fonction de coût

La fonction de coût mesure la performance d'un modèle d'apprentissage automatique pour un dataset. Cette fonction va quantifier les erreurs entre la donnée prédite et la donnée attendue. Ces erreurs sont représentées sous la forme d'un nombre. On retrouve deux types de fonctions :
* Fonctions de perte: Elles mesurent l'écart entre les prédictions et les valeurs réelles
* Fonctions de récompense: Elles mesurent la performance du modèle en fonction d'un objectif spécifique

Il y a aussi le principe de **Minimisation** vs **Maximisation** : 
* Minimisation : la plupart des fonctions de coût sont minimisées
* Maximisation : certaines fonctions de coût, comme la fonction de vraisemlance, sont maximisées

### L. La descente de gradient

La descente de gradient est un algorithme d'optimisation permettant d'identifier le minimum/maximum d'une fonction. Cette méthode est souvent utilisée en machine learning et deep learning afin de minimiser la fonction de cout. Le modèle ajuste ses paramètres lors de l'entraînement d'un modèle d'apprentissage automatique ou d'apprentissage profond afin de réduire la fonction de coût au fur et à mesure afin qu'elle se rapproche de 0. La fonction de coût agit comme un indicateur de performance des paramètres.

![gradient descent](https://datacorner.fr/wp-content/uploads/2021/03/gradient_descent_1.jpg)
