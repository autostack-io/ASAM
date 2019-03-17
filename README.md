# ASAM

## About

### What's ASAM
ASAM is an API management developed by Autostack Community.

> API management is the process of creating and publishing web APIs, enforcing their usage policies, controlling access, nurturing the subscriber community, collecting and analyzing usage statistics, and reporting on performance. API Management components provide mechanisms and tools to support developer and subscriber community. [Wikipedia](https://en.wikipedia.org/wiki/API_management).

### Features
- API Gateway
- Load Balancer
- Access Control

## Install and Build
Clone the repository and submodules:
```sh
$ git clone https://github.com/autostack-io/api-manager.git
$ cd api-manager
$ git submodule init && git submodule update
```
Run this commands on `client` folder:
```sh
$ cd client
$ npm install && npm run build
```
Go back to the previous directory
```sh
$ cd ..
```
Run this commands on `server` folder:
```sh
$ cd server
$ npm install && npm run build
```