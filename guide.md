1. Create an ntfs partition (You can also use your already existing ntfs drives/partitions)

(You can do this easily with gnome disks)

![image](https://github.com/user-attachments/assets/5a162e0d-f1ab-4997-8a75-6019600c723e)

Recommended partition size: 12-15 GBS

![image](https://github.com/user-attachments/assets/25ea69c7-a00f-4f33-9c46-df63f0398331)

2.Install the ntfs-3g ntfs driver

e.g. for Arch

```
sudo pacman -S ntfs-3g
```

3.Create a wine prefix from your desired wine manager (Heroic, bottles, lutris..)

4.Install EA App and gw1 how you normally would

5.Download and extract FMM/FE 1.0.6.3 inside the prefix

6.Extract brekko's gw1 patch to (can be found in the [GW Frostbite modding server](https://discord.gg/HVhjRf8per) ) your FMM/FE installation and replace when asked

7.Install your mods and press launch (should work in theory haven't tested myself but yeah)
