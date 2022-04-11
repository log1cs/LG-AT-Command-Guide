### List of AT commands for LG Android-powered devices ###

### Proceed with caution, also there is a few notice for you before doing this! ###
 + These commands can be sent using any tool that supports sending AT commands e.g putty, etc...)
 
 + There's no guarantees that these commands will work on your LG device (i mean it does work, but not on all devices)

 + If you find any other command and you want to contribute to this repository, just make a Pull Request with proper description (this command will do etc etc, and the command) in this format:
```bash
### Description ###
```bash
your command goes here
```

### How to connect to the Modem Port ###
+ Download [PuTTY](https://www.putty.org/)
+ Remember to install [LGE AndroidNet USB Driver 4.8.0](https://www.lg.com/us/support/help-library/lg-mobile-drivers-and-software-CT10000026-20150179827560)

WARNING: WINDOWS 7 USERS SHOULD USE 4.5.0 VERSION OF LGE ANDROIDNET USB DRIVER! (else it won't work, in some cases)
+ Open Device Manager, expand the Modem section
+ Find "LGE AndroidNet USB Modem" then right click, find the COM Port (it should be COMx) (x here is integer)
+ Go to PuTTY, press COM, type your COM Port then press Connect
+ Enjoy! 


### Restart the device ### 
```bash
AT%RESTART
```

### Factory reset the device (in any state, even normal mode with or w/o lockscreen) ###
```bash
AT%FRST
```

### Exit Manual Mode ###
```bash
AT%QEM=1
```

### Enter Manual Mode ###
```bash
AT%QEM=0
```

### PID Write ###
```bash
AT%INFO=<Your PID here>
```

### IMEI Write - Not sure this will work! - But hey, it's worth a try ###
```bash
AT%IMEI=<Your IMEI here>
```

### BT Addr Write ###
```bash
AT%BTAD=<Your BT Address here>
```

### WiFi MAC Addr Write ### 
```bash
AT%MAC=<Your Wi-Fi MAC Address here>
```

### Manufacture SN Write ###
```bash
AT%MSN=<Your SN here>
```

### Manufacture Date Write ###
```bash
AT%MDATE=<Your Manufacture Date here>
```

### Suffix Code Write ###
```bash
AT%SUFFIX=<Your Suffix Code here>
```

### NT Code Write ###
```bash
AT%NTCODE=<Your NT Code here>
```

### PID Read ###
```bash
AT%INFO
```

### IMEI Read ###
```bash
AT%IMEI?
```

### HW Version Read ###
```bash
AT%HWVER
```

### BT Addr Read ###
```bash
AT%BTAD
```

### WiFi MAC Addr Read ###
```bash
AT%MAC
```

### Manufacture SN Read ###
```bash
AT%MSN
```

### Manufacture Date Read ###
```bash
AT%MDATE
```

### Suffix Code Read ###
```bash
AT%SUFFIX?
```

### OS Version Read ###
```bash
AT%OSVER
```

### External Socket Memory Check ###
```bash
AT%EMT
```

### Device ID Read ###
```bash
AT%DEVICEID
```

### USIM Card Test Result ###
```bash
AT%ISSIM
```

### AAT Result Check ###
```bash
AT%DEVICETEST
```

### CAL Data Check ###
```bash
AT%CALDT
```

### QFUSE Check ###
```bash
AT%EFUSECHECK
```

### Battery Level Check ###
```bash
AT%BATTLEVEL
```

### RAM Size ###
```bash
AT%RAMSIZE
```

### Internal Flash Memory Size (your UFS/EMMC size) ###
```bash
AT%EMMCSIZE
```

### Manual Mode Status Check ###
```bash
AT%QEM?
```

### NT Code Read ###
```bash
AT%NTCODE?
```

### SIM Lock Type Status Check ###
```bash
AT%SLTYPE?
```

### Full Signature Status Check ###
```bash
AT%FUSG?
```

### IMPL Status ###
```bash
AT%IMPL?
```

### SIM ID Read ###
```bash
AT%SIMID
```

### File CRC Check ###
```bash
AT%FILECRC
```

### Input SW Version ###
```bash
AT%SWOV
```

### Output SW Version ###
```bash
AT%SWV
```

### SW Fixed Area Version ###
```bash
AT%SWFV
```

### DB CRC Check ###
```bash
AT%DBCHK
```

### FPRI CRC Check ###
```bash
AT%FPRICRC
```

