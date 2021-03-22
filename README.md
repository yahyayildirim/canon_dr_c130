# DEB DOSYASI İLE KURULUM
Canon imageFORMULA DR-C130 Tarayıcısının PARDUS'ta çalışması için hazırladığım DEB dosyasıdır. Orjinal dosyanın postinst ve postrm dosyalarında düzenleme yapılmıştır. Dosyayı [BURADAN](https://github.com/yahyayildirim/canon_dr_c130/blob/beta/cndrvsane-drc130_fixed.deb?raw=true) indirin.
* Kurulumdan önce mutlaka `sudo dpkg --add-architecture i386` kodunu çalıştırın.
* Sonra depoları güncelleyin `sudo apt update` komutunu çalıştırın.
* Daha sonra DEB dosyasının olduğu dizinde `sudo apt install -f ./cndrvsane-drc130_fixed.deb` komutunu çalıştırın.

Güle güle kullanın...
