# Kali-Linux-2021.3-vmware_TP-Link-Archer-T2UH_mt7610u_fix
Kali Linux 2021.3 Vmware Edition TP-Link Archer T2UH AC600 MediaTek MT7610U chipset fix

Usb is listing on Kali and you can see your wifi-card on vmware connected usb list. But no wifi connection !
![problem](https://user-images.githubusercontent.com/68458759/139579828-4bfd4db5-f0b8-49f1-999c-5f5f20757c3e.png)

On Virtual Machine Settings (Ctrl+D) change USB Compatibility USB 2.0 to USB 3.1
![usb_3_1](https://user-images.githubusercontent.com/68458759/139579907-cd658d65-2a9d-4007-ad04-0243af61fcdb.png)

Re-plug your wifi-card and select connect to VM. Now you can connect to wifi networks.
![fix](https://user-images.githubusercontent.com/68458759/139580145-b657cdaa-4a56-4b34-9458-695dbc6a4b58.png)
