milis-arm
===============

Milis GNU/Linux paketlerinin Arm mimarisine taşınması için oluşturulan depo.

## NOTLAR:
* Paketler inşa edilirken statik derlenmiş qemu kullanıldı.

    https://wiki.debian.org/QemuUserEmulation

* Nasıl kullanılacağı aşağıdaki anlatımda mevcut.

    https://gist.github.com/bferturk/fbc8e7d5d9c4728dfe2c6f7bf37eae01

* Disk kalıbında varsayılan root şifresi:

    root:toor

* Disk kalıbını sd karta yazdırmak için:

```bash
mkfs.vfat /dev/sdX -I
```
```bash
dd if=MilisARM_Kur_Sad.img of=/dev/sdX bs=4M
```
   komutları kullanılır.
  
  
  ## Görüntüler:
  
  
![1.resim](https://i.hizliresim.com/5DgjMd.png)



![2.resim](https://i.hizliresim.com/p60OEJ.png)

    





