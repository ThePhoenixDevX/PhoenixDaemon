# Phoenix Daemon

![PhoenixDaemon Logo](https://raw.githubusercontent.com/ThePhoenixDevX/PhoenixDaemon/refs/heads/main/daemon.webp)

<h1 align="center">PhoenixDaemon</h1>
## Overview
Phoenix Daemon is the daemon for the Phoenix Panel.

## Installation
1. Clone the repository:
`git clone https://github.com/ThePhoenixDevX/PhoenixDaemon.git`

2. Install dependencies:
`npm install`

3. Configure PhoenixDaemon:
- Get your Panel's access key from the Phoenix panel's config.json file and set it as 'remoteKey'. Do the same for the other way, set your PhoenixDaemon access key and configure it on the Panel.

4. Start the Daemon:
`node . # or use pm2 to keep it online`

## Configuration
Configuration settings can be adjusted in the `config.json` file. This includes the authentication key for API access.

## Usage
The daemon runs as a background service, interfacing with the Hydra Panel for operational commands and status updates. It is not typically interacted with directly by end-users.

## Contributing
Contributions to enhance the functionality or performance of the Hydra Daemon are encouraged. Please submit pull requests for any enhancements.


## Credits
ThePhoenixDevX
