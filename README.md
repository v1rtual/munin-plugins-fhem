munin-plugins-fhem
==================
Plugins for munin to show temperature/humidity and gas/power meter readings from fhem (Fhem is a GPL'd perl server for house automation, see http://fhem.de/).
These are only examples of my current configuration. Perhaps it is useful to someone.

2 different types:
- simple reading from logfile (most other scripts)
- reading from logfile and counting events (fhem-piri script)

You have to set up fhem to log to file / adjust logfilenames in scripts

usage
-----
1. install to `/var/share/munin/plugins`
2. run `munin-node-configure --shell`
3. link to /etc/munin as shown
4. restart munin-node

