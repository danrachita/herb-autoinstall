# Autoinstall HERB

Open up an SSH client (Putty) then Register & Log in to your VPS as root. Ubuntu(16.04) VPS is recommended.
```
wget https://raw.githubusercontent.com/danrachita/herb-autoinstall/autoinstall.sh 
```
```
chmod 755 autoinstall.sh
```
```
./autoinstall.sh
```
Autosetup script will ask for MN_GENKEY

WIN WALLET

Send 10000 HERB to the MN_ADDRESS

Open Debug console.

In the debug console command box enter the:

```
masternode genkey
```
```
masternode outputs
```


Edit masternode.conf file.

Find your masternode.conf file:

c:\Users\username\AppData\Roaming\HERB (windows)

Open masternode.conf with Notepad

Format your masternode information:

MASTERNODE_ALIAS_NAME VPS_IP:13555 MN_GENKEY TX_ID TX_INDEX
