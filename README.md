# Amiga-PPC-links

Amiga 4k had PPC CPU accelerator card, that allowed to Run AmigaOS4.1 </br>
it is interesting an Amiga PCB with dual CPU, 68k and PowerPC 604e @ 233MHz. </p>

https://amiga.resource.cx/exp/cyberstormppc </br>
http://phase5.a1k.org/index.html </br>
https://translated.turbopages.org/proxy_u/de-en.en.020075d3-639a999b-ccf08960-74722d776562/https/www.amigawiki.org/doku.php?id=de:expansion:cpu:cyberstorm_ppc </p>

https://youtu.be/AZL86gZr0LA </p>

https://en.wikipedia.org/wiki/PowerUP_(accelerator)#Cyberstorm_PPC </br>
https://en.wikipedia.org/wiki/PowerPC_600#PowerPC_604e </br>
http://www.a-eon.com/?page=x5000 </br>
http://wiki.amiga.org/index.php?title=X5000 </br>
https://en.wikipedia.org/wiki/QorIQ#P5 </br>
https://en.wikipedia.org/wiki/AmigaOne_X1000 </br>
https://en.wikipedia.org/wiki/PWRficient </br>
https://www.hyperion-entertainment.com/ </br>
https://www.amigaos.net/ </br>
https://en.wikipedia.org/wiki/Sam460ex - https://en.wikipedia.org/wiki/PowerPC_400#AMCC_460 </br>
http://www.sam4x0.com/sam460ex.html </br>
https://www.acube-systems.biz/ </br>
https://www.amiga-shop.net/en/A-EON:.:42.html </br>
http://www.ggsdata.se/index-en.php / Classic / AmigaOS </p>

but probably would require faster Pi 4B+ or Faster Odroid N2+ </br>
or multiple Pi boards to emulate a 4-core PowerPC, like the Amiga X5000 </br>
AmigaOne 500 "Sam460ex" PPC 440 / 460EX core @ 1.115 GHz </br>
X1000  PPC PA6T-1682M dual core 2Ghz. </br>
X5000  PPC P5020 / P5040 two / quad core @ 2GHz / 2.4Ghz. </br>
but... P5 CPUs dont have https://en.wikipedia.org/wiki/AltiVec </p>

in my experience faster is better vs. more but slower cores, because interrupts, OS are Not designed for True Parallel processing with less/No interrupts. </p>

https://fs-uae.net/docs/amigaos-4-1 </br>
https://www.hyperion-entertainment.com/index.php/where-to-buy/direct-downloads/174-amigaos-41-final-edition-for-classic </br>
AmigaOS4 does Not Boot directly on older Apple PowerMac G5, requires Qemu / WinUAE / LinuxPPC/OSX Sorbet 10.5.9 </br>
but does Boot directly on older Amiga A3000 / A4000 with PPC Cyberstom CPU board. </br>
X1000 / X5000 require a different CD Image / Installer "No Classic" included with HW purchase / registration. </br>
Different PowerPC CPUs require different installers. </br>

-----

AmigaOS4.1 QuickStart Guide v1.1 </p>

Option A) VirtualMachine with PowerPC CPU Emulator. </br>
Option B) Real PowerPC compatible Hardware. </p>

Option A) </br>
is the most economic method to enter AmigaOS ecosystem, </p> 

Limitations: </br>
AmigaOS4.1 does Not run / install directly on a Vintage Apple PowerMac G5 </br>
thats weird because AmigaOS4 is designed for PowerPC CPUs, and Apple PowerMac G5 has PowerPC CPU, </br>
but Not all PowerPC are the same. </br>
the problem is different Boot Firmware & CPU design, like QEMU requires specific CPU to run. </br>
AmigaOS4.1 has different DVD installers: Final Classic available for purchase, </br>
compatible with AmigaOne 500 "Sam440/460ex PPC CPUs", FS-UAE, QEMU, Amiga 4000 with CyberStorm PPC accelerator board, </br>
and the X1000 / X5000 installer designed for P5020 and P5040 PowerPC CPUs, Bundled when purchasing a New HW. </p>

Unknown if Classic installer or X5000 installer Boot directly on Newer Raptor Talos II "dual cpu" / Lite or BlackBird "single cpu" </br>
https://www.raptorcs.com/content/base/products.html </br>
Those machines are designed for a similar IBM POWER9 v2 PowerPC architecture. </br>
https://en.wikipedia.org/wiki/POWER9 </p>

To Run AmigaOS4.1 on a Vintage PowerMac G5 2003-2005 with CPUs: 970 / 970FX / 970MP </br>
https://en.wikipedia.org/wiki/Power_Mac_G5 </br>
requires emulating PowerPC in PowerPC, to solve the OpenFW & CPU differences. </p>

