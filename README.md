# Jenkins pipelines

My Jenkins pipelines for:

* Syncing my [Home-assistant](https://github.com/tedsluis/home-assistant) fork with upstream: https://github.com/home-assistant/home-assistant
* Syncing my [Home-assistant.io](https://github.com/tedsluis/home-assistant.io) fork with upstream: https://github.com/home-assistant/home-assistant.io
* Syncing my [Sonoff-Tastoma](https://github.com/tedsluis/Sonoff-Tasmota) fork with upstream: https://github.com/arendst/Sonoff-Tasmota
* Syncing my [Rak8s](https://github.com/tedsluis/rak8s) fork with upstream: https://github.com/rak8s/rak8s
* Syncing my [GassistPi](https://github.com/tedsluis/GassistPi) fork with upstream: https://github.com/shivasiddharth/GassistPi
* Add, commit and push my local jenkins config to this repo. 

Install systemd jenkins docker daemon:
```
$ mkdir /home/jenkins
$ wget -O /etc/systemd/system/jenkins.service https://raw.githubusercontent.com/tedsluis/jenkins/master/jenkins.service
$ systemctl enable jenkins.service
$ systemctl start jenkins.service
```
