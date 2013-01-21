bbpa-installer
==============

Mac-OSX only

Downloader and Installer for BlackBerry Playbook Android Player Applications

SETTING IT UP
=============

Set a password on your Playbook and turn development mode on. (Settings -> Security -> Development Mode)

You'll want to make sure you have the latest Java Runtime Environment installed on your machine.
	Right now they're at version 1.6 update 25, and you can download the latest for your system here: 
		http://www.oracle.com/technetwork/java/javase/downloads/jre-6u25-download-346243.html


USING THE SCRIPT
================

Change the permissions on bbpa-installer.sh to allow it to execute:

chmod +x bbpa-installer.sh

[INSTANT USE SETUP]
./bbpa-instller -a {IP} -p {PASSWORD} -i {PACKAGE_ID}


[PROPER SETUP]

Edit the file in your favorite text editor 
Enter your IP ADDRESS 
Enter your PASSWORD 

Run the script from terminal
> cd [/path/to/bbpa-installer]
> ./bbpa-installer -i {PACKAGE_ID}

[OPTIONAL] Add it to your aliases to run with a single command

WHAT IT DOES
============
The script performs by referencing the list of Apps listed here:
http://apps.goodereader.com/playbook/playbook-android-apps/

It is a duplicate of 

The script will perform downloads for you should the be available and save them to a folder named `installed` and attempt to install the files onto your device

Note that apps are being downloaded from 

Visit http://bbpa-installer.nexpace.com/ to locate package id's and copy commands to auto-download and install apps to your Playbook















