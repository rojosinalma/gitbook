# Install raspi-config in ubuntu server

Install raspi-config in ubuntu server 22.04



```
sudo echo "deb http://archive.raspberrypi.org/debian/ buster main" >> /etc/apt/sources.list
```

<pre><code><strong>sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 7FA3303E</strong></code></pre>

```
sudo apt-get update
sudo apt-get install raspi-config
```

```
sudo raspi-config
```
