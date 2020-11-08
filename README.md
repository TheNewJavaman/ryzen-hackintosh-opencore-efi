# ryzen-hackintosh-opencore-efi

EFI files for my Hackintosh desktop. Specs below.

If you have any questions/issues, **please let me know!** I've fixed too many minor problems to list here.

## specs

- CPU: Ryzen 5 1600
- GPU: AMD XFX RX 580 8GB
- RAM: Team Dark 3000mhz
- Drives:
    - WD Black 500GB hard drive (2014ish)
    - Other SSDs for Windows and Ubuntu
- Motherboard: MSI Tomahawk B350
- MacOS: Catalina 10.15.5

## what works

- Everything I've tested
- Xcode!

## what doesn't

- Emulation in Xcode/Android Studio

## what i haven't tested

- iServices (I don't use an iPhone)
- Motherboard audio (I use a SteelSeries Arctis 7 USB audio card)

## kexts/drivers/config.plist

I edited my MacOS's EFI to use the RELEASE versions of every kext/driver. These changes are (probably) not reflected in this repository.

For a detailed installation guide, visit the official OpenCore project [here](https://dortania.github.io/OpenCore-Install-Guide/)
