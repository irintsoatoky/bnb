## Installation
```
git clone https://github.com/irintsoatoky/bnb.git
cd bnb
composer install
```

## Configuration
Créer un fichier `.env.local` : 
```dotenv
DATABASE_URL=mysql://DATABASE_USER:@DATABASE_HOST:3306/DATABASE_NAME
```

## Configuration de la base de donnée
```
php bin/console d:d:c
php bin/console d:s:u -f
```

## Démarrer le serveur
```
symfony serve
```

💻 Happy coding 🥳