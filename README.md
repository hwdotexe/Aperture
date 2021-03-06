## Overview
Aperture is a camera management plugin, wherein players can create cameras and view their footage in real-time. Unlike many other camera plugins, Aperture works from anywhere on your server by displaying camera footage in 3D space. Say goodbye to the days of teleport-based cameras!

This plugin was originally a Premium resource of mine on Spigot, and having moved on from plugin development, I recently decided to publish the source code for free.

![image](https://i.imgur.com/jIRlKHv.gif)

## Usage
### Commands
/ap stream [player]  
/ap share  
/ap reload  
/ap getcamera

### Permissions
- aperture.player
  - aperture.stream - Stream from your cameras
  - aperture.share - Share a camera with someone else
  - aperture.break - Break your cameras
  - aperture.place - Place down new cameras
- aperture.admin
  - aperture.stream.other - Stream from other players' cameras
  - aperture.reload - Reload the plugin config
  - aperture.break.other - Break other players' cameras
  - aperture.getcamera - Get a new crafted camera item
  - aperture.bypasslimit - Own as many cameras as you want
  - aperture.camera.*  - Have access to every camera

## Installation (Server)
To use the plugin, simply download a `.jar` binary from the [Releases](https://github.com/hwdotexe/Aperture/releases) page for your server's version. You will also need the applicable version of [ProtocolLib](https://www.spigotmc.org/resources/protocollib.1997/). Place both of these files in your server's `plugins` folder and restart.

## Installation (Development)
If you'd like to install the codebase and make changes, simply follow these instructions:

### Step 1: Clone
In a terminal, use `git clone https://github.com/hwdotexe/Aperture.git`

### Step 2: Import as a Maven Project
This plugin uses Maven as its build system. As such, you'll need to import it using Maven as well. This process varies by IDE, so please seek out their instructions if needed.

### Step 3: Building
When you're ready to compile the plugin locally, you can use `mvn clean package` to generate your `.jar` file. 

## Contributing
If you like this plugin and want to contribute, please do! I welcome any and all Pull Requests from eager developers who want to help out. 
