# OpenboxInstall
 This is an extension to the Arch base install script to install GUI.
 
 https://github.com/smsriharsha/ArchBaseInstall.git
 
Choose the applications that you require to modify the script

The GUI is from JOYFUL desktop .

This uses various other git projects in the scipt to build the desktop.
 ## Screenshot
 
![5_6188198762796549223](https://user-images.githubusercontent.com/23277835/159973528-02b36055-c773-4690-a218-1f4df88c753f.png)


## Resource Usage
This is built on arch base 
uses 13 gb disk space and 650MB of ram.

## Steps to Install.
Clone the Git repo

```
git clone https://github.com/smsriharsha/OpenboxInstall.git
```

Go into the downloaded folder and
```
chmod 777 openbox_install.sh enabling_services.sh
```

Run the openbox_install script
```
./openbox_install.sh
```

switch to root
```
sudo -s
./enabling_services.sh
```


Credits:

This uses the dotfiles of https://github.com/owl4ce/dotfiles.git.
