#Download des Linux Treibers
Als erstes muss der Treiber herrunter geladen werden.

Link:

http://www.acs.com.hk/download-driver-unified/6258/ACS-Unified-Driver-Lnx-Mac-110-P.zip

#Installation des Treibers

1.als root anmelden

2.Entpacken des Treibers

**tar -jxvf acsccid-x.y.z.tar.bz2**
 
**cd acsccid-x.y.z**

3.benötigte Programme

**apt-get install libusb-1.0.0-dev**

4.installieren

**./configure**


**make**

**make install**
#Starten des Treibers:

**/etc/init.d/pcscd start**