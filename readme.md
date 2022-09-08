![This is an image](/assets/images/logo.png)

## Projet SAUTHEUHZ
Notre premier projet nodeJS en MVC. 
L'objectif du projet sautheuhz est de créer une application web permettant à une pharmacie et ses employés de gerer ses clients, ordonnances et stocks de manières aussi simple qu'intuitive.

## Quelles technologies ? 
**FrontEnd**    
-Nous avons opté pour l'utilisation de Bootstrap au niveau du css.  
-Utilisation de Chart.Js le graphique sur la page d'acceuil (prévoyant les stocks sur les 6 prochains mois).  

**BackEnd**   
Du côté serveur nous utilisons deux frameworks principaux pour  ce projet :  
-NodeJS  
-ExpressJs  

**Base de données**  
La base de données est hébergé sur AlwaysData sous PhpMyAdmin.  

Lien pour accéder aux projet hébergé: 

## Installer le projet sur votre ordinateur ? 

Après avoir installer git ainsi que node sur votre pc, clonez le projet grâce a la commande : 
```
git clone https://github.com/guclusefa/sautheuhz.git
```
- Récuperez la base de données et importer là dans votre gestionnaire de base de données.  
- Il s'agit du fichier : assets/bdd/sautheuhz_bdd.sql
- Ensuite insérer vos identifiants dans le fichier de connexion à la base de données.
- Il s'agit du fichier : config/database.js

Il vous suffit alors d'installer les middlewares  : 
```
npm install iniparser mysql express ejs express-session connect-flash
```
Pour finir, pour accèder au site web, lancer le serveur : 
``` 
node index.js
```
Et rendez vous sur l'url suivante
``` 
localhost:3000/sautheuhz
```
## Auteurs
- [IlianCode](https://github.com/IlianCode)
- [guclusefa](https://github.com/guclusefa)
