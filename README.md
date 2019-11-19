# my-hackintosh-plist
For Clover EFI Emulator/Bootloader

My `neofetch` (Ubuntu):
```
            .-/+oossssoo+/-.               nnn1590@ubuntu 
        `:+ssssssssssssssssss+:`           ----------- 
      -+ssssssssssssssssssyyssss+-         OS: Ubuntu 18.04.3 LTS x86_64 
    .ossssssssssssssssssdMMMNysssso.       Host: Endeavor TY5000S AP1-0003-EV3 
   /ssssssssssshdmmNNmmyNMMMMhssssss/      Kernel: 4.15.0-70-generic 
  +ssssssssshmydMMMMMMMNddddyssssssss+     Uptime: 59 mins 
 /sssssssshNMMMyhhyyyyhmNMMMNhssssssss/    Packages: 4307 
.ssssssssdMMMNhsssssssssshNMMMdssssssss.   Shell: bash 4.4.20 
+sssshhhyNMMNyssssssssssssyNMMMysssssss+   Resolution: 1366x768 
ossyNMMMNyMMhsssssssssssssshmmmhssssssso   DE: LXDE 
ossyNMMMNyMMhsssssssssssssshmmmhssssssso   WM: Openbox 
+sssshhhyNMMNyssssssssssssyNMMMysssssss+   WM Theme: Fuga 
.ssssssssdMMMNhsssssssssshNMMMdssssssss.   Theme: Lubuntu-default [GTK2/3] 
 /sssssssshNMMMyhhyyyyhdNMMMNhssssssss/    Icons: Lubuntu [GTK2/3] 
  +sssssssssdmydMMMMMMMMddddyssssssss+     Terminal: gnome-terminal 
   /ssssssssssshdmNNNNmyNMMMMhssssss/      CPU: Intel i7-2700K (8) @ 3.900GHz 
    .ossssssssssssssssssdMMMNysssso.       GPU: AMD Radeon HD 6770 
      -+sssssssssssssssssyyyssss+-         Memory: 2703MiB / 7954MiB 
        `:+ssssssssssssssssss+:` 
            .-/+oossssoo+/-.                                       
```

Wi-Fi:
```bash
$ dmesg | grep -e mvm -e Wire
[   25.757677] Intel(R) Wireless WiFi driver for Linux
[   25.987510] iwlwifi 0000:02:00.0: loaded firmware version 29.1044073957.0 op_mode iwlmvm
[   26.484992] iwlwifi 0000:02:00.0: Detected Intel(R) Dual Band Wireless AC 7265, REV=0x210
[   26.791095] ieee80211 phy0: Selected rate control algorithm 'iwl-mvm-rs'
```
