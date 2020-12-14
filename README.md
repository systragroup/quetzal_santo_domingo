Quetzal Santo Domingo
=======
powered by quetzal

Architecture 
============

inputs
------
gtfs-Santo_Domingo-base.zip vient de itsim
road vient openstreetmaps il est créé automatiquement et c'est là qu'il faudrait rajouter des routes

latest
------
contient le dernier export JSON du modèle -> pour regarder les données avec un SIG (geoJSON)

model
-----
ce sont les sauvegardes .zip et les fichiers de travail du modèle
on y trouve les différents scénarios aux différentes étapes
et toutes les étapes de la préparation

notebooks
---------
ce sont tous les scripts du modèle
en cliquant sur jupyter_here, on lance l'environnement de développement. 

notebooks
=========

preparation
-----------

transport
---------
pas la peine de faire la distribution, c'est la même dans tous les scénarios (on pourrait faire mieux)
puis on calcule les nds vp
puis nds pt
puis partage modal 
puis les stacks par scénario
puis les cartes par scénario
puis on concatène les stacks 

analysis
--------
contient le bse de saint domingue







