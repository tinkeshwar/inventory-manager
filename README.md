## Developer Guide

After cloning the project, go to the root folder of the project and run,

    composer install

After composer install successfully, create environment file from sample env.example and setup required credentials in .env file

    cp .env.example .env

After entering required values in .env generate the app key by following the command

    php artisan key:generate

create the database with the same name used in the .env file in your MySQL and run the following command

    php artisan migrate
