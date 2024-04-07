# Build your own Linux distribution

## Set Up Your Environment

For the well being of our computer, we will proceed to work inside a virtual machine in order to be sure not to break the computer with bad manipulations.

1. Download [Virtual Box](https://www.virtualbox.org/wiki/Downloads)
2. Download a Linux Distribution ISO
    * Such as a [Linux Mint Edition](https://linuxmint.com/download.php)
3. Access Virtual Box and create a new Virtual Machine
    * Select expert mode
    * Name = Whatever
    * ISO = Iso downloaded in previous step
    * Type = Linux
    * Version = Version of downloaded ISO
    * Check the "Skip Unattended Installation"
    * In the hardware section, maximize the memory nd processors
    * In the hard disk section, set a minimum of 30Gb of memory
    * Select Finish
4. Configure the new VM (Virtual Machine)
    * Maybe set the video memory higher in the display section of the settings
5. Start the VM and don't install Linux Mint
    * Everything can be done in the live version since the VM save the state of the computer and that we will eventually reboot the VM with the new linux distro.

From here I will be following the Linux From Scratch [Documentation](https://www.linuxfromscratch.org/lfs/view/stable/)

## Partition the disks

1. Using your OS partitioning tool, set up a root partition and a swap partition

## Set the root password

1. sudo passwd root
    * set a simple password for faster development, such as 1234


## Change to user root
```bash
su -
```
