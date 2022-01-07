## 5e.tools:Archived

Archived for redundancy

## Installing a local javascript server to host this repo
 - for private use of 5e.tools and any other compatiable content

Node.js is somesort of framework for javascript environments but needs specific utilities depending on what you want to get done.
Use their package manager (npm) instead of pacman but pacman could be used as the servers code we want is available in the AUR (https://github.com/http-party/http-server / https://aur.archlinux.org/packages/nodejs-http-server/).
However the server package needs other dependencies that npm will package up for us. You could find them in the NPM directory and get their github repos...
Just install npm

# sudo pacman -S nodejs
(https://wiki.archlinux.org/title/Node.js)

# sudo pacman -S npm
npm is the package manager for node.js

# sudo npm install --global http-server
(https://www.npmjs.com/package/http-server)

Start the http-server; open a terminal in the folder with the index file
# http-server

go to: http://192.168.0.8:8080 in Chrome

-------------------------------------------------------------------------

You can visit the [main site](https://5e.tools/index.html) or go to the GitHub [mirror](https://github.com/5etools-mirror-1/5etools-mirror-1.github.io) that this repo is (hopefully) in sync with.

You can join the 5etools Discord [here](https://discord.gg/5etools)

## License

This project is licensed under the terms of the MIT license.
