# assessment

This assessment was created as per the requirements set out.
Please ensure that your system has all the necessary dependencies in place. to support a Laravel application.
The system reads from a local mysql database. i made use of Xamp and used phpmyadmin.
System runs under the assumption that there is no root login password neccessary.

Once all the relevent requirements have been met please do the following:
1. Please extract the contents of the zip file to you default directory(Localhost) your server will recognise. 
2. A database needs to be created named "shops".
3. Through gitbash or the command line cd to the newly extracted directory.
4. Run the following command in order to create tables and seed them
    php artisan migrate (This should complete without any errors).
    now run php artisan db:seed
5. Default users will have been created in terms of the seed they are 'muhammedy.haet@gmail.com; using 'Password'. this is the default        system administrator. busster.18@gmail.com using 'Password' will also have been setup.
6. The system allows any person to register and their default Role will be 'User'.
7. Now login as the Admin and populate the respective tables that have been created namely : products discounts (categories).
8. Categories is a table created for future use as the system grows and the needs change.

The system make use of the jquery CDN as a dependency and therefore the localhost or host serer must have access to the internet in order to function. it is possible to setup the CDN locally however i did not do so.

The administrator and the user have individual menu items so as to prevent the admin from conducting purchases which may dirty the data. the environment assumed is that of production and not test hence the preceding decision.

The Routes being made use of for the system is web.php and api.php.
should you have any questions please email me at busster.18@gmail.com so i can assist you in any way. please do allow 48 hours for my response as i do not have access to my email daily.



