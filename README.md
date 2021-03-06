# Projet 7 : Détectez des faux billets
-------------------

Projet réalisé dans le cadre de mes études de _data analyst_.

Mise en situation
-------------------

Dans ce projet, nous avons faisons partie d'une société bancaire présente a travers plusieurs pays dans le monde. Elle souhaite maintenant cibler de nouveaux client potentiel et plus particulièrement de jeune client pour qu'ils ouvrent leur premier compte.

Nous devons donc créer un modèle permettant se déterminer le revenu potentiel d'une personne.

Processus
------------

Notre mission ici et de construire un modèle qui pourra prédire les revenus potentiels d'une personne en fonction des conditions de son pays, mais également en fonction du revenue des parents de notre individu.

J'ai commencé par regarder les données pour les avoirs un peut mieux en mains, j'ai ensuite, vérifier si cette population de pays est diversifié.

Une fois ces deux points accomplis, j'ai comparé quelques pays pour montrer lequel pourraient être intéressant pour notre société bancaire.

Finalement, j'ai simulé la classe de revenu des parents de mes individus actuel en me basant sur le coefficient d'élasticité, mensurant la mobilité intergénérationnelle du revenu ([plus d'information](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-analyst/2011-measuring-intergenerational-income-mobility-art.pdf)), pour enfin prédire les revenus potentiels des enfants des clients actuels de notre société.
 
Données utilisées et sources
-------------------

Dans ce projet, j'ai utilisé un fichier fournie pour le projet, ainsi que des données issus de la [Banque Mondiale](https://data.worldbank.org/):

* `data-projet7.csv` -- Information sur les salaires des populations par pays (données fournis pour le projet)
* `population.csv` -- Population des pays du monde par années
* `GiniEvolution.csv` -- Évolution de l'indice de Gini par années
* `info_pays.csv` -- Région et groupe économique de chaque pays


Projet réalisé en python en utilisant Jupyter, ainsi que les librairies suivantes :

* `matplotlib`
* `pandas`
* `seaborn`
* `scipy`
* `numpy`
* `statsmodels`

Plus quelques fonctions personnel dans le fichier *fonction.py*

