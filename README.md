<br/>
<img align="left" src="https://i.imgur.com/jwwzAxj.png" width="100px">
<br/><br/><br/><br/>

[README in English](README.en.md) • [README на русском](README.ru.md)

<h2>What is «Medium»?</h2>
The «Medium» project was initially thought of as a <a href="https://en.wikipedia.org/wiki/Mesh_networking">Mesh-network</a> in the <a href="https://en.wikipedia.org/wiki/Kolomna">Kolomna city</a>, however after some time it became obvious that there just aren't enough people to turn this concept into a real thing.
<br><br>
For this reason, after some time «Medium» became an independent and free Yggdrasil network provider — enthusiasts set up their own access points in a way that after connecting to them it would be able to use Yggdrasil resources.
<br><br>
From a security point of view this method has some fundamental downsides — for example, it is possible to freely sniff the traffic between the user and the router that he is connected to at the moment. It's worth mentioning that <a href="https://en.wikipedia.org/wiki/Tor_(anonymity_network)">Tor</a> has a similar problem — but in Tor's case, it's the <a href="https://hackertarget.com/tor-exit-node-visualization/">exit nodes</a>.
<br><br>
This problem can be handled using <a href="https://en.wikipedia.org/wiki/Transport_Layer_Security">TLS</a>, <a href="https://en.wikipedia.org/wiki/Secure_Sockets_Layer">SSL</a>, <a href="https://en.wikipedia.org/wiki/HTTPS">HTTPS</a> <a href="https://en.wikipedia.org/wiki/Cryptographic_protocol">etc.</a> — that's enough to feel confident about using the network's resources. And, of course, let's not forget <a href="https://en.wikipedia.org/wiki/Pretty_Good_Privacy">PGP</a> and asymmetric cryptography when exchanging messages.
<br><br>
From legal point of view (in accordance with <a href="www.consultant.ru/document/cons_doc_LAW_162586/">Federal law № 97-FZ from May 5, 2014</a>), «Medium», located on territory of Russian Federation, may partially get under restrictions imposed by law. But keep following nuances in mind:
<br><br>
<ol><li>«Medium» is not a legal entity; every member is an autonomous ISP with the same name;</li>
	<li>«Medium» access points may be open (not password protected by default), but hidden: person without knowing the network name will not be able to connect to it;</li>
	<li>«Medium» allows access to an Yggdrasil network, not to the Internet (though there is a possibility of exiting to the Web through outproxy — at the will of current «Medium» operator; for this reason «Medium» can be easily called ISP).</li></ol>
<h2>What is «Medium» designed for?</h2>
We believe that the Internet should be politically neutral and free — the principles that the World Wide Web is built on don't stand a chance for criticizm. <a href="https://www.vanityfair.com/news/2018/07/the-man-who-created-the-world-wide-web-has-some-regrets">They are obsolete</a>. <a href="https://lifehacker.com/its-no-surprise-anymore-your-data-is-never-safe-onlin-1471858210">They are unsafe</a>. We live in the Legacy. Any decentralized network is compromised by default — and this is one of those reasons that we create «Medium» for. 
<br><br>
We believe that privacy is one of those basic things necessary for quiet and peaceful human life.
<br><br>
We believe that every person has the right for privacy and integrity of his personal data.
<br><br>
We believe that «Medium» will be able to help Yggdrasil network grow up — with each «Medium» access point a new Yggdrasil node appears.
<h2>How is «Medium» built?</h2>
The essence of decentralized «Medium» ISP is to give the end user possibility of using Yggdrasil network resources without directly paying for internet traffic.
<br><br>
The concept of «Medium» ISP is prosaic enough — many interested people set up their wireless points with access to Yggdrasil network without direct internet connection possibility by default (outproxy usage isn't forbidden, but isn't welcome too: «Medium» must contribute to the growth of transit nodes and sites in Yggdrasil network). Infrastructure deployment is free of charge — it's all pure enthusiasm.
<br><br>
And also on the ease of user's connection to the network: Wi-Fi connection availability isn't anything supernatural for an ordinary user now.
<h2>From where can be «Medium» accessed?</h2>
On current state of development «Medium» has several access points in <a href="https://github.com/medium-isp/medium/tree/master/index/ru/50/kolomna">Kolomna</a>, <a href="https://github.com/medium-isp/medium/tree/master/index/ru/50/ozyory">Ozyory</a>, <a href="https://github.com/medium-isp/medium/tree/master/index/ru/72/tyumen">Tyumen</a>, <a href="https://github.com/medium-isp/medium/tree/master/index/ru/63/samara">Samara</a>, <a href="https://github.com/medium-isp/medium/tree/master/index/ru/86/hanty-mansiysk">Hanty-Mansiysk</a>, and one in <a href="https://github.com/medium-isp/medium/tree/master/index/lv/01/riga">Riga</a>.
<br><br>
We hope for community's active contribution to the growth of «Medium» — the instructions for setting up your authentic point can be found <a href="https://github.com/medium-isp/medium/blob/master/README.en.md#%D1%8F--%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80">here</a>. You can also issue a pull request for adding your access point in the public list of all the network points.
<h2>I want to volunteer! What do I have to do?</h2>
Set your <a href="https://github.com/medium-isp/medium/blob/master/README.en.md#%D1%8F--%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80">access point</a> up and join the <a href="https://github.com/medium-isp/medium/issues/1">project discussion</a>. In this branch, the most significant nuances of «Medium»'s long-term development are discussed.
<br><br>
If you are an operator of an active «Medium» access point already, then don't forget to <a href="https://github.com/medium-isp/medium/pulls">issue a PR</a> to add your point to the public list of all the access points. <a href="https://github.com/medium-isp/medium/blob/master/CONTRIBUTING.md">Here</a> you can find useful info about how to issue a PR.
<br><br>
<a href="https://github.com/medium-isp/medium/wiki">Wiki</a> • <a href="https://github.com/medium-isp/medium-dns/blob/master/README.md">List of available services</a> • <a href="https://github.com/medium-isp/medium-dns">Register domain</a> • <a href="https://github.com/medium-isp/medium-pki">Certification authority</a> • <a href="https://github.com/medium-isp/medium/blob/master/README.en.md">AP setup guide</a> • <a href="https://github.com/medium-isp/medium/blob/master/CONTRIBUTING.md">Add your AP to the public list</a>
