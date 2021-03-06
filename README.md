
```python

                          ██████╗ ██╗███╗   ██╗ ██████╗ ██╗  ██╗██╗   ██╗ ██████╗ 
                          ██╔══██╗██║████╗  ██║██╔═══██╗██║ ██╔╝╚██╗ ██╔╝██╔═══██╗
                          ██████╔╝██║██╔██╗ ██║██║   ██║█████╔╝  ╚████╔╝ ██║   ██║
                          ██╔═══╝ ██║██║╚██╗██║██║   ██║██╔═██╗   ╚██╔╝  ██║   ██║
                          ██║     ██║██║ ╚████║╚██████╔╝██║  ██╗   ██║   ╚██████╔╝
                          ╚═╝     ╚═╝╚═╝  ╚═══╝ ╚═════╝ ╚═╝  ╚═╝   ╚═╝    ╚═════╝ 
                                 Sends fake probe requests with SSID ınfo                                        
```

<p align="center">
<img src="uploads/pin.png" height="200" width="200"></img>
</p>


### Purpose
+ 🍓🤥🍍If threats like wifi pineapple attacks or karma attacks are active around, users will be informed about these threats. 
+ Fills the SSID pool of WiFi Pineapple device with the SSID informations in pinokyo.txt
+ Generates fake probe requests against KARMA attacks.


### Working Principles

+ Collects probe requests
+ Seperates MAC Addresses from probe requests
+ Creates new probe packets with collected MAC addresses
+ Sends probe requests with pinokyo.txt

<p align="center">
<img src="uploads/pinokyo.png"></img>
</p>

### Screenshots

<img src="uploads/piscreen.jpg" height="%45" width="35%"></img>
<img src="uploads/piscreen2.png" width="35%"></img>

### Tested

+ Wifi Pineapple Mark V
+ KARMA Attack
+ MANA (mana-toolkit) Attack
