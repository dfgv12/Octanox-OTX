About Octanox - OTX 
===================
Octanox is decentralized cryptocurrency with x11 algorithm and using POW and POS Systems that are focused on multiple platforms that would be used for virtual economy and virtual activities. Octanox is a revolutionary new way to make transactions online. Our decentralized platform prevents any interference to Octanox, and its source code is publicly available to see. Octanox is a solution to a growing problem, and together we can watch the coin flourish!

Specs:
=====

Coin Name: Octanox
Coin Abbreviation: OTX
Coin Type: Pow-Pos
Hashing Algorithm: X11
Block Time: 120 seconds
Block Reward: variable (from 0.5 OTX to 0.1 OTX)
Year interest: 0.1%
Premine Amount: 25,000,000 OTX
PoW Coins: 25,000,000 OTX
Supply: 50,000,000 OTX
Maximum Supply: up to 100,000,000 OTX with PoS
Maximum Block Size: 2MB
PoS activation: after PoW end


Dynamic Block structure:
========================

1: 25000000 OTX
2-11058118: 0.5 OTX (5529058 coins)
11058119-29591058: 0.4 OTX (7413176 coins)
29591059-45472708: 0.3 OTX (4764495 coins)
45472709-56418018: 0.2 OTX (2189062 coins)
56418019-107460108: 0.1 OTX (5104209 coins)

Ports:
======
RPC PORT 36210 
P2P PORT 36212 

Nodes:
======
45.32.222.147
108.61.215.249
185.69.54.33


Compile Instructions (Ubuntu):
==============================

sudo apt-get update
sudo apt-get install libdb++-dev
sudo apt-get install build-essential
sudo apt-get install libssl-dev
sudo apt-get install libboost-all-dev
sudo apt-get install libqrencode-dev

sudo git clone https://github.com/dfgv12/Octanox-OTX.git Octanox


cd Octanox/src/leveldb
sudo chmod +x build_detect_platform
sudo make clean

sudo make libleveldb.a libmemenv.a

cd ..

mkdir obj

so you will be Ocatnox/src now

sudo make clean -f makefile.unix USE_UPNP=-
sudo make -f makefile.unix USE_UPNP=-



