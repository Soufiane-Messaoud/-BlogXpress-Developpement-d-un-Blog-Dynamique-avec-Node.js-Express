📌 Description du projet

BlogXpress est une application web de type Blog développée avec Node.js et le framework Express. Ce projet repose sur une architecture RESTful API et permet d'effectuer des opérations CRUD sur les entités principales : Utilisateurs, Articles, Commentaires et Tags. Il utilise MySQL comme base de données et Sequelize comme ORM. L'authentification est sécurisée grâce à JSON Web Token (JWT).

🚀 Fonctionnalités

📌 Gestion des utilisateurs (inscription, connexion, rôles)

📝 Création, modification, suppression et affichage des articles

💬 Ajout et gestion des commentaires

🏷️ Gestion des tags et association avec les articles

🔐 Authentification et sécurité avec JWT

🛠 Technologies utilisées

Backend : Node.js, Express.js, Sequelize ORM

Base de données : MySQL

Authentification : JSON Web Token (JWT)

Frontend : HTML5, CSS3, Bootstrap

📊 Conception de la base de données

Les principales entités et leurs relations :

User (id, username, email, password, role)

Article (id, title, content, published, userId)

Comment (id, content, articleId, userId)

Tag (id, name)

Relations :

Un utilisateur peut écrire plusieurs articles.

Un article peut avoir plusieurs tags et vice-versa.

Un article peut recevoir plusieurs commentaires.
