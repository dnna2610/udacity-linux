# Configuring Linux Server
* IP Address: `35.164.221.235`
* SSH Port: 2200
* Url: [link](http://35.164.221.235)
* Summary of software installed and configuration made
    - Installed apache2, mod-wsgi, postgresql, flask, psycopg2, Flask-SQLAlchemy
    - Upgrade all packages
    - Create a new user named 'grader', give that user sudo access, add key log-in for that user
    - Disable password login, disable remote root login
    - Change SSH port to 2200
    - Configure UFW to deny all incoming, allow all outgoing, allow all for port 2200(SSH), 80(http), 123 (ntp) and then enable UFW
    - Set time to UTC
    - Create new user name catalog for postgresql with password: 'udacity'
    - Install git, clone and setup the catalog app 