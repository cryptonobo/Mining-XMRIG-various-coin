# MinnigTools
 MinnigTools  BSC/ETH  GFX/CPU

lscpu

Commands Used to Install the Mining Software -

sudo apt-get install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev

git clone https://github.com/xmrig/xmrig.git

mkdir xmrig/build && cd xmrig/build

cmake .. -DARM_TARGET=8 or -DARM_TARGET=7

make -j$(nproc)

wget https://raw.githubusercontent.com/xmrig/xmrig/master/src/config.json



(edit config .json) 

rx.unmineable.com:3333 for CPU 

CAKE:YourAddress.YourWorkerName

no pass

------------

launch from build folder (in xmrig folder)

sudo ./xmrig 

-------------


Link :

https://unmineable.com/coins


0x185d26a5fc664c474523c8ce88798b2b51a8e195
