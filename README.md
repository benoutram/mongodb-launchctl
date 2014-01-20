mongodb-launchctl
=================

Mac OSX launchctl configuration file to run the mongod process as a daemon at startup.

Installation
------------

After installing MongoDB with MacPorts, configure mongod as a daemon process by installing the configuration file.

    sudo launchctl load -w /Library/LaunchDaemons/org.macports.mongodb.plist
