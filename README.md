ReqBase Requirements Database
=============================

Local Install
-------------

1. Create empty database in MySQL (e.g., reqbase-dev)
2. Create MySQL user (e.g., reqbase-dev)
3. Download database from http://lelystad.informatik.uni-mannheim.de/reqbase-db/
4. Gunzip it: gunzip DUMP-FILE
5. Load database: mysql -u reqbase-dev -p reqbase-dev < UNZIPPED-FILE
6. Clone ReqBase
7. Copy htdocs/sites/default/reqbase-settings.php to htdocs/sites/default/settings.php
8. Adjust settings.php to your needs (just the password, if you use reqbase-dev)
9. Make htdocs accessible via Apache (see Drupal manual for details)

Update
------

1. Update your GIT repository
2. Download recent database dump
3. Empty your database (e.g., reqbase-dev)
4. Reload database using steps above

