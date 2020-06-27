Check Detailed documenttaon here (https://github.com/srix/konsole-varwidth/wiki)

# Build instructions
snapcraft

#sudo snap install konsole_17.12.3_amd64.snap --devmode --dangerous

sudo snap install konsole-vw_17.12.3_amd64.snap --devmode --dangerous

snap remove konsole

# Run
#snap run konsole

snap run konsole-vw.konsole

ssh user@127.0.0.1

export DISPLAY=:0
