# -juego-de-adivinanzas-de-n-meros
Actividad final de certificación de freecodecamp base de datos relacional

# Number Guessing Game

Este proyecto es un juego de adivinanza de números donde el jugador debe adivinar un número aleatorio generado por el sistema entre 1 y 1000. El sistema proporciona retroalimentación sobre si la suposición del jugador es demasiado alta o demasiado baja hasta que se adivina correctamente.

## Descripción

El juego tiene una base de datos que almacena la información del usuario, como el nombre de usuario, la cantidad de juegos jugados y la cantidad mínima de intentos que ha utilizado para ganar. Al comenzar el juego, se pedirá el nombre de usuario. Si el usuario es nuevo, el sistema le dará la bienvenida, de lo contrario, mostrará el número de juegos jugados y el mejor puntaje de ese usuario.

## Características

- Generación aleatoria de un número entre 1 y 1000.
- Validación de entradas para asegurar que solo se ingresen números enteros.
- Registro de la cantidad de juegos jugados y los mejores puntajes para cada usuario.
- Base de datos PostgreSQL para almacenar los datos de los usuarios.

## Requisitos

- Bash
- PostgreSQL
- Git

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/number_guessing_game.git
   cd number_guessing_game
psql --username=freecodecamp --dbname=postgres
CREATE DATABASE number_guess;
chmod +x number_guess.sh
