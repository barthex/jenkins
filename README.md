# jenkins

My Jenkins pipelines for:

* syncing my [Home-assistant](https://github.com/tedsluis/home-assistant) & [Home-assistant.io](https://github.com/tedsluis/home-assistant.io) fork with upstream: 
** https://github.com/home-assistant/home-assistant
** https://github.com/home-assistant/home-assistant.io
* syncing my [Sonoff-Tastoma](https://github.com/tedsluis/Sonoff-Tasmota) fork with upstream: https://github.com/arendst/Sonoff-Tasmota
* syncing my [Rak8s](https://github.com/tedsluis/rak8s) fork with upstream: https://github.com/rak8s/rak8s
* syncing my [GassistPi](https://github.com/tedsluis/GassistPi) fork with upstream: https://github.com/shivasiddharth/GassistPi
* add, commit and push my local jenkins config to this repo. 

Install systemd jenkins docker daemon
```
$ mkdir /home/jenkins
$ wget -O /etc/systemd/system/jenkins.service https://raw.githubusercontent.com/tedsluis/jenkins/master/jenkins.service
$ systemctl enable jenkins.service
$ systemctl start jenkins.service
```
