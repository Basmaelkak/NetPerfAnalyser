# 🚀 NetPerfAnalyzer: Network Performance Analyzer

NetPerfAnalyzer est une **plateforme complète** pour tester et analyser la performance réseau.  
Elle combine **React** pour le frontend, **Spring Boot & Maven** pour le backend, et une base de données **MySQL** appelée `netperf`.  

---

## 📑 Table des Matières
1. [⚙️ Architecture Logicielle](#️-architecture-logicielle)  
2. [🎨 Frontend](#-frontend)  
3. [🛠 Backend](#-backend)  
4. [💻 Configuration locale et exécution](#-configuration-locale-et-exécution)  
5. [🎥 Démonstration Vidéo](#-démonstration-vidéo)  
6. [🤝 Contributeurs](#-contributeurs)  

---

## ⚙️ Architecture Logicielle

- **Frontend** : React  
- **Backend** : Spring Boot  
- **Communication** : API REST sécurisées par **JWT**  
- **Base de données** : MySQL  


---
## Frontend
🛠 Technologies utilisées

React

Redux

React Router

Bootstrap

Chart.js

Axios

jsPDF + html2canvas

Jest & Testing Library

👉 Fournit une interface moderne et réactive, communiquant avec le backend via JWT.

---
## 🛠 Backend
🛠 Technologies utilisées

Spring Boot 2.7.0

Spring Security

Spring Data JPA

Spring Web

JWT (JSON Web Tokens)

MySQL

📂 Structure du projet backend
application → Point d’entrée (Application.java)

controllers → Endpoints REST sécurisés

models → Entités JPA (tables MySQL)

repository → DAO via Spring Data JPA

service → Logique métier

request → DTO pour requêtes entrantes

response → DTO pour réponses sortantes

security → Configuration Spring Security

---
## 💻 Configuration locale et exécution

🔹 Prérequis

Git → Télécharger ici

XAMPP → Télécharger ici

Démarrer Apache & MySQL

NVM (Node Version Manager) → Guide d’installation

nvm install 18

🔹 Backend

git clone https://github.com/Basmaelkak/NetPerfAnalyser

cd backend

mvn clean install

mvn spring-boot:run

🔹 Frontend

cd frontend

nvm use 18

npm install

npm start

---
## 🎥 Démonstration Vidéo


https://github.com/user-attachments/assets/018e82a5-b017-481d-8b85-47ecc9f33dd7

---
## 🎥 🤝 Contributeurs

-EL-KAK Basma https://github.com/Basmaelkak

-SAAD Oumaima https://github.com/oumaimasaad-debug

