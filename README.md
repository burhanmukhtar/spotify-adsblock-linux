# spotify-adblock-linux ![Language](https://img.shields.io/github/languages/top/vsvinav/spotify-adblock-linux?style=flat)

**A Spotify adblocker for Linux**

Installation   
------------
```
$ git clone https://github.com/burhanmukhtar/spotify-adsblock-linux.git
$ cd spotify-adblock-linux
$ pip3 install -r requirements.txt
```

Usage   
-----
Open Spotify before running the script

`$ python3 adspotter` (keep it running)

Troubleshooting
-----
If in case you're not able to install dbus-python, run `# apt-get install libdbus-1-dev libdbus-glib-1-dev` to fix.
And then run `$ pip3 install -r requirements.txt` again.
