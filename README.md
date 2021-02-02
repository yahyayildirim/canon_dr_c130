# MANUEL KURULUM
Pardus 19 kurulu cihazlarda Canon DR-C130 imageFORMULA Tarayıcısının kurulumu hakkında tutmuş olduğum dökümandır. [BU DOSYADAN](https://github.com/yahyayildirim/canon_dr_c130/blob/main/dr-c130-tan%C4%B1tma.txt) manuel kurulum yapabilirsiniz.


# DEB DOSYASI İLE KURULUM
Canon DR-C130 imageFORMULA Tarayıcısının PARDUS'ta çalışması için hazırladığım DEB dosyasıdır. Orjinal dosyanın postinst ve postrm dosyalarında düzenleme yapılmıştır. Dosyayı [BURADAN](https://github.com/yahyayildirim/canon_dr_c130/blob/main/cndrvsane-drc130_fixed.deb?raw=true) indirin.
* Kurulumdan önce mutlaka `sudo dpkg --add-architecture i386 && sudo apt update` kodunu çalıştırın.
* Daha sonra DEB dosyasının olduğu dizinde `sudo apt install -f ./cndrvsane-drc130_fixed.deb` komutunu çalıştırın.
* xsane programını açtığınızda size iki seçenek sunabilir. Siz `Canon DRC130 sheetfed scanner` olanı seçmelisiniz.
