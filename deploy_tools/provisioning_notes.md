Provisioning a new site

Required packages:

nginx
Python 3
Git
pip
virtualenv

sudo apt-get install nginx git python3 python3-pip
sudo pip3 install virtualenv

see nginx.template.conf
replace SITENAME with fds-1.cloudapp.net

/home/username
	sites
		SITENAME
			database
			source
			static
			virtualenv

			
