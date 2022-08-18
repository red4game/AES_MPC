# AES_MPC
This repository is a fork of MP-SPDZ with the program in programs/Source/aesLT and the inputs of players in Player-data/

## Installation
On Linux, this requires a working toolchain and [all
requirements](#requirements). On Ubuntu, the following might suffice:
```
sudo apt-get install automake build-essential git libboost-dev libboost-thread-dev libntl-dev libsodium-dev libssl-dev libtool m4 python3 texinfo yasm
```

## Programs 
all programs are in the programs/Source/ directory.

## Player-data
all players datas are in the Player-data/ directory.

## Compilation 

```bash
./compile.py aesLT -lMD
```

## running (with SPDZ2K)

```bash
Scripts/spdz2k.sh aesLT -b 64
``` 