> Epitech Project 2021 <br>
> B2 - Introduction to DevOps<br>
> B-MUL-200

# Popey
#### Set sail for the amazing world of containers

### Coding Style
- style mark: 0<br>
- style major: 0
- style minor: 0
- style info: 0
<br>

### Note : 100%
- 01: 3/3
- 02: 4/4
- 03: 3/3
- 04: 7/7

<br>

### GENERAL DESCRIPTION
You will have to containerize and define the deployment of a simple web poll application.
There are five elements constituting the application:
- Poll, a Flask Python web application that gathers votes and push them into a Redis queue.
- A Redis queue, which holds the votes sent by the Poll application, awaiting for them to be consumed by
the Worker.
- The Worker, a Java application which consumes the votes being in the Redis queue, and stores them into
a PostgreSQL database.
- A PostgreSQL database, which (persistently) stores the votes stored by the Worker.
- Result, a Node.js web application that fetches the votes from the database and displays the. . . well, result. ;)

<br><br>

>- **Student:** Adrien VERMERSCH
>-  **Email:** adrien.vermersch@epitech.eu
>- **Year:** 2022
>- **Promotion:** 2026
>- **Campus:** Bordeaux

Code rédigé selon la norme Epitech (promo 2026).<br><br>
Recopier ce repo revient au vol de code.<br>
Autrement dit, -42<br><br>
