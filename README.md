### Dell-XPS-15-9570-macOS-Mojave
## Note: This EFI is a modification by me of the original "DELL-XPS-15-9570-8950-4K-macOS-Mojave" EFI by shenlinsl. shenlinsl's EFI currently does not have sleep working when brightness adjustment is enabled, along with power management issues related to audio. This modified EFI solves these issues.

### My laptop: XPS 15 9570 i7 8750H, 4K 16GB RAM, Toshiba XG5 512GB. If you have a different CPU/SSD/Screen you may need to further modify this EFI.

## 10.14.x System Installation: 
      1. Use macOS-Mojave OS Installer to install and restart to enter the system
      2. Reconstruct kextcache (sudo kextcache-i/)
      3. Replace the DELL XPS 15 9570 8950 4K macOS Mojave EFI folder
      4. restart


## Working
      Intel UHD 630 Graphics
      Wifi & Bluetooth - Works, but need to use a DW1830/DW1560 (this EFI includes support for DW1560 as that is what I am using)
      Sound - using layout-id 72 and included kexts works great. layout-id 30 causes power management issues for me with an i7-8750H. May differ with you.
      Camera
      Screen brightness: brightlight control works, need to connect an external keyboard ONCE to setup brightness increase/decrease shortcut keys in settings
      Sleep: Sleep works (both by pressing the sleep button in menu bar, and by closing the lid)
      Touchpad: Working with voodoops2 (later will use voodooi2c for advanced gestures)

## Not working
      HDMI Output
      1050TI graphics card(can not be driven under macOS-Mojave system)
      The hardware of SD card reader is not recognized and can not work properly.
      Thunderbolt 3?
      Battery capacity identification 82 watts, the actual battery capacity is 95 watts. (Capacity is not correctly identified)

## Thank you.
      Making device-driven gods for Hackintosh (this is not a list, thank you all)
      Thanks to FireWolf Pl for solving the zero panic problem and improving xps15 9570
      Thank you very much for your help. Shaohua, officials, ham sausage, Taoge, Big Cousin, Daliansky and other brothers!
      
## Additional thanks to @shenlinsl, @xigtun, and @bavariancake whose work, by examining their EFIs made this EFI possible.
