# Hackintosh MSI Z97 GAMING 5

This repository contains my EFI folders and bootloaders configurations to boot macOS on my MSI Z97 Gaming 5 motherboard.

If you want to use them, don't forget to generate your own SMBIOS and update your config.plist files.

### Specifications :

- Motherboard : [MSI Z97 GAMING 5](https://msi.com/Motherboard/z97-gaming-5.html)
- CPU : [Intel Core i5-4690k](https://ark.intel.com/content/www/us/en/ark/products/80811/intel-core-i5-4690k-processor-6m-cache-up-to-3-90-ghz.html)
- GPU : Intel HD Graphics 4600

### Bios settings :

`Settings > Advanced > Integrated Graphics Configuration`

- Set `Initiate Graphic Adapter` to `IGD`
- Set `Integrated Graphics Shared Memory` to `64M`

`OC > CPU Features`

- Set `Intel VT-D Tech` to `Disabled`
- Set `CFG Lock` to `Disabled`

## Credits

- [OpenCore Bootloader](https://github.com/acidanthera/OpenCorePkg)
- [Clover Bootloader](https://github.com/CloverHackyColor/CloverBootloader)
- [acidanthera](https://github.com/acidanthera) for OpenCore & Kexts
