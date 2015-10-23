## Required packages:

* nginx
* Python 3
* Git
* pip
* virtualenv

eg, on Ubuntu:

	sudo apt-get install nginx git python3 python3-pip
	sudo pip3 install virtualenv
	
## Nginx Virtual Host config

* see nginx.template.conf
* replace SITENAME with, eg, staging.my-domain

## Upstart Job

* see gunicorn-upstart.template.conf
* replace SITENAME with, eg, staging.my-domain

## Folder structure
Assume we have a user acount at /home/username

/home/ username 
└ ─ ─ sites
     └ ─ ─ SITENAME
     	├ ─ ─ database
     	├ ─ ─ source
     	├ ─ ─ static
     	└ ─ ─ virtualenv

Percival, Harry J. W. (2014-06-11). Test-Driven Development with Python (Kindle Locations 4641-4642). O'Reilly Media. Kindle Edition. 