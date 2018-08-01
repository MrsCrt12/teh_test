The application was developed in Laravel framework

The main code you can find in :
*routes/web
*app/Person.php
*app/Http/Controllers/PersonsController
*resources/views/welcome.blade.php
*public/js/functions.js

The DB is in MYSQL

To instal you can use this project or create a new project and copy (and replace) the the files mentioned above.
Set up the .env file for DB connection with user and password and db name.

I hope I did as was required,because the search could be done in several ways:

*full_name like $search % / % $search %
*full_name as first_name like % $search % /like  $search % 
 OR 
 full_name as last_name like % $search % /like  $search %
*full_name as first_name like % $search % /like  $search % 
 AND 
 full_name as last_name like % $search % /like  $search %
.
.
.

Cheers!
