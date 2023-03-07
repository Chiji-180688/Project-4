# Documenting Project 4

`sudo apt update`
`sudo apt upgrade`
`sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates`
[curl -SL](https://deb.nodesource.com/setup_12.x | sudo -E bash -)
`sudo apt install -y nodejs`
![nodejs installation](./Images%204/nodejs%20installation.PNG)
`sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 0C49F3730359A14518585931BC711F9BA15703C6`
`echo "deb [ arch=amd64 ] https://repo.mongodb.org/apt/ubuntu trusty/mongodb-org/3.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.4.list`
![preparing to install mdb](./Images%204/preparing%20to%20install%20mdb2.PNG)
`sudo apt install -y mongodb`
`sudo service mongodb start`
`sudo systemctl status mongodb`
![confirming mdb service](./Images%204/confirming%20that%20mdb%20service%20is%20running.PNG)
`sudo apt install -y npm`
`sudo npm install body-parser`
![installing body-parser](./Images%204/installing%20body-parser.PNG)
`mkdir Books && cd Books`
`npm init`
![npm initialized](./Images%204/npm%20initialized.PNG)
`vi server.js`
`sudo npm install express mongoose`
![express mongoose installation](./Images%204/express%20mongoose%20installation.PNG)
`mkdir apps && cd apps`
`touch routes.js`
`vim routes.js`
`mkdir models && cd models`
`touch book.js`
`vim books.js`
`cd ../..`
`mkdir public && cd public`
`touch script.js`
`vi script.js`
`touch index.html`
`vim index.html`
`cd ..`
`node server.js`
![node server.js running](./Images%204/node%20server.js%20running.PNG)
[curl -S](http://localhost:3300)
![testing local server](./Images%204/testing%20localhost%20server.PNG)
![testing local server2](./Images%204/testing%20localhost%20server2.PNG)
![browser](./Images%204/browser.PNG)
