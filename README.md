# pebble-sdk
Pebble SDK for Linux64 fixed for Rebble

# To install it
```
sudo apt-get update
sudo apt-get install python-pip python2.7-dev libsdl1.2debian libfdt1 libpixman-1-0 git npm

sudo pip install --upgrade pip
sudo pip install virtualenv

git clone https://github.com/jcrona/pebble-sdk.git ~/pebble-sdk
cd ~/pebble-sdk

virtualenv --no-site-packages .env
source .env/bin/activate
pip install -r requirements.txt
deactivate

pebble sdk install latest
```
