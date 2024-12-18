## Description du projet ##  
Ce projet représente le backend d'une application e-commerce distribuée. Il est structuré autour de plusieurs microservices dédiés à la gestion des clients, des produits, 
de la facturation, ainsi qu'à une passerelle API. Ce backend repose sur une architecture orientée microservices, offrant des APIs RESTful pour garantir une meilleure scalabilité, modularité et facilité de maintenance.
## Structure du Projet ##
Le projet est organisé autour de plusieurs microservices :
 - Customer Service : Microservice dédié à la gestion des clients, incluant des endpoints pour les opérations CRUD.
 - Inventory Service : Microservice chargé de la gestion des stocks et des produits.
 - Gateway : Passerelle API centralisant et orchestrant les appels vers les différents services.
 - Discovery Service : Service de découverte basé sur Eureka, permettant la localisation des microservices.
 - Billing Service : Microservice responsable de la gestion des factures et des articles associés.
 - Config Service : Serveur de configuration centralisé pour une gestion uniforme des paramètres.
## Technologies utilisées ##
 - Langage : Java
 - Framework : Spring Boot
 - Base de données : H2
 - Communication : REST API
 - Découverte de services : Spring Cloud Eureka
 - Passerelle API : Spring Cloud Gateway
 - Configuration centralisée : Spring Cloud Config Server
 - Outil de build : Maven
## Installation et Configuration ##
 - Cloner le dépôt : git clone https://github.com/Loubnaettaleb/ecom-ms.git) cd microservice-app-ecom
 - Lancer les microservices
 - Configurer le Discovery Service
Ce projet constitue le backend d’une application e-commerce distribuée, conçu selon une architecture basée sur les microservices.
Il intègre plusieurs services spécialisés, notamment pour la gestion des clients, des produits et de la facturation,
tout en s’appuyant sur une passerelle API pour centraliser les communications. En exposant des APIs RESTful,
ce backend offre une solution hautement évolutive et facile à maintenir, adaptée aux besoins d’une application moderne et scalable.
## Execution ##
Ordre de démarrage :
  - Démarrer le Config Service.
  - Lancer le Discovery Service.
  - Initialiser les autres microservices.
  - Démarrer la passerelle API (Gateway) en dernier.
![image](https://github.com/user-attachments/assets/8263157b-1f65-4ad1-8c2c-3b94443ebe77)
![image](https://github.com/user-attachments/assets/10537bdb-0476-4385-b439-6509b1b9d777)
![image](https://github.com/user-attachments/assets/db3e690b-f85c-45d5-94b1-95022219a2c8)
![image](https://github.com/user-attachments/assets/25e58464-428d-4b2d-b830-a006c10266d3)
![image](https://github.com/user-attachments/assets/1f66102f-6cef-4bd0-99c0-588de924a84a)