installing OSX for PPC or Linux for PPC, there are different Linux for old & New PowerPC machines, like:</br> 
https://youtu.be/g-Ugfqj1ank </br>
https://cdimage.debian.org/cdimage/ports/current/ </br>
https://forums.macrumors.com/threads/debian-sid-installation-guide-powerpc.2146795/ </br>
https://youtu.be/AArGaJGFVH4 </br>
https://www.adelielinux.org/download/ </br>
https://amigaonthelake.com/new-6-13-2020-fienix-linux-distro-for-amigaone-64-bit-powerpc-systems/ </p>

OSX Leopard 10.5.8 for PPC, there is also 10.5.8 for intel "MacPro1,1 2006". </br> 
or OSX Sobet 10.5.9 R15 "New 2022, faster! PPC optimized." </br> 
https://macintoshgarden.org/apps/sorbet-leopard </br>
https://forums.macrumors.com/threads/sorbet-leopard-your-power-mac-unleashed-revision-1-5-released.2300924/ </br>
installing FS-UAE for LinuxPPC or OSX PPC </br>
or installing QEMU for LinuxPPC or OSX PPC </br>
Emulating PPC with PPC is Not The Best: Bare Metal option, </br>
but if you have a G5, is an option. </p>

IF you are bored with the same OS, there are different options: </br>
Linux for old & New PPC CPUs </br>
NewOld OSX 10.5.9 for old PPC CPUs </br>
AmigaOS4.1 for New and old Amiga PowerPC CPUs.</br>
All can be Run Real or Emulated.</p>

Boot Differences: OSX G5 PPC vs. Amiga A4000 PPC </br>
OSX OpenFirmware loads from Disk to RAM to Boot / initialize the Machine devices "keyboad, HDD controllers, etc. </br>
Amiga A4000 loads directly from EEPROM to Initialize / Boot the machine. </br>
The Newer OSX method is suceptible to Boot Rom Virus, the boot partition can be modified from OSX, </br>
but is cheaper, smaller & faster to manufacture.</br>
Amiga EPROM has limited size, requires a board PCB re-design to increase the size, a New Bigger EEPROM or multiple EEPROMs </br>
More expensive, and Bigger size on the PCB, but EPROMs last 1 Million R/W cycles  "last forever", better than Newer Flash ROMs, </br>
the only way to modify an EPROM is to Remove it, Erase it with UV-C light or HighVoltage 21vdc, and Write again with a Programmer = 100% Safer.</br>
https://forums.macrumors.com/threads/the-open-firmware-wiki.2225024/ </p>

Running / Installing AmigaOS4.1 can be done Emulated on a Newer Windows, Mac or Linux. </p>

All have very similar configuration steps. </p>

#1. buy AmigaOS4.1 hard copy or download: </br>
https://www.amigaos.net/content/4/where-buy </br>
https://amigaonthelake.com/amigaos-4-1-final-edition-sam-460-amigaone-500/#description </br>
https://www.hyperion-entertainment.com/index.php/where-to-buy/direct-downloads/174-amigaos-41-final-edition-for-classic </p>

After purchasing the Download version, </br> 
will receive a Serial Activation Code by e-mail, </br>
create an account in Hyperion website, </br>
Login & Register your Serial, </br>
find: AmigaOS4.1 Final Classic, </br>
type your Serial, </br>
Download the .iso and HotFix2 update from Downloads, </br>
there are also Game Demos for Download. </br>

Then you need to Purchase a legal Amiga KickStart ROM 3.1 from an authorized website, </br>
Total is aprox. $50usd. </br>
The idea is to support developers, support a parallel digital reality, another timeline, to think outside the box. </br>
There are KickStart ROMs in FloppyDisk for A1000, A3000, Not Recommended. </br>
Real EPROMs, some machines require single 1MB or double 512k EPROMs, from stores like: </br>
https://www.amigaforever.com/value/ </br>
https://www.vesalia.de/e_kickstart.htm </br>
https://www.amigaroms.com </br>
or ROM image file, a license purchase or extracted from a Real Amiga Hardware if you own one. </p>

After 3.1 ROMs, Amiga bankrupt, some people created modified versions of the ROMs with bug fixes and upgrades, </br>
like the 3.X ROM that should have been called 3.10, .x is too weird. </br>
That ROM allows to have Bigger than 4GB / 4096MB Boot drive, and many other fixes for Real SCSI Amigas. </br>
There is also a Diagnostic ROM for Amiga Hardware, but also works in Emulators. </br>
https://www.diagrom.com/index.php/download/ </br>
The problem with 3.x Rom: is Bigger than 1024KB, and requires a file of the ROM to be outsde the ROM on the Boot drive, </br>
unless someone creates a modified A4000 board that allows Bigger EPROMs, single 2MB, or dual 1MB instead of dual 512KB. </br>
https://github.com/libretro/libretro-uae/blob/master/README.md </br>
https://www.amigaforever.com/kb/15-127 </p>

