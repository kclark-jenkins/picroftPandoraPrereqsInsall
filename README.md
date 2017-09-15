# picroftPandoraPrereqsInsall
Installs all the required software to get the Pandora skill for mycroft working on PiCroft v.08b.

# Disclaimer
This does *NOT* mean the pandora skill will work, that is up to that skills developer.  This script simply installs the latest version of painobar and all it's pre-reqs so it will work on the PiCroft 0.8b image as a standalone application.  This should mean the pandora skill will work after running this, but again that is up to the skills developer.

# Instructions

```
sudo su
cd /usr/local/src
git clone https://github.com/kclark-jenkins/picroftPandoraPrereqsInsall.git
cd picroftPandoraPrereqsInstall
chmod +x ./picroftPandoraPrereqsInstall.sh
./picroftPandoraPrereqsInstall.sh
```

Then follow the pianobar configuration instructions
