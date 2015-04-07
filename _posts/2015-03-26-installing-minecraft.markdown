---
layout: post
title:  "Installing Minecraft"
date:   2015-03-26
categories: games minecraft
---
Minecraft client software can be downloaded from http://minecraft.net

CanaryMod minecraft server can be downloaded and installed as follows:

- create a folder for the server
- download CanaryMod.jar from http://canarymod.net/releases
- rename the file to CanaryMod.jar if necessary

Run the server with the commands:

- $ cd "$( dirname "$0" )"
- $ java -Xmx1024M -jar CanaryMod.jar
(see Andy Hunt's start_minecraft script)

Grant yourself operator privileges:

 '> op MyName

The Minecraft server can be stopped with the >stop commands

Server will be available from server address localhost.