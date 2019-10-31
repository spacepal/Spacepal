# Spacepal
Online version of Konquest game [in development]

# Spacepal is a step-by-step game.
* The main goal is to capture all the planets of the opponent and remain the last on the map
* Each step player sends ships from one planet to another
* Every planet has its own kill percentage and production number
* Ships can:
  * capture the planet (in that way player get the planet)
  * land on the planet (if player is already the owner)
  * be destroyd by planet (if planet is stronger)
* Each step there is a fear for every planet and fleet to be damaged by pirates
* You can play with ouyr friends or any other people
* No need to sign up, only type in the name

# Requirements
- docker-compose

# How to play
- Download:
```bash
git clone --recurse-submodules -j8 https://github.com/spacepal/Spacepal.git
cd Spacepal
```
- Up server:
```bash
docker compose up
```
- Enter http://localhost:8080 and enjoy game