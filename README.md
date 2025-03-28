# Application Spring Boot Hello World

Ce projet est une application Spring Boot simple qui affiche "Hello World!" via un endpoint REST.

## Prérequis

- Java 17 ou supérieur
- Maven 3.6 ou supérieur

## Structure du projet

```
src/
├── main/
│   └── java/
│       └── com/
│           └── example/
│               └── demo/
│                   ├── DemoApplication.java
│                   └── controller/
│                       └── HelloController.java
└── pom.xml
```

## Comment exécuter l'application

1. Clonez le projet
2. Ouvrez un terminal dans le répertoire du projet
3. Exécutez la commande suivante :
   ```bash
   mvn spring-boot:run
   ```
4. L'application sera accessible à l'adresse : http://localhost:8080

## Endpoints disponibles

- GET `/` : Retourne "Hello World!"

## Technologies utilisées

- Spring Boot 3.2.3
- Java 17
- Maven 