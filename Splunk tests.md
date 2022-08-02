download `.deb` (or sth else) -> copy to`/opt` -> `cd /opt` -> `sudo dpkg -i splunk.deb` -> `cd /opt/splunk/bin` -> `service ./splunk start`

on port 8000 - must be available for Web interface

to install additional splunk app: 
e.g. `https://github.com/splunk/botsv3` to `/opt/splunk/etc/apps`

Forwarders - passes logs to indexers
Indexers - wstepne sortowanie, backupy
