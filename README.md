# Amiga-PPC-links

Amiga 4k had PPC CPU accelerator card, that allowed to Run AmigaOS4.1 </br>
it is interesting an Amiga PCB with dual CPU, 68k and PowerPC 604e @ 233MHz. </p>

https://amiga.resource.cx/exp/cyberstormppc </br>
http://phase5.a1k.org/index.html </br>
http://phase5.a1k.org/ </br>
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
is the most economic way to enter AmigaOS4.1 ecosystem, </p> 

Limitations: </br>
AmigaOS4.1 does Not run / install directly on a Vintage Apple PowerMac G5 </br>
thats because: </br>
Apple PowerPC, Pegasos and other PowerPC like ACube Sam460 are CHRP-compliant systems. </br>
but AmigaOne X1000, AmigaOne X5000 and NXP T2080RDB-PC are Not. </br>
and X1000 is also different than X5000 / NXP </br>
AmigaOS4 is designed for PowerPC, and Apple PowerMac G5 has PowerPC CPU, </br>
but All PowerPC are Not the same. </br>
different Boot Firmware & CPU design, like QEMU requires specific CPU to run. </p>

AmigaOS4.1 and Fienix Linux has different .iso installers: </br>
AmigaOS4.1 Classic Final Edition available for purchase from Hyperion Website or Boxed from Authorized distributors, </br>
Classic is compatible with AmigaOne 500 "Sam440/460ex" PPC CPUs, FS-UAE, QEMU, and Amiga 4000 with CyberStorm PPC accelerator board, </br>
the X1000 / X5000 installer designed for other PowerPC CPUs, Bundled when purchasing X5000 New. </p>

Untested: Build rEFInd from source on PPC, </br>
http://www.rodsbooks.com/refind/getting.html </p> 

Unknown if Classic installer or X5000 installer Boot on Newer Raptor Talos II "dual cpu" / Lite or BlackBird "single cpu" </br>
https://www.raptorcs.com/content/base/products.html </br>
Those machines have a similar IBM POWER9 v2 PowerPC architecture. </br>
https://en.wikipedia.org/wiki/POWER9 </br>
Unknown IF Raptor Sforza CPUs allow VM. </p>

To Run AmigaOS4.1 on a Vintage PowerMac G5 2003-2005, CPUs: 970 / 970FX / 970MP </br>
https://en.wikipedia.org/wiki/Power_Mac_G5 </br>
requires emulating PowerPC in PowerPC, to solve the OpenFW & CPU differences. </p>

installing OSX or Linux for PPC: </br>
there are different Linux for old & New PowerPC machines, like:</br> 
https://youtu.be/g-Ugfqj1ank </br>
https://cdimage.debian.org/cdimage/ports/current/ </br>
https://forums.macrumors.com/threads/debian-sid-installation-guide-powerpc.2146795/ </br>
https://youtu.be/AArGaJGFVH4 </br>
https://www.adelielinux.org/download/ </br>
New PPC64Le: </br>
https://torrent.fedoraproject.org/ </br>
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
The idea is to support developers, support parallel digital reality, another timeline, think outside the box. </br>
There are KickStart ROMs in FloppyDisk for A1000, A3000, Not Recommended. </br>
Real EPROMs, some machines require single 1MB or double 512k EPROMs, from stores like: </br>
https://www.amigaforever.com/value/ </br>
https://www.vesalia.de/e_kickstart.htm </br>
https://www.amigaroms.com </br>
or ROM image file, a license purchase or extracted from a Real Amiga Hardware if you own one. </p>

After 3.1 ROMs, Amiga bankrupt, some people created modified versions of the ROMs with bug fixes and upgrades, </br>
like the 3.X ROM that should have been called 3.10, .x is too weird. </br>
That ROM allows to have Bigger than 4GB / 4096MB Boot drive, and many other fixes for Real SCSI Amigas. </p>

Diagnostic ROM for Amiga HW, also works in Emulators. </br>
https://www.diagrom.com/index.php/download/ </br>
HW Floppy Test Kit </br>
https://github.com/keirf/amiga-stuff </br>
PPC PowerUP Test Disk: </br>
https://powerup.amigaworld.de/index.php?lang=en&page=24 </br>
https://powerup.amigaworld.de/download.php?id=59 </p>

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
https://www.keka.io/ </br> 
https://d.keka.io/ </p>

Untar to: </br> 
/Users/YOU/Documents/FS-UAE/System/CAPSImg </br>
/Users/YOU/Documents/FS-UAE/System/QEMU-UAE </p>

