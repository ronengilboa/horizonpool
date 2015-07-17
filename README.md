# horizonpool
checks the utilization of dedicated pools
gets a pool / list of machines (should be dedicated or the script has no meaning)
also gets the vcenter that desktops are in.
checks for each desktops when was the last time it was logged on to by checking a file that is created on each logon.
uses horizon powercli and vsphere
