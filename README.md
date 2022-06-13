# data_titanic
Charger, dans un tableau nomme titanic, les données situées : https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv 

Vérifiez les valeurs manquantes (faire le dataviz) 

Faire l’analyse exploratoire des données avec dataviz 

Quelle est la proportion de survivants ? 

Quelle est l'âge moyen des passagers ? 

Combien a coûté la place la plus chère (variable: Fare)? 

Afficher les effectifs de la variable Embarked de titanic 

Afficher les 10 premières lignes des variables Survived, Pclass et Name 

Dans une copie de titanic que nous appellerons titanic_numeric, effectuer les opérations suivantes : 

titanic_numeric <- titanic 

titanic_numeric 

 

install.packages("tidyverse") 

install.packages("dplyr") 

library(dplyr) 

 

titanic_numeric 

names(titanic_numeric)[names(titanic_numeric) == "Embarked"] <- "EmbNum" 

titanic_numeric 

 

Remplacer les modalités ['S','C','Q'] de EmbNum par le triplet [0,1,2] 

Transformer cette variable (EmbNum) en variable numérique 

Faire apparaître la moyenne obtenue pour cette variable(EmbNum) 

 

Créer un tableau female_C contenant les informations des femmes (Sex = 'female') ayant embarqué à Cherbourg ( Embarked = 'C') 

Créer male_C qui contient les informations des hommes ayant eux aussi embarqués à Cherbourg 

Comparer la proportion de survivants chez les femmes et les hommes qui ont embarqué à Cherbourg (faire des graphiques) 

Créer le Data Frame Cherbourg obtenu en concaténant par lignes les deux tableaux female_c et male_c 

Afficher titanic trie de façon décroissante en fonction de l'âge des passagers 

De quel endroit a embarqué le passager le plus âgé ? 

Les survivants ont-ils paye leur billet plus cher ? 

Afficher pour chaque classe ('Pclass') la proportion 
