# Static IP addresses assignment

Static DHCP server addresses assignment is useful when it's required that devices, connected to your network, will get 
permanent IP address.

Log in to [LuCI](../luci), then choose *DHCP and DNS* in top navigation menu.

![Screenshot 1](screenshot_1.png)

You can see the list of the currently connected devices, which had assigned IP addresses from DHCP server, on the bottom
of the page. Then click the *Add* button under that list.

![Screenshot 1](screenshot_2.png)

Fill the new row with:

 * **Hostname** - any name you want to identify the device.
 * **MAC-Address** - Hardware identification number. It can be select from the list of list MAC addresses of connected
devices or filled manually by selecting the *\-\-custom\-\-* option.
 * **IPv4-Address** - An IP address to be permanently assigned to a device identified by MAC address. It can be select
from the list of last used IP addresses or filled manually by selecting the *\-\-custom\-\-* option.

![Screenshot 1](screenshot_3.png)

You can add more devices by clicking *Add* button. If you are done, please don't forget to press *Save & Apply* button.

!!! warning
    IP address changes will not take effect immediately. If the computer has an IP address, it waits until it expires
    and then asks for a new one. If you need the address change to take effect immediately, and you can't do it on your
    device operating system, then disconnect the device from the network and reconnect it again.
