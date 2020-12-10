<h1 align="center">
    <br>
    <p>Discord BOT Dashboard - v1.0</p>
<h1>
<p align="center">
    <a href="https://github.com/papasnags/Discord-BOT-Dashboard/releases">
        <img alt="GitHub release" src="https://img.shields.io/github/release/PapaSnags/Discord-BOT-Dashboard.svg">
    </a>
</p>

# About
Discord BOT Dashboard is made to make **Discord BOT Development** easy, designed to create applications without having to write a single line of code while using a user freindly Web-Dashboard!

# Dashboard Preview 
<img src="https://i.imgur.com/mcF1WMj.png">


## Requirements
* [Node.JS](https://nodejs.org/en/) (v12.3.1 or later)

## Installation / Setup
#### Installing Requirements
Download the latest version from [Releases](https://github.com/papasnags/Discord-BOT-Dashboard/releases), open up the root directory and run the following command.
```bash
npm install
```

#### Setting up BOT
Open up the config.json file found in the **cfg** folder and input the required fields.
```json
{"token":"token_here","prefix":"prefix_here"}
```

#### Starting the application 
Open up the root directory and run the following command.
```bash
node index.js
```
You should now be able to access the dashboard at **http://localhost:3000**. Goto the Plugins tab and enable what commands you want!


## Upcoming Features
* User Auth (Login to access dashboard). **In Development**
* Ability to change the BOTS profile picture in settings. **Not yet in Development**
* Change BOTS status in settings. **In Development**
* More statistics on main dashboard. **Not yet in Development**
* **Open issues for features you want**

## Commands / Plugins List
### Moderation:
* **Ban** - Bans a user from the server. **Usage:** !ban @user
* **Kick** - Kicks a user from the server. **Usage:** !kick @user
* **Clear** - Clears messages from a channel. **Usage:** !clear 5

### Utilities
* **User Info** - Sends information about a given user. **Usage:** !user-info @user
* **Server Info** - Sends information about the current server. **Usage:** !server-info
* **Stats** - Statistics of the BOT. **Usage:** !stats
* **Help** - Sends a list for all plugins / commands enabled. **Usage:** !help

### Fun
* **Coin Flip** - Flip a coin (heads / tails). **Usage:** !coin
* **Dog** - Sends a random image of a dog. **Usage:** !dog
* **Cat** - Sends a random image of a cat. **Usage:** !cat
* **8-Ball** - Ask the 8-ball a question. **Usage:** !8-ball
* **Roll** - Roles a dice (6-Sided). **Usage:** !roll

### Music
* **Play** - Plays a song. (Youtube Link) **Usage:** !play URL
* **Stop** - Stops currect song playing. **Usage:** !stop
* **Leave** - Disconnects from currecnt VC. **Usage:** !leave

## Contribute
If you would like to contribute to the project please open a PR (Pull Request) clearly showing your changes.

## Issues
If you have any issues feel free to open an issue or join the [Discord Server](https://discord.com/invite/w7B5nKB)

## Extra
__Created by PapaSnags#1555__
* [Website](https://papa-snags.com/projects/PLUG/)
* [Twitter](https://twitter.com/PapaSnags)
* [Instagram](https://www.instagram.com/papa.snags/)
* [Discord Server](https://discord.com/invite/w7B5nKB)
</br>

