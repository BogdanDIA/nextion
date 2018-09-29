### Project: Nextion HMI
HMI for Nextion displays

**NX4827T043-ND-Dual_HostSpot-5.HMI**   
Dual HotSpot screens for NX4827T043

- it adds TS2 beside TS1
- adds LastHeard page (DMR2)
- requires ON7LDS L3 (needs NextionDriver installed in pi-star)
- lots of fixes and improvements especially when switching between pages
- based ON7LDS single timseslot hotspot
- only DMR has been tested

**How to install**   
There are several ways to install. Here is just one:

- install Nextion Editor https://nextion.itead.cc/resources/download/nextion-editor/
- open .HMI file in the editor
- connect nextion display over serial to your PC. If using USB2serial adapter, PC2102 is recommended
- hit Upload, choose your serial port and go


![alt text][logo]

[logo]: https://github.com/BogdanDIA/nextion/raw/master/last_heard.png "Last Heard with dual TS"

