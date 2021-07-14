# Conception d'une application au service de la santé publique

Ce projet a été réalisé dans le cadre de la formation "Ingénieur Machine Learning" avec OpenClassrooms et Centrale Supelec.
Les compétences évaluées étaient : 
- Communiquer ses résultats à l’aide de représentations graphiques lisibles et pertinentes
- Effectuer des opérations de nettoyage sur des données structurées
- Effectuer une analyse statistique multivariée
- Effectuer une analyse statistique univariée
Ce projet a été soutenu et validé le 9 juillet 2021. 

## Présentation de l'application

Il existe des scores permettant d'évaluer les aliments en fonction de leurs données nutritionnelles (Nutriscore) ou de leurs impacts sur l'environnement (Ecoscore).
Cependant ces scores ne sont pas obligatoires et ne se retrouvent pas dans tous les pays. Par exemple, les pays d'Amérique du Sud vont se baser sur le groupe NOVA.
L'idée de l'application est de créer une classification qui prennent en compte les données nutritionnelles (Protéines, Glucides, Lipides), les données énergétiques et leurs compositions (huile de palme et additifs).
De plus, cette classification pourrait par la suite s'adapter à d'autres produits vendus dans d'autres pays.

L'idée de Nutr'avel est donc d'être une application qui se base sur un algorithme de segmentation pour classer des produits issus d'une base de données open source.
A l'issue de cette classification, on pourrait ensuite prédire le score Nutr'avel d'un produit vendu à l'étranger. 