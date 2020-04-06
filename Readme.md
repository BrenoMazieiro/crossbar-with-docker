# Information

This repository is a example showing how to use crossbar with docker and docker-compose

# Install instructions 

## 1 - Build nodejs images
`docker build -t nodejs-serve registry/nodejs-serve`

## 2 - Update /etc/hosts

```
127.0.0.1   emitter.local.crossbar.com 
127.0.0.1   receiver.local.crossbar.com 
127.0.0.1   emitter.local.crossbar.com 
127.0.0.1   crossbar.local.crossbar.com 
```

## 3 - Start containers
`docker-compose up`

## 4 acess links

### Go to your browser and access:

```
Emitter:  http://emitter.local.crossbar.com
Receiver: http://receiver.local.crossbar.com
```
