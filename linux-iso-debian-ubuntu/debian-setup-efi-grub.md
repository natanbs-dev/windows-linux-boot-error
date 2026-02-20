```
lsblk
ls /sys/firmware/efi
sudo apt-get install --reinstall grub-efi-amd64 shim-signed
grub-install --target=x86_64-efi --efi-directory=/boot/efi --bootloader-id=debian
update-grub
```

## print error: 

```
o carregador de inicialização não pôde ser instalado. o comando de instalação <pre> 
grub-install --target=x86_64-efi --efi-directory=/boot/efi --botloader-id=Debian --force</pre> retornou
 o codigo de erro 1.
 ```