# ecommerce_nb

Olist est une entreprise brésilienne qui propose une solution de vente sur les marketplaces en ligne.

Elle souhaite qu'on fournisse à ses équipes d'e-commerce une segmentation des clients qu’elles pourront utiliser au quotidien pour leurs campagnes de communication.

L'objectif est de comprendre les différents types d’utilisateurs grâce à leur comportement et à leurs données personnelles.

On doit fournir à l’équipe Marketing une description actionable de notre segmentation et de sa logique sous-jacente pour une utilisation optimale, ainsi qu’une proposition de contrat de maintenance basée sur une analyse de la stabilité des segments au cours du temps.

Notre mission est d’aider les équipes d’Olist à comprendre les différents types d'utilisateurs. Des méthodes non supervisées vont être utilisées pour regrouper des clients de profils similaires. Ces catégories pourront être utilisées par l’équipe Marketing pour mieux communiquer.

Le projet se découpe en 3 notebooks :
* un notebook de nettoyage et de préparation de données avec une analyse exploratoire de celles-ci,
* un notebook d'essai où sont testés et évalués 3 modèles de clustering non supervisés : AgglomerativeClustering (hiérarchique), k-means et DBSCAN,
* un notebook de simulation où on cherche à établir une fréquence de maintenance du meilleur modèle trouvé sur le notebook précédent.
