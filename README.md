# OpenFuckV2.c Exploit  

Apache mod_ssl < 2.8.7 OpenSSL - 'OpenFuckV2.c' working exploit. 

The original copy can be found [here](https://www.exploit-db.com/exploits/47080)  

In the code following modification has been done : [Link](https://hypn.za.net/blog/2017/08/27/compiling-exploit-764-c-in-2017/)  

## Compilation 

First install libssl-dev in your machine.  

```shell   
sudo apt install libssl-dev
```  

Compile the code  

```shell  
gcc OpenFuckV2.c -o OpenFuckV2 -lcrypto
``` 
