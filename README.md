#Ruwin-notify
This is a [NodeCG](http://github.com/nodecg/nodecg) bundle.

Notification graphic for [Ruwin's stream](http://twitch.tv/ruwin).
Forked from [lange-notify](github.com/lange/lange-notify)

## Installation
_If you already have NodeCG installed, skip to step #3._






HAHAHAHHAHAHHAHAAAAAAAAAAAAAAAA







1. Install [Node.js & npm](https://nodejs.org/en/).

2. Open a command prompt and run the following commands to install NodeCG.
Keep this command prompt open after NodeCG has been installed.
	```sh
	npm install -g bower
	npm install -g nodecg-cli
	mkdir nodecg
	cd nodecg
	nodecg setup
	```

3. Install lange-notify and three of the bundles that it depends on.
	```sh
	nodecg install drewwww/ruwin-notify
	nodecg install "supportclass/lfg-filter#^3.0.0"
	nodecg install "supportclass/lfg-nucleus#^2.0.0"
	```

4. To listen for subscriptions and resubs, install and configure one of the following:
	- [lfg-sublistener](https://github.com/SupportClass/lfg-sublistener) - **Recommended** Listens directly to Twitch chat.  
		`nodecg install supportclass/lfg-sublistener`
	- [lfg-siphon](https://github.com/SupportClass/lfg-siphon) - Listens to Twitch chat via [Streen](https://github.com/SupportClass/streen).  
		`nodecg install supportclass/lfg-siphon`
  
5. To listen to [StreamTip](https://streamtip.com), install and configure [lfg-streamtip](https://github.com/SupportClass/lfg-streamtip).
	```sh
	nodecg install supportclass/lfg-streamtip
	```

6. Start NodeCG.
	```sh
	nodecg start
	```

### Usage
- Add [`http://localhost:9090/graphics/ruwin-notify`](http://localhost:9090/graphics/ruwin-notify) 
(or whatever your NodeCG hostname and port are) as a Browser Source in OBS, with dimensions of 1920x80
- Use lfg-nucleus' "Notifications" panel on the dashboard ([`http://localhost:9090`](http://localhost:9090)) to send test subs, resubs, and tips.

### Additional Credits
- Sound design by [Anthony "Airon" Oetzmann](http://aironaudio.weebly.com/) 

### License
ruwin-notify is provided under the MIT license, which is available to read in the [LICENSE][] file.
[license]: LICENSE
