# Poweroff
```
sudo shutdown -h now
```

# Newtwork tool
```
nmap vg.no
```

# Free space
```
df
```

## Free space in GB
```
df -BG
```

# Restart apatche
```
sudo service apache2 restart
```

# Graceful Restart apatche
```
sudo service apache2 reload
```

# Update system
```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get dist-upgrade
http://askubuntu.com/questions/222348/what-does-sudo-apt-get-update-do

apt full-upgrade performs the same function as apt-get dist-upgrade.
https://askubuntu.com/questions/770135/apt-full-upgrade-versus-apt-get-dist-upgrade
```

# All devices on subnet
```
arp -a
```

# Get local ip adress
```
ipconfig
```

# Sett full premission recursivly
```
sudo chmod -R 777 /var/www/moodle
```

# Get GPU temp
```
vcgencmd measure_temp
```

# Get CPU temp
```
cpu=$(</sys/class/thermal/thermal_zone0/temp)
echo "$((cpu/1000)) c"
```

# Make folder moodle
```
mkdir moodle
```

# Move content of folder up one level (folder moodle)
```
mv moodle/* .
```

# List all video recording devices
```
ls -ltrh /dev/video*
```

# List all audio recording devices
```
arecord -l
```
