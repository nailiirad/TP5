# Système de Gestion d'Ustensiles
Ce projet Java présente un système de gestion d'ustensiles de cuisine, comprenant des classes telles que `Assiette`, `AssietteCarree`, `AssietteRonde`, `cuillere`, et `Ustensile`.

* Les principales classes comprennent :

1. `Ustensile`: Une classe de base avec un attribut d'année de fabrication et des méthodes pour obtenir et définir cette année, ainsi que pour calculer la valeur de l'ustensile en fonction de son âge.
2. `Assiette`: Étend la classe `Ustensile` et sert de classe de base pour les assiettes.
3. `AssietteCarree` et `AssietteRonde`: Étendent la classe `Assiette` et ajoutent des attributs spécifiques à chaque type d'assiette tels que la longueur du côté pour les assiettes carrées et le rayon pour les assiettes rondes.
4. `cuillere`: Étend la classe `Ustensile` et ajoute un attribut spécifique à la cuillère, la longueur.

* La classe `Main` contient la méthode principale pour démontrer la fonctionnalité des classes en créant des instances d'assiettes carrées, rondes et de cuillères, et en affichant leurs caractéristiques.

Le projet illustre les principes de la programmation orientée objet tels que l'héritage, l'encapsulation et la polymorphie. Les utilisateurs peuvent interagir avec le système en créant des instances d'ustensiles et en affichant leurs caractéristiques. Le code des exemples de gestion des dates à l'aide de la classe LocalDate.