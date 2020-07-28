# BonziWORLD

This project has been forked because we want a backup of this.
All the source code for the server and client is publically available here. If you want to run your own BonziWORLD, by all means go ahead. Do whatever you'd like with this code. Just try to put me somewhere in the credits.

## Dependencies
- Node.js and npm
- Ruby
- Sass
- Git
- Cordova (Optional)

## Setup
In a terminal/command prompt, navigate to where you'd like BonziWORLD to be placed and run the following.
**Keep in mind if it does not work, remove the git thing.**
```
git clone https://github.com/Collaty/BonziWORLD
cd BonziWORLD
```

### Client
```
cd src
npm install
grunt build_www
cd ..
```

### Server
```
cd server
npm install
node index.js
```
After this, BonziWORLD will be accessible on port 3000. (http://localhost:3000/)

## Disclaimer
I'm not responsible if you screw up anything with your computer while setting this up. I have no idea how you would, but someone will find a way. I also will not provide support for installing dependencies. If you have everything installed properly, the above commands will work, if its not loading, you should ask HOST.

## License
MIT.
