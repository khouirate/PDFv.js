## PDFv.js project installation guide

You just cloned PDFv.js : git clone https://github.com/LCluber/PDFv.js.git

### Install nodejs on your server :
  - Windows and OSX : **https://nodejs.org/en/**
  - Linux : run
    - **curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -**
    - **sudo apt-get install -y nodejs**


### Install grunt :
  - Run **npm update -g npm** to update npm
  - Run **npm install -g grunt-cli**


### Install typescript :
  - Run **npm install -g typescript**


### Install project dependencies
  - Run **npm install** in your project directory


### Workflow
  - Run **grunt** to serve the website. (http://localhost:3000/)
  - Run **grunt build** to build the library and serve the website.
  - Use **grunt --help** to see the list of tasks.

  - Set node environment if needed :
    - Run **export NODE_ENV=development**
    - Or **export NODE_ENV=production**
