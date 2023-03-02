# dualra1n

A script that lets you dualboot iOS 14-15 on checkm8 devices.


# Usage

Example: ./dualboot.sh --dualboot 14.3 

    --dualboot          Dualboot your device with any SEP and Baseband compatible iOS 14 version.
    
    --jail-palera1n     Use this only when you already jailbroken with semitethered palera1n to avoid disk errors. 
    
    --jailbreak         Jailbreak the dualbooted iOS with Pogo. Usage :  ./dualboot.sh --jailbreak 14.3

    --taurine           Jailbreak dualbooted iOS with Taurine. Usage: ./dualboot.sh --jailbreak 14.3 --taurine 
   
    --help              Print this help.
       
    --get-ipsw           Automaticly downloads IPSW that you want to dualboot. Dont forget specify iOS version.

    --dfuhelper         A helper to enter DFU if you struggling in it.
    
    --boot              Lets you boot into dualbooted iOS. Use it alone. Usage : ./dualboot.sh --boot
    
    --dont-create-part   Skips the creating a new disk partition if you have them already.
    
    --restorerootfs     Deletes dualbooted OS. and remember put --jail-palera1n if you have palera1n semitethered jailbreak 
    
    --fix-preboot       that restore preboot with the prebootBackup. --fix-preboot
    
    --debug             Debug the script

Subcommands:

    clean               Deletes the created boot files 

---
# Dependencies
- A desactivated passcode on A10-A11 
- unzip
- python3
- A IPSW iOS 14-15 
- 15GB+ free storage

# Warnings
- I am **NOT** responsible for any data loss. The user of this program accepts responsibility should something happen to their device.
 **If your device is stuck in recovery, please run one of the following:**
   - futurerestore --exit-recovery
   - irecovery -n

# Ideal Dualboot Versions
iOS 14.2 is the ideal version as on that version the Camera and flash works, while on other version usually they don't.

Dualbooting any version of iOS 15 will give you kernel panics, so you will have to use --jailbreak 15.* after the first boot. That should be a one time fix.

iOS 13 is working but has only been tested with 13.7, but hasn't for others. If you want to dualboot with iOS 13.x, use the iOS 13 branch. This will not work on iPads without a baseband (WiFi Only).

# How would I dualboot?

[A full tutorial](https://github.com/dualra1n/dualra1n/blob/main/tutorial.md)


# Problems and issues contact me on the official [Discord](https://discord.gg/E6jj48hzd5)


# Credits

<details><summary>dualra1n Contributors</summary>
<p>

- [Edwin](https://github.com/edwin170) owner :)
- [Fatih](https://github.com/swayea) help with readme and linux support and is a very good person.
- [azaz0322](https://github.com/m00nl1ghts) helped with readme a bit more.

</details>
<details><summary>Other credits for tools and codes used in dualra1n</summary>

- Edward thanks for my brother for gave me a hackintosh to test this:).

- [palera1n](https://github.com/palera1n) for some code 

- [Dualboot guide](https://dualbootfun.github.io/) for the guide

- [Darling](https://github.com/darlinghq) for a macOS emulator

- [blacktop](https://github.com/blacktop) for the ipsw downloader

- [Nathan](https://github.com/verygenericname) for the ramdisk

- [Mineek](https://github.com/mineek)
	- For patchfinders for RELEASE kernels
	- [Kernel15Patcher](https://github.com/mineek/PongoOS/tree/iOS15/checkra1n/Kernel15Patcher)
	- [Kernel64Patcher](https://github.com/mineek/Kernel64Patcher)
    
- [Amy](https://github.com/elihwyma) for the [Pogo](https://github.com/elihwyma/Pogo) app
- [checkra1n](https://github.com/checkra1n) for the base of the kpf
- [m1sta](https://github.com/m1stadev) for [pyimg4](https://github.com/m1stadev/PyIMG4)
- [tihmstar](https://github.com/tihmstar) for [pzb](https://github.com/tihmstar/partialZipBrowser)/original [iBoot64Patcher](https://github.com/tihmstar/iBoot64Patcher)/original [liboffsetfinder64](https://github.com/tihmstar/liboffsetfinder64)/[img4tool](https://github.com/tihmstar/img4tool)
- [xerub](https://github.com/xerub) for [img4lib](https://github.com/xerub/img4lib) and [restored_external](https://github.com/xerub/sshrd) in the ramdisk
- [libimobiledevice](https://github.com/libimobiledevice) for several tools used in this project (irecovery, ideviceenterrecovery etc), and [nikias](https://github.com/nikias) for keeping it up to date
- [Dora](https://github.com/dora2-iOS) for iBoot payload and iBootpatcher2
- [Sam Bingner](https://github.com/sbingner) for [Substitute](https://github.com/sbingner/substitute)
- [CoolStar](https://github.com/coolstar) for [Libhooker]
- [Ralp0045](https://github.com/Ralph0045/Kernel64Patcher) amazing dtree_patcher and kernel64patcher ;)

</p>
</details>
