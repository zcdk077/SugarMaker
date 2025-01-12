# SUGARMAKER
<a href=https://moneyblink.com/ABVz5>Original Script</a>

# ANDROID SMARTPHONE

## Bahan-Bahan Mining
1. <a href=https://moneyblink.com/UhQzhTymk>Termux</a>
2. <a href=https://moneyblink.com/7kzerY1eXJx1>AutoStart Manager</a> <br><br>

A. TUTORIAL TERMUX

## [ Install Update & Upgrade ]

```
yes | pkg update && pkg upgrade -y
```

## [ Install Builds ]

```
yes | pkg install wget curl proot tar nano
```

## [ Autorun Ubuntu ]

```
nano ../usr/etc/bash.bashrc
```

## [ Copy dan paste dibaris paling bawah ]

```
termux-wake-lock
clear
./start-ubuntu.sh
```

## [ Install Ubuntu ]

```
wget https://raw.githubusercontent.com/AndronixApp/AndronixOrigin/master/Installer/Ubuntu/ubuntu.sh -O ubuntu.sh && chmod +x ubuntu.sh && bash ubuntu.sh && ./start-ubuntu.sh
```

B. TUTORIAL UBUNTU

## [ Install Update & Upgrade ]

```
yes | apt-get update && apt-get upgrade -y
```

## [ Install Builds ]

```
apt-get install clang git build-essential libcurl4-openssl-dev autotools-dev automake libtool nano
```

## [ Clone & Install SugarMaker ]
```
git clone https://github.com/zcdk077/sugarmaker && cd sugarmaker && chmod +x start.sh && ./autogen.sh && ./configure CFLAGS="-Wall -O2 -fomit-frame-pointer" CXXFLAGS="$CFLAGS -std=gnu++11" && make
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
cd .. && nano ../etc/bash.bashrc
```

## [ Copy dan paste dibaris paling bawah ]

```
clear
cd sugarmaker/&&./start.sh
```

Jika tidak mengerti tentang autorun bisa melewati langkah ## [ Autorun Ubuntu ] dan [ Autorun Mining ]
