# sdwan_bgp_lab

The configuration files from a blog post I wrote about [Cisco SD-WAN using BGP on the transport side](https://theworldsgonemad.net/2022/sdwan-vpn0-bgp/)

![network-diagram](https://user-images.githubusercontent.com/33333983/192093780-dcf1e706-b520-419f-b03b-64556e50bb7c.png)

The lab is built in EVE-NG using the following devices and images with a username/password of admin/admin.

**vManage01, vBond01, vSmart01, vSmart02:** *20.3.4*\
**S11-cEdge01, S11-cEdge02, S11-Core01, S21-cEdge01, S21-Core01:** *CSR using IOS-XE 17.3.4a*\
**ISP:** *IOS router using IOSv 15.6(2)T*

The device configs are attached as well as all the vManage device and feature templates and the CSV files of the values for these.

![eve-lab-topology](https://user-images.githubusercontent.com/33333983/192093886-05e17b35-4688-4f63-9437-7ee27bc5b0cb.png)