in my opinion, Plugins should be installed in ../Plugins, Not ../System but FS-UAE requires /System </br>
FS-UAE is Not intuitive for begginers in some areas. </p>

There are 2 Options here: </br>
Aa) Boot & Install from Floppy </br>
Ba) Boot & Install from CD.iso </p>

Aa) Option has Low-Res graphics.
Copy AmigaOS4.1.iso to:</br>
/Users/YOU/Documents/FS-UAE/CD-ROMs/ClassicInstallCD-53.71.iso </br>
mount in host OSX/Windows/Linux </br>
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

Optional: /Users/YOU/Documents/FS-UAE/Kickstarts/A4091.rom </p>

Required: /Users/YOU/Documents/FS-UAE/Hard Drives/AOS41.hdf </p>

Ba) To Boot from CD, </br>
requires Manually Edit CyberStorm PPC Bios, </br>
pressing [Esc] at Boot, requires latest ROM 44.71 </br>
SCSI menu: </br>
adjust SCSI device ID 0 or 1 for CD Boot, LUA 1 for each Device.  </br>
Later after HD is installed, CD can be changed to Mount Onlu, No Boot.</br>
All other devices can be set to: No LUA "Dissabled" <7p>

Recomended: 3990 MB </br>
90000 Clusters 3/4 = 75% size to Boot Partition, </br>
remaining Clusters to SWAP partition. </p>

Zorro-III Fast RAM cards can be used as Fast SWAP in AmigaOS4.1 </br>
No SWAP partition in HDD needed, That is a Good Options, Zorro-RAM is Faster than SCSI-2 & IDE.</br>
Latest AmigaOS4.1 Hotfix2 has a patch to use FastRam as RAM. </br>
The Fastest RAM is closer to the CPU</br>
Zorro-3 FastRAM is Slower than CPU RAM because its far from the CPU, and Zorro slot is a Bottleneck vs. Direct to CPU. </br> 
In my Opinion FastRAM is Not Real RAM, even its Detected as RAM is too Slow to be Real RAM.</br>
same as modern PCs, for decades PCIe was slower vs. RAM drive. </br>
Some Amiga applications wont care if Zorro-RAM is slower. </br>
Quake cares, but to Play videos & large photos Zorro-RAM is fast enough, its faster than SCSI-2 & IDE.</br>
there are Amiga players that play direcly from SCSI & IDE, but most Play from RAM. </p>

All FS-UAE RAM cards with 128MB recommended. </p>

Emulating Sam460ex PPC + Picaso-IV in OSX HighSierra 10.13.6 x86_64 requires: </br>
100% CPU load on a 2-core Mac Mini 2014 i5 2.8Ghz 8GB RAM. </br>
and Macs Fan Control: https://crystalidea.com/macs-fan-control/download </p>

----

Option B) Compatible Hardware: </br>
Amiga A4000 with Phase5 PowerUp Cyberstorm PPC dual CPU accelerator board 68k & PowerPC 604e at 233MHz. </br>
AmigaOne 500 "Sam440/Sam460ex" PPC 1-core @ 1.115 GHz. </br>
X1000 PPC PA6T-1682M dual core 2Ghz. </br>
X5000 PPC P5020 / P5040 two / quad core @ 2GHz / 2.4Ghz. </p>

Links / Tutorials: </br>
http://pjhutchison.org/emulation/fs-uae_windows.html </br>
QEMU Tutorial: http://zero.eik.bme.hu/~balaton/qemu/amiga/ </br>

Boot Menus: </br>
Amiga 3.2 ROM: Click Both Mouse Buttons at Boot. </br>
CyberStorm PPC PowerUP Boot Rom Menu: Press [Esc] at Boot. </p>

AmigaOS4 AmiStore AppStore: </br>
http://www.amistore.net/install/ </br>
http://www.amistore.net/install/index.php?file=Install_AMIStore.lha </br>
AmiStore allows to Buy / Download A-EON software like Enhancer, Paint, RadeonHD driver, etc...</br>
http://secure.a-eon.biz/register_user.php </br>
A-EON software for AmigaOS3 has downloads from the web page. </p>

SysInfo 4.5 Beta (2021) or Vintage 3.24 (07-Nov-93) </br>
https://sysinfo.d0.se </p>

-----

Amiga 68k

ApolloOS 68k <-- AROS 68k <-- AmigaOS3.2 </br>
CaffeineOS <-- AROS 68k <-- AmigaOS3.2 </br>
CoffinOS <-- AmigaOS3.9 </p>

