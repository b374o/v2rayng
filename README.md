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
your user & password is **admin**
```
http://your-server-ip-address:54321
```
--Translate to English
if you use chrome you can press Right Click and select Translate  to English. 

By following the steps below, you can change the port to enter the panel.
 Go to your server shel & Eneter The below code:
```
x-ui
```
Enter the 16 and press enter
Enter a number to change yor login port. For example : 443, 1234, 743 or any number. press enter to change port.
---
-for change username and password to login go to x ui panel
-go to setting>
