# reactjs-interview

Objectif:
Créez une application React/TypeScript qui permet aux utilisateurs de visualiser, ajouter et supprimer des missions spatiales. Vous devez démontrer votre compétence dans l'utilisation des hooks React, TypeScript et l'organisation de projet.

Description:

L'application doit avoir les fonctionnalités suivantes :

Liste des Missions Spatiales :

Affichez une liste des missions spatiales.
Chaque mission doit avoir un nom, une date de lancement, un équipage (liste de noms) et une description.
À côté de chaque mission, il devrait y avoir un bouton ou une icône pour supprimer la mission.

- Ajout de Missions :

Un bouton "Ajouter une mission" qui, lorsqu'il est cliqué, ouvre un pop-in/formulaire pour ajouter une nouvelle mission.
Le formulaire devrait contenir des champs pour le nom, la date de lancement, l'équipage (au moins un membre, avec la possibilité d'ajouter plus) et une description.

- Pop-in :

Lorsque l'utilisateur clique sur le bouton "Ajouter une mission", un pop-in doit apparaître à l'écran (sans l'utilisation de librairies extérieures).
Le pop-in doit avoir une option pour être fermé, soit par un bouton de fermeture, soit en cliquant en dehors du pop-in.

- Exigences Techniques :

  - Vous devez utiliser React et TypeScript pour cet exercice.
  - Vous n'êtes pas autorisé à utiliser des librairies extérieures pour la gestion des états ou les composants UI (comme Material-UI, Ant Design, Redux, MobX, etc.).
  - Utilisez les hooks React autant que possible.
  - Assurez-vous de bien organiser votre projet et séparez les composants de manière logique.
  - Pensez à la réutilisabilité des composants.

- Bonus :

Implémentez une fonctionnalité de recherche pour filtrer les missions par nom.
Ajoutez des animations pour l'apparition et la disparition du pop-in.


# Conseils :

Considérez l'utilisation du hook useState pour gérer l'état local de l'application.
Le hook useEffect peut être utilisé pour simuler le chargement des données (comme si elles étaient chargées depuis une API).
Pour le typage avec TypeScript, définissez des interfaces pour les objets, comme la mission spatiale.

- Rendu :

Veuillez fournir le code source complet de l'application.
Un README avec des instructions sur la manière d'exécuter l'application.
