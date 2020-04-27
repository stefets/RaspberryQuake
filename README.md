# quake3-server-config

* useradd -m -g users -s /bin/bash -d /home/quake3 quake3 # create quake3 user
* passwd quake3 # set password
* With root, download, build and install ioquake3 https://github.com/ioquake/ioq3
* With quake3 user
* mkdir -p /home/quake3/.q3a/baseq3
* copy all the required pk3 files in /home/quake3/.q3a/baseq3
* copy all the required cfg files in /home/quake3/.q3a/baseq3
* start with /usr/local/games/quake3/ioq3ded.x86_64 +exec autoexec.cfg +exec server.cfg +exec levels.cfg +exec bots.cfg
