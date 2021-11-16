## Mining 

- [x] Raspberry pi (tested on 4b and 3) 
- [x] 16GB card   
- [x] SSH  & Wifi (can be set ON via rapsberry pi Manager before flashing arm64 OS) use (control + shift + x) in rapsberry pi Manager when opened 
     (very usefull for non screen & keyboard user)

![This is an image](https://github.com/cryptonobo/MinnigTools/blob/master/istockphoto-1170634914-612x612.jpg)

_Compatible only with 64arm 

link below if needed_

http://downloads.raspberrypi.org/raspios_lite_arm64/images/raspios_lite_arm64-2021-11-08/


**Commands Used to Install the Mining Software (Xmrig) -**

$ sudo apt update

$ sudo apt-get install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev

$ git clone https://github.com/xmrig/xmrig.git

$ mkdir xmrig/build && cd xmrig/build

$ cmake .. 

$ make 


**( be sure to wget from the build folder (in the xmrig folder)!)**

$ wget https://raw.githubusercontent.com/xmrig/xmrig/master/src/config.json


$ sudo nano config.json 

_exemple _

![This is an image](https://github.com/cryptonobo/MinnigTools/blob/master/Screenshot%202021-11-16%20at%2006.45.36.png)
![This is an image](https://github.com/cryptonobo/MinnigTools/blob/master/Screenshot%202021-11-16%20at%2006.45.28.png)

"rx.unmineable.com:3333" for CPU 

"token:YourAddress.YourWorkerName"

("no pass") "x"

------------

**be sure to launch from the build folder (in the xmrig folder)**

$ ./xmrig 


**Enjoy!
**

![This is an image](https://github.com/cryptonobo/Mining-XMRIG-various-coin-/blob/master/Screenshot%202021-11-16%20at%2007.06.49.png)

![This is an image](https://github.com/cryptonobo/Mining-XMRIG-various-coin-/blob/master/Screenshot%202021-11-16%20at%2007.06.55.png)
-------------


**Link :**  of diverse token 

https://unmineable.com/coins

