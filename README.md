# Jenkins pipelines

### Jenkins pipelines for syncing forks with upstream:

| My forks                                                            | Upstream                                             |
| ------------------------------------------------------------------- | ---------------------------------------------------- |
| [Home-assistant](https://github.com/tedsluis/home-assistant)        | https://github.com/home-assistant/home-assistant     |
| [Home-assistant.io](https://github.com/tedsluis/home-assistant.io)  | https://github.com/home-assistant/home-assistant.io  |
| [Sonoff-Tastoma](https://github.com/tedsluis/Sonoff-Tasmota)        | https://github.com/arendst/Sonoff-Tasmota            |
| [Rak8s](https://github.com/tedsluis/rak8s)                          | https://github.com/rak8s/rak8s                       |
| [GassistPi](https://github.com/tedsluis/GassistPi)                  | https://github.com/shivasiddharth/GassistPi          |

### Jenkins build pipelines:

| Source                                                              | Output
| ------------------------------------------------------------------- | ---------------------------------------------------- |
| [Home-assistant](https://github.com/tedsluis/home-assistant)        | https://hub.docker.com/r/tedsluis/home-assistant     |


Install systemd jenkins docker daemon:
```
$ mkdir /home/jenkins
$ wget -O /etc/systemd/system/jenkins.service https://raw.githubusercontent.com/tedsluis/jenkins/master/jenkins.service
$ systemctl enable jenkins.service
$ systemctl start jenkins.service
```
