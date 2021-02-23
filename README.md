# MSI GS65 Stealth Thin Triple Boot

[!]()

Resources and guide for triple booting Windows 10, Elementary OS, and macOS 11 Big Sur on an MSI GS65 Stealth Thin 8RF laptop, using OpenCore and rEFInd.

It's assumed that the base operating system on the laptop is a recent version of Windows 10.

### Note:
My current hardware (only listing important differences between GS65 models) is:
- 2x 1TB NVMes (Opened up laptop and removed 512 GB M.2 SSD to install them)
- NVidia GeForce 1070 8GB with Max-Q Design
- 16 GB stock RAM
- Intel Wireless-AC 9560 160MHz

Having 2 hard drives simplifies the process, I will not be covering this installation when only a single hard drive is available

## Installation

Writing of instructions is in progress. If you know what you are doing and are looking for resources, check my OpenCore directory in EFI/.

### Refind

For the rEFInd theme, check EFI/Boot/themes/minimal. I made it based on various existing themes ([1](https://github.com/andersfischernielsen/rEFInd-minimal-black) and [2](https://github.com/lukechilds/refind-ambience)).

I made the background and the custom elementaryos icon, and added an [oxygen cursor](https://www.deviantart.com/lavalon/art/Oxygen-Cursors-76614092) if you prefer to have the mouse in refind (enable it in theme.conf).





