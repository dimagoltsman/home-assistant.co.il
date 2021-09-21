# home-assistant.co.il one click install

# To install on pi, ssh to rpi and run:
```
sudo curl -s https://raw.githubusercontent.com/dimagoltsman/home-assistant.co.il/main/preInstallScript | sh 
```
this will update the pi to latest version and restart (requered. otherwise docker will fail to install)

after that, ssh to pi again and run:
```
curl -s https://raw.githubusercontent.com/dimagoltsman/home-assistant.co.il/main/install | sh
```


# To install on Ubuntu 20, open terminal or ssh to it and run:

```
wget -O - https://raw.githubusercontent.com/dimagoltsman/home-assistant.co.il/main/installUbuntu | sh
```
