# Download

to use this firstly install: cd C:\Users\example\downloads
# Extract ZENTRIX_COMPLETE.zip to: C:\Users\example\downloads\zentrix_crypto\
cd zentrix_crypto
pip install -r requirements.txt
pip install flask-cors



Secondly you want to create a wallet using: cd C:\Users\example\downloads\zentrix_crypto
python wallet.py create

Thridly in order to start mining use: cd C:\Users\thata\downloads\zentrix_crypto
python miner.py --node http://localhost:5000 --address "YOUR_ADDRESS_HERE"

IMPORTANT TO VIEW YOUR ADRESS USE: cd C:\Users\example\downloads\ZENTRIX_COMPLETE
python wallet.py address

To check balance use: python wallet.py price --node http://localhost:5000
