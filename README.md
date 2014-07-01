# Setup

## git

    sudo apt-get install -y git
    cd /tmp
    git clone git@github.com:tigris/home.tigris.id.au
    sudo mv home.tigris.id.au /srv

## ddclient

You will need to create ~root/.ddclient containing cleartext password for your
password for ddclient

## Initial setup

    cd /srv/home.tigris.id.au
    ./setup
