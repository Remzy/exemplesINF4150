Mise à niveau avec Javascript
=============================

Le Javascript est nécessaire pour programmer les interactions avec l'utilisateur
dans le fureteur. Notamment, c'est avec le Javascript qu'on met en place de la
divulgation progressive. Cet atelier est une mise à niveau afin de permettre
d'utiliser le Javascript.

Si vous n'avez jamais fait de Javascript, il est suggérer d'aller compléter un
tutoriel avant de faire l'atelier afin de voir les bases du langage.

Objectifs
---------

* Introduire le Javascript.
* Interagir avec l'utilisateur d'un site web.

Exercices
---------

1. Créez une page web avec un formulaire d'authentification :
   * un champ pour le nom d'utilisateur;
   * un champ pour le mot de passe;
   * un bouton pour compléter l'authentification.

2. Ajoutez le Javascript nécessaire afin de faire des validations lorsqu'un
   utilisateur appuie sur le bouton. Toute erreur doit afficher une alerte avec
   la fonction `alert` contenant un message significatif. En cas d'erreur, le
   formulaire ne doit pas être soumis. Voici les validations à programmer :
   * le nom d'utilisateur ne doit pas être vide;
   * le mot de passe ne doit pas être vide;
   * le mot de passe doit contenir au moins 6 caractères, incluant une
     minuscule, une majuscule et un chiffre.

3. Remplacez le `alert` par un message d'erreur intégré à la page, c'est-à-dire
   un `span` ou un `div` qui apparaît à côté du champ en erreur et contenant le
   message significatif de l'erreur. Le message doit s'afficher en rouge.

4. Si un utilisateur entre le nom d'utilisateur `admin`, affichez un champ
   supplémentaire (divulgation progressive) demandant à l'utilisateur le serveur
   sur lequel il désire se connecter (placez une liste déroulante avec 3 choix).
   Si l'utilisateur change son nom d'utilisateur et qu'il n'est plus `admin`, le
   champ doit disparaître.
