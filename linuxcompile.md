Simple steps to get Linux GUI 

1. Open Putty Terminal and log in to your VPS
2. Copy and paste code below into PUTTY TERMINAL 

apt-get update && apt-get -y upgrade && apt-get -y install libwww-perl build-essential libtool automake autotools-dev autoconf pkg-config libssl-dev libgmp3-dev libevent-dev bsdmainutils libdb++-dev libminiupnpc-dev libboost-all-dev libqrencode-dev unzip && fallocate -l 4G /swapfile && chmod 600 /swapfile && mkswap /swapfile && swapon /swapfile && echo "vm.swappiness=10" >> /etc/sysctl.conf && echo "/swapfile none swap sw 0 0" >> /etc/fstab

4. go to GCFORK folder 

cd dev/GCFORK

5. RUN 

qmake (then when thats done run)

make

6. Onced its finished go to the GCFORK folder and you will see PearlaCoin-QT (move to desktop and open )


