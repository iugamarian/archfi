# archfi

# Modified to work better with EFI autopartitioning and booting (for M.2 SSD)

Just a simple bash script wizard to install Arch Linux after you have booted on the official Arch Linux install media.

With this script, you can install Arch Linux with two simple terminal commands.

This wizard is made to install minimum packages (Base, GRUB, and optionally efibootmgr).<br />
At the end of this wizard, you can install or launch [archdi](https://github.com/MatMoul/archdi) (Arch Linux Destop Install) to install and configure desktop packages.<br />

You can watch MatMoul's videos to see how to use it [here](https://www.youtube.com/playlist?list=PLytHgIKLV1caHlCrcTSkm5OF2WSVI1_Sq).

### How to use:<br />
Boot with the Arch Linux image found [here](https://www.archlinux.org/download/).

Download the script with:<br/>
`mount -o remount,size=512M /run/archiso/cowspace`<br />
`pacman -Sy git`<br />
`git clone git://github.com/iugamarian/archfi`<br />

And launch the script with:<br />
`cd archfi*`<br />
`sh archfi`<br />
then follow the on-screen instructions to completion.

If you require extra help, visit the provided video playlist and follow my example.
