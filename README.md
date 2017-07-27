## Linux Server Configuration Project


-----

#### Server Information:

**IP address:** `54.234.125.1`

**Port:** `2200`

**Homepage:** http://54.234.125.1/


-----


#### Actions:
* Updated packages
* Created user `grader` with sudo access
* Generated SSH key for `grader`
* Set port `2200`, `80`, and `123` to allow
* Changed SSH to port `2200`
* Disabled root login
* Installed and configured Apache
* Created project directory under /var/www with proper WSGI file and python files.
* Created virtual host file `pokedex.conf`
* Installed Flask and Item Catalog (Pokedex) project
* Installed PostgreSQL and made the `pokedex` database
* Made changes to file paths in project code


-----


#### Third-Party Resources:
When running into issues with this project, I ocasionally referred to Digital Ocean's [Flask Ubuntu VPS tutorial](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps). Digital Ocean has a lot of great resource for getting started with a VPS.
