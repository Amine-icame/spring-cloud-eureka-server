# Spring Cloud Eureka Server (Service Registry)

Ce projet héberge le serveur de découverte de services (Service Registry) de notre architecture de microservices. Les microservices s'enregistrent auprès de lui et peuvent se découvrir mutuellement grâce à lui.

## 🚀 Technologies Utilisées

-   **Spring Boot 3+**
-   **Spring Cloud Netflix Eureka Server**
-   **Maven**
-   **Java 17+**

## ⚙️ Comment le Lancer ?

1.  **Configuration :** Aucune configuration spécifique n'est généralement nécessaire, le port par défaut est `8761`.
2.  **Lancement :**
    ```bash
    mvn spring-boot:run
    ```
    Le serveur Eureka sera accessible sur `http://localhost:8761`.

## 🧪 Vérification

Ouvrez votre navigateur et accédez au tableau de bord Eureka : `http://localhost:8761`.
Après le démarrage des autres microservices, vous devriez les voir s'enregistrer et apparaître dans la liste des instances disponibles.
<img width="1808" height="966" alt="image" src="https://github.com/user-attachments/assets/7055fe0e-9432-41a5-9fbc-540694f8be1a" />


---

*Développé par Amine içame/Salma BenOmar pour le module JEE.*
