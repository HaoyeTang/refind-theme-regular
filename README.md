# rEFInd theme rEVIsed

A simplistic clean and minimal theme for rEFInd

![Screenshot 01](http://i.imgur.com/wQQ5OiQ.png)
**press F10 to take screenshot


### Installation:

1. Clone git repository to your $HOME directory.
   ```
   git clone https://github.com/HaoyeTang/refind-theme-regular.git
   ```

2. Locate refind directory under EFI partition. For most Linux based system is commonly `/boot/efi/EFI/refind/`. Copy theme directory to it.

   ```
   sudo cp -r refind-theme-regular /boot/efi/EFI/refind/
   ```
3. Remove unused directory.
   ```
   sudo rm -rf /boot/efi/EFI/refind/refind-theme-regular/{.git}
   ```

4. To enable the theme add `include refind-theme-regular/theme.conf` at the end of `refind.conf`.
   ```
   sudo nano /boot/efi/EFI/refind/refind.conf
   ```
## Credits
[Evan Purkhiser](https://github.com/EvanPurkhiser)

[Munlik](https://github.com/munlik)
