# Fancy for TeamSpeak 3
[![Node.js](http://i.imgur.com/J3acu8r.png)](http://nodejs.org)

Fancy is a free, self-hosted, asynchronous bot for TeamSpeak 3.

  - [Installation](#Installation)
  - [Configuration](#Configuration)
  - [Features](#Features)
  - [Permissions](#Permissions)
  - [Commands](#Commands)
  - [License](#License)

### It's as simple as can be
  - Install [node.js]
  - Edit configuration file
  - Upload files to your server
  - Run it
  - Magic!


### Installation
Fancy requires [node.js] v6+ and build tools to run. [Install instructions.]

Install node.js and build tools (example for Ubuntu and Debian)
```sh
$ curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
$ sudo apt-get install -y nodejs build-essential
```
Edit configuration file (default: config/config.yml)
```yaml
connection:
    ip: 127.0.0.1
    server_port: 9987
    query_port: 10011
    login: serveradmin
    password: Z+67aUoi
[...]
```

Upload files to your server

Install the dependencies and start the bot.

```sh
$ cd fancy
$ npm install
$ node fancy.js
```

### Configuration

### Features
| Feature | Description |
|---------|-------------|
|         |             |
|         |             |
|         |             |

### Permissions
| Feature | Permissions |
|----------|:-----------:|
|          |             |
|          |             |
|          |             |

### Commands
| Command | Description | Aliases |
|---------|:-----------:|--------:|
|         |             |         |
|         |             |         |
|         |             |         |

### License
GPL-3.0
You can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.


**Always free. Always fancy.**


   [node.js]: <http://nodejs.org>
   [Install instructions.]: <https://nodejs.org/en/download/package-manager/>
