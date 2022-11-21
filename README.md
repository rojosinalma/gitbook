# Install raspi-config in ubuntu server

Install raspi-config in ubuntu server 22.04



```
# Add debian repo
sudo echo "deb http://archive.raspberrypi.org/debian/ buster main" >> /etc/apt/sources.list

# Add keys
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 7FA3303E

# Update
sudo apt-get update

# Install & Run
sudo apt-get install raspi-config
sudo raspi-config
```

