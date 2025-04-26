# Syncer

Syncer is a very simple application I made in RUST that will copy/update files from one folder to another. Target use for this application is syncing content to or from your mounted SMB folder.

## Getting started
To get started you will need to install the application:
echo "deb [trusted=yes] https://anzepirnat.github.io/syncer-repo/apt ./" | sudo tee /etc/apt/sources.list.d/syncer.list
sudo apt update
sudo apt install syncer

After installing you will need to configure the syncer.toml script which has to be in the same directory as the syncer binary. In syncer.toml you will configure one or multiple "sync-pairs", which consist of source and destination folder.
