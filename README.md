# Plymouth Theme for Alien Conquest

Be ready - they are coming!

## Changing Plymouth Theme

To change to this plymouth theme execute, copy the plymouth_alien to
directory /usr/share/plymouth/themes. Then execute these commands (as
root):

<code>
plymouth-set-default-theme plymouth_alien
/usr/libexec/plymouth/plymouth-update-initrd
grub2-mkconfig -o /boot/grub2/grub.cfg 
</code>

I also changed my /etc/plymouth/plymouthd.conf file to:

[Daemon]
Theme=plymouth_alien
ShowDelay=1
