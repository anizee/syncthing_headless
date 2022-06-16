Syncthing Headless
======================

I'm going to show you how to set up Syncthing in the context of my setup. So having that 'central' server. You could use a cheap Raspberry PI to set up your 'central' server.

My 'central' server is running Ubuntu Server, so the following instructions are tailored for Debian distros.

Firstly, you need to install the correct package locations in order to download Syncthing correctly.

sudo apt-get install curl apt-transport-https

curl -s https://syncthing.net/release-key.txt | sudo apt-key add -

echo "deb https://apt.syncthing.net/ syncthing stable" | sudo tee /etc/apt/sources.list.d/syncthing.list
Next, update your local repository with the new Syncthing repository

sudo apt-get update
sudo apt-get upgrade

sudo apt-get install syncthing
The next thing you want to do is enable Syncthing as a system service. This will allow start-up on boot and continuous execution in the background of your server.

sudo systemctl enable syncthing@username.service

sudo systemctl start syncthing@username.service
So this will start Syncthing on your Ubuntu Server. Problem is, Ubuntu Server is usually headless. So at the moment there is no way to access the Syncthing GUI to configure your folders and nodes.

The way we can change this to allow local access from another machine is to change the serve address.

When you ran the Syncthing command above, a syncthing folder was created under your /home/username/.config folder.

Inside that will be a config.xml file.

Open this with a text editor, something like Vim or Nano. It really doesn't matter.

Within config.xml there is a section that looks like this:

...
<gui enabled="true" tls="false" debugging="false">
    <address>127.0.0.1:8384</address>
    <apikey>...</apikey>
    <theme>default</theme>
</gui>
...
Under the address attribute, you need to update the ip address.
0.0.0.0 will allow all machines on your local network to be able to access the Syncthing GUI.

...
<gui enabled="true" tls="false" debugging="false">
    <address>0.0.0.0:8384</address>
    <apikey>...</apikey>
    <theme>default</theme>
</gui>
...
Save and close config.xml and then restart Syncthing by running the following command.

sudo systemctl restart syncthing@username.service
Second Node
For Syncthing to work, you need to set up another Syncthing node. Simply follow the above steps again on another machine, or jump to the bottom of this page quickly and install Syncthing on Windows or Android
Accessing the Syncthing GUI
Now with all that running, you should be able to access the Syncthing GUI by navigating to:

http://{your_server_ip}:8384
Once entering your ip-address or hostname, you should be presented with something that looks like this
