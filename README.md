# Contexte
1. Site de vente en ligne.
2.	Chaque article a 2 attributs :
* Date de « péremption »
* Valeur (en points)
3. A la fin de chaque jour la valeur des articles est revue suivant les règles suivantes :
*	Les articles « normaux » voient leur valeur diminuer de 1 par jour
*	La valeur diminue deux fois plus vite une fois la date de péremption dépassée.
*	La valeur d’un article ne peut jamais être négative
*	Les articles dits de «collection » voient leur valeur augmenter de 1 jusqu’à la date de péremption
*	La valeur des articles ne peut dépasser 50
*	Les articles dits « unique » n’ont pas de date de péremption et leur valeur augmente de 1
*	Les articles dits « événement » augmente en valeur à l’approche de la date de péremption et tombe à 0 après cette date :
    -	+1 avant 10 jours
    -	+2 entre 10 et 5 jours
    -	+3 entre 5 et 0 jours

# But
1. Coder la méthode qui permet de calculer la valeur d’un panier composé de plusieurs articles.
2. Coder la méthode qui permet de mettre à jour la valeur des articles.
