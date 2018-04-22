# Temporary-MYSQL-to-MYSQLI-Compliance
Very quick fix to keep your mysql website running without upgrading it. 

Open your website phpmyadmin
Open Settings
Open your php.ini file

Find 
output_buffering = Off
and change it to 
output_buffering = On

Find 
error_reporting = E_ALL ^ ...
and change it to 
error_reporting = E_ALL ^ E_DEPRECATED

Save and exit.
You are welcome.

This will only work until mysql is not supported at all anymore.