AROS.Research.Operating.System </br>
was called Amiga.Research.Operating.System, but copyrights happened. </br>
AROS has different versions for x86, 68k like Linux. </br>
icAROS, ArosONE, ApolloOS, Vision, Aspire, Caffeine, PiAROS, etc... </p>

http://aros-vision.de </br>
http://www.aros-vision.de/downloads/aros_2020_Basis_UAE.7z </br>
https://aros.sourceforge.io/download.php </br>
https://aros.sourceforge.io/nightly1.php </br>

icAROS </br>
http://live.icarosdesktop.org </br>
https://vmwaros.blogspot.com/p/versions-comparison.html </br>
https://vmwaros.blogspot.com/p/download.html </br>
http://www.icarosdesktop.com/icarosfiles/IcarosLive_2_3_0.zip </br>
http://www.icarosdesktop.com/icarosfiles/IcarosDesktop_manual.pdf </p>
Beta:
http://www.icarosdesktop.com/BETA/20220624/live-experimental.iso </br>
https://vmwaros.blogspot.com/2022/06/a-new-beta.html </br>
https://ae.amigalife.org/index.php?topic=922.0 </p>
for x64: </br>
https://vmwaros.blogspot.com/p/64-bit.html </br>
https://vmwaros.blogspot.com/p/icaros-64-current-status.html </br>
https://vmwaros.blogspot.com/2019/07/lets-talk-frankly-about-64-bits.html </br>
https://vmwaros.blogspot.com/2019/10/icaros-64-v000-pre-alpha-is-available.html </br>
Icon Designer: </br>
https://vmwaros.blogspot.com/p/iconposer.html </p>

AspireOS to Run in old / weak x86 machines "LightWeight" Q6600, etc... </br>
https://sites.google.com/site/arosaspireone/ </br>

ArosONE 
https://sites.google.com/view/arosone
for x86
https://drive.google.com/file/d/1aciaZv0C7e0uJrwuQeIMZd_5GE1X7Txu/view?usp=share_link
https://drive.google.com/file/d/1dejqGqW3Hic89ij6JkTduamHriLPFWIP/view?usp=share_link
for 68k
https://www.google.com/url?q=https%3A%2F%2Fae.amigalife.org%2Findex.php%3Ftopic%3D696.0&sa=D&sntz=1&usg=AOvVaw3vimUzGUbQ6r2MvMMSJAp9

icAROS for x86 machines has AmiBridge a 68k emulator, and HostBridge when used as VM </br>
https://vmwaros.blogspot.com/p/amibridge.html </br>
https://vmwaros.blogspot.com/p/hostbridge.html <(p>

AmigaOS3 / 4 are Closed Source like UNIX or Win. </br>
AmigaOS3 is for Motorola 68k CPUs. </br>
AmigaOS4 is for PowerPC CPUs, different CPUs require different installer .iso </br> 
for pruchase on Hyperio Website is Classic Final Edition for Sam460 CPUs, Pegasos, and Emulators. </p>

AROS is binary compatible Open Source to AmigaOS3.x, like Linux or ReactOS are to UNIX and Win. </br>
MorphOS is Closed Source AROS for PowerPC machines, soon ARM. </br>
Fienix is a Linux Distro for PowerPC, https://fienixppc.blogspot.com </p>

https://www.amigafrance.com/forums/topic/winuae-coffinos/ </br>
https://getcoffin.net </br>
https://archive.org/search.php?query=CaffeineOS </br>
http://45.133.9.142/retro/apollo-os-8-1/ </p>

Most AROS distros work with Legal Amiga KickStart ROMS from AmigaForever or extracted from a Real Amiga HW </br>
some require special custom ROMs. </p>

Amiga DEMO Scene is still alive, and very usefull to test differences between HW accelerators,</br>
Demos are Short Programs desgined to test Sound and Image OCS ECS AGA chips or as Benchmark. </br>
test running inside the OS </br>
New Demos are made today exaple: </br>
https://www.pouet.net/prod.php?which=93011 </br>
https://www.pouet.net/prod.php?which=2597 </br>
https://files.scene.org/view/mirrors/amigascne/Groups/C/CarillonCyberiad/Deep-The_Psilocybin_Mix.LHA </p>
Demos Winning competition in 1995: </br>
http://janeway.exotica.org.uk/release.php?id=10900
https://aminet.net/package/demo/ta95/Zif_Parallax
https://files.scene.org/view/mirrors/amigascne/Groups/P/Parallax/PARALLAX-zif-AGA.lha 
https://www.pouet.net/prod.php?which=1149 </p>

