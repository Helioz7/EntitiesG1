#MyFirstSymfony

## Installation

```bash

symfony new MyfirstSymfony
cd MyfirstSymfony
```

### installation de `maker`

```
bash
composer require --dev symfony/maker-bundle
``` 


pour voir ce que l'on peut faire dans la console

```bash
symfony console
php bin/console
```
pour voir les actions possibles de maker : 

```bash
php bin/console make:
```
 ###création d'un controller

```bash
php bin/console make:controller First
```
Le nom dois être en pascale case

#MySecondSymfonyC1

installation de la version lts(long term support)avec la majorité des bibliothéques pour un site web (`--webapp`)

#Mise à jours des version de sécurité 
composer update

## Lancement du serveur 
symfony serve -d
ou
symfony server:start -d

pour le fermer 
symfont server:stop


l'adresse est généralement de type htpps://127.8.8.1:8000

### Création d'un contrôleur 

symfony console make:controller

php bin/console make:controller

le nom doit être en PascaleCase terminé par controller, mais symfony se charge de le corriger en cas d'oubli.

php bin/console make:constroller HomeController
created: src/Controller/HomeController
created: template