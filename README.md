# rpi3b
 - Raspberry Pi 3B Kernel
 - sources https://github.com/raspberrypi/linux/blob/rpi-6.1.y/COPYING

Cross-aarch64 (arm64), Gentoo x86_64 Host using GCC-12 thats been compiled with Graphite, LTO, & PGO optimizations.

Im currently running it on my GentooPi

```
 mrturcot  on GentooRig /home/mrturcot/github/rpi3b on   main took 10s
[ 01:04:30 AM ] ➜ ssh mrturcot@192.168.1.104
mrturcot@GentooPi ~ $ neofetch 
         -/oyddmdhs+:.                mrturcot@GentooPi 
     -odNMMMMMMMMNNmhy+-`             ----------------- 
   -yNMMMMMMMMMMMNNNmmdhy+-           OS: Gentoo Linux aarch64 
 `omMMMMMMMMMMMMNmdmmmmddhhy/`        Host: Raspberry Pi 3 Model B Rev 1.2 
 omMMMMMMMMMMMNhhyyyohmdddhhhdo`      Kernel: 6.1.0-rc8-filthy+ 
.ydMMMMMMMMMMdhs++so/smdddhhhhdm+`    Uptime: 9 mins 
 oyhdmNMMMMMMMNdyooydmddddhhhhyhNd.   Packages: 385 (emerge) 
  :oyhhdNNMMMMMMMNNNmmdddhhhhhyymMh   Shell: bash 5.2.12 
    .:+sydNMMMMMNNNmmmdddhhhhhhmMmy   Terminal: /dev/pts/0 
       /mMMMMMMNNNmmmdddhhhhhmMNhs:   CPU: ARM Cortex-A53 (4) @ 1.000GHz 
    `oNMMMMMMMNNNmmmddddhhdmMNhs+`    Memory: 43MiB / 922MiB 
  `sNMMMMMMMMNNNmmmdddddmNMmhs/.
 /NMMMMMMMMNNNNmmmdddmNMNdso:`                                
+MMMMMMMNNNNNmmmmdmNMNdso/-                                   
yMMNNNNNNNmmmmmNNMmhs+/-`
/hMMNNNNNNNNMNdhs++/-`
`/ohdmmddhys+++/:.`
  `-//////:--.
```

 and Debian Pi-hole :)

```
mrturcot@Pi-hole:~ $ screenfetch 
         _,met$$$$$gg.           mrturcot@Pi-hole
      ,g$$$$$$$$$$$$$$$P.        OS: Debian  bookworm
    ,g$$P""       """Y$$.".      Kernel: aarch64 Linux 6.1.0-rc8-v8+
   ,$$P'              `$$$.      Uptime: 1h 24m
  ',$$P       ,ggs.     `$$b:    Packages: 648
  `d$$'     ,$P"'   .    $$$     Shell: bash 5.2.2
   $$P      d$'     ,    $$P     Disk: 2.5G / 30G (9%)
   $$:      $$.   -    ,d$$'     CPU: BCM2835 @ 4x 1.2GHz
   $$\;      Y$b._   _,d$P'      GPU: 
   Y$$.    `.`"Y$$$$P"'          RAM: 173MiB / 922MiB
   `$$b      "-.__              
    `Y$$                        
     `Y$$.                      
       `$$b.                    
         `Y$$b.                 
            `"Y$b._             
                `""""
```