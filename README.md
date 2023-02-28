# Machine Learning Portfolio
	
Voici mon Portfolio contenant des projets de Machine Learning/Data Science que j'ai réalisé. Ils ont été réalisé dans le cadre d'une formation "Ingénieur Machine Learning" d'Openclassrooms que je viens de finaliser. Ce parcours d'Openclassrooms en partenariat avec CentraleSupélec est constitué de ces huits projets ci-dessus. La finalité est l'obtention un titre "Data scientist" de type RNCP:

Projet 1 : Définissez votre stratégie d'apprentissage

Projet 2 : Concevez une application au service de la santé publique

Projet 3 : Anticipez les besoins en consommation électrique de bâtiments

Projet 4 : Segmentez des clients d'un site e-commerce

Projet 5 : Catégorisez automatiquement des questions

Projet 6 : Classez des images à l'aide d'algorithmes de Deep Learning

Projet 7 : Développez une preuve de concept (Segmentation d'images sous-marines)

Projet 8 : Participez à une compétition Kaggle
	
	
## [Projet: Concevez une application au service de la santé publique](https://github.com/Bounkass/P2_OC_Parcours_IML)
L'agence "Santé publique France" a lancé un appel à projet autour des problématiques alimentaires. Vous proposerez une application basée sur des données nutritionnelles.


### Compétences développées:

- Effectuer des opérations de nettoyage sur des données structurées

- Effectuer une analyse statistique univariée et multivariée

L'application proposée **nutri-vegan** permet d'abord de savoir si un aliment convient pour un régime végétarien ou végitalien, en fonction des ingrédients d'orogine animale contenants dans le produit. Cette étape est réalisée uns fois scanner le code-barres du produit. En suite l'application propose le score nutritinelle du produits vegan, détaille ses ingrédients et estime sa composition nutritionnelles, notamment les micro-nutriments. L'application ainsi peut recommander d'autre produits de la même famille qui contient plus de teneur en macro et micro-nutriments notamment le fer le calcium et de la vitamine c.

<p float="left">
  <img src="https://github.com/Bounkass/ML-DS_Portfolio/blob/main/Images/appli2.png" width="40%" height="45%"/>
  <img src="https://github.com/Bounkass/ML-DS_Portfolio/blob/main/Images/Mcorr.png" width="54%" height="65%"/>	
</p>

## [Projet: Anticipez les besoins en consommation électrique de bâtiments](https://github.com/Bounkass/P3_OC_Parcours_IML)

La ville de Seatlle veut atteindre son objectif ambitieux d'une ville neutre en émissions de carbone en 2050. Elle s’intéresse aux émissions des bâtiments non destinés à l’habitation. Des relevés minutieux ont été effectués par des agents experts en 2015 et 2016. Cependant, ces relevés sont coûteux à obtenir pour chaque année, ainsi en se basant sur ceux déjà réalisés, la ville souhaite dans un premier temps:

- Prédire les émissions de Co2 et la consommation totale de l'énergie des bâtiments pour lesquels elles n’ont pas encore été mesurées.
- Evaluer l'influence de feature Star Energy Score sur les prédictions.

Source des données : https://www.kaggle.com/city-of-seattle/sea-building-energy-benchmarking#2015-building-energy-benchmarking.csv

### réalisations du projet:
- Préparation des données 
- Entraînement de différents algorithmes de machine learning (Regresion linéaire, SVR, XGBoost, Random Forest Regressor)
- Optimisation des hyperparamètres
- Recherche d'importance des features
- Mise en oeuvre du modèle optimal pour la  prédiction de consommation et émissions de C02
- Evaluation de  l'influence de feature Star Energy Score sur les prédictions

<p align="center">
  <img src="https://github.com/Bounkass/ML-DS_Portfolio/blob/main/Images/city_seattle.png" width="55%" height="40%">
</p>
<p align="center">
  <img src="https://github.com/Bounkass/ML-DS_Portfolio/blob/main/Images/GBR_RFR.png">
</p>

## [Projet: Segmentez des clients d'un site e-commerce](https://github.com/Bounkass/Segmentez-des-clients-d-un-site-e-commerce)
Segmentation des clients pour le site e-commerce Brazilien OLIST. Source des données : https://www.kaggle.com/olistbr/brazilian-ecommerce

### Les objectifs:

- Comprendre les différents types d’utilisateurs grâce à leur comportement et leurs données personnelles.

- Essais de clustering par différents algorithmes (KMeans, Clustering Hiérarchique, DBScan)

- Fournir à l’équipe marketing une description actionable de votre segmentation et de sa logique sous-jacente pour une utilisation optimale.

- Proposition de contrat de maintenance basée sur une analyse de la stabilité des segments au cours du temps.

<p float="left">
  <img src="https://github.com/Bounkass/ML-DS_Portfolio/blob/main/Images/RFMolist.png" width="45%" height="45%"/>
  <img src="https://github.com/Bounkass/ML-DS_Portfolio/blob/main/Images/clusterkm.png" width="45%" height="45%"/>	
</p>
<p align="center">
  <img src="https://github.com/Bounkass/ML-DS_Portfolio/blob/main/Images/radial_cl.png"  width="55%" height="65%"/>
</p>


## [Projet: Categoriser-automatiquement-des-questions](https://github.com/Bounkass/Categoriser-automatiquement-des-questions)

L'objectif de ce projet est de développer un système automatique de suggestion de tags pour le 
site Stack Overflow. En assignant automatiquement plusieurs tags pertinents à une question proposer par des utilisateurs moins expérimentés.

La mission de ce projet:

- Réaliser le pétraitement des questions (documents) issues des données de l'API stackexchange-explorer

- Comparer des approches suppervisées (LR, KNN, SVM, RF, Gboust) et non supervisées (LDA, NMA) avec plusieurs tests de méthodes d'extraction de features. Notamment, une approche de type bag-of-words, et 3 approches de Word/Sentence Embedding Word2Vec, BERT et USE.

- Développer une API et la mettre en production.

<p float="left">
  <img src="https://github.com/Bounkass/ML-DS_Portfolio/blob/main/Images/comp0.png" width="54%" height="65%"/>
  <img src="https://github.com/Bounkass/ML-DS_Portfolio/blob/main/Images/ap0.png" width="45%" height="65%"/>	
</p>


## [Projet: Classez des images à l'aide de Deep-Learning]() https://github.com/Bounkass/Classez-des-images-l-aide-de-Deep-Learning

L'objectif de ce projet est la comparaison d'un modèle CNN from "Scratch" et des modèles CNN pré-entrainés utilisant du "transfer learning". On utilise les données de  "Stanford Dogs Dataset", http://vision.stanford.edu/aditya86/ImageNetDogs/. Ce dataset est constitué de 20 580 images de chiens triées en 120 races.

### Les démarches de l'entraînement sont:

- Modèle initial "from scratch" avec du préprocessing: égalisation et le débruitage, on introduit aussi de la data augmentation, l'ajout du dropout et de batchnormalization.

-Transfer learning modèle préentrainés sur ImageNet. Notemment, les modèles VGG19, ResNet50, EffecientNetB3 et Xception. Dans ce cadre on supprime la couche dense et on congèle une partie ou la totalité des autres couches

-Le meileur modèle est intégré dans une Api développée à l'aide du framework "Gradio".

<p float="left">
  <img src="https://github.com/Bounkass/ML-DS_Portfolio/blob/main/Images/matC.png" width="80%" height="75%"/>
  <img src="https://github.com/Bounkass/ML-DS_Portfolio/blob/main/Images/dog_pred.png" width="80%" height="65%"/>	
</p>


## [Projet: Développez une preuve de concept](https://github.com/Bounkass/D-veloppez-une-preuve-de-concept)

L’objectif de ce rapport est d'élaborer une preuve de concept (poc) en réalisant une veille thématique via la recherche de sources pertinentes. Nous cherchons à résoudre un problème concret en testant de nouvelles approches conduisant à de meilleures solutions en termes de temps de calcul et de précision.
Nous nous plaçons ici dans le cadre d’un autre sujet de la vision par ordinateur. Il s'agit de la segmentation sémantique d'images, un sujet clé avec beaucoup d'application: la compréhension des scènes, l'imagerie médicale, la perception de la robotique, la vidéosurveillance...

Plusieurs modèles inspirés de la classification CNN ont été développés pour performer la tache de la segmentation sémantique. Notamment le modèle "SegFormer", un framework de transformer de pointe qui considère conjointement l'efficacité, la précision et la robustesse (Xie et al).

L’objectif est de comparer, de vérifier l'efficacité de ce modèle sur des images sous-marines. Ce type d'images représentent un défi pour la tâche de la segmentation. En effet, leur contenu visuel est entièrement différent en raison des catégories d'objets spécifiques au domaine, des motifs d'arrière-plan. Des proplèmes liés à la mauvaise apparence visuelle, de la turbidité et des artefacts de distorsion et de la diffusion de la lumière. 

<p align="center">
  <img src="https://github.com/Bounkass/ML-DS_Portfolio/blob/main/Images/test_unet.png" width="85%" height="70%">
</p>


## [Projet: Participez-a-une-competition-Kaggle](https://github.com/Bounkass/Participez-a-une-competition-Kaggle)

Ce projet consiste à participer à une compétition organisée par  Kaggle, une plateforme qui organise des compétitions en data science avec une récompensation des meilleurs data scientistes internationaux.

### Context du sujet de la compétition choisi: 

- L'expression écrite est fondamentale dans l’apprentissage d’une seconde langue

- La population d’apprenant de l’anglais est en croissance rapide, l’évaluation des  compétences linguistiques est une tâche fatigante pour les enseignants. 

- Les outils de l’ évaluation existants sont moins efficaces et parfois biaisée au détriment de l'apprenant.

### Mission:

- Développer un modèle de ML afin d’évaluer avec précision les compétences linguistiques des apprenants de la langue anglaise.

### Les données: 

- Des essais de rédaction d'expressions écrites (en anglais) notés selon six mesures analytiques: cohésion, syntaxe, vocabulaire, phraséologie, grammaire et conventions.

<p float="left">
  <img src="https://github.com/Bounkass/ML-DS_Portfolio/blob/main/Images/Cnlp.png" width="49%" height="49%"/>
  <img src="https://github.com/Bounkass/ML-DS_Portfolio/blob/main/Images/pdf.png" width="49%" height="49%"/>
  <img src="https://github.com/Bounkass/ML-DS_Portfolio/blob/main/Images/acc.png" width="48%" height="85%"/>	
</p>
