# USB-Unblock
How to unblock usb without rebooting the server.

# How to unblock usb without rebooting server.
  
  vim /etc/modprobe.d/blacklist.conf
    #blacklist uas
    #blacklist usb-storage
  :wq ( Save file )
 
# Then run below modprobe command
  modprobe usb-storage
