# .htaccess


<IfModule mod_rewrite.c>
RewriteEngine on
RewriteBase /projectFolderName/projectFolderName2/
RewriteCond %{REQUEST_FILENAME} !-f
RewriteCond %{REQUEST_FILENAME} !-d
RewriteRule ^(.*)$ index.php/$1 [L]
</IfModule>

