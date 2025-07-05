
# 🚗 Vehicle API – Projet Propelize

API de gestion des utilisateurs et véhicules avec des fonctionnalités d'authentification basée sur **JWT** développée en **Java (Spring Boot)** avec une base de données **MySQL**.
Suivez ce guide pour explorer les endpoints disponibles et tester l'API avec Postman ou tout autre client HTTP..

## ✅ Fonctionnalités

- Créer un véhicule
- Lire tous les véhicules
- Lire un véhicule par ID
- Modifier un véhicule
- Supprimer un véhicule
- Données initiales insérées automatiquement via `data.sql`
- créer un utiliateur
- Authentifier un utilisateur

---

## 🛠️ Technologies

- Java 17
- Spring Boot
- Spring Data JPA
- MySQL 8
- Docker & Docker Compose
- Postman (pour tester l’API)

---

## 🏗️ Structure du projet

src/
├── controller/ # Contrôleur REST (VehicleController)\
├── model/ # Modèle de données (Vehicle)\
├── repository/ # Accès aux données (VehicleRepository)\
├── service/ # Logique métier (VehicleService)\
├── resources/\
│ ├── application.properties # Config DB\
│ └── data.sql # Données initiales


---

## ⚙️ Lancement en local 
0. Avec docker 
```docker-compose up --build


Executer la commande docker-compose up -d; 
```
2. Configure src/main/resources/application.properties 
```
spring.datasource.url=jdbc:mysql://localhost:3306/vehicle_db
spring.datasource.username=root
spring.datasource.password=
```
3.Compile et exécute :
```
./mvnw spring-boot:run
```
L’API est hébergé 

La documentation swagger de l'application sera disponible ici http://localhost:8080/swagger-ui/index.html

 
#👨‍💻 Auteur (Groupe 4)
Développé dans le cadre du TP00 - TP01 – Software Testing - API Construction pour le cours ICT 304.



Université de Yaoundé I
Département d’Informatique – Faculté des Sciences
Encadré par Dr KIMBI 


# VehiculeAPI
test d'une api de véhicule 



