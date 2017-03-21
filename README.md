# Stuff

### Build VS CODE on ARM

https://github.com/Microsoft/vscode/wiki/How-to-Contribute#build-and-run-from-source
https://gist.github.com/ted-piotrowski/e5c223a6a2f6f3079cb38c959ceecaa6#file-visualstudiocode-sh


apt-get update && apt-get upgrade
apt-get install build-essential
sudo apt-get install libxss1
sudo apt-get install libgconf-2-4

sudo apt-get uninstall nodejs                                           # uninstall nodejs 4.2.6
wget https://nodejs.org/dist/v6.6.0/node-v6.6.0-linux-armv7l.tar.gz     # get latest ARM build
tar -xvf node-v6.6.0-linux-armv7l.tar.gz                                # extract it
sudo cp node-v6.6.0-linux-armv7l /etc/node6.6                           # copy extracted file to /etc folder
sudo ln -s /etc/node6.6/bin/node /usr/bin/node                          # link the nodejs executable
sudo ln -s /etc/node6.6/bin/npm /usr/bin/npm                            # link the npm executable
node --version     

apt-get install python


```

### PREZ

http://slides.com/rhwy/being-functional
