### Détetcion d'objets

### Auteurs: Adjoua HOUNDONOUGBO and Morel MBEDI

### Ce projet  a été réalisé dans le cadre du cours "Method Advanced in ML" de notre formation "Master 2  Machine learning pour l'Intelligence Artificielle" à l'université Lumière Lyon 2


### L'objectif de ce projet est d'explorer les modèles  pré-entrainés de detection d'objets

### Méthodolodie :

- Recherches des méthodes pré-entrainés pour effectué la tâche de détection d'objets
- utilisation  du modèle  pré-entrainés  fasterRCNN-resnet50 avec  la librairie fiftyone sur python
- Exploration du modèle avec les données COCO qui a été utilisées pour entrainer le modèle: Nous avons sélectionné 4 classes à détecter à savoir: cat,dog,apple,et orange
- Utilisation du même modèle pour détecter des images collecter sur l'internet de meme classe que précédemment (voir my_images.zip et resultats_detect.zip)
- Tentative d'entrainner avec les 4 classes et calcul des metrics d'évaluation; mAp,préciosn, rappel, accuracy, matrice de confusion(voir mc1.jpg,mc2.jpg)


