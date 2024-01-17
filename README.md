# Blog Books Symfony PHP

Petit projet en Symfony PHP 6.4

## Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- [PHP](https://www.php.net/) (6.4)
- [Composer](https://getcomposer.org/)
- [Symfony CLI](https://symfony.com/download)

## Installation

1. **Clonez le dépôt :**

    ```bash
    git clone https://github.com/D-Seonay/blogbooks.git
    ```

2. **Installez les dépendances avec Composer :**

    ```bash
    cd blogbooks.git
    composer install
    ```

3. **Configurez l'environnement :**
Créez un fichier `.env.local` à la racine de votre projet avec les informations suivantes :

    ```.env
    DATABASE_URL="mysql://username:password@127.0.0.1:8889/database_name?serverVersion=8.0.32&charset=utf8mb4"
    MAILER_DSN=smtp://smtp_username:smtp_password@smtp_server:smtp_port
    ```

4. **Créez la base de données :**

    ```bash
    php bin/console doctrine:database:create
    ```

5. **Effectuez les migrations :**

    ```bash
    php bin/console doctrine:migrations:migrate
    ```

6. **Lancez le serveur de développement Symfony :**

    ```bash
    symfony serve
    ```

    Le serveur sera accessible à l'adresse `http://localhost:8000`.

## Utilisation

A écrire : 


## License

Ce projet est sous licence [LICENSE NAME](LICENSE.md) - voir le fichier [LICENSE.md](LICENSE.md) pour plus de détails.

---

