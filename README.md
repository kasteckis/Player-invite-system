# Player invite system
![github-large](readme.gif)
This project was done to strengthen my knowledge using `Symfony` framework. It was made for one CS:GO community. This project main goal is to have big database of STEAM players, where you can take those players from random pool, then you can contact them and try to sell them some kind of service. Basically it works like Tinder swap, but with random steam players.
# How to install
1. Clone this repository
2. `$ composer install`
3. Add your database connection information to `.env` file (or to `.env.local`)
4. `$ php bin/console doctrine:schema:update --force`
5. If you want to have some data, upload SQL dump from `database_dump.sql
# Where I Improved
1. Symfony
2. Easy admin bundle
3. Twig
4. Doctrine
