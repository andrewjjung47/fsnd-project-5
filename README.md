# fsnd-project-5

## Access:
*  IP: 52.11.161.89
*  SSH port: 2200
*  Username: grader, password: 'QL4K[ZcFt=8v5pg
 
## Summary of Modifications
1. Create a new user, `grader`, and granted sudo permissions. Also, enabled ssh access to this user.
2. Modified `sshd_config` to change ssh port to 2200 and disable root access.
3. Disable all ports except `80`, `2200`, and `123` using `ufw`.
4. Updated `apt-get` list and upgraded installed softwares.
5. Installed `git` and cloned catalog app from my Github.
6. Installed Apache and Postgresql. Created database and a user for the catalog app. Configured Apache configuration file accordingly.
7. Installed `pip` and installed all the required packages for the catalog app using `requirement.txt`.
8. Created `myapp.wsgi` for the app.
9. Modified database connection from SqlLite to Postgresql.
 
## Summary of Softwares Installed:
* Apache
* Postgresql
* Pip
* Git
* Python Flask and SqlAlchemy
* Python packages from `requirement.txt`. Important ones include `oauth2client`, `requests`, `httplib2`, `Jinja2`, etc...

##Resources:
* https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-14-04
* https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-14-04