Amiga 68k OS, Original Amiga or AROS "UNIX or Linux" </br>
allow to Run MacOS 7.1 to MacOS8.1 Color Emulation, </br>
https://shapeshifter.cebix.net </br>
many Games and software can be found in MacGardern, MacRepository and Archive.org </p>

Sonnet G3 G4 PCI cards & others can be installed in BigBox Amigas with Mediator PCI riser board. </br>
requires AmigaOS3.9 and installation is Not easy, but allows to Run PPC software, </br>
but New PPC machines are much faster. </p>

------

Amiga Hardware: </br>

There are 3 Paths: </br>
68k </br>
PowerPC </br>
Hybrid PPC cards in 68k machines </br>
or 68k SW emulation in PPC machines. </p>

BigBox Amigas like 4000 </br>
Are the most expandable, upgradable machines. </br>
But 060 CPUs have compatibility issues with older Amiga 500 Games, </br>
68k cpus were 16-Bits, </br>
Since 68030 the transition to 32-Bit begun, </br>
But that Transition had errors. </br>
For example, the last 68k CPU </br>
Was Motorola / Freescale 68060 Rev6 </br>
available in 50Mhz, 60Mhz and 66MHz.  </br>
75MHz was also available but was LC060 No FPU, </br>
And EC060 No FPU, No MMU. </br>
FPU was the same 68882 in all versions. </p>

There was 6 revisions of the same 060 CPU, </br>
Before that, there were many more... </br>
020, 030, 040, 060 </p>

Most Games were designed with/for Amiga500, </br>
Not Amiga 4000 </br>
Accelerator boards were rare those days, </br> 
But today are very common. </p>

68060 has several problems: </br>
#1. Price, sold at $400usd. From China and Russian Sellers. </br>
#2. Requires a BFG9060 CPU PCB Board, with FPGA + RAM. </br>
The Only advantage is the 128MB CPU RAM. "fastest RAM possible." </br>
But The price of the board is over $300usd. Pre-built, Flashed. No CPU. </br>
CPU + Board is closer to $800usd. Including shipping. </p>

For that money you can buy an Apollo Vampire V4 Stand Alone. </br>
With 68080 FPGA CPU  </br>
Way faster: 3x vs. 060 at 100Mhz. </br>
Much More advanced 080 instructions. </p>

As Fast as PowerPC at 800Mhz, </br>
Almost as fast as Sam460ex CPU in the AmigaONE 500 1.1Ghz CPU & Pegasos. </p>

Another problem is that Original Motorola / Freescale CPU is ASIC, </br>
Cannot be Upgraded with a Firmware update, errors cannot be fixed, </br> 
and that CPU architecture is No longer manufactured. </br> </br>
Would be very interesting to see a 1.4volts or less 5nm 060 CPU, </br>
It could run way faster than 100Mhz, but that is dream land, </br>
Its possible someone can reverse eng. the CPU.  </br>
And ask a FAB like TSMC or Intel to Print the CPUs with New technology.  </br>
But Printing ICs takes months, and costs $$$, requires to a full 300mm waffer.  </p>
in the mean time... </br>

There are other options: </br>
Vampire 080 FPGA CPU, </br>
PiStorm + Emu68k </p>

Vampire 080 is 64-Bit FPGA CPU, much better than 060, has AMMX instructions, SAGA and many other improvements. </br>
PiStorm+Emu68k is 16-Bit Only, but is Fast. </p>

When Emu68k is run Bare Metal in PiStorm, has the fastest Sysinfo Drystone Score, </br>
between 600k and 800k </br>
There are other PiAmigas, but require RaspberryOS, and that lowers performance a lot, </br>
to the same level of a 060 at 100Mhz, less than 150k Drystones. </p>

PiStorm32 is soon to be released, </br>
That would kill the BFG9060 board and the 060 R6 CPU at 100Mhz, </br>
Price is much lower, and Performance the same or faster Unknown at this moment. </p>

unknown what CPU Emu68 plan to emulate, 030, 040, 060 or different to solve compatibility issues. </br>

At this moment,  </br>
waiting for a PiStorm32 is a better option than purchasing a BFG9060 + 060 R6 CPU. </p>

The Best option Right Now:  </br>
Purchasing a Vampire V4 080 FPGA is the best option. </br>
But Not all Vampire V4 are the same, </br>
Fire and Standalone are the Best / Fastest, the others are a bit slower. </p>

