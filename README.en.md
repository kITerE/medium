<img align="left" src="https://i.imgur.com/RkjJPEr.png" width="100px">
<br/><br/><br/><br/>

Independent decentralized ISP for our friends

## I am a user
To connect to the already existing Medium node, you need to [select your city](https://github.com/medium-isp/medium/tree/master/ru) and find the operator nearest you.

To connect, you need to create a new connection with the following parameters: SSID - «Medium» (without quotes), authentication type — without password.

Be careful: the Medium network by default is hidden from prying eyes; in the list of available networks, it will not be displayed until you create a new connection with the above parameters.

To test the network, try visiting the [medium.i2p](http://medium.i2p/?i2paddresshelper=dLJzgrK601vSbtNZGQ~R8V0ruRsdeG35gaIdH0RkXzoFioASVww8YociZfrgLsnHmKmMfA46fFv6goHkWYLMcWCDqoNc1X1bUzJwNxGHDcJJ1svKCuMGJDm5Ve~UMkdqEWofeT4tc4F14dJE48ff10jM4Y3Zc1tJCBuXKwtwa~mAdSacDlowXABP3kQ76kpMqQZ6dAithyAi53u-USvTmpK0Lc4uvZsWQL32m~qGMEiNrrlAhHZY2ttPbPUq8ig1bhEoBkN9CEYDdEgH3mw9CNmIhUrQThD9Hp~Wlsvd1x0815U-DDPqQvbwj2KgVRRt4z0uvZ-Ol0gpJwSgXfovVmuGj-PjbzFlfe-oGB-hQWEM~rTvIGdoS09nyWZtzzEQMnOwxv72fEM7HVQbMzSQ3B2UMHDWcXaY~lmQNnXcvNPMZiWA9Qt0ogUdWzDMyz1OvK5hsUPOLEYJMQ7GS272Mx3E6fqGct2EJ20IDIY8MfMVvCzYOK58lvTqeEsAz-fRBQAEAAcAAA==) page after connecting.

## I am an operator
To raise your Medium network node, you need the following things:
* Internet access
* Free router
* Free time and enthusiasm

### Step 1. Connecting to the I2P network
First of all, you need to connect to the I2P network. You can do this with [i2pd](https://github.com/PurpleI2P/i2pd/wiki/Using-i2pd).

### Step 2. Sharing the connection
After the connection is made, you need to configure your wireless router so that all traffic goes through a proxy located on the server where the i2pd service was raised. It is assumed that it is deployed in the local home network. For example, 192.168.0.1:4444.

Pay special attention to the fact that for authenticity the network should have the following parameters: SSID — Medium, no password, the network is hidden.

### Step 3. Block traffic
Depending on the model of your router, deny any traffic that somehow relates to the external Internet.

### Step 4. Adding a point to the public list
After completing the configuration of your access point and testing its operation, you can add it to [public list](https://github.com/medium-isp/medium/blob/master/CONTRIBUTING.md).
