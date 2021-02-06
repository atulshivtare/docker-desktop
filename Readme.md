# Docker Desktop on Windows.

*Download* **boot2docker.iso** from [boot2docker release page](https://github.com/boot2docker/boot2docker/releases)

# Create a virtual machine
* as docker-vm
* with 4GB of ram 
* 100GB of dynamically allocated vmdk hdd.
* additional Host-Only adaptor
* a shared folder to save docker data outside of vm.
  
  ![alt image](shared-folder.JPG)
  ![alt image](docker-vm.JPG)

# Start docker-vm

* Mount boot2docker.iso

  ![alt boot2docker.iso](iso-mount.JPG)

# Restart docker-vm

  ![alt vmstart](docker-vm-started.JPG)

# Get IP Address
* Type *ifconfig* and press Enter.

  ![alt ipAddress](ip-address.JPG)

# Open super-putty
* Enter Host as the **ip address** from previous step.
* Enter Login as **docker**
* Enter Password as **tcuser**
* Enter **sudo -i** to login as *root*

  ![alt ssh](ssh.JPG)

# Done