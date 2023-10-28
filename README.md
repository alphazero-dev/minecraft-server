# Minecraft Server

This is a Minecraft server that uses PaperMC, GeyserMC and Floodgate to provide a fast, secure and cross-platform gaming experience.

## PaperMC

PaperMC is a Minecraft server software based on Spigot, designed to greatly improve performance and offer more advanced features and API. PaperMC is compatible with any modern Minecraft version and can be installed either as a plugin or ran as a standalone program.

## GeyserMC

GeyserMC is a bridge between Minecraft: Bedrock Edition and Minecraft: Java Edition, allowing Bedrock clients to join Java servers. GeyserMC translates the data from the Bedrock client into a format the Java server understands and vice versa.

## Floodgate

Floodgate is a hybrid mode plugin that allows Xbox Live authenticated Bedrock clients to securely join online-mode Java servers without needing a Java account. Floodgate works with GeyserMC and can be installed either as a plugin or ran as a standalone program.

## Installation

To install this Minecraft server, you need to follow these steps:

1. Clone this repository using `git clone https://github.com/alphazero-dev/minecraft-server`
2. Run the PaperMC jar file with `java -jar paper.jar`.
3. Edit the config files of PaperMC, GeyserMC and Floodgate according to your preferences. You can find more information on how to configure them on their respective websites or wikis.

## Usage

To use this Minecraft server, you need to do the following:

- If you are playing on Java Edition, you can join the server by adding it to your server list with its IP address and port.
- If you are playing on Bedrock Edition, you can join the server by adding it to your server list with its IP address (you public local IP if you are running it locally) and port `25565` (or any other port that you have configured for GeyserMC).
- If you are playing on Bedrock Edition with an Xbox Live account, you can join the server without needing a Java account thanks to Floodgate.

## Features

This Minecraft server has some features that make it unique and enjoyable:

- It supports cross-play between Java and Bedrock players, allowing for true cross-platform gaming.
- It has improved performance and stability compared to vanilla or Spigot servers, thanks to PaperMC's optimizations and enhancements.
- It has security and compatibility features, thanks to GeyserMC's translation layer and Floodgate's hybrid mode.
