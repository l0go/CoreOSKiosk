# CoreOS Kiosk
An example of using Fedora CoreOS as a "Kiosk"

This is based on my previous [BetterbellCoreOS]() project which provides Pipewire support

## Usage
The following instructions assume you are on Fedora or another similar dnf based distro, but it will work on other distros
1. Install ``just``
 
```
sudo dnf install just
```

2. Boot it in a VM
> On first boot it will layer needed packages and then restart to the Kiosk interface (which by default is Firefox)
```
just setup-fedora ignite qemu
```
