supportRTC
==========

This repo is the code for [this tutorial](http://blog.voxbone.com/voxbone-crm-bot/) on how to build a Twitter Support Line Bot

It is a Nodejs app built with WebRTC to create a support hotline straight from a user's browser. The app is available here: [http://voxbone-click2call.rhcloud.com/support](http://voxbone-click2call.rhcloud.com/support)

To install:

######1. Install the dependencies

```
    npm install
```

######2. Change your credentials in config.js

```
    default_username: 'your_username',
    default_secret: 'your_webrtc_secret_key'
```
######3. Start th MongoDB

```
    cd NAME_OF_DIRECTORY
    mongod
```    
######4. Start the application

```
    npm start
```    

######5. Access it via [http://localhost:3000/support](http://localhost:3000/support)
