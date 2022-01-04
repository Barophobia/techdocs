+++
title = "WIP How to install Arch Linux"
weight = 5
chapter = true
pre = "<b> - </b>"
+++

## How to install Arch Linux

Arch linux is a sort of 'build it yourself' OS allowing you to create the environment you desire, I use this to have a low resource requirement extending the life of 'old' hardware but it can be used for more than that.

### Steps to install Arch Linux

Download the Arch Linux ISO from the website.
[https://www.archlinux.org](https://www.archlinux.org)

If you are building a virtual machine just mount the ISO to the machine and boot to it.

If you are building a physical machine you will need to use a tool like balenaEtcher to build a live USB.
If you don't want to use a tool then you can use the command below on Linux and change it to your path.

```
dd bs=4M if=/path/to/archlinux.iso of=/dev/sdx status=progress && sync
```

Now boot to Arch Linux, this will take you to a live terminal session.

Firstly, check your network connection using ping and ip link.

```
ping archlinux.org
```

ip link will show you available interfaces.
```
ip link
```

If you would like to use Wi-Fi:
```
wifi-menu
```

Now set your time and date using NTP:

```
timedateclt set-ntp truet
```

list all disk and partitions:

```
fdisk -l
```

Now select the disk you are going to format and partition:

```
cfdisk /dev/sda
```
This will bring up a screen asking to select the label type, choose: 'gpt'

![LabelType](/themes/hugo-theme-learn/images/img/labeltype.png)
![Minion](https://octodex.github.com/images/minion.png?width=20pc)
![stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg)

This is some text.