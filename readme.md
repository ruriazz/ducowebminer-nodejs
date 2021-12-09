# Duino Coin Web Miner
### Installation

```sh
git clone https://github.com/ruriazz/ducowebminer-nodejs.git
```

### Configuration

Set your duino coin wallet at app.js
````
const username = "DUCOWALLET";
````

### Test

```sh
cd ducowebminer-nodejs
npm install
node app.js
```

### Background work with pm2
````sh
cd ducowebminer-nodejs
npm install
pm2 start app.js
````

### pm2 live monitor
````sh
pm2 monit
````