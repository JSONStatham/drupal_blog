### Clone project from current repo or load zip file

### Install Drupal

- <code>cd /var/www/[project]</code>
- <code>composer install</code>
- <code>cd /var/www/[project]/web</code>
- <code>drush si standard --account-name=admin --account-pass=admin --db-url=mysql://[user]:[pass]@localhost/[db_name]</code>
- <code>drush cim</code>

### Import database
Import db using some manager tools (adminer, phpmyadmin etc.)

run <code>drush cim</code> from <code>/web</code> folder

#### Update via composer

- <code>cd /var/www/[project]</code>
- <code>composer update</code>
