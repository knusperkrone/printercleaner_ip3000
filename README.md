# printercleaner_ip3000

Cleans the printerhead of an Canon Ip3000 under linux.

This was done by siniffing the urb packets on an windows machine and sending it to your printer via a python script.<br>
Depending on your linux-distribution you may need `sudo` to access your USB-ports.

### Dependencies

 - python3
 - pyusb

### Usage

```bash
  git clone https://github.com/knusperkrone/printercleaner_ip3000.git
  cd printercleaner_ip3000
  ./clean_ip3000.py
```
