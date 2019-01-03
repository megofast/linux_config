# linux_config

## Connecting
  - IP Address: 3.17.76.65
  - Port: 2200
  
 ## Software and Configuration Installed
  - Installed Apache2
  - Installed WSGI for Apache2
  - Installed PostgreSQL
  - Installed psycopg2
  - Installed PIP
  - Installed python packages with PIP
    - Requests
    - Flask
    - OAuth2Client
    - SQLAlchemy
  - Configured WSGI
    - Created new virtual host file for Catalog_App.conf.
    - Disabled default virtual host and enabled new virtual host.
    - Created wsgi script in the folder containing the python server.
  - Created PostgreSQL role catalog.
    - set permissions for only Login.
    - Granted privileges for only the catalog database.
    
  ## Resources used
    - http://terokarvinen.com/2016/deploy-flask-python3-on-apache2-ubuntu
    - http://flask.pocoo.org/docs/1.0/deploying/mod_wsgi/
    - https://www.postgresql.org/docs/10/sql-grant.html
    
