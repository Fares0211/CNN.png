# CNN.png

Dans ce projet, nous visons à développer et à comparer des modèles d'apprentissage profond sur des données d'images. Pour des raisons de temps, le nombre total d'époques est toujours fixé à 50 et la patience égale à 5. Enfin, le fichier soumis doit être un HTML, vous pouvez utiliser le document joint expliquant comment le générer.

1. Téléchargez les données X et y en utilisant la fonction load du package numpy.

2. Tracez 6 images et montrez leurs étiquettes.

3. Divisez les données en deux ensembles (train et test) (15 %).

4. Définissez un premier modèle d'apprentissage sans la cellule CNN avec 2 couches denses cachées et donnez les scores de validation et de test.

5. Écrivez une fonction permettant de tracer les étiquettes prédites. Le résultat doit indiquer la probabilité de l'étiquette prédite en vert si la prédiction est correcte, sinon en rouge.

6. Entraînez un deuxième modèle utilisant la structure CNN avec 3 couches CNN cachées avec un arrêt précoce.
7. Calculez les scores de validation et de test.

8. Entraînez et comparez deux approches d'apprentissage par transfert avec deux modèles différents de l'API Keras.

9. Placez les meilleurs scores de test des quatre modèles dans un tableau unique et imprimez-le.

10. Entraînez un autoencodeur de débruitage avec des régularisateurs L1 (avec l1=0.0001) sur les données et illustrez votre modèle en utilisant quelques images. Pour construire l'image bruitée, utilisez une distribution normale avec une moyenne égale à 0,35 et une variance égale à 0,25.
