# Project Deep-Leaning
# Aperçu du projet
La pomme de terre est une culture importante qui est sensible à diverses maladies. La détection précoce et la classification de ces maladies sont cruciales pour prévenir les pertes de rendement. Ce projet vise à développer un système de classification qui peut identifier avec précision différentes maladies affectant les plants de pomme de terre à l'aide de techniques d'apprentissage en profondeur.

Je développe un modèle basé sur #CNN pour la classification des maladies de la pomme de terre en utilisant les classes CNN 3 dans cette étude. Pour extraire les fonctionnalités pertinentes, l'architecture du modèle se compose de 16 couches, dont #Conv2D et #MaxPooling2D. Pour optimiser la formation, nous utilisons des techniques telles que la mise en cache et la prélecture. La fonction d'activation #softmax dans la couche dense permet des prédictions probabilistes. La formation se déroule sur 35 époques, favorisant la convergence et l'amélioration des performances. Les techniques d'augmentation des données telles que la remise à l'échelle, le retournement aléatoire et la rotation traitent des données limitées et améliorent la généralisation. Cette recherche contribue à la surveillance automatisée des cultures et à la prévention des maladies, fournissant des informations précieuses sur le diagnostic des maladies des plantes.

# Base de données
L'ensemble de données utilisé pour ce projet se compose d'images de plants de pommes de terre sains ainsi que de plantes affectées par trois maladies courantes : 'Potato___Early_blight', 'Potato___Late_blight' et 'Potato___healthy. L'ensemble de données est divisé en ensembles d'entraînement, de validation et de test.
## Téléchargements

Vous pouvez télécharger le fichier de jeu de données à partir du lien ci-dessous :

[here.](https://www.kaggle.com/datasets/arjuntejaswi/plant-village)
