<h1>Projet n°2 :  Analysez les tests de l’application Magic GitHub</h1>

Magic Github est une application permettant d'afficher une liste d'utilisateurs avec lequel il est possible d'interagir. Elle n'est cependant pas compilable et ne valide ni les tests unitaires ni les tests d'instrumentations.
J'ai donc terminé le développement de l'application afin qu'elle soit compilable et qu'elle passe les tests unitaires ainsi que les tests d'intégrations.
Ce repo contient l'application qui valide les tests, avec les fonctionnalités supplémentaires qui ont été ajoutées. 

<h2>Dans le cadre de l’application :</h2>


<b>Les test unitaires </b> vérifiaient le bon comportement des méthodes liés à la manipulation de la liste d'utilisateurs (création, génération aléatoire, suppression).

<b>Les tests d'instrumentation</b> vérifiaient que la RecyclerView correspondait bien à la liste d'utilisateurs (nombre d'items de la RecyclerView égal au nombre d'utilisateurs dans la liste), et s'adaptait à celle-ci. 
