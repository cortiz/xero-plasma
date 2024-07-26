# The Plasma Installer Script

With the help of this script you will be able to install **Plasma** in one of 4 methods as you can see in the image below. Not only that, it will also fix **PipeWire** and **Bluetooth**.. Make sure to inspect the script [**Here**](https://github.com/xerolinux/xero-plasma/blob/main/xero-plasma.sh) before running it to see what and how it does things...
<br />

<div align="center">

![Script](https://i.imgur.com/TOZNp4j.png)

</div>

### How To Use :

First off, you will need to download latest [**Arch ISO**](https://archlinux.org/download/), boot it and follw the steps below.. 

**- Step 1 :**
Grab latest version of **ArchInstall** script
```
pacman -Syy archinstall
```

**- Step 2 :**
Run the **ArchInstall** guided setup via command below
```
archinstall --advanced
```

**- Step 3 :**
Go through the mothions skipping the **Profiles** and **Additional Packages** steps ignoring them completly, don't forget to set parallel downloads to as many as you want for faster downloads. Oh and skip GPU Drivers, since you will be able to do that and more via my toolkit which will be offered during install, and select **NetworkManager** for your network (Will be installed by this script anyway).

**Note :**

> This guide expects you to be connected to the internet via ethernet. If you aren’t and need to connect over WiFi, you can follow guide on the [**ArchWiki**](https://wiki.archlinux.org/title/Installation_guide#Connect_to_the_internet)

Finally select install, and let it do its thing, won't take long as it will just install basic packages nothing too big. Once it's done, it will prompt you if you want to **chroot** into your installed system, select yes since you don't have **Plasma** installed yet... 

**- Step 4 :**
Now is the time to run my script. To do so, type the below command in terminal, hit enter and have fun.. A video will be made soon and added here, so keep it locked to this git...
```
bash -c "$(curl -fsSL https://tinyurl.com/PlasmaInstall)"
```

### Full Guide :

> For a more full in-depth guide with video included, feel free to check it out on our [**Official Site**](https://xerolinux.xyz/xero-news/xerolinux-plasma/) where we go over each step in detail. Video and written guide are to be used in tandem, as in together, otherwise you will surely get lost.

### Report Issues

To report any issues or suggest quality of life modifications to script please feel free to do so on the [**Issues**](https://github.com/xerolinux/xero-plasma/issues) page. Otherwise I won't be able to get to them fast enough or at all. Thanks.

Enjoy ;)
