# proxy
Execute the python program to setup proxy in ubuntu without the hassle of going to the system and setting up the values

Download the proxy.py file and now run that from your terminal using the following command :
If you use python 2.x
python proxy.py proxyadress proxyport username password
Eg : python proxy.py 172.16.0.1 3128 uem 12345
If you donot need authentication then follow the below
Eg : python proxy.py 172.16.0.1 3128

If you use python 3.x then use the following commands
if you have authentication for your proxy server
python2.7 proxy.py 172.16.0.1 3128 uem 12345
if you donot need authentication
python2.7 proxy.py 172.16.0.1 3128
