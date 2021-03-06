Overview
=========
The following test script can be used to setup an MSE with a predefined venue. Then send a predefined path for a set of clients to the cloud server.
The clients will repeat the path continuously while the test is running. The clients use a sequential MAC address starting from 00:00:00:00:00:00 and incrementing by one.


## Installing the dependencies
###	Node.js
Node.js can be downloaded from http://nodejs.org.

## Running tests
Run the command '**node cmxMseSimTest.js**'

The following are the parameters which will be needed:

+ **userId** - User Id required by cloud server to authenticate user
+ **password** - User password required by cloud server to authenticate user
+ **host** - Host address of the cloud server
+ **numberClients** - Number of clients to simulate

Example: *node cmxMseSimTest.js --numberClients 1000 --userId admin --password cisco --host 172.19.28.10*

There are other options which can be used. To view all the options run the command '**node cmxMseSimTest.js -h**'