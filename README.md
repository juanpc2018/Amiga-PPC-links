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
http://zero.eik.bme.hu/~balaton/qemu/amiga/ </br>
https://www.hyperion-entertainment.com/index.php/where-to-buy/direct-downloads/174-amigaos-41-final-edition-for-classic </br>
AmigaOS4 does Not Boot directly on older Apple PowerMac G5, requires Qemu / WinUAE / LinuxPPC/OSX Sorbet 10.5.9 </br>
but does Boot directly on older Amiga A3000 / A4000 with PPC Cyberstom CPU board. </br>
X1000 / X5000 require a different CD Image / Installer "No Classic" included with HW purchase / registration. </br>
Different PowerPC CPUs require different installers. </br>

-----

AmigaOS4.1 QuickStart Guide v1.1 </p>

Option A) Use PPC emulator. </br>
Option B) Use compatible Hardware. </p>

Option A) </br>
AmigaOS4 does Not run / install directly on a Vintage Apple PowerMac G5 </br>
strange because AmigaOS4 is designed for PPC, and Apple PowerMac G5 are PowerPC, but Not all PowerPC CPUs are the same </br>
the problem is different CPU design, like QEMU requires specific CPU to run. </br>
AmigaOS4.1 has different DVD installers, Classic version available for purchase, </br>
compatible with 440/460ex PPC CPUs, FS-UAE, QEMU and CyberStorm PPC accelerator board for A4000, maybe AmigaOne 500 also, </br>
and the X1000 / X5000 version, designed for P5020 and P5040 PPC CPUs, only available when purchasing / registering New HW. </p>

Unknown if Classic installer or X5000 installer Boot directly on Newer Raptor Talos II "dual cpu" / Lite or BlackBird "single cpu" </br>
https://www.raptorcs.com/content/base/products.html </br>
Those machines are designed around IBM POWER9 v2 PPC RISC architecture. </br>
https://en.wikipedia.org/wiki/POWER9 </p>

To Run AmigaOS on a Vintage PowerMac G5 <2005 970 / 970FX / 970MP </br>
https://en.wikipedia.org/wiki/Power_Mac_G5 </br>
requires emulating PowerPC in a PowerPC, to solve OpenFW & CPU differences </br>
installing OSX for PPC or Linux for PPC, there are different Linux for PPC </br> 
OSX Leopard 10.5.8 for PPC, there is also for 10.5.8 for intel. </br> 
or OSX Sobert 10.5.9 "unofficial, but faster! optimized for PPC" </br> 
installing FS-UAE for LinuxPPC or OSX PPC </br>
or installing QEMU for LinuxPPC or OSX PPC </br>
Emulating PPC with PPC is Not The Best: Bare Metal option, </br>
but if you have a G5, is an option. </br>

Running / Installing AmigaOS4.1 can also be done on a Newer Windows, Mac or Linux. </p>

All have the same or very similar configuration steps. </p>

#1. buy AmigaOS4.1 hard copy or download: </br>
https://www.amigaos.net/content/4/where-buy </br>
https://www.hyperion-entertainment.com/index.php/where-to-buy/direct-downloads/174-amigaos-41-final-edition-for-classic </p>

After purchasing the Download version, </br> 
will receive a Serial Activation Code by mail, </br>
then open an account in hyperion website, </br>
Register your Product on your Hyperion account, </br>
find: AmigaOS4.1 Final Classic, </br>
type your Serial Number, </br>
Download the .iso and HotFix2 update from Downloads, </br>
there are also Game Demos for download. </br>

Then you need to Purchase a legal Amiga KickStart ROM 3.1 from an authorized website, </br>
Total is around $50usd. </br>
The idea is to support the developers, support a digital parallel reality, another timeline, think outside the box </br>
There are KickStart ROMs in FloppyDisk for A1000, A3000 </br>
Real EEPROMs, some machines require single and double 512k EEPROMs, stores like: </br>
https://www.vesalia.de/e_kickstart.htm </br>
https://www.amigaroms.com </br>
and ROM file images, purchased license or extracted from a real Amiga Hardware. </br>

After 3.1 ROMS, Amiga bankrupt, some people created modified versions of the ROMs with bug fixes and upgrades, </br>
like the 3.x ROM that should have been callled 3.10, .x is too weird. </br>
That ROM allows to have bigger than 4GB / 4096MB Boot drive, and many other fixes for real SCSI amigas. </br>
There is also a Diagnostic ROM for real Amiga Hardware, but also works in Emulators. </br>
The problem with 3.x rom is that is Bigger than 1024KB, and requires a file of the ROM to be outsde on the Boot drive, </br>
unless someone creates a modified A4000 recreation board that allows Bigger EEPROMS, a dual 1MB instead of dual 512KB. </p>

Runing an Emulated AmigaOS4.1 has limitations vs. HW: </br>
New Hardware has drivers for New Video cards, much faster, emulated video cards are Not the same </br>
FS-UAE PPC is limited to the old Picasso-IV or A4000 AGA chip emulation </br>
Emulation does Not allow to use Newer ZZ9000 "faster 100% compatible to Picasso-IV", with built in scan doubler, VGA out, 1Gb Ethernet, </br>
future USB Firmware upgrade. </p>

New X5000 Hardware allows to install Faster / Newer Radeon HD / RX </br>
New & old A4000 allow Newer / Faster ZZ9000 Zorro3 cards. </br>
Emulation does Not. </br>
JIT Compiler option in FS-UAE allows to Skip some steps, and Run Faster CPU, but does Not work with MMU.</p>

FS-UAE or QEMU requires to create a Virtual Harddrive, .hdf </br>
FS-UAE has an option to Create .hdf clicking the FS-UAE icon, Not the most intuitive design. </br>
Has 2-options 1 partition or multiple partitions, for Boot requires multiple partitions, </br>
1GB SWAP partition like Linux, Boot Partition Not Bigger than 4096MB "4GB" if using KickStart ROM 3.1. </p>

Option B) Compatible Hardware: </br>
Amiga A4000 with Phase5 PowerUp Cyberstorm PPC dual CPU accelerator board 68k & PowerPC 604e at 233MHz. </br>
AmigaOne 500 "Sam440/Sam460ex" PPC 1-core @ 1.115 GHz. </br>
X1000 PPC PA6T-1682M dual core 2Ghz. </br>
X5000 PPC P5020 / P5040 two / quad core @ 2GHz / 2.4Ghz. </p>
