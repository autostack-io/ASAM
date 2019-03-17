# api-manager

## Install and Build

Clone the repository:
```
git clone https://github.com/autostack-io/api-manager.git
git submodule init && git submodule update
```

Run this commands on `api-manager-client` folder:
```
cd api-manager-client
npm install && npm run build
```

Go back to the previous directory
```
cd ..
```

Run this commands on `api-manager-server` folder:
```
cd api-manager-server
npm install && npm run build
```