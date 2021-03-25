# Step-by-step guide
- Download VirtualBox → VirtualBox binaries → VirtualBox x.x.x platform packages → OS X hosts
- Install VirtualBox.
- Download desired VM from https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/
- Follow instructions on developer.microsoft.com for VM extraction & installation
- Go to VirtualBox → File → Import Appliance
- Select *.ovf file for your VM
- Keep default settings, and select Import.

# Gotchas! 

- Once your VM is setup with desired screen resolution, browsers etc, take a snapshot so you don't have to worry about Windows trial expiring.
- To setup bi-directional Copy-paste between Mac and VM, Go to Settings → General → Advanced. Set Shared Clipboard and Drag'n'Drop to "Bidirectional"
- To avoid getting mouse pointer getting captured, Go to Settings → System, and set Pointing Device to "USB Tablet"
- To increase screen resolution on VM: Install virtual box guest addition and the shut down your virtual machine, go to setting->display, increase the memory from 12 (or whatever it is) to maximum(i think that will be 256). Save and power on your virtual machine. Also adjust Scale Factor according to screensize - example from 100% to 250% if screen size is too small to use.
- For VirtualBox v6 and up, Set Graphics Controller to VBoxVGA by going to Settings → Display.
