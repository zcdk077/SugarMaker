# SUGARMAKER
Original Script : https://github.com/decryp2kanon/sugarmaker

# ANDROID SMARTPHONE

## Bahan-Bahan Mining
1. <a href=https://moneyblink.com/UhQzhTymk>Termux</a>
2. <a href=https://moneyblink.com/7kzerY1eXJx1>AutoStart Manager</a> <br><br>

A. TUTORIAL TERMUX

## [ Install update & upgrade ]

```
yes | pkg update && pkg upgrade -y
```

## [ Install libs]

```
yes | pkg install wget curl proot tar nano
```

## [ Autorun Ubuntu ]

```
cd ..
nano ../usr/etc/bash.bashrc
```

## [ Copy dan paste dibaris paling bawah ]

```
termux-wake-lock
clear
cd ubuntu/&&./start-ubuntu20.sh
```

## [ Install Ubuntu 20 ]

```
mkdir ubuntu && cd ubuntu
wget https://raw.githubusercontent.com/AndronixApp/AndronixOrigin/master/Installer/Ubuntu20/ubuntu20.sh -O ubuntu20.sh && chmod +x ubuntu20.sh && bash ubuntu20.sh && ./start-ubuntu20.sh
```

B. TUTORIAL UBUNTU

## [ Install update & upgrade ]

```
yes | apt-get update && apt-get upgrade -y
```

## [ Install libs ]

```
apt-get install clang git build-essential libcurl4-openssl-dev autotools-dev automake libtool nano
```

## [ Clone & Install SugarMaker ]
```
git clone https://github.com/zcdk077/sugarmaker
```
```
cd sugarmaker
```
```
./autogen.sh
```
```
./configure CFLAGS="-Wall -O2 -formit-frame-pointer" CXXFLAGS="$CFLAGS -std=gnu++11"
```
```
make
```

## [ Edit Wallet ]
```
nano start.sh
```

## [ Start SugarMaker ]
```
./start.sh
```

## [ Autorun Mining ]

```
nano ~/bashrc
```

## [ Copy dan paste dibaris paling bawah ]

```
cd sugarmaker/&&./start.sh
```

Jika tidak mengerti tentang autorun bisa melewati langkah ## [ Autorun Ubuntu ] dan [ Autorun Mining ]
