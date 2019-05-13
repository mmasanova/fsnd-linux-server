# Linux Server Configuration
Linux Server Configuration project for Udacity's Full Stack Nanodegree program

IP Adress: 18.130.212.16
SSH port: 2200

Tested ssh connection using below command and ssh key provided in the submission process:
```ssh -i ~/.ssh/grader grader@18.130.212.16 -p 2200```

Application url: http://18.130.212.16.xip.io/

## Software installed

* upgraded all existing packages
* libapache2-mod-wsgi
* postgresql
* apache2
* pip
* SQLAlchemy
* requests
* psycopg2
* flask
* oauth2client
* git

## Configuration changes

* Firewall - only allow http 80, ssh 2200, ntp 123

* Created grader user with sudo permissions

* Confirmed local timezone to be UTC

* Configured Apache to serve the item-catalog app as a Python mod_wsgi application

* Confirmed no remote connections are allowed for postgres

* Created catalog user with limited permissions to the item_catalog database

* ssh authentiction is enforced

* remote root login is disabled

## Resources used

* Udacity Full Stack Nanodegree

* stackoverflow 

* documentation for each library/software/package