080 New instructions and faster vs. RaspberryOS Amiga Emulations </br>
and vs. Real 060 CPU overclocked to 100Mhz. </p>

Not as Fast as PiStorm + Emu68k Bare Metal "No RaspberryOS", </br>
But has New 080 64-Bit instructions, </br>
Emu68k has only 16-Bit instructions. </br>

The Future of Amiga68k is the 080 CPU. </br>
Is ready Today, and has New instructions to develop New, More advanced software. </p>

FPGA can also emulate PowerPC CPUs in the future,  </br>
The future of Amiga looks bright. </br>
68k + PPC Hybrid system. </p>

Running AmigaOS4.1 Emulated in weak x86_64 requires too much CPU+Cooling. </br>
Would be interesting to see how it works in a 13900k, </br>
But... that money could be used to buy a True X5000 or ACube Sam460ex PowerPC CPU. </br>
With much lower power consumption. </br>
Using 150watts CPU to emulate a 15watt CPU makes No sense. </p>

Apollo V4+ Standalone </br>
Firebird V4+ Accelerator for A500/A1000/A2000 </br>
Icedrake V4 for Amiga 1200 </br>
Manticore V4 for Amiga 600 </p>

Plus version is a bit faster. </p>

--------

FPGA Emulations: </p>

MIST v1.3 is Open Source, since v1.4 has MIDI ports for AtariST core, BTO. </br> 
Vampire V4+ Stand Alone is Closed Source, High End 080 CPU "The Future" </bt>
MISTer is a fork of MIST that runs on FPGA developer boards, Not custom PCB, No AtariST MIDI. </p>
MiniMig 1.91 Rev9 is a Hybrid MIST fork,</br>
allows to plug CPU accelerator boards for A500, </br>
Has Xylinx Spartan3 to emulate all OCS, ECS, AGA chipset, </br>
but comes with a Real 68k CPU to work out of the box. </br>
Some FPGA allow to Run other ROM systems: AtariST, AMIGA, Arcade "PacMan", Comodore64, and others. </p>

if already own an accelerator board or plan to build a Real Amiga 500 </br>
MiniMig is a nice way to start. </br>
IF do Not plan to build a Real Amiga & dont have an Accelerator Board, </br>
a Stand alone would be better option, MiniMig Stand Alone CPU is too slow like a real 68k CPU. </br>
IF Want AtariST MIDI, MIST v1.5 is the best FPGA option. </br>
IF want the fastest & most advanced FPGA for Amiga: V4+ </p>

IF want to use Zorro expansion cards, AtariST or Commodore Cartridges. </br>
FPGA is Not for you. </p>

https://www.minimig.ca </br>
http://www.apollo-computer.com/ </br>
https://lotharek.pl/productdetail.php?id=45  </p>

Price aprox.: </br>
MIST 1.5 $250usd. </br>
Minimig 1.91 Rev9 $350usd. </br>
Vampire V4+ Stand Alone $800usd. </p>

Vampire has the Option for RTC to Remeber the Time&Date every time you Turn-Off the machine. </br>
i dont like MISTer, because its Not a custom PCB, just a developer board, and does Not have MIDI</br>
around $550usd. + Custom Software, sold in Amiga Authorized Stores. </p>

-----

Accelerator Boards </p>

Have 3 categories: </br>
A) Real Motorola CPU </br>
B) Emulated CPU </br>
C) Hybrid CPU. </p>

A) Original Amiga A3630 A3640 </br>
Replicas with Real CPU. </br>
Other manufacurers like CyberStorm Mk1/2/3 </p>

B) Emulated CPU </br>
FPGA or PiStorm+Emu68k Software Emualtion, </br>
compatible Hardware to interact with real Amiga Hardware PCB. </br> 
FPGA if done properly is more for parallel processing, </br> 
ARM is more for Fast Serial processing. </br>
in Theory Motorola 68K CPUs are CISC, similar to x86 </br> 
Faster Serial Emulation could be faster, </br>
Parallel emulation IF done properly, can have Perfect Timings in all i/o lines,</br>
exactly the same as the real 68k CPU, but faster, but Not as fast as ARM. </br>
Turtle vs. Rabbit Tale. </p>

C) CyberStorm PPC604e Boards, </br>
Motorola + PowerPC CPU. </br>
There is also stand alone PowerPC PCI cards from Sonnet and others, </br>
works on BigBox Amigas with MEDIATOR PCI or Prometheus PCI Riser Boards. </p>

