### DETECTION D'OBJETS

### Auteurs: Adjoua HOUNDONOUGBO and Morel MBEDI

### Ce projet  a été réalisé dans le cadre du cours "Method Advanced in ML" de notre formation "Master 2  Machine learning pour l'Intelligence Artificielle" à l'université Lumière Lyon 2


### L'objectif de ce projet est d'explorer les modèles  pré-entrainés pour faire la detection d'objets dans les images

### Méthodologie :

- Recherche des modèles pré-entrainés pour effectuer la tâche de détection d'objets
- utilisation  du modèle fasterRCNN-resnet50 avec la librairie fiftyone sur python
- Exploration du modèle sur les données COCO qui ont été utilisées pour entrainer le modèle. Nous avons sélectionné 4 classes à détecter à savoir: cat,dog,apple et orange
- Utilisation du même modèle pour détecter des images collecter sur l'internet de même classes que précédemment (voir my_images.zip et resultats_detect.zip)
- Tentative d'entrainner avec les 4 classes et calcul des metrics d'évaluation; mAp,précision, rappel, accuracy, matrice de confusion(voir mc1.jpg,mc2.jpg)