Runing an Emulated AmigaOS4.1 has limitations vs. HW: </br>
New Hardware has drivers for New Video cards, much faster, emulated video cards are Not the same. </br>
FS-UAE PPC is limited to the old Picasso-IV or A4000 AGA chip emulation </br>
https://en.wikipedia.org/wiki/Amiga_4000 </br>
https://en.wikipedia.org/wiki/Amiga_4000T </br>
Emulation does Not allow to use Newer MNT ZZ9000 "Faster 100% compatible Picasso-IV GPU" with built-in scan doubler, VGA out, 1Gb Ethernet, future USB Firmware upgrade. </p>

New AmigaOne 500 & X5000 HW allows to install Faster Radeon HD / RX GPUs. </br>
New & old A4000 allow Newer & Faster ZZ9000 Zorro3 cards. </br>
Emulation does Not. </br>
JIT Compiler option in FS-UAE allows to Skip some steps, and Run Faster, but does Not work with MMU.</p>

FS-UAE or QEMU requires to create a Virtual Harddrive, .hdf </br>
FS-UAE has an option to Create .hdf clicking the [FS-UAE] icon at the left, Not the most intuitive design. </br>
Has 2-options: 1 partition or multiple partitions, for Boot requires multiple partitions, </br>
1GB SWAP partition like Linux, Boot Partition Not Bigger than 4096MB "4GB" if using KickStart ROM 3.1. </p>

FS-UAE requires to manually instal the Optional Plugins, </br>
https://fs-uae.net/download#plugins </p>

in OSX .tar.gz requires Keka.app </br>
https://www.keka.io/ </p>

Untar to: </br> 
/Users/YOU/Documents/FS-UAE/System/CAPSImg </br>
/Users/YOU/Documents/FS-UAE/System/QEMU-UAE </p>

in my opinion, Plugins should be installed in ../Plugins, Not ../System but FS-UAE requires /System </br>
FS-UAE is Not intuitive for begginers in some areas. </p>

AmigaOS4.1.iso </br>
/Users/YOU/Documents/FS-UAE/CD-ROMs/ClassicInstallCD-53.71.iso </br>
needs to be mounted in host OSX/Windows/Linux </br>
inside has 2 .adf </br>
copy to: </br>
 /Users/YOU/Documents/FS-UAE/Floppies/BootFloppy.adf </br>
Optional: </br>
/Users/YOU/Documents/FS-UAE/Floppies/GREXBootDisk.adf </p>

Other important Files: </br>
/Users/YOU/Documents/FS-UAE/Kickstarts/Kickstart v3.1 rev 40.70 (1993)(Commodore)(A4000).rom </br>
/Users/YOU/Documents/FS-UAE/Kickstarts/picasso_iv_flash.rom </br>
/Users/YOU/Documents/FS-UAE/Kickstarts/cyberstormppc.rom </br>

Blizzard SCSI does Not work when Cyberstom PPC SCSI is running. </br>
/Users/YOU/Documents/FS-UAE/Kickstarts/Blizzard_SCSI_Kit_IV_v8.5.bin </p>

Optional: /Users/juanpc/Documents/FS-UAE/Kickstarts/A4091.rom </p>

Required: /Users/juanpc/Documents/FS-UAE/Hard Drives/AOS41.hdf </p>

Recomended: 3990 MB </br>
90000 Clusters 3/4 = 75% size to Boot Partition, </br>
remaining Clusters to SWAP partition. </p>

ZorroIII Fast RAM card can be used as Faster RAM SWAP in AmigaOS4.1 </br>
No SWAP partition needed. </p>

All FS-UAE RAM cards with 128MB recommended. </p>

Emulating Sam460ex PPC + Picaso-IV in OSX HighSierra 10.13.6 x86_64 requires: </br>
100% CPU load in a 2-core Mac Mini 2014 i5 2.8Ghz 8GB RAM. </p>

----

Option B) Compatible Hardware: </br>
Amiga A4000 with Phase5 PowerUp Cyberstorm PPC dual CPU accelerator board 68k & PowerPC 604e at 233MHz. </br>
AmigaOne 500 "Sam440/Sam460ex" PPC 1-core @ 1.115 GHz. </br>
X1000 PPC PA6T-1682M dual core 2Ghz. </br>
X5000 PPC P5020 / P5040 two / quad core @ 2GHz / 2.4Ghz. </p>

Links / Tutorials: </br>
http://pjhutchison.org/emulation/fs-uae_windows.html </br>
QEMU Tutorial: http://zero.eik.bme.hu/~balaton/qemu/amiga/ </br>
