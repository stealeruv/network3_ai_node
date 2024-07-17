# network3_ai_node
Network3 ai client points mining node guide

# Network3
Network3 builds an AI Layer2 helping AI developers worldwide inference train or validate models widely quickly, conveniently, and efficiently

Website: https://account.network3.ai/register_page?rc=3ac00dd4


X: https://x.com/network3_ai

# Register account

https://account.network3.ai/register_page?rc=3ac00dd4

# Installation Guide for Ubuntu

### 1. Server preparation

```
sudo apt update
sudo apt install wget curl make clang net-tools pkg-config libssl-dev build-essential jq lz4 gcc unzip snapd -y
```


### 2. Download and Extract the tar file
```
cd $HOME
wget https://network3.io/ubuntu-node-v1.1.tar && \
tar -xf ubuntu-node-v1.1.tar && \
rm -rf ubuntu-node-v1.1.tar && \
cd ubuntu-node
```
### 3. Open Screen

```
screen -S n3ai
```
### 4. Start NOde
```
sudo bash manager.sh up
```

### 5 . Deatach from screen

CTRL + A + D

### 6. Get Private Key

```
sudo bash manager.sh key
```

Copy and save this key for Binding process.


### 7. Provides node access to your account 

Trick to enable binding + option

First download the APK file for mobile or exe for windows and run it for 5 mins.

Then,

Open a browser which you signin for network3 and visit: https://account.network3.ai/main?o=xx.xx.xx.xx:8080 

`Replace it With your VPS IP address is xx.xx.xx.xx`

`Port 8080`

Then you could click the '+' button on the top-right of the panel of current node in the dashboard.

Input the private key that you copied from the node in the dialog box to bind. 

Now you can uninstall your apk or exe app on your phone or system.


