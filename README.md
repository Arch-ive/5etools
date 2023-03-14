## 5e.tools:Archived

Recorded and Stored

## Running a local javascript server to host this repo
- for private use of 5e.tools and any other compatiable content

Node.js is a javascript runtime environment. It needs specific utilities depending on how the content you're trying to run is built.
Npm is the package manager and tool for nodejs which has utility we can't get out of pacman. Pacman could be used to retrieve dependancies we need that should be available in the AUR eg https://github.com/http-party/http-server & https://aur.archlinux.org/packages/nodejs-http-server/.
However installing dependencies the developer has specified with npm will package up for us with the npm install command. I assume you could find required packages in the NPM directory and get their github repos...
Just install npm alongside nodejs

# Installation
- sudo pacman -S nodejs
(https://wiki.archlinux.org/title/Node.js)

- sudo pacman -S npm
(npm is the package manager for node.js)

- sudo npm install --global http-server
(https://www.npmjs.com/package/http-server)

# Running the server

To start the http-server; open a terminal in the root folder and run the script listed in the package.json file
- npm run server

This runs the following: "http-server -c-1 --cors --port 5000 -o"

The server will push the site open in an applicable browser and/or you can manually go to http://localhost:5000/ in the browser of your choice.

## License

