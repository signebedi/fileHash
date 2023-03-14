# fileHash
get file hashes


#### Installation

Run the following as root:

```bash
cd /opt
git clone https://github.com/signebedi/fileHash.git
cd fileHash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
chmod 770 /opt/fileHash/gethash
```

Optionally, add it to your path by adding the following line to bashrc:

```bash
export PATH=$PATH:/opt/fileHash/
```
