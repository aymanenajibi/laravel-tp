# 🎟️ Laravel-tp

🚀 **Laravel-tp** est un projet développé avec **Laravel**. Ce guide vous expliquera comment l'installer et l'utiliser correctement.

## 📌 Prérequis

Avant de commencer, assurez-vous d'avoir installé :

- 📌 [PHP](https://www.php.net/) (version 8.0 ou supérieure)
- 📌 [Composer](https://getcomposer.org/)
- 📌 [MySQL](https://www.mysql.com/) ou une autre base de données compatible
- 📌 [Node.js](https://nodejs.org/) (si vous utilisez Laravel Mix)
- 📌 [Git](https://git-scm.com/)
- 📌 Un serveur web comme [Apache](https://httpd.apache.org/) ou [Nginx](https://www.nginx.com/)
- 📌 Un éditeur de code comme [VS Code](https://code.visualstudio.com/)

## 👥 Installation

1. **Cloner le projet** 🛠️  
   ```bash
   git clone https://github.com/ton-utilisateur/Laravel-tp.git
   cd Laravel-tp
   ```

2. **Installer les dépendances** 📦  
   ```bash
   composer install
   ```

3. **Copier le fichier d'environnement** 📄  
   ```bash
   cp .env.example .env
   ```

4. **Générer la clé d'application** 🔑  
   ```bash
   php artisan key:generate
   ```

5. **Configurer la base de données** 🛢️  
   - Ouvrir le fichier `.env` et modifier les paramètres de la base de données :
     ```
     DB_CONNECTION=mysql
     DB_HOST=127.0.0.1
     DB_PORT=3306
     DB_DATABASE=nom_de_votre_base
     DB_USERNAME=nom_utilisateur
     DB_PASSWORD=mot_de_passe
     ```

6. **Exécuter les migrations** 🏗️  
   ```bash
   php artisan migrate
   ```

## ▶️ Lancer le projet

1. **Démarrer le serveur Laravel** 🚀  
   ```bash
   php artisan serve
   ```
   Ensuite, ouvrez votre navigateur et accédez à **http://127.0.0.1:8000/**.

2. **Compiler les assets (si nécessaire)** 🎨  
   ```bash
   npm install
   npm run dev
   ```

## ⚙️ Scripts disponibles

- `php artisan serve` ➞ Lance le serveur de développement Laravel.
- `php artisan migrate` ➞ Exécute les migrations pour créer les tables.
- `php artisan db:seed` ➞ Remplit la base de données avec des données fictives.
- `npm run dev` ➞ Compile les fichiers CSS et JavaScript avec Laravel Mix.

## 📂 Structure du projet

```
Laravel-tp/
│── app/           # 📂 Contient la logique du projet (modèles, controllers...)
│── bootstrap/     # 🚀 Démarrage de l'application
│── config/        # ⚙️ Configuration de Laravel
│── database/      # 🛢️ Migrations et seeds
│── public/        # 🌍 Fichiers accessibles publiquement
│── resources/     # 🎨 Vues Blade, CSS, JS
│── routes/        # 📜 Fichiers de routes
│── storage/       # 📦 Logs et fichiers temporaires
│── tests/         # 🧪 Tests unitaires et fonctionnels
│── .env           # 🔑 Configuration locale
│── artisan        # 🛠️ Commandes Artisan
│── composer.json  # 📜 Gestion des dépendances PHP
│── package.json   # 📜 Gestion des dépendances JS
│── README.md      # 📖 Documentation
```

## 🤝 Contribuer

1. **Forker** le projet 🍽️  
2. **Créer une branche** (`git checkout -b feature-nouvelle-fonctionnalité`) 🌳  
3. **Commiter** vos modifications (`git commit -m "Ajout d'une nouvelle fonctionnalité"`) 💾  
4. **Pusher** (`git push origin feature-nouvelle-fonctionnalité`) 🚀  
5. **Créer une Pull Request** 🔄  

## 🛠️ Technologies utilisées

- ⛓️ **Laravel** - Framework PHP
- 🎨 **Blade** - Moteur de template
- 📦 **MySQL** - Base de données
- 🖥️ **Bootstrap/Tailwind CSS** - Styles et mise en page
- ⚡ **Laravel Mix** - Compilation d'assets

## 📜 Licence

📝 Ce projet est sous licence **MIT**.

## 💌 Contact

💡 **Auteur** : [Aymane Najibi](https://github.com/aymanenajibi)  
📧 **Email** : aymanee.najibi@gmail.com

