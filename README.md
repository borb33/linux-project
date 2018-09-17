# Linux Server Configuration Project

The following are the information to access to the server:
IP Address: 54.172.41.220
SSH Port: 2200

To view the web application visit http://54.172.41.220.xip.io

# Software installed
The packages installed to run the application are: pip, flask, oauth2client, flask-httpauth, sqlalchemy, flask-sqlalchemy, psycopg2, requests, postgresql, git, libapache2-mod-wsgi-py3.

# Configuration
To complete the project first it was created and configured the user grader. Next, it was created the key based ssh authentication. Then, the firewall was configured to allow the ports for ssh, http and ntp. Next, the ssh configuration was updated to change the default port to 2200 and to enforce the key based authentication. Next, it was installed the packages required to run the application. Then, it was created the catalog database using PostgreSQL. Then, the application was cloned using Git and changed the database connection settings with the database. Finally, the Google oauth credentials was updated in order to allow the use within this server.

# Third-party resources
http://flask.pocoo.org/docs/0.12/deploying/mod_wsgi/
https://flask-wtf.readthedocs.io/en/stable/
https://www.howtoforge.com/tutorial/ufw-uncomplicated-firewall-on-ubuntu-15-04/
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-18-04
https://www.compose.com/articles/using-postgresql-through-sqlalchemy/

## Author

* **Boris Bonilla Araujo**