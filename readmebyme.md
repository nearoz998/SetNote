Hello,
This is the creator of this folder,
To have this app in your environment, follow the steps:
1. Clone this repo in your computer,
2. Rename .env.example to .env,
3. Add folder database/database.sqlite,
4. Copy path of the file database.sqlite,
5. Add following to .env:
            DB_CONNECTION=sqlite
            DB_DATABASE='PATH OF THE FILE YOU COPIED' //for example ''C:\PROJECT FILES\SetNote\database\database.sqlite'
            DB_FOREIGN_KEYS=true
6. php artisan serve