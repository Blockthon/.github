# Blockthon
Blockthon Python Package for Generate and Converting Wallet Private Key and Mnemonic for Address Bitcoin

#### Install Blockthon On Windows
```bash
# on windows
pip install Blockthon
```

#### Install Blockthon On Linux / Debian:
```shell
sudo apt-get update&&sudo apt-get upgrade -y
sudo apt-get install autoconf automake -y
sudo apt-get install gcc libffi-dev -y
pip3 install Blockthon
```

or for download manual:
```bash
git clone https://github.com/Blockthon/Blockthon
cd Blockthon
make
```


### Generate Private Key (Hex) [Random]:

generated private key hex random with Blockthon in Python very fast for any os:

```python
import Blockthon
PrivateKey = Blockthon.PrivateKey()
``` 

---

## Blockthon / `Python` Example:

---

Generated Compressed Address and Un Compressed Address Wallet Bitcoin From Private Key Hex : example to [ `AddrFromHex_CheckBalance.py` ](https://github.com/Blockthon/Blockthon/blob/main/example/AddrFromHex_CheckBalance.py)

---
### Generated `Compress` and `Un Compress` Bitcoin Wallet Address :

```python
import Blockthon as block
