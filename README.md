# car_rental_with_djnago
# CAR RENTAL ADMIN PANEL


==> Il s'agit d'un projet scolaire pour une base de données + un panneau d'administration pouvant être utilisé pour des projets de location de voitures.
==>Notre projet se concentre principalement sur la mise en œuvre de la base de 
données, le site web que l'utilisateur qui louerait une voiture voit est hors de portée 
de ce projet. ainsi, la "vue" dans notre exemple est la page du panneau 
d'administration avec laquelle l'administrateur interagirait. Le "modèle" et le 
"contrôleur" sont respectivement la base de données contenant les informations et le 
code logique qui donne à l'administrateur la possibilité d'ajouter, de modifier et 
d'insérer les données dans la base de données
La première interface que voit l'administrateur est la page de connexion afin 
qu'il puisse se connecter en utilisant son nom d'utilisateur et son mot de passe. Cette
page fournit également des liens vers le code source du projet et la page de l'équipe 
du projet.
Une fois connecté, une "session" est créée et l'administrateur peut voir sa 
page. Cette page contient 3 parties
La base de données et les vues sont toutes deux configurées. Ce qu'il faut 
maintenant, c'est un moyen de les lier afin que l'administrateur puisse manipuler les 
données de la base de données en utilisant la page que nous avons créée 
précédemment. Pour cela, nous avons choisi Python comme un langage moderne 
puissant pour le back-end utilisant le micro Framework FLASK.
Les tests unitaires font référence au test de certaines fonctions et zones du 
code. Il permet de vérifier que toutes les fonctions fonctionnent comme prévu. 
Finalement, il aide à identifier les échecs dans les algorithmes ainsi que la logique 
pour aider à améliorer la qualité du code qui compose une certaine fonction.


vous pouvez vous connecter avec l'un des comptes suivants:

  1- username: ayoubelmaghraoui  password: 123456
  
  2- username: simo  password: 1234
  
  3- username: lekraichi  password: 01234
  
 

==> si vous souhaitez tester le projet chez votre hôte local(localhost) , procédez comme suit:

  1- téléchargez python 3.8 sur votre machine.
  
  2- télécharger le code sur votre machine.
  
  3- créer une base de données dans votre localhost avec le code du fichier database.sql (vous pouvez utiliser phpMyAdmin).
  
  4- accédez au dossier du projet dans votre terminal(commande cd) puis tapez: python app.py et appuyez sur Entrée.
  
  5- vous pouvez maintenant accéder au site Web dans votre navigateur à l'adresse : http://localhost:5000/
  
  6- si vous rencontrez toujours des problèmes, veuillez accéder au dossier "env" depuis le terminal(commande cd) puis tapez: pip install flask-mysql et appuyez sur Entrée. puis refaites l'étape 5.
