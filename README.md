# Epson L3160 Ink Waste Resetter

This python script resets the ink waste counter of the printer Epson L3160.
It uses [Easy SNMP](https://easysnmp.readthedocs.io/en/latest/) which might be tricky to install, therefore also is included a Dockerfile to build an image with all dependencies. Probably compatible with L3166 and L3168. Try at your own risk.

## How to use it
To use this script the printer must be connected by Wi-Fi. 

```
### Run

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python resetter.py <PRINTER_IP>
```
