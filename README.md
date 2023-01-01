# v2rayng
First of all, you need to install ubuntu 18.04 or ubuntu 20.04 operating system on vps.

---

*After installing the operating system, update the operating system with the code below.*
```
apt-get update -y && apt-get upgrade -y
```
---
Then install the following codes in order.
```
apt install curl socat -y
```
```
curl https://get.acme.sh | sh
```
---
After executing the above codes, v2ray needs to be installed. Enter the code below to install
```
bash <(curl -Ls https://raw.githubusercontent.com/vaxilu/x-ui/master/install.sh)
```
---
The work is done and you need to access the x-ui panel.
By entering the following link in the browser, you can access the right panel. If you have trouble opening, log in with vpn.
```
http://yourip:54321
```
