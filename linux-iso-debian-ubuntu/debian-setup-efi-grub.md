3  sudo nano /etc/default/grub
4  lsblk
5  ls /sys/firmware/efi
6  sudo apt-get install --reinstall grub-efi-amd64 shim-signed
7  grub-install --target=x86_64-efi --efi-directory=/boot/efi --bootloader-id=debian
8  update-grub

error: 

o carregador de inicialização não pôde ser instalado. o comando de instalação <pre> 
grub-install --target=x86_64-efi --efi-directory=/boot/efi --botloader-id=Debian --force</pre> retornou
 o codigo de erro 1.