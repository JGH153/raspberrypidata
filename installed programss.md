# Main
```
sudo apt-get install nmap -y
sudo apt-get install apache2 -y
sudo apt-get install php5 libapache2-mod-php5 -y
sudo apt-get install mysql-server php5-mysql -y
sudo apt-get install phpmyadmin
sudo service apache2 restart

sudo apt-get install gnome-schedule
sudo apt-get install fswebcam

```

# Help phpmyadmin
```
https://www.stewright.me/2012/09/tutorial-install-phpmyadmin-on-your-raspberry-pi/
```

# Moodle
```
sudo apt-get install graphviz aspell php5-pspell php5-curl php5-gd php5-intl php5-mysql php5-xmlrpc php5-ldap
```

# Move to folder for install
```
sudo git clone git://git.moodle.org/moodle.git
OR
sudo git clone -b MOODLE_31_STABLE https://github.com/TheGlobalATeam/moodle.git
```

# Installing own plugin post install
```
cd moodle/blocks
sudo git clone https://github.com/TheGlobalATeam/moodle-blockplugn-birdidnews.git birdidnews
```

# Zip and unzip
```
sudo apt-get install zip unzip
```

# SDKman
```
curl -s "https://get.sdkman.io" | bash
```

# Gradle (remember to check for newer versions)
```
sdk install gradle 3.4
```

# Nodejs v 6.x
```
curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
sudo apt-get install -y nodejs 
sudo apt-get install -y build-essential
```
