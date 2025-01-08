# Ubuntu 24.04 webcam Apple Inc. MacBookAir7,2 2015
Ubuntu 24.04 How to enable webcam facetime hd on macbook air  Apple Inc. MacBookAir7,2 2015

Create temporary directory  
```
mkdir /home/someone/tmp
cd /home/someone/tmp
```
Clone the repo
```
git clone https://github.com/patjak/facetimehd-firmware.git
```
Compile the source
```
cd facetimehd-firmware
make
sudo make install
sudo depmod
sudo modprobe -D facetimehd
```
reboot ubuntu
