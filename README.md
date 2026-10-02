# Basic POS System

This is a four-page CodeIgniter 4 website using static PHP arrays.

## Pages

- `/`
- `/about`
- `/customers`
- `/users`

## Run with XAMPP

1. Place the `fa3` folder in `C:\xampp\htdocs`.
2. Start Apache & MySQL in XAMPP.
3. open `http://localhost/phpmyadmin` then import fa2_pos.sql from folder directory
4. Then go to the config file(php.ini) under Apache and change this line from `;extension=gd` to `extension=gd`
5. Open `http://localhost/fa3/public/`.

PHP 8.2 or newer is required.

Database and the ability to edit exisiting profiles, add new ones, and add profile pictures was added in this activity.
