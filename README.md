# MinnigTools


(lscpu -DARM_TARGET=8 or -DARM_TARGET=7)

**Commands Used to Install the Mining Software -**

sudo apt update

sudo apt-get install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev

git clone https://github.com/xmrig/xmrig.git

mkdir xmrig/build && cd xmrig/build

cmake .. 

make 


**( be sure to wget from the build folder (in the xmrig folder)!)**

wget https://raw.githubusercontent.com/xmrig/xmrig/master/src/config.json


sudo nano config .json 

"rx.unmineable.com:3333" for CPU 

"token:YourAddress.YourWorkerName"

("no pass")

------------

**be sure to launch from the build folder (in the xmrig folder)**

sudo ./xmrig 

-------------


**Link :**

https://unmineable.com/coins

