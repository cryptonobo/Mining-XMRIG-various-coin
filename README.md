# MinnigTools
 MinnigTools  BSC/ETH  GFX/CPU

Commands Used to Install the Mining Software -

sudo apt-get install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev

git clone https://github.com/xmrig/xmrig.git

mkdir xmrig/build && cd xmrig/build

cmake ..

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



