# Legacy PHP Functions
Restores PHP functions that were removed in new versions of PHP

A little file containing functions that were removed from PHP helpful for getting legacy software back online till you can update it.

Includes:
mysql_*
create_function
ereg
eregi
ereg_replace
eregi_replace
split
spliti


Pro Tip!

In your php.ini You can set auto_prepend_file setting and this will automaticly be included on any scripts on the server.
auto_prepend_file =  /var/www/pathtofile/phplegacy-helper.php
