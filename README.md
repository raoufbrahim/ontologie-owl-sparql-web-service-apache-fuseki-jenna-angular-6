# ontologie-owl-sparql-web-service-apache-fuseki-jenna-angular-6


  
Table des matières 
1.	Introduction	1
2.	Web sémantique	1
3.	OWL	1
4.	Ontologie	1
5.	SPARQL	2
6.	Réalisation d’ontologie	2
6.1.	Hiérarchie des classes	2
6.2.	Ontologie	3
7.	Service web	4
7.1.	Le service web	4
7.2.	Implémentation d’ontologie dans un service web	4
8.	Réalisation des interfaces	6
9.	Conclusion	9




 
1.	Introduction
Le Web classique peut être vu comme un ensemble de ressources (textes, images, services) conçues et interconnectées, suivant une syntaxe bien définie, pour être traitées et comprises par des utilisateurs humains. Mais, avec le volume croissant de la quantité d'information existante sur le Web, les outils présumés accompagner l'utilisateur à y accéder, ont montré leurs limites.
2.	Web sémantique
Le Web Sémantique a pour but d'ajouter des informations caractéristiques aux informations existantes pour aider à l'automatisation des services, de découvrir, de relier et d’inférer des connaissances qui sont vraisemblables. 
Son architecture s’appuie sur une pyramide de langages pour représenter des connaissances sur le web en satisfaisant les critères de standardisation, d’interopérabilité et de flexibilité.
3.	OWL
Le langage d'ontologie Web OWL est conçu pour décrire des classes et leurs relations, lesquelles sont inhérentes aux documents et applications Web.
4.	Ontologie
Une ontologie a pour rôle principal la représentation d'un domaine, elle est utilisée dans divers domaine.
Les critères d’évaluation d’une ontologie :
•	Les classes doivent être bien définies et la présence des classes disjointes.
•	Les propriétés doivent être organisées en une hiérarchie.
•	Les instances.
5.	SPARQL
Le SPARQL permet l’interrogation d’une ontologie. Il sert à consulter la source de données. 
Le protocole va permettre à un client Web de consulter, en exécutant une requête SPARQL, puis un service ou point d’accès SPARQL qui traitera la requête pour retourner la réponse sous différents format (HTML, XML, RDF/XML, N3, JSON). 
6.	Réalisationd’ontologie
L’ontologie que nous avons construite se porte sur le thème du football.
6.1.	Hiérarchie des classes
Notre ontologie se compose d’un ensemble de classes etde sous classes :
•	Classe Awards.
•	Classe compétition.
•	Classe competitors.
•	Classe Defender.
•	Classe Division.
•	Classe Goalkeeper.
•	Classe Goals.
•	Classe Match.
•	Classe Match-official.
Cette figure représente la hiérarchie des classes.
 

6.2.	Ontologie
L’objectif principal d’une ontologie est de modéliser un ensemble de connaissances dans un domaine donné.
La réalisation d’ontologie est faite par le logiciel protégé qui est très populaire dans le domaine du web sémantique. 
Son utilisation est très simple, il suffit juste de créer les classes d’une façon hiérarchique et de définir les classes disjointes.
Puis on spécifie les propriétés et les relations.
7.	Service web
7.1.	Le service web
 Un service Web est un modulaire, bien défini composant de logiciel qui expose son interface sur un réseau. 
Il permet à des plusieurs organismes d’agir l’un sur l’autre d’une façon uniforme et bien définie, qui représente une étape importante vers l’interaction entre les systèmes répartis hétérogènes multiples.
7.2.	Implémentation d’ontologie dans un service web
Nous allons expliquerles différentes étapes de l'implémentation d'ontologie.
•	Étape 1: utilisation du logiciel Apach 

 
•	Étape 2 :  création du dataset  

 
•	Étape3: uploder le fichier match.owl  
 
•	Étape 4: lancement du serveur avec la présence du quatre URL (web service) à utiliser.
 
•	Étape 5 : création d'un service (angular) qui exploite le web service
 
8.	Réalisation des interfaces
Cette interface indique la position du stade et la position actuel d'utilisateur qui est généralement un entraineur et dessiner le schéma le plus cours pour arriver au stade.
 
en cliquant sur le maker nous aménons à une autre interface qui représente la formation du football  et affichons les listes de joueurs.
 
 
 Par la suite l'entraineur va choisir les joueurs qui vont participer au match.


 
Après le choix des joueurs, un calcule de score sera effectué pour savoir la meilleure formation 
 



9.	Conclusion
Le partage de connaissances entre systèmes informatiques permettra, de plus, une interaction et une coopération entre ces derniers et l'utilisateur humain. Cela se manifeste, par exemple dans : les systèmes d'aide à la décision, les systèmes d'enseignement assisté par ordinateur, la recherche d'information sur le web.





