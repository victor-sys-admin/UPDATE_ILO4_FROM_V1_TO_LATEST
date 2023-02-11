# UPDATE_ILO4_FROM_V1_TO_LATEST

## 1 - SET UP THE SERVER

In order to connect to your ILO you need to set-up your ILO IP and create an 
user.

When your server boot wait till the server show us the key to press to 
configure the ILO it should be `F8`.

Go to network select TCP/IP set an IP 
exemple :
```
IP : 10.0.0.1
Mask : 255.0.0.0
Gateway : 10.0.0.2 (it will be your pc)
```

Then got to user, create an user.

## 2 - CONNECT TO ILO

Connect your pc directly to the ILO port.

Set up your pc to be on the same network :
```
IP : 10.0.0.2
Mask : 255.0.0.0
Gateway : 10.0.0.1 (it's your server ILO)
```

Now go on your favorite web browser and open a new tab with the ip of your ILO 
(here `10.0.0.1`).

If your ilo version is too old the UI of the website will not load proprely. 
You will need to download an old version of a browser. On this repo you can 
find a version of firefox compatible with old ILO.

You can also find it here : 
```
https://ftp.mozilla.org/pub/firefox/releases/10.0.1/mac/en-US/
```

## 3 - UPDATE YOUR ILO

You will find on this repo the version 2.81 of ILO 4 from 7 sept. 2022.

You can find it here :
```
https://support.hpe.com/connect/s/softwaredetails?language=fr&softwareId=MTX_47590c9ba0974132ba3946e21d
```

Download the update file, if you download from the site you will need to unpack 
the archive and use the file ilo4_VERSION.bin

Now on the ILO search were to upload your update.
