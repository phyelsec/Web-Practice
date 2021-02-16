### Installing Node.js
wget https://nodejs.org/dist/v14.15.5/node-v14.15.5-linux-x64.tar.xz
sudo tar -C /usr/local --strip-components 1 -xzf node-v14.15.5-linux-x64.tar.gz
#To verify our installation:
node --version
Once it is installed the package.json appears.

### Installling Express.js
Located at this folder, type: npm install --save express
After installation, the file package-lock.json will be generated. This file package.lock.json
is automatically generated for any operations where npm modifies either the node_modules tree, or package.json.

### Run the server
At console type in node server.js
For stopping just type Ctrl+C
Basically we're serving static content using Express.js.


