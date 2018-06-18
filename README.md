# Formation java Cap _ Semaine 1
## Partie 1: Gestion de projet
### Installation
[Eclipse](http://mirror.ufs.ac.za/eclipse/technology/epp/downloads/release/oxygen/3a/eclipse-jee-oxygen-3a-win32-x86_64.zip )
[java8 JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
[Maven] (https://maven.apache.org/download.cgi)
1. Ajouter pathofmavenfile/bin dans variable d'envirement 
2. Tester dans CMD

```
mvn -version
```

Commande pour commencer le projet et recuperer les dependances :
```
clean install => clean/ build /test unitaire 
```
### Outils de gestion projet :
1. SVN; Gestion des branches  /MVN; framework pour gestion de projet 
2. git 

 Trunk  : suivis version (cest comme devop, ma branche mere; la version quelle contient est la version de depart cad ce qui est ce qui est mis en prod( version prise des Tags et puis renommer )

 0.0.1_sapshot( Pemiere version; creation)=> Release (pour la livraison, Ex: 0.0.1 ) / Tag 0.0.1 (la version stable de celle qui etait en cours)
 ### Integration continue 
 Assurer que les modifs ne prodisent pas de regression sur l'appli/ Tester les modules
 ### Qualité du code: Utilisation de Sonar
Il faut pas avoir des violation critique sinon refonte du projet.
 ### Automatiser le deploiment 
 [jenkins plugin] (https://plugins.jenkins.io/deploy)
 ### Must read
 1.  [Jenkins](https://www.quora.com/What-is-Jenkins-When-and-why-is-it-used) // Similar of Rollbar
 2.  [web service appelé MAS](https://www.quora.com/What-are-web-services)
 3. [Artifact and archetype](https://www.quora.com/What-is-a-Maven-archetype-and-artifact-in-layman-terms)

### To do: Tutorials 
1. [Maven](https://github.com/in28minutes/MavenIn28Minutes), [MavenDoc](https://www.tutorialspoint.com/maven/index.htm)
2. SVN
3. [Jenkins](https://jenkins.io/doc/pipeline/tour/getting-started/)

#### Note/ Best practice:
* Il faut ecrire les commit; aider a savoir les incident
* Un checkout c'est comme un clone sur SVN
* Java doc(== doc string)  et Commentaires; consituent 45% du total du code
* jar files: The .jar files contain libraries, resources and accessories files like property files.
* war files: The war file contains the web application that can be deployed on any servlet/jsp container. The .war file contains jsp, html, javascript and other files necessary for the development of web applications

* /Info a verifier / web services doivent avoir meme architecture dou l'intert de architype

## Partie 2: Java syntaxe
