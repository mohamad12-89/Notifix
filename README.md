#Running the Project
(do this in the terminal of VS Code)
1) npm run dev (in one terminal)
2) php -S localhost:8000 -t public (in the other terminal)

#How to get access to the Project from github
1) First the root user will send you an invitation to join the GitHub repository.
(do the below in the terminal of VS Code)
2) git clone https://github.com/mohamed12-89/Notifix.git
3) cd Notifix
4) composer install
5) npm install
6) "Make sure that you have the file called "database.sqlite" in the database. Otherwise create this file in the VS Code manually (better). then put this command int terminal: php artisan migrat"
7) cp .env.example .env
8) npm run dev (in one terminal) and php -S localhost:8000 -t public(in another terminal)


