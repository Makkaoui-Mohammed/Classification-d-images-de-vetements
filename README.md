# Classification-d-images-de-vetements
Le code illustre le processus de création, d'entraînement et d'évaluation d'un modèle de classification d'images de vêtements à l'aide de TensorFlow et du jeu de données Fashion MNIST

Le code Python utilise TensorFlow pour créer, entraîner et évaluer un modèle de classification d'images de vêtements en utilisant le jeu de données Fashion MNIST. Voici une description détaillée du code :

Importation des bibliothèques :

tensorflow : pour la création et l'entraînement du modèle de machine learning.
numpy : pour effectuer des opérations mathématiques efficaces sur les tableaux.
matplotlib.pyplot : pour visualiser les images.
Chargement du jeu de données Fashion MNIST :

Le jeu de données Fashion MNIST est chargé à l'aide de la fonction fashion_mnist.load_data().
Le jeu de données est divisé en ensembles d'entraînement (train_images et train_labels) et de test (test_images et test_labels).
Les classes de vêtements sont définies dans la liste class_names.
Affichage de quelques exemples du jeu de données :

Quelques exemples d'images du jeu de données d'entraînement sont affichés pour visualiser les données.
Construction du modèle :

Un modèle séquentiel est créé avec une couche d'aplatissement (Flatten) suivie d'une couche dense de 128 neurones avec une fonction d'activation ReLU, et enfin une couche dense de 10 neurones (correspondant au nombre de classes) sans fonction d'activation.
Compilation du modèle :

Le modèle est compilé avec l'optimiseur 'adam' et la fonction de perte SparseCategoricalCrossentropy pour la classification.
Entraînement du modèle :

Le modèle est entraîné sur les données d'entraînement (train_images et train_labels) pendant 10 époques.
Évaluation du modèle :

La précision du modèle est évaluée sur les données de test (test_images et test_labels).
Prédiction et visualisation :

Des prédictions sont générées à l'aide du modèle pour les images de test.
La fonction plot_image est définie pour afficher une image avec sa prédiction et la fonction plot_value_array pour afficher les valeurs de prédiction sous forme de barres.
Des exemples d'images de test avec leurs prédictions sont affichés.
Prédiction sur une seule image :

Une seule image de test est sélectionnée pour effectuer une prédiction individuelle.
La fonction plot_value_array est utilisée pour afficher les valeurs de prédiction sous forme de barres.
Résultats finaux :

La classe prédite pour l'image sélectionnée est affichée.

![image](https://github.com/Makkaoui-Mohammed/Classification-d-images-de-vetements/assets/108239380/b785a484-623b-4e34-a1b0-6d7b6cbea24a)

![image](https://github.com/Makkaoui-Mohammed/Classification-d-images-de-vetements/assets/108239380/3805822d-0216-4015-b756-6c94a9ca8f6e)

