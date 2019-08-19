<img align="left" src="https://i.imgur.com/jwwzAxj.png" width="100px">
<br/><br/><br/><br/>

Independent decentralized ISP for our friends

## I am a user
To connect to the already existing Medium node, you need to [select your city](https://github.com/medium-isp/medium/tree/master/index) and find the operator nearest you.

To connect, you need to create a new connection with the following parameters: SSID - «Medium» (without quotes), authentication type — without password.

Be careful: the Medium network by default is hidden from prying eyes; in the list of available networks, it will not be displayed until you create a new connection with the above parameters.

To test the network, try visiting the [medium.isp](http://medium.isp/) page after connecting.

## I am an operator
To raise your Medium network node, you need the following things:
* Internet access
* Free router
* Free time and enthusiasm

### Step 1. Connecting to the Yggdrasil network
First of all, you need to connect to the Yggdrasil network. You can do this with [yggdrasil-go](https://github.com/yggdrasil-network/yggdrasil-go) client.

### Step 2. Sharing the connection
After the connection is made, you need to configure your wireless router so that all traffic goes through a proxy located on the server where the Yggdrasil instance was raised. It is assumed that it is deployed in the local home network.

Pay special attention to the fact that for authenticity the network should have the following parameters: SSID — Medium, no password, the network is hidden.

### Step 3. Block traffic
Depending on the model of your router, deny any traffic that somehow relates to the external Internet.

### Step 4. Adding a point to the public list
After completing the configuration of your access point and testing its operation, you can add it to [public list](https://github.com/medium-isp/medium/blob/master/CONTRIBUTING.md).
